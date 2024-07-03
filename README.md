# Machine Unlearning in Deep Neural Networks
A companion repository to the comparative study "Machine Unlearning in Deep Neural Networks" containing jupyter notebooks used for experiments.

Notebooks provided are modified versions of the scripts provided in the [Selective Synaptic Dampening GitHub repository](https://github.com/if-loops/selective-synaptic-dampening), with the exception of the SCRUB notebook which is a modified version of the .
Notable changes include modifications to accomodate lower resources provided by the Kaggle free tier, as well as additions to facilitate unlearning on MARBERT and BERT-based sentiment analysis
models.

Notebooks provided contain all required cells with the main unlearning action being done by the bottom-most cell(s), changes to the unlearning parameters are done by modifiying the args dictionary at the beginning of the cell.

## Other Resources:
- [Used pretrained MARBERT model on HAR dataset including data used](https://www.kaggle.com/datasets/moustafaeltawy/marbert-hard-data/versions/2)
- [Used pretrained ResNet18 model on CIFAR-10 dataset](https://www.kaggle.com/datasets/omsafa/resnet18-cifar10)
- [Used pretrained ResNet18 model on CIFAR-20 dataset](https://www.kaggle.com/datasets/omsafa/resnet18-cifar20)
- [Used pretrained ResNet18 model on CIFAR-100 dataset](https://www.kaggle.com/datasets/omsafa/resnet18-cifar100)
- [Used pretrained ViT model on CIFAR-10 dataset](https://www.kaggle.com/datasets/omsafa/ViT-cifar10)
- [Used pretrained ViT model on CIFAR-20 dataset](https://www.kaggle.com/datasets/omsafa/ViT-cifar20)
- [Used pretrained ViT model on CIFAR-100 dataset](https://www.kaggle.com/datasets/omsafa/ViT-cifar100)

## Acknowledgements
This work would not be possible without the research and contributions of the following researchers:
- The Selective Synaptic Dampening team (Jack Foster, Stefan Schoepf, Alexandra Brintrup)
  [Fast Machine Unlearning Without Retraining Through Selective Synaptic Dampening](https://arxiv.org/abs/2308.07707)
  [GitHub repository](https://github.com/if-loops/selective-synaptic-dampening)
- The Incompetent Teacher team (Vikram S Chundawat, Ayush K Tarun, Murari Mandal, Mohan Kankanhalli)
  [Can Bad Teaching Induce Forgetting? Unlearning in Deep Networks using an Incompetent Teacher](https://arxiv.org/abs/2205.08096)
  [GitHub repository](https://github.com/vikram2000b/bad-teaching-unlearning)
- The Amnesiac Unlearning team (Laura Graves, Vineel Nagisetty, Vijay Ganesh)
  [Amnesiac Machine Learning](https://arxiv.org/abs/2010.10981)
- The UNSIR team (Vikram S Chundawat, Ayush K Tarun, Murari Mandal, Mohan Kankanhalli)
  [Fast Yet Effective Machine Unlearning](https://ieeexplore.ieee.org/document/10113700)
  [GitHub repository](https://github.com/vikram2000b/Fast-Machine-Unlearning)
- The SCRUB team (Meghdad Kurmanji, Peter Triantafillou, Jamie Hayes, Eleni Triantafillou)
  [Towards Unbounded Machine Unlearning](https://arxiv.org/abs/2302.09880)
  [GitHub repository](https://github.com/meghdadk/SCRUB)

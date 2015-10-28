# Full ImageNet Network

#### Note
Models are hosted by [git lfs](https://git-lfs.github.com/). If you don't have git-lfs, please download from Github.com website directly instead of ```git clone``` to avoid possible error.

This model is a pretrained model on full imagenet dataset [1] with 14,197,087 iamges in 21,841 classes. The model is trained by only random crop and mirror augmentation.

The network is based on Inception-BN network [2], and added more capacity. This network runs roughly 2 times slower than standard Inception-BN Network.

We trained this network on a machine with 4 GeForce GTX 980 GPU. Each round costs 23 hours, the released model is the 9 round.

Train Top-1 Accuracy over 21,841 classes: 37.19%

Single image prediction memory requirement: 15MB

ILVRC2012 Validation Performance:

|        | Over 1,000 classes | Over 21,841 classes |
| ------ | ------------------ | ------------------- |
| Top-1  | 68.3%              | 41.9%               |
| Top-5  | 89.0%              | 69.6%               |
| Top=20 | 96.0%              | 83.6%               |


Note: Directly use 21k prediction may lose diversity in output. You may choose a subset from 21k to make perdiction more reasonable.

The compressed file contains:
- ```Inception-symbol.json```: symbolic network
- ```Inception-0009.params```: network parameter
- ```synset.txt```: prediction label/text mapping

There is no mean image file for this model. We use ```mean_r=117```, ```mean_g=117``` and ```mean_b=117``` to noramlize the image.


##### Reference:

[1] Deng, Jia, et al. "Imagenet: A large-scale hierarchical image database." *Computer Vision and Pattern Recognition*, 2009. CVPR 2009. IEEE Conference on. IEEE, 2009.

[2] Ioffe, Sergey, and Christian Szegedy. "Batch normalization: Accelerating deep network training by reducing internal covariate shift." *arXiv preprint arXiv:1502.03167* (2015).

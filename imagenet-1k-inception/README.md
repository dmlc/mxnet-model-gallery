# Inception-BN Network

This model is a pretrained model on ILSVRC2012[1] dataset. The model is trained by only random crop and mirror augmentation.

This model is able to achieve 89.9% Top-5 accuracy on ILSVRC2012-Validation Set.

Single image prediction memory requirement: 10MB


The compressed file contains:
- ```mean_224.nd```: image mean file
- ```synset.txt```: prediction label/text mapping
- ```Inception_BN-symbol.json```: symbolic network
- ```Inception_BN-0039.params```: network parameter



##### Reference:

[1] Russakovsky, Olga, et al. "Imagenet large scale visual recognition challenge." *International Journal of Computer Vision* (2014): 1-42.

[2] Ioffe, Sergey, and Christian Szegedy. "Batch normalization: Accelerating deep network training by reducing internal covariate shift." *arXiv preprint arXiv:1502.03167* (2015).

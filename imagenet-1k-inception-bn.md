# Inception-BN Network

The mode is hosted on http://data.dmlc.ml, you can download by

```bsah
wget http://data.dmlc.ml/mxnet/models/imagenet/inception-bn.tar.gz
```

The compressed file contains:

- ```mean_224.nd```: image mean file
- ```synset.txt```: prediction label/text mapping
- ```Inception_BN-symbol.json```: symbolic network
- ```Inception_BN-0039.params```: network parameter

This model is a pretrained model on ILSVRC2012[1] dataset. The model is trained by only random crop and mirror augmentation.
It is able to achieve 89.9% Top-5 accuracy on ILSVRC2012-Validation Set.

Single image prediction memory requirement: 10MB

##### Reference:

[1] Russakovsky, Olga, et al. "Imagenet large scale visual recognition challenge." *International Journal of Computer Vision* (2014): 1-42.

[2] Ioffe, Sergey, and Christian Szegedy. "Batch normalization: Accelerating deep network training by reducing internal covariate shift." *arXiv preprint arXiv:1502.03167* (2015).

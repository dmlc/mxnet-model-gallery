<img src=https://raw.githubusercontent.com/dmlc/dmlc.github.io/master/img/logo-m/mxnet2.png width=135/> Model Gallery
=====

[![GitHub license](https://img.shields.io/badge/licence-cc0-blue.svg)](./LICENSE)

### [Inception-BN Network](imagenet-1k-inception-bn.md)

This model is a pretrained model on ILSVRC2012 dataset. The model is trained by only random crop and mirror augmentation. This model is able to achieve 89.9% Top-5 accuracy on ILSVRC2012-Validation Set.

### [Inception-V3 Network](imagenet-1k-inception-v3.md)

This model is converted from TensorFlow released pretrained model. By single crop on 299 x 299 image from 384 x 384 image, this model is able to achieve 76.88% Top-1 Accuracy and 93.344% Top-5 Accuracy on ILSVRC2012-Validation Set.

### [Full ImageNet Network](imagenet-21k-inception)

This model is a pretrained model on full imagenet dataset with 14,197,087 iamges in 21,841 classes. The model is trained by only random crop and mirror augmentation. This model is able to achieve 37.19% Top-1 accuracy on training data. This model is about 50% more complex than standard Inception-BN Network

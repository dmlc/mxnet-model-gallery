# VGG16 Network

The mode is hosted on http://data.dmlc.ml, you can download by

```bash
wget http://data.dmlc.ml/mxnet/models/imagenet/VGG/vgg16.tar.gz
```

The compressed file contains:

### VGG16
- ```vgg16-symbol.json```: symbolic network
- ```vgg16-0000.params```: network parameter

The mode is hosted on http://data.dmlc.ml, you can download by

```bash
wget http://data.dmlc.ml/mxnet/models/imagenet/VGG/vgg19.tar.gz
```

The compressed file contains:

### VGG19
- ```vgg19-symbol.json```: symbolic network
- ```vgg19-0000.params```: network parameter

These model are pretrained models on ILSVRC2012[1] dataset. vgg16 is able to achieve 71.0% Top-1 Accuracy and 89.9% Top-5 accuracy on ILSVRC2012-Validation Set. vgg19 achieve similar accuracy on the same dataset. These models are also converted from caffemodel and they are widely used in transfer learning like object detection and image semantic segmentation.

##### Reference:
[1] Simonyan, Karen, and Andrew Zisserman. "Very deep convolutional networks for large-scale image recognition." arXiv preprint arXiv:1409.1556 (2014).

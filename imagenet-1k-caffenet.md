# CaffeNet Network

The model is hosted on http://data.dmlc.ml, you can download by

```bash
wget http://data.dmlc.ml/mxnet/models/imagenet/caffenet/caffenet.tar.gz
```

The compressed file contains:

- ```caffenet-symbol.json```: symbolic network
- ```caffenet-0000.params```: network parameter

This model is a pretrained model on ILSVRC2012[1] dataset. It is able to achieve 54.5% Top-1 Accuracy and 78.3% Top-5 accuracy on ILSVRC2012-Validation Set. This model is converted from caffenet provided in Caffe Model Zoo.


##### Reference:

[1] Krizhevsky, Alex, Ilya Sutskever, and Geoffrey E. Hinton. "Imagenet classification with deep convolutional neural networks." Advances in neural information processing systems. 2012.

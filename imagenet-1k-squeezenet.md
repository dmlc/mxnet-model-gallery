# Squeezenet_v1.0 Network

The mode is hosted on http://data.dmlc.ml, you can download by

```bash
wget http://data.dmlc.ml/mxnet/models/imagenet/squeezenet/squeezenet_v1.0.tar.gz
```

The compressed file contains:

- ```squeezenet_v1.0-symbol.json```: symbolic network
- ```squeezenet_v1.0-0000.params```: network parameter

This model is a pretrained model on ILSVRC2012[1] dataset. It is able to achieve 55.4% Top-1 Accuracy and 78.8% Top-5 accuracy on ILSVRC2012-Validation Set.


##### Reference:

[1] Iandola, Forrest N., et al. "SqueezeNet: AlexNet-level accuracy with 50x fewer parameters and< 1MB model size." arXiv preprint arXiv:1602.07360 (2016).

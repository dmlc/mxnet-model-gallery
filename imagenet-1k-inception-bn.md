# Inception-BN Network

The mode is hosted on http://data.dmlc.ml, you can download by

```bash
wget http://data.dmlc.ml/mxnet/models/imagenet/inception-bn.tar.gz
```

The compressed file contains:

- ```synset.txt```: prediction label/text mapping
- ```Inception-BN-symbol.json```: symbolic network
- ```Inception-BN-0126.params```: network parameter

This model is a pretrained model on ILSVRC2012[1] dataset. It is able to achieve 72.5% Top-1 Accuracy and 90.8% Top-5 accuracy on ILSVRC2012-Validation Set.

Single image prediction memory requirement: 10MB

##### Reference:

[1] Russakovsky, Olga, et al. "Imagenet large scale visual recognition challenge." *International Journal of Computer Vision* (2014): 1-42.

[2] Ioffe, Sergey, and Christian Szegedy. "Batch normalization: Accelerating deep network training by reducing internal covariate shift." *arXiv preprint arXiv:1502.03167* (2015).

# Inception-V3 Network

Models are hosted on http://data.dmlc.ml. You can download it by

```bash
wget http://data.dmlc.ml/mxnet/models/imagenet/inception-v3.tar.gz
```

The compressed file contains:

- ```preprocessing.py```: sample code for preprocessing image
- ```synset.txt```: prediction label/text mapping
- ```Inception-7-symbol.json```: symbolic network
- ```Inception-7-0001.params```: network parameter

This model is converted from TensorFlow Pretrained [Inception-V3 model](https://www.tensorflow.org/versions/master/tutorials/image_recognition/index.html). Original licence is attached.

By single crop on 299 x 299 image from 384 x 384 image, this model is able to achieve 76.88% Top-1 Accuracy and 93.344% Top-5 Accuracy. Difference to reported accuracy may due to crop from different size of image.

This model uses different preprocessing method, sample code is provided.

##### Reference:
[1] Szegedy, Christian, et al. "Rethinking the Inception Architecture for Computer Vision." arXiv preprint arXiv:1512.00567 (2015).

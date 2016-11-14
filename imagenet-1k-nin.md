# NIN Network

The model is hosted on http://data.dmlc.ml, you can download by

```bash
wget http://data.dmlc.ml/mxnet/models/imagenet/nin/nin.tar.gz
```

The compressed file contains:

- ```nin-symbol.json```: symbolic network
- ```nin-0000.params```: network parameter

This model is a pretrained model on ILSVRC2012[1] dataset. It is able to achieve 58.8% Top-1 Accuracy and 81.3% Top-5 accuracy on ILSVRC2012-Validation Set.


##### Reference:

[1] Lin, Min, Qiang Chen, and Shuicheng Yan. "Network in network." arXiv preprint arXiv:1312.4400 (2013).

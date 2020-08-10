# 2020-08
自用+学习，原版本代码用于py2环境，需要做一些修改，另外数据加载器dataloader在使用中也会报错
当前代码仅可用于训练，而无法用在测试，后续可以补充相应功能


# mxnet-siamise
siamise networks[^1]  

Here use simple mlp as forward networks, you can replace it with CNN or anything complicate netowrks.

[^1] ["Dimensionality Reduction by Learning an Invariant Mapping"](http://yann.lecun.com/exdb/publis/pdf/hadsell-chopra-lecun-06.pdf)
    
### Usage  

```
python train_siamise_mnist.py --batch_size 128 --epoches 20 --gpu 0,1
```



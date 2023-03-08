# NVDLA
这个确实是业界良心之做，能看到的业界直接开源全套的东西，真的是非常非常少。但是NVDIA做到了，
NVDLA可以认为是两个类型，一个是低功耗版，一个是高性能版本，但是架构相同，只是配置不同，上的MAC数量不同。

NVDLA可以认为它分成几个块
Convolution Core 卷积计算引擎
Single Data Processor Activation Function引擎
Planar Data Processor Pooling 引擎

Channel Data Processor Normalization Function引擎
Dedicated Memory and Data Reshape Engines 内存数据处理如Reshape、Copy等

这个架构都是可以通过配置来增加或者减少的，如果你倾向于增加什么方向的性能，就动那个好了。
# 参考
http://nvdla.org/primer.html  
https://github.com/CSL-KU/firesim-nvdla  RISC-V integrated NVDLA
https://arxiv.org/pdf/1903.06495.pdf     RISC-V integrated NVDLA
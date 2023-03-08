# 编译器基本概念
一句话的解释，编译器就是把源码编译成CPU/NPU/GPU能够执行的语言。其实编译器也是一个翻译器，就是一个软件。但是它可能是单一软件里应用了所有主流的计算机算法的产品。
这些算法会包括如下这些：
贪心算法 greedy algorithms (register allocation),
启发式搜索技术 heuristic search techniques (list scheduling), 
图算法 graph algorithms (dead-code elimination), 
动态规划 dynamic program- ming (instruction selection),
自动机理论  automata theory (scanning and parsing)
定点算法 fixed-point algorithms (data-flow analysis)
 
它同时也涉及到了非常多的数学方面的问题。如果做好一个编译器

说句不客气的话，Compiler是整个计算机世界的皇冠。
## 基本组成
前端->优化->后端代码生成
前端，负责把人类能明白表述出来的东西，翻译成一个中间结果 IR，这个结构是人与机器都能接受的。
优化，针对IR做优化，比如无用代码删除，算子融合。
代码生成，直接用代码生成标准数据。



## 参考
编译器设计 Engineering a Compiler Third Edition [美]Keith D. Cooper, Linda Torczon

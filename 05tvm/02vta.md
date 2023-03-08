# vta 是什么

# build VTA and tvm docker
Warning Using a mad network is to waste your life.  
. 首先要有所有的TVM代码下载到本地（安装Docker这个不用说了吧，尽管这东西越来越难用）
```
git clone --recursive https://github.com/apache/tvm tvm
```
切换到Docker这个目录下，开始编译镜像，要是想在本地运行，一定要选择好相应的镜像名字，通常X86平台用 ‘ci_cpu’ 是可以的。而'ci_gpu'一定要有GPU环境才成。
```
/path/to/tvm/docker/build.sh <image-name>
```



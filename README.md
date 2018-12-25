# openjdk-comment

从官方网站（ http://jdk.java.net/ ）下载的源码包，放到这里记录一下阅读源码后添加的注释，方便快速查阅。

原始源码在master分支，添加的注释在comment分支。

## Tips

- gdb中可以设置handle SIGSEGV pass noprint nostop，因为Hotspot中使用SEGV做一些自己的事情。具体参考https://stackoverflow.com/questions/44533670/jdk9-hotspot-debug-using-gdb-causing-sigsegv-segmentation-fault-in-eclipse-ubun
- 如果出错的话，尝试指定一下classpath

## Topics

1. JVM的启动
2. 线程的启动
3. JNI
4. C++ Interpreter初始化

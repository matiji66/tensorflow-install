# tensorflow-install
# 具体使用请参考文档： tensorflow install on win7 64.docx
环境是win7 64
Conda --version Anaconda 64 4.3.13

1.新建一个python 3.5 版本

conda create -n tensorflow python=3.5
2. Activate tensorflow
3. pip install tensorflow
4. 如何进入Python 命令行，使用tf呢
4.1 activate tensorflow
4.2 python 

5如何在PyCharm使用呢：
5.1在PyCharm中打开设置界面Ctrl +alt +s 快捷键


下面看到的是安装完Anaconda-python 2.7的解释器：



下面是手动切换到自己建立的tensorflow 的python3.5 环境的解释器：


选中之后就能使用python的3.5 的环境以及tensorflow的开发测试.

　　可见不论是在 python shell中还是在其他的python IDE 中都是很容易的进行python的版本切换。
　　这比使用docker安装方便多了，关键是搞了半天，docker-tool安装好了，但是dock的tensorflow镜像下载不下了。
　　
　　补充说明的是python以及python package的安装过程中使用国内的镜像比较快。

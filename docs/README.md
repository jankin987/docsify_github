
<div align=center style='display: none'>
<img width="500" src="img/cover.png" alt="封面"/>
</div>

<!--
[本项目](https://tangshusen.me/Dive-into-DL-PyTorch)将[《动手学深度学习》](http://zh.d2l.ai/) 原书中MXNet代码实现改为PyTorch实现。原书作者：阿斯顿·张、李沐、扎卡里 C. 立顿、亚历山大 J. 斯莫拉以及其他社区贡献者，GitHub地址：https://github.com/d2l-ai/d2l-zh

此书的[中](https://zh.d2l.ai/)[英](https://d2l.ai/)版本存在一些不同，针对此书英文版的PyTorch重构可参考[这个项目](https://github.com/dsgiitr/d2l-pytorch)。
There are some differences between the [Chinese](https://zh.d2l.ai/) and [English](https://d2l.ai/) versions of this book. For the PyTorch modifying of the English version, you can refer to [this repo](https://github.com/dsgiitr/d2l-pytorch).
-->
[本项目](https://tangshusen.me/Dive-into-DL-PyTorch)
## 简介
本仓库主要包含code和docs两个文件夹（外加一些数据存放在data中）。其中code文件夹就是每章相关jupyter notebook代码（基于PyTorch）；docs文件夹就是markdown格式的《动手学深度学习》书中的相关内容，然后利用[docsify](https://docsify.js.org/#/zh-cn/)将网页文档部署到GitHub Pages上，由于原书使用的是MXNet框架，所以docs内容可能与原书略有不同，但是整体内容是一样的。欢迎对本项目做出贡献或提出issue。

## 面向人群
本项目面向对深度学习感兴趣，尤其是想使用PyTorch进行深度学习的童鞋。本项目并不要求你有任何深度学习或者机器学习的背景知识，你只需了解基础的数学和编程，如基础的线性代数、微分和概率，以及基础的Python编程。

## 食用方法 
### 方法一
本仓库包含一些latex公式，但github的markdown原生是不支持公式显示的，而docs文件夹已经利用[docsify](https://docsify.js.org/#/zh-cn/)被部署到了GitHub Pages上，所以查看文档最简便的方法就是直接访问[本项目网页版](https://tangshusen.me/Dive-into-DL-PyTorch)。当然如果你还想跑一下运行相关代码的话还是得把本项目clone下来，然后运行code文件夹下相关代码。

### 方法二
你还可以在本地访问文档，先安装`docsify-cli`工具:
``` shell
npm i docsify-cli -g
```
然后将本项目clone到本地:
``` shell
git clone https://github.com/ShusenTang/Dive-into-DL-PyTorch.git
cd Dive-into-DL-PyTorch
```
然后运行一个本地服务器，这样就可以很方便的在`http://localhost:3000`实时访问文档网页渲染效果。
``` shell
docsify serve docs
```


## 目录
* [简介]()
* [阅读指南](read_guide.md)
* 1\. ubuntu操作系统配置
   * [1.1 装完操作系统后的常规步骤](chapter01_computer-skills/1.1_after-installed-ubuntu.md)
   * [1.2 装驱动和cuda](chapter01_computer-skills/1.2_nvidia_driver.md)
   * [1.3 smb](chapter01_computer-skills/1.3_smb.md)
   * [1.4 docker](chapter01_computer-skills/1.4_docker.md)
   * [1.5 远程技术](chapter01_computer-skills/1.5_remote.md)
   * [1.6 sublime text](chapter01_computer-skills/1.6_sublime.md)



持续更新中......




## 原书地址
中文版：[动手学深度学习](https://zh.d2l.ai/) | [Github仓库](https://github.com/d2l-ai/d2l-zh)       
English Version: [Dive into Deep Learning](https://d2l.ai/) | [Github Repo](https://github.com/d2l-ai/d2l-en)


## 引用
如果您在研究中使用了这个项目请引用原书:
```
@book{zhang2019dive,
    title={Dive into Deep Learning},
    author={Aston Zhang and Zachary C. Lipton and Mu Li and Alexander J. Smola},
    note={\url{http://www.d2l.ai}},
    year={2020}
}
```



# windows

## 本次安装的是

* 安装版本为 2.6，一定注意；
* mmcv可以在这里 https://openmmlab.oss-accelerate.aliyuncs.com/mmcv/dist/index.html，下载对应的版本，然后安装

## QA

##     Q. assert pycocotools.__version__ >= '12.0.2' AttributeError: module 'pycocotools' has no attribute '__version__'

这是由于pycocotools和mmpycocotools冲突，需要重装

```
pip uninstall pycocotools --no-cache-dir -y
pip install mmpycocotools --no-cache-dir --force --no-deps
```

## Q. 有没有教程

* 可以严格按照这个教程进行安装；get_started.md
* 有问题直接查一下

  

# mmdection框架学习的一些教程

## 初始三篇
* https://zhuanlan.zhihu.com/p/337375549
* https://zhuanlan.zhihu.com/p/341954021

## 轻松掌握 MMDetection 中常用算法

* [轻松掌握 MMDetection 中常用算法(一)：RetinaNet 及配置详解](https://zhuanlan.zhihu.com/p/346198300)


# 阅读经验
* [不得不知的 MMDetection 学习路线(个人经验版)](https://zhuanlan.zhihu.com/p/369826931)
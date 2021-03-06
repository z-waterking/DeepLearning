# DeepLearning库

## 说明

本代码库所用的python版本为Anaconda包中的3.6

pytorch环境为1.5.1: https://pytorch.org/get-started/previous-versions/

## 什么是好代码？

本库的目标在于写"笨代码"。
其间有两个要素，清晰的代码结构与完善的代码文档。

## 深度学习一般套路

1. 加载数据
2. 构造输入
3. 搭建网络
4. 计算输出
5. 计算loss
6. 反向传播
7. 打完收工

# Pytorch

## 1. Pytorch基础

基础部分做一个参考。随着Pytorch版本的提升，许多方法、变量都会废弃，

| Content    | .ipynb 文件  |  .py 文件 |
| ------------------ | :---------------------: | :--------------------------: |
| 1.Tensor基础 |  [Tensor基础.ipynb](PreKnowledge/1.Tensor基础.ipynb) | [Tensor基础.py](PreKnowledge/1.Tensor基础.py) |
| 2.autograd机制 | [autograd机制.ipynb](PreKnowledge/2.autograd机制.ipynb) | [autograd机制.py](PreKnowledge/2.autograd机制.py) |
| 3.线性回归 | [线性回归.ipynb](PreKnowledge/3.线性回归.ipynb) | [线性回归.py](PreKnowledge/3.线性回归.py) |
| 4.多层感知机 | [多层感知机.ipynb](PreKnowledge/4.多层感知机.ipynb) | [多层感知机.py](PreKnowledge/4.多层感知机.py) |
| 5.Dataset和DataLoader | [Dataset和DataLoader.ipynb](PreKnowledge/5.Dataset和DataLoader.ipynb) | [Dataset和DataLoader.py](PreKnowledge/5.Dataset和DataLoader.py) |
| 6.CNN和MNIST | [CNN和MNIST.ipynb](PreKnowledge/6.CNN和MNIST.ipynb) | [CNN和MNIST.py](PreKnowledge/6.CNN和MNIST.py) |
| 7.参数初始化和使用预训练模型 | [参数初始化和使用预训练模型.ipynb](PreKnowledge/7.参数初始化和使用预训练模型.ipynb) | [参数初始化和使用预训练模型.py](PreKnowledge/7.参数初始化和使用预训练模型.py) |
| 8.模型微调的各种trick | [模型微调的各种trick.ipynb](PreKnowledge/8.模型微调的各种trick.ipynb) | [模型微调的各种trick.py](PreKnowledge/8.模型微调的各种trick.py) |
| 9.模型保存和加载 | [模型保存和加载.ipynb](PreKnowledge/9.模型保存和加载.ipynb) | [模型保存和加载.py](PreKnowledge/save_load.py) |
| 10.循环神经网络（RNN） | [循环神经网络（RNN）.ipynb](PreKnowledge/10.循环神经网络.ipynb) | [循环神经网络（RNN）.py](PreKnowledge/10.循环神经网络.py) |

# 参考文献

* pytorch教程：http://pytorch123.com/

* pytorch-handbook: https://github.com/zergtant/pytorch-handbook

* pytorch-tutorial: https://github.com/yunjey/pytorch-tutorial

* 简单粗暴Tensorflow：https://tf.wiki/zh_hans

* 动手学深度学习：https://zh.d2l.ai/index.html
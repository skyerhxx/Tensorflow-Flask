# Tensorflow-Flask
Tensorflow与Flask结合打造手写体数字识别项目(MNIST数据集)

---

使用tensorflow框架，构建回归和CNN两种模型，对手写数字体进行识别

</br>

## 开发环境

* Python:3.7
* Tensorflow: 1.13.1
* cuda 10.1
* Flask: 1.1.2
* IDE: Pycharm
* OS：Win10

</br>

## 文件说明&运行方式

>*  main.py是主程序
>
>* src、static、templates是前端代码



> mnist目录中
>
> * convolutional.py和regression.py分别是训练线性回归模型和卷积模型的代码
>
> * model.py中是线性回归模型和卷积模型的代码的网络结构代码
>
> * data中存放生成的ckpt文件
>
> * tmp中是用于tensorboard的日志文件
>
> * MNIST_data是MNIST数据集



**运行方式：运行main.py**

</br>

## 项目具体过程：

- https://blog.csdn.net/hxxjxw/article/details/108088711
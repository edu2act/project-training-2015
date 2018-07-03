<img src="../../../image/logo.png"/>

# 2015级项目实训成果展示 

## 《Neural_Style_Transfrom》 - Python与机器学习


[Github](https://github.com/yanzhengbin/Neural_Style_Transform)

[Redmine](./readmine.md)

[项目的具体原理](./explain.md)


### 项目介绍

随着计算机计算能力和硬件水准的提升，基于大量数据处理的深度学习也迎来了一个自己发展的转折点，也着实惊艳了世界。谷歌公司的AlphaGo，这款围棋人工智能程序在2017年上半年取得了不小的成就。围棋一直被认为是智力高超的人类才能掌握的游戏，而AlphaGo不仅仅能够下围棋而且甚至打败了李世石，柯洁等一系列围棋大师。AlphaGo的后续版本：master等人工智能程序也成功地打败了围棋界的著名大师。这也宣布了人工智能时代的到来。

图像风格迁移是一种基于深度学习的图像处理程序，这款产品是通过深度神经网络将图像的风格转换为另一种风格，因此每个人都可以通过这款产品把自己的图片转换到自己想要的风格。
随着照相技术的发展，照片变的越来越清晰，但是这些照片的风格却是大同小异的。如果图像经过处理后得到一种完全不同的风格，那照相这件事就会变成一件有意思的事情。

###  项目组成员
我们的项目组由三个人构成，项目构建的过程主要涉及：编程环境的搭建，神经网络的构成，神经网络的训练过程，web界面的展示，这几个步骤。
其中：
* 闫政斌同学(主要负责神经网络的构建和调参过程。)
    * github: [https://github.com/yanzhengbin](https://github.com/yanzhengbin)
    * 邮箱:[912510143@qq.com](912510143@qq.com)
* 高燕昭同学(主要负责web端的展示。)
    * github: [https://github.com/Gaoyanzhao](https://github.com/Gaoyanzhao)
    * 邮箱:[837534638@qq.com](837534638@qq.com)
* 周海洋同学(主要负责编程环境的搭建过程和神经网络的训练过程。)
    * github: [https://github.com/haiyang007](https://github.com/haiyang007)
    * 邮箱:[522294609@qq.com](522294609@qq.com)

### 效果展示

|  | 《星月夜》 |时光塔|  《星月夜》版时光塔   |
|:---:|:-----:|:-----:|:--------:|
| 展示  | <img src='./image/style_denoised_starry.jpg'> | <img src='./image/timetower.jpg' width=400 height=256> |<img src='./image/timetower_gen.jpg' width=400 height=256> |

|  | 《wave》 |时光塔|  《wave》版时光塔   |
|:---:|:-----:|:-----:|:--------:|
| 展示  | <img src='./image/wave.jpg' width=256 height=256> | <img src='./image/timetower.jpg' width=400 height=256> |<img src='./image/wave_time.jpg' width=400 height=256> |

|  | 《cubist》 |时光塔|  《cubist》版时光塔   |
|:---:|:-----:|:-----:|:--------:|
| 展示  | <img src='./image/cubist.jpg' width=256 height=256> | <img src='./image/timetower.jpg' width=400 height=256> |<img src='./image/cubist_time.jpg' width=400 height=256> |

#### 首页

<img src='./image/home.jpg'>

#### 转换界面

<img src='./image/scre.jpg' >

#### 完成界面

<img src='./image/trans.jpg'>

### 项目主题

利用神经网络进行图片风格的迁移

### 项目范围

图片风格迁移能根据一张图片生成相应的风格图片。<br/>
我们会提供功能和展示的web端（基于Flask），用户可以自行选择风格图片和选择修改的图片，网站会给出相应的风格转换图片。<br/>
项目的主体分为两部分，一部分为神经网络的算法和结构的实现，另一部分为可视化的web界面。用户可以在web界面上进行操作。<br/>
项目的目标是能更快更准确地生成风格图片，更漂亮简洁地展示风格图片。通过改进算法来加快风格图片的生成，通过修改代码结构使展示界面更加简洁漂亮。

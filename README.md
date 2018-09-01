# PyTorch-Deep-Learning-Minicourse
Minicourse in Deep Learning with PyTorch [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/Atcold/PyTorch-Deep-Learning-Minicourse/master)
PyTorch-深学习型Minicourse
使用PyTorch进行深度学习的话语 活页夹

这些课程是在我在普渡大学和纽约大学教学的几年中开发的，现在被提议用于普林斯顿大学的高能物理计算和数据科学（CoDaS-HEP）暑期学校。已记录整个课程，并在此处提供播放列表。检查幻灯片以获得更好视觉质量的图纸。我还计划在更安静的环境中以更慢的速度录制它们，将它们添加到我的YouTube频道，并在此处提供。

目录
T：理论（幻灯片和动画）
P：练习（Jupyter笔记本）

T 学习范式：监督，无监督和强化学习
P 开始使用这些工具：Jupyter笔记本，PyTorch张量和自动分化
T+P 神经网络的前向和后向传播用于分类
T+P 卷积神经网络通过利用数据特性来提高性能
T+P 无监督学习：香草和变分自动编码器，生成对抗网
T+P 循环网络原生支持顺序数据
会议和相关材料
周二下午的时间段1（1小时30分钟+ 45分钟= 2小时15分钟）
主题：1,2,3。
幻灯片：01 - ML和螺旋分类。
笔记本电脑：01，02，03，04。
视频：01，02。
周三下午的时间段2（1小时30分钟+ 45分钟= 2小时15分钟）
主题：4。
幻灯片：02 - CNN。
笔记本：05。
视频：03，04。
周四下午的额外部分（45分钟）
主题：5。
幻灯片：03 - 生成模型。
笔记本电脑：06，07。
视频：05。
星期五早上的额外部分（1小时30分钟）
主题：6。
幻灯片：04 - RNN。
笔记本电脑：08-1，08-2，8月3日，8月4日。
视频：06。
笔记本可视化
在这些讲座中使用Jupyter笔记本进行交互式数据探索和可视化。

我对GitHub和Jupyter Notebook都使用了黑暗风格。你最好这样做，否则他们会看起来很难看。要正确查看内容，请安装以下内容：

Jupyter笔记本黑暗主题 ;
GitHub黑暗主题并注释掉invert #fff to #181818代码块。
媒体报道
普林斯顿研究计算机文章 ;
普林斯顿大学主页文章。
保持联系
欢迎在Twitter上关注我，订阅我的YouTube频道，获取最新的免费教育资料。

入门
为了能够跟进研讨会练习，您将需要一台配备Miniconda（Anaconda的最小版本）和几个Python软件包的笔记本电脑。以下说明将适用于Mac或Ubuntu Linux用户，Windows用户需要在Gitbash终端中安装和工作。

下载并安装Miniconda
请访问Anaconda网站。为您的操作系统下载并安装适用于Python 3.6 的最新 Miniconda版本。

wget < http：//链接到miniconda > 
sh < miniconda .sh >
之后，键入：

conda --help
并阅读手册。

通过练习签出git存储库
一旦Miniconda准备就绪，请检查课程存储库并继续设置环境：

git clone https://github.com/Atcold/PyTorch-Deep-Learning-Minicourse
如果你没有git并且不想安装它，只需将存储库下载为zip，然后解压缩它：

wget的https://github.com/Atcold/PyTorch-Deep-Learning-Minicourse/archive/master.zip
 ＃对于Mac用户：
＃卷曲-O https://github.com/Atcold/PyTorch-Deep-Learning-Minicourse /archive/master.zip 
unzip master.zip
创建孤立的Miniconda环境
切换到课程文件夹，然后键入：

＃ CD PyTorch-深学习型Minicourse
conda env create -f environment.yml
来源激活codas-ml
在Jupyter中启用anaconda内核
要在Jupyter中显示新创建的miniconda环境，请安装ipykernel：

python -m ipykernel install --user --name codas-ml --display-name “ Codas ML ”
启动jupyter笔记本
如果您正在使用JupyterLab容器，请双击右上角的“文件”选项卡。找到第一个笔记本，双击打开。不要尝试jupyter从终端窗口启动。

如果在笔记本电脑上工作，请照常从终端开始：

jupyter笔记本
These lessons, developed during the course of several years while I've been teaching at Purdue and NYU, are here proposed for the Computational and Data Science for High Energy Physics ([CoDaS-HEP](http://codas-hep.org/)) summer school at Princeton University.
The whole course has been recorded and the playlist is made available [here](https://www.youtube.com/playlist?list=PLLHTzKZzVU9duBIJCVGRh3tiy39d7Iz1q).
Check the slides for drawings of better visual quality.
I'm also planning to record them in a more quiet environment and at a slower pace, add them to my YouTube channel, and made available [here](https://github.com/Atcold/pytorch-Video-Tutorials).

## Table of contents
`T`: theory (slides and animations)  
`P`: practice (*Jupyter Notebooks*)

 1. `T` Learning paradigms: supervised-, unsupervised-, and reinforcement-learning
 2. `P` Getting started with the tools: Jupyter notebook, PyTorch tensors and autodifferentiation
 3. `T+P` Neural net's forward and backward propagation for classification
 4. `T+P` Convolutional neural nets improve performance by exploiting data nature
 5. `T+P` Unsupervised learning: vanilla and variational autoencoders, generative adversarial nets
 6. `T+P` Recurrent nets natively support sequential data

## Sessions and relative material
 1. Time slot 1 (1h30min + 45 min = 2h15min) on Tuesday afternoon  
    Topics: 1, 2, 3.  
    Slides: [01 - ML and spiral classification](slides/01%20-%20ML%20and%20spiral%20classification.pdf).  
    Notebooks: [01](01-tensor_tutorial.ipynb), [02](02-space_stretching.ipynb), [03](03-autograd_tutorial.ipynb), [04](04-spiral_classification.ipynb).  
    Videos: [01](https://youtu.be/u--4YzUQlj8), [02](https://youtu.be/panJ-pkaqBQ).
 2. Time slot 2 (1h30min + 45 min = 2h15min) on Wednesday afternoon  
    Topic: 4.  
    Slides: [02 - CNN](slides/02%20-%20CNN.pdf).  
    Notebook: [05](05-convnet.ipynb).  
    Videos: [03](https://youtu.be/jFK4odq_f0A), [04](https://youtu.be/ST73HFC4Lpo).
 3. Extra section (45min) on Thursday afternoon  
    Topic: 5.  
    Slides: [03 - Generative models](slides/03%20-%20Generative%20models.pdf).  
    Notebooks: [06](06-autoencoder.ipynb), [07](07-VAE.ipynb).  
    Video: [05](https://youtu.be/PRKq8ztYkZw).
 4. Extra section (1h30min) on Friday morning  
    Topic: 6.  
    Slides: [04 - RNN](slides/04%20-%20RNN.pdf).  
    Notebooks: [08-1](08-1-classify_seq_data.ipynb), [08-2](08-2-echo_data.ipynb), [08-3](08-3-temporal_order_classification_experiments.ipynb), [08-4](08-4-echo_experiments.ipynb	).  
    Video: [06](https://youtu.be/S2kNR3R30s8).

## Notebooks visualisation
*Jupyter Notebooks* are used throughout these lectures for interactive data exploration and visualisation.

I use dark styles for both *GitHub* and *Jupyter Notebook*.
You better do the same, or they will look ugly.
To see the content appropriately install the following:

 - [*Jupyter Notebook* dark theme](https://userstyles.org/styles/153443/jupyter-notebook-dark);
 - [*GitHub* dark theme](https://userstyles.org/styles/37035/github-dark) and comment out the `invert #fff to #181818` code block.

## Media coverage
 - Princeton Research Computing [article](https://researchcomputing.princeton.edu/news/princetons-codas-hep-summer-school-young-physicists-gain-edge-computational-skills);
 - Princeton University main page [article](https://www.princeton.edu/news/2018/07/27/princeton-summer-program-graduate-student-physicists-gain-computational-skills).

## Keeping in touch
Feel free to follow me on [Twitter](https://twitter.com/AlfredoCanziani) and subscribe to my [YouTube channel](https://www.youtube.com/user/Atcold/) to have the latest free educational material.

# Getting started
To be able to follow the workshop exercises, you are going to need a laptop with Miniconda (a minimal version of Anaconda) and several Python packages installed.
Following instruction would work as is for Mac or Ubuntu linux users, Windows users would need to install and work in the Gitbash terminal.

## Download and install Miniconda
Please go to the [Anaconda website](https://conda.io/miniconda.html).
Download and install *the latest* Miniconda version for *Python* 3.6 for your operating system.

```bash
wget <http:// link to miniconda>
sh <miniconda .sh>
```

After that, type:

```bash
conda --help
```

and read the manual.

## Check-out the git repository with the exercise
Once Miniconda is ready, checkout the course repository and and proceed with setting up the environment:

```bash
git clone https://github.com/Atcold/PyTorch-Deep-Learning-Minicourse
```

If you do not have git and do not wish to install it, just download the repository as zip, and unpack it:

```bash
wget https://github.com/Atcold/PyTorch-Deep-Learning-Minicourse/archive/master.zip
#For Mac users:
#curl -O https://github.com/Atcold/PyTorch-Deep-Learning-Minicourse/archive/master.zip
unzip master.zip
```

## Create isolated Miniconda environment
Change into the course folder, then type:

```bash
#cd PyTorch-Deep-Learning-Minicourse
conda env create -f environment.yml
source activate codas-ml
```

## Enable anaconda kernel in Jupyter
To make newly created miniconda environment visible in the Jupyter, install `ipykernel`:

```bash
python -m ipykernel install --user --name codas-ml --display-name "Codas ML"
```

## Start jupyter notebook
If you are working in a JupyterLab container double click on "Files" tab in the upper right corner.
Locate first notebook, double click to open.
Do not attempt to start `jupyter` from the terminal window.

If working on a laptop, start from terminal as usual:

```bash
jupyter notebook
```

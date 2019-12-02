# 前言

Hey，大家好。

恭喜你终于下定决心要上路。 这一章我们将学习如何通过 Ananconda 来安装 Python。

说实话，安装 Python 有很多方法，甚至你如果用的是 Mac，连安装都不用，系统自带了 Python。而我推荐的，也是我觉得最方便的方式就是 Anaconda。

# 什么是 Anaconda？

Anaconda 对 Python 来说是一个百宝箱。Anaconda 包含了conda、Python在内的超过180个科学包及其依赖项。

Anaconda 是一个包含 180+ 的数据科学包及其依赖项的发行版本。其包含的科学包包括：conda, numpy, scipy, ipython notebook等。

给一个生动的比喻：

XXXXX

## 1. 适用平台
Anaconda可以在以下系统平台中安装和使用：
+ Windows
+ macOS
+ Linux（x86 / Power8）

## 2. 安装条件
+ 系统要求：32位或64位系统均可
+ 下载文件大小：约500MB
+ 所需空间大小：3GB空间大小（Miniconda仅需400MB空间即可）

# macOS 系统安装 Anaconda 步骤

## 1. 下载 Anaconda，[最新下载地址](https://www.anaconda.com/distribution/)

- 注意下载对应版本，Windows 或者是 Mac
- 选择 Python3 就好

[图：下载页面]

## 2. 完成下载之后，双击下载文件

在对话框中“Introduction”、“Read Me”、“License”部分可直接点击下一步

## 3. “Destination Select”部分选择“Install for me only”并点击下一步。

注意：若有错误提示信息“You cannot install Anaconda in this location”则重新选择“Install for me only”并点击下一步。

## 4. “Installation Type”部分

可以点击“Change Install Location”来改变安装位置。标准的安装路径是在用户的家目录下。在这一步我没有改变安装位置。若选择默认安装路径，则直接点击“Install”进行安装。

## 5. 等待“Installation”部分结束

在“Summary”部分若看到“The installation was completed successfully.”则安装成功，直接点击“Close”关闭对话框。
 
## 6. 在mac的Launchpad中可以找到名为“Anaconda-Navigator”的图标，点击打开。

## 7. 若“Anaconda-Navigator”成功启动，则说明真正成功地安装了Anaconda；如果未成功，请务必仔细检查以上安装步骤。

提示：“Anaconda-Navigator”中已经包含“Jupyter Notebook”、“Jupyterlab”、“Qtconsole”和“Spyder”。（图中的“Rstudio”是我后来安装的，但它默认出现在“Anaconda-Navigator”的启动界面，只需要点击“Install”便可安装。）

Jupyter Notebook 有助于我们编写代码、运行代码以及获取代码的运行结果，特点是可以令我们便捷地为代码及其运行结果添加文档的描述、解释和说明。无论是学习还是工作，Jupyter Notebook 都是提高效率和学习、工作质量的利器。

也是我们接下来学习的重要工具，具体的使用，可以跳到下一篇文章：[《》]()

# windows 系统安装 Anaconda 步骤

## 1. 前往官方下载页面下载。有两个版本可供选择：Python 3.6 和 Python 2.7，选择版之后根据自己操作系统的情况点击“64-Bit Graphical Installer”或“32-Bit Graphical Installer”进行下载。

## 2. 完成下载之后，双击下载文件，启动安装程序。

注意：
① 如果在安装过程中遇到任何问题，那么暂时地关闭杀毒软件，并在安装程序完成之后再打开。

② 如果在安装时选择了“为所有用户安装”，则卸载Anaconda然后重新安装，只为“我这个用户”安装。

## 3. 选择“Next”。

## 4. 阅读许可证协议条款，然后勾选“I Agree”并进行下一步。

## 5. 除非是以管理员身份为所有用户安装，否则仅勾选“Just Me”并点击“Next”。

## 6. 在“Choose Install Location”界面中选择安装Anaconda的目标路径，然后点击“Next”。

注意：
① 目标路径中不能含有空格，同时不能是“unicode”编码。

② 除非被要求以管理员权限安装，否则不要以管理员身份安装。

# Anaconda 基础操作


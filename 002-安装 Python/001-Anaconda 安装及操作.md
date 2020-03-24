![](https://pptwinpics.oss-cn-beijing.aliyuncs.com/CDA%E8%AE%B2%E5%B8%88%E6%B0%B4%E5%8D%B0_20200314161940.png)

# 前言

大家好，我是 CDA 曹鑫。

我的 Github 地址：https://github.com/imcda 。

我的邮箱：caoxin@cda.cn 。

这节课我们将学习如何通过 Anaconda 来安装 Python。

说实话，安装 Python 有很多方法，甚至你如果用的是 Mac，连安装都不用，系统就自带了 Python，我也曾经在一台电脑用3种方法装了4-5个版本的 Python，以至于我一段时间不用，都不知道该怎么打开对应版本的 Python 了。所以，今天我推荐的，也是我觉得最方便的方式就是 Anaconda。

# 什么是 Anaconda？

Anaconda 对 Python 来说是一个百宝箱。Anaconda 包含了conda、Python在内的超过180个科学包及其依赖项。

Anaconda 是一个包含 180+ 的数据科学包及其依赖项的开发平台。其包含的科学包包括：conda, numpy, scipy, ipython notebook等。

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

## 1. 下载 Anaconda
**[最新下载地址](https://www.anaconda.com/distribution/)**

![Anaconda-下载](https://pptwinpics.oss-cn-beijing.aliyuncs.com/Anaconda-%E4%B8%8B%E8%BD%BD_20191216095539.png)

- 注意下载对应版本，Windows 或者是 Mac
- 选择 Python3 就好

## 2. 完成下载之后，双击下载文件

在对话框中“Introduction”、“Read Me”、“License”部分可直接点击下一步

## 3. “Destination Select”部分选择“Install for me only”并点击下一步。

注意：若有错误提示信息“You cannot install Anaconda in this location”则重新选择“Install for me only”并点击下一步。

![Anaconda-安装-1](https://pptwinpics.oss-cn-beijing.aliyuncs.com/Anaconda-%E5%AE%89%E8%A3%85-1_20191216090830.jpg)

## 4. “Installation Type”部分

可以点击“Change Install Location”来改变安装位置。标准的安装路径是在用户的家目录下。在这一步我没有改变安装位置。若选择默认安装路径，则直接点击“Install”进行安装。

![Anaconda-安装-2](https://pptwinpics.oss-cn-beijing.aliyuncs.com/Anaconda-%E5%AE%89%E8%A3%85-2_20191216090926.jpg)

## 5. 等待“Installation”部分结束

在“Summary”部分若看到“The installation was completed successfully.”则安装成功，直接点击“Close”关闭对话框。

![Anaconda-安装-3](https://pptwinpics.oss-cn-beijing.aliyuncs.com/Anaconda-%E5%AE%89%E8%A3%85-3_20191216091004.jpg)
 
## 6. 在mac的Launchpad中可以找到名为“Anaconda-Navigator”的图标，点击打开。

![Anaconda-安装-4](https://pptwinpics.oss-cn-beijing.aliyuncs.com/Anaconda-%E5%AE%89%E8%A3%85-4_20191216091111.jpg)

## 7. 若“Anaconda-Navigator”成功启动，则说明真正成功地安装了Anaconda；如果未成功，请务必仔细检查以上安装步骤。

![Anaconda-安装-5](https://pptwinpics.oss-cn-beijing.aliyuncs.com/Anaconda-%E5%AE%89%E8%A3%85-5_20191216091254.jpg)

提示：“Anaconda-Navigator”中已经包含“Jupyter Notebook”、“Jupyterlab”、“Qtconsole”和“Spyder”。（比如图中的“Rstudio”，它默认出现在“Anaconda-Navigator”的启动界面，只需要点击“Install”便可安装。）

Jupyter Notebook 有助于我们编写代码、运行代码以及获取代码的运行结果，特点是可以令我们便捷地为代码及其运行结果添加文档的描述、解释和说明。无论是学习还是工作，Jupyter Notebook 都是提高效率和学习、工作质量的利器。

也是我们接下来学习的重要工具，具体的使用，可以跳到下一篇文章：[《Jupyter Notebook 教程》](https://github.com/imcda/Python-Tutorial-for-Humans/blob/editing/002-%E5%AE%89%E8%A3%85%20Python/002-Jupyter%20Notebook%20%E6%95%99%E7%A8%8B.ipynb)

# windows 系统安装 Anaconda 步骤

## 1. 前往官方下载页面下载
**[最新下载地址](https://www.anaconda.com/distribution/)**

![Anaconda-下载](https://pptwinpics.oss-cn-beijing.aliyuncs.com/Anaconda-%E4%B8%8B%E8%BD%BD_20191216095539.png)

有两个版本可供选择：Python 3.6 和 Python 2.7，选择版之后根据自己操作系统的情况点击“64-Bit Graphical Installer”或“32-Bit Graphical Installer”进行下载。

**版本选择 Python 3 即可，通常系统也是选择 64-Bit Graphical Installer**

## 2. 完成下载之后，双击下载文件，启动安装程序。

注意：
- 如果在安装过程中遇到任何问题，那么暂时地关闭杀毒软件，并在安装程序完成之后再打开。

- 如果在安装时选择了“为所有用户安装”，则卸载Anaconda然后重新安装，只为“我这个用户”安装。

## 3. 选择“Next”。

## 4. 阅读许可证协议条款，然后勾选“I Agree”并进行下一步。

## 5. 除非是以管理员身份为所有用户安装，否则仅勾选“Just Me”并点击“Next”。

## 6. 在“Choose Install Location”界面中选择安装Anaconda的目标路径，然后点击“Next”。

注意：
- 目标路径中不能含有空格，同时不能是“unicode”编码。

- 除非被要求以管理员权限安装，否则不要以管理员身份安装。

![Win-Anaconda-安装-1](https://pptwinpics.oss-cn-beijing.aliyuncs.com/Win-Anaconda-%E5%AE%89%E8%A3%85-1_20191216091606.jpg)

## 7. 在“Advanced Installation Options”中要勾选“Add Anaconda to my PATH environment variable.”（“添加Anaconda至我的环境变量。”）。

同时勾选“Register Anaconda as my default Python 3.6”。

然后点击“Install”开始安装。如果想要查看安装细节，则可以点击“Show Details”。

![Win-Anaconda-安装-2](https://pptwinpics.oss-cn-beijing.aliyuncs.com/Win-Anaconda-%E5%AE%89%E8%A3%85-2_20191216091911.jpg)

**注意：**

如果你没有勾选，在 windows 端，你可以右击我的电脑->属性->高级系统设置->环境变量，在下面的系统变量里面，找到path。打开，新建，添加

`C:\Users\你的用户名\Anaconda3`

`C:\Users\你的用户名\Anaconda3\Scripts`

![](https://pptwinpics.oss-cn-beijing.aliyuncs.com/20171103165713538_20200324085704.png)

## 8. 点击“Next”。

## 9. 进入“Thanks for installing Anaconda!”界面则意味着安装成功，点击“Finish”完成安装。

**注意：**
如果你不想了解“Anaconda云”和“Anaconda支持”，则可以不勾选“Learn more about Anaconda Cloud”和“Learn more about Anaconda Support”。

![Win-Anaconda-安装-3](https://pptwinpics.oss-cn-beijing.aliyuncs.com/Win-Anaconda-%E5%AE%89%E8%A3%85-3_20191216091951.jpg)

## 10. 验证安装结果。可选以下任意方法：

- “开始 → Anaconda3（64-bit）→ Anaconda Navigator”，若可以成功启动Anaconda Navigator则说明安装成功。

- “开始 → Anaconda3（64-bit）→ 右键点击Anaconda Prompt → 以管理员身份运行”，在Anaconda Prompt中输入 conda list ，可以查看已经安装的包名和版本号。若结果可以正常显示，则说明安装成功。

![](https://pptwinpics.oss-cn-beijing.aliyuncs.com/CDA%E8%AE%B2%E5%B8%88%E6%B0%B4%E5%8D%B0_20200314161940.png)

# Anaconda 基础操作：conda 

接下来均是以命令行模式进行介绍，Windows用户请打开“Anaconda Prompt”；macOS和Linux用户请打开“Terminal”（“终端”）进行操作。

## 1. 验证conda已被安装
```
conda --version
```
终端上将会以 `conda` 版本号 的形式显示当前安装`conda`的版本号。如： `conda 3.11.0`

**注意：**
如果出现错误信息，则需核实是否出现以下情况：
- 使用的用户是否是安装Anaconda时的账户。
- 是否在安装Anaconda之后重启了终端。

## 2. 更新conda至最新版本
```
conda update conda
```

执行命令后，`conda`将会对版本进行比较并列出可以升级的版本。同时，也会告知用户其他相关包也会升级到相应版本。

当较新的版本可以用于升级时，终端会显示 `Proceed ([y]/n)?` ，此时输入 `y` 即可进行升级。

## 3. 查看conda帮助信息
```
conda --help
```
或
```
conda -h
```

## 4. 卸载conda

**Linux 或 macOS**
```
rm -rf ~/anaconda3
```
即删除Anaconda的安装目录。根据安装的Anaconda版本选择相应的卸载命令。

**Windows**

控制面板 → 添加或删除程序 → 选择“Python X.X (Anaconda)” → 点击“删除程序”

**注意：**
- Python X.X：即Python的版本，如：Python 3.6。
- Windows 10的删除有所不同。

# Anaconda 基础操作：管理包

## 1. 查找可供安装的包版本

**精确查找**
```
conda search --full-name <package_full_name>
```
**注意：**
- --full-name 为精确查找的参数。

- `<package_full_name>` 是被查找包的全名。包名两边不加尖括号`<>`。

例如： `conda search --full-name python` 即查找全名为`python`的包有哪些版本可供安装。


**模糊查找**
```
conda search <text>
```
**注意：** `<text>` 是查找含有此字段的包名。此字段两边不加尖括号`<>`。
**例如：** `conda search py` 即查找含有`py`字段的包，有哪些版本可供安装。

## 2. 获取当前环境中已安装的包信息
```
conda list
```
执行上述命令后将在终端显示当前环境已安装包的包名及其版本号。

## 3. 安装包

**在当前环境中安装包**
```
conda install <package_name>
```
**注意：**
- `<package_name>` 即要安装的包名。包名两边不加尖括号`<>`。

- 执行命令后在当前环境中安装包。

例如：`conda install pandas` 即在当前环境中安装pandas包。

**使用pip安装包**

**使用场景**

当使用 `conda install` 无法进行安装时，可以使用`pip`进行安装。例如：see包。

**命令**
```
pip install <package_name>
```
**注意：**
-  `<package_name>` 为指定安装包的名称。包名两边不加尖括号`<>`。
如：`pip install see` 即安装see包。

**注意**

- pip只是包管理器，无法对环境进行管理。因此如果想在指定环境中使用pip进行安装包，则需要先切换到指定环境中，再使用pip命令安装包。
- pip无法更新python，因为pip并不将python视为包。
- pip可以安装一些conda无法安装的包；conda也可以安装一些pip无法安装的包。因此当使用一种命令无法安装包时，可以尝试用另一种命令。

## 4. 卸载包

**卸载当前环境中的包**
```
conda remove <package_name>
```
**注意：**
- `<package_name>` 即要卸载包的名称。包名两边不加尖括号`<>`。

- 执行命令后即在当前环境中卸载指定包。

例如： `conda remove pandas` 即在当前环境中卸载pandas包。

## 5. 更新包

**更新所有包**

```
conda update --all
```
或

```
conda upgrade --all
```
建议：在安装Anaconda之后执行上述命令更新Anaconda中的所有包至最新版本，便于使用。

**更新指定包**

```
conda update <package_name>
```
或
```
conda upgrade <package_name>
```
**注意：**
- `<package_name>` 为指定更新的包名。包名两边不加尖括号`<>`。

- 更新多个指定包，则包名以空格隔开，向后排列。如： `conda update pandas numpy matplotlib` 即更新`pandas`、`numpy`、`matplotlib`包。

![](https://pptwinpics.oss-cn-beijing.aliyuncs.com/CDA%E8%AE%B2%E5%B8%88%E6%B0%B4%E5%8D%B0_20200314161940.png)
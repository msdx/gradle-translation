Gradle 翻译
===

此项目为 Gradle 翻译项目，使用 OmegaT 辅助翻译软件，目前翻译版本为 Gradle 1.12。翻译的章节，将合并到 [msdx/gradledoc](https://github.com/msdx/gradledoc) 项目当中。


加入翻译
---


**1.下载并安装OmegaT**

你可以从OmegaT官网上下载，或者从我的百度网盘中下载，地址如下：http://pan.baidu.com/s/1c0pMOPa

**2.fork 本项目**

点击右上角fork按钮，将本项目fork到你自己的项目当中。

**3.检出本项目**

打开OmegaT，点击项目菜单，下载团队项目，填入版本库网址及选择本地空文件夹，按确定。

**4.使用翻译引擎辅助翻译**

在OmegaT当中，你可以使用翻译引擎。必应API申请教程可以参考此帖：http://www.5icat.cn/thread-7180-1-1.html。然后打开OmegaT的安装目录的`OmegaT.l4J.ini`文件，加上以下代码：
```
-Dmicrosoft.api.client_id=你申请的APP ID 
-Dmicrosoft.api.client_secret=你申请的APP SECRET
```
然后在OmegaT的选项菜单中，选择机器翻译，勾上Microsoft Translator，并把界面底部的机器翻译窗口拖到右下角即可。
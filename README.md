Gradle 翻译
===

此项目为 Gradle 翻译项目，使用 OmegaT 辅助翻译软件，目前翻译版本为 Gradle 1.12。翻译的章节，将合并到 [msdx/gradledoc](https://github.com/msdx/gradledoc) 项目当中。


加入翻译
---

**1.下载并安装OmegaT**

你可以从OmegaT官网上下载，或者从我的百度网盘中下载，地址如下：http://pan.baidu.com/s/1c0pMOPa

**2.加入本项目**

留言加入本项目。

**3.检出本项目**

打开OmegaT，点击项目菜单，下载团队项目，填入版本库网址及选择本地空文件夹，按确定。

**4.使用翻译引擎辅助翻译**

在OmegaT当中，你可以使用翻译引擎。必应API申请教程可以参考此帖：`http://www.5icat.cn/thread-7180-1-1.html`。然后打开OmegaT的安装目录的`OmegaT.l4J.ini`文件，加上以下代码：
```
-Dmicrosoft.api.client_id=你申请的APP ID 
-Dmicrosoft.api.client_secret=你申请的APP SECRET
```
接着在OmegaT的选项菜单中，选择机器翻译，勾上Microsoft Translator，并把界面底部的机器翻译窗口拖到右下角即可。

**5.开始翻译**

在项目文件窗口（如果没有，请在项目菜单中找到并打开）中，选择*其他人未翻译的*文件，开始翻译。

翻译计划
---
目前先翻译1.12版本，翻译完成后，branch出1.12的分支，然后升级到2.0，继续翻译，以此类推。

由于使用了计算机辅助翻译软件，有翻译记忆库，更新版本的翻译效率会提高很多。

每一个章节翻译完毕，将整合到双语版的 Gradle 翻译项目(https://github.com/msdx/gradledoc)当中。
---
title: "Decrypt9（浏览器）"
permalink: /decrypt9-(browser).html
lang: zh_CN
ref: decrypt9-(browser)
---

本教程要做的第一件事就是让你运行Decrypt9，它是一个多用途的工具，可以允许我们安装包含漏洞的2.1.0版本的固件。我们需要这一漏洞以便完成后续的破解。
{: .notice}

如果你的3DS之前已经破解，并安装了基于EmuNAND的自制系统，请务必注意本教程仅适用于SysNAND，教程内的步骤应当应用在你的SysNAND上。注意EmuNAND和RedNAND是[同一概念](http://3dbrew.org/wiki/NAND_Redirection)的两种略微不同的实现。
{: .notice--info}

#### 你需要

* 最新版本的[Decrypt9WIP](https://github.com/d0k3/Decrypt9WIP/releases/latest)

#### 操作指南

1. 在SD卡根目录下创建`files9`文件夹（如果没有的话）
2. 解压缩Decrypt9WIP压缩包，复制其中的`Launcher.dat`和`Decrypt9WIP.dat`文件到你SD卡的根目录
3. 将SD卡重新插入你的3DS
4. 在3DS上打开浏览器然后进入到下面任意一个连接
  + `https://dukesrg.github.io/?Decrypt9WIP.dat`
  + `http://go.gateway-3ds.com/`
  + `http://www.reboot.ms/3ds/load.html?Launcher.dat`
  + `http://dukesrg.dynu.net/3ds/rop?GW17567.dat&Launcher.dat`
  + 如果第一个网址用不了，把剩下的都试一下（有些机器用不了第一个网址，有些用不了后三个）
  + 如果出现错误，参见[问题排查](Troubleshooting#ts_browser)
5. 如果漏洞利用成功，Decrypt9将会启动

---

继续进行[2.1.0 ctr迁移](2.1.0-ctrtransfer)
{: .notice--primary}

# WSL 使用指南 User's Guidance

### 00 项目愿景 Project Vision

#### 项目由来 Project Origin

&emsp;&emsp;作为软粉，WSL在诞生之际我便开启这项功能了，但是直到我学习Hadoop分布式课程时我才真正开始研究WSL。 As a soft powder, I started this feature when WSL was born, but I didn't really start researching WSL until I was studying the Hadoop distributed course. 

&emsp;&emsp;我的WSL之旅总的来说是“一步一个坑”，从研究如何安装桌面环境到如何实现两台Win10设备的WSL之间通过ssh连接（以实现Hadoop“真”分布式）；从研究WSL内部的自动化到研究Win10和WSL协同的自动化（以实现一键开启WSL桌面环境）……由于WSL底层限制较多，一些完整Linux系统的组件无法直接在WSL中使用，但这些无法掩盖WSL的优秀潜力！WSL的出现大幅简化了使用Linux工具链的操作，作为子系统存在也避免了虚拟机的资源消耗……（关于WSL的详细介绍见文章[WSL入门][1]） My WSL trip is generally "one step at a time", from researching how to install the desktop environment to how to implement WSL between two Win10 devices via ssh connection (to achieve Hadoop "true" distributed); from researching WSL Internal automation to study the automation of Win10 and WSL collaboration (to achieve a one-click open WSL desktop environment) ... due to the underlying restrictions of WSL, some components of the complete Linux system can not be used directly in WSL, but these can not cover the excellent WSL potential! The emergence of WSL greatly simplifies the operation of using the Linux toolchain. As a subsystem, it also avoids the virtual machine's resource consumption... (For a detailed introduction to WSL, see the article [WSL Getting Started] [1]) 

&emsp;&emsp;在“驯服”WSL的路上，我走过不少坑，但我们每个人不必都经历一遍，通过本指南，希望WSL能在大家手中实现更多可能！（WSL Guideline的后续内容将以**Ubuntu发行版**为主）On the way to "taming" WSL, I walked through a lot of pits, but each of us didn't have to go through it. Through this guide, I hope that WSL can realize more possibilities in everyone's hands! (The follow-up content of the WSL Guideline will be based on the **Ubuntu distribution**)

&emsp;&emsp;Enjoy！



### 目录  Table of Contents

&emsp;&emsp;[01 WSL入门][1] [01 Getting Started with WSL][1]

&emsp;&emsp;[02 安装配置][2] [02 Installation Configuration][2]

&emsp;&emsp;[03 避免的坑][3] [03 Pits to Avoid][3]

&emsp;&emsp;[04 安装桌面环境][4] [04 Install Desktop Environment][4]

&emsp;&emsp;[05 自定义桌面环境][5] [05 Custom Desktop Environment][5]

&emsp;&emsp;[06 配置SSH][6] [06 Configuring SSH][6]

&emsp;&emsp;[07 通过脚本提高效率][7] [07 Improve Efficiency Through Scripts][7]

[1]:01-WSL入门.md [1]: Getting Started with WSL.md

[2]:02-安装配置.md [2]: Installation Configuration.md

[3]:03-避免的坑.md [3]: Avoided Pits.md

[4]:04-安装桌面环境.md [4]: Installing the Desktop Environment.md

[5]:05-自定义桌面环境.md [5]: Custom Desktop Environment.md

[6]:06-配置SSH.md [6]: Configure SSH.md

[7]:07-通过脚本提高效率.md [7]: Increase Efficiency Through Scripting.md

---
《WSL使用指南》也会有[英文版](../English/00-About.md) The WSL User Guide will also have [English]

---
本作品采用[知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议][privacy]进行许可。欢迎转载、使用、重新发布，但务必保留文章署名Wang Jiaxiang（包含链接：[https://github.com/iWangJiaxiang/WSL-Guideline][github]），不得用于商业目的，基于本文修改后的作品务必以相同的许可发布。如有任何疑问，请[与我联系][contact]。 This work is licensed under [Creative Commons Attribution-Noncommercial Use-Share Alike 4.0 International License Agreement] [privacy]. Welcome to reprint, use, re-release, but be sure to keep the article signed by Wang Jiaxiang (including the link: [https://github.com/iWangJiaxiang/WSL-Guideline][github]), not for commercial purposes, based on this revised Works must be published under the same license. If you have any questions, please contact me [contact].

[privacy]:https://creativecommons.org/licenses/by-nc-sa/4.0/
[github]:https://github.com/iWangJiaxiang/WSL-Guideline
[contact]:mailto:iwangjiaxiang@outlook.com

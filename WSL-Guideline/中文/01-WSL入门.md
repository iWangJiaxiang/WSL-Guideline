# WSL 使用指南

### 01 WSL入门

#### 什么是WSL

&emsp;&emsp;WSL是“Windows Subsystem for Linux”的缩写，顾名思义，WSL就是Windows系统的Linux子系统，其作为Windows组件搭载在Windows10周年更新（1607）后的Windows系统中。  

&emsp;&emsp;既然WSL是“子系统”，那么WSL的地位我们能大概推测出——  
1. “子系统”作为系统层的一部分，相较于应用层（虚拟机）会消耗更少的资源，并且与系统锲合度更高。  
2. 因为“子系统”依附于“系统”，所以“子系统”会受到一些限制。  

&emsp;&emsp;事实上，的确是这样！只需要打开一个类似`CMD`的Bash命令行窗口，你的WSL就可以使用了（相当于建立了一个Session，因为WSL会一直伴随Win10的运行而运行），相对于从虚拟机启动既省时又省力。
除此之外，虽然WSL不是完整的Linux系统，但你依然可以做到绝大多数在完整Linux系统能做的事（比如`vim`, `apt-get`等）。

&emsp;&emsp;我们知道，Linux是一个系统内核，那么WSL是Linux发行版吗？并不是。WSL本质上是系统层面对Linux内核的支持，我们在Win10的应用商店[Microsoft Store][MSStore]内搜索下载我们喜欢的Linux发行版即可。目前，WSL支持[Ubuntu][ubuntu-l]，[Kali Linux][kali-l]，[GNU][GNU-l]，[OpenSUSE][suse-l]等，后续可能会有更多Linux发行版支持WSL。

&emsp;&emsp;更多详细信息请参阅微软官方文档[Windows Subsystem for Linux Documentation](https://docs.microsoft.com/en-us/windows/wsl/about)以及[Windows Command Line Tools For Developers](https://blogs.msdn.microsoft.com/commandline/)

---
#### 下一步

* 了解WSL的[安装和配置](02-安装配置.md)

[MSStore]:https://www.microsoft.com/zh-cn/store/apps/

[ubuntu-l]:https://www.microsoft.com/zh-cn/store/p/ubuntu/9nblggh4msv6

[kali-l]:https://www.microsoft.com/zh-cn/store/p/kali-linux/9pkr34tncv07

[suse-l]:https://www.microsoft.com/zh-cn/store/p/opensuse-leap-42/9njvjts82tjx

[GNU-l]:https://www.microsoft.com/zh-cn/store/p/debian-gnu-linux/9msvkqc78pk6

---
本作品采用[知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议][privacy]进行许可。欢迎转载、使用、重新发布，但务必保留文章署名Wang Jiaxiang（包含链接：[https://github.com/WangJiaxiang96/WSL-Guideline][github]），不得用于商业目的，基于本文修改后的作品务必以相同的许可发布。如有任何疑问，请[与我联系][contact]。 

[privacy]:https://creativecommons.org/licenses/by-nc-sa/4.0/
[github]:https://github.com/WangJiaxiang96/WSL-Guideline
[contact]:mailto:iwangjiaxiang@outlook.com

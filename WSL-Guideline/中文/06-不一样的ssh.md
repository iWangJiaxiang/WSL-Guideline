# WSL 使用指南

### 06 不一样的ssh

&emsp;&emsp;众所周知，SSH的默认连接端口是`22`，但是微软在Win10中内置了`SSH Server For Windows`并占用了默认的`22`端口，因此如果要在WSL中开启`SSH Server`，我们必须修改WSL中的默认SSH监听端口。Win10新增的SSH Server服务如下：

&emsp;&emsp;<img width="300" src="../images/06-不一样的ssh/ssh-server-for-windows.png">    

当然，也要在Windows防火墙中允许WSL SSH端口


---
#### 下一步

* 了解如何[通过脚本提高效率](07-通过脚本提高效率.md)
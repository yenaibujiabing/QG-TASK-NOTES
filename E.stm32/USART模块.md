# USART
在stm32使用USART模块不可或缺的两个环节分别就是**IO口的配置**以及**USART模块的配置**

在读取数据或者发送数据有三个重要的标志位：TXE,TC,RXNE
基本上需要读取或者发送数据的时候都需要查看存储器是否为空或者过程是否完成来决定是否进行下一步。

![alt text](c99a466c0db36bc7c33e4fb3b4e9b24a.png)
![alt text](6601a7ae27a06ab021eb138c97de21ce.jpg)
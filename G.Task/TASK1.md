# 用RTOS完成两灯闪烁
![所用函数与变量](f97baac833f77d8bce87679312d85d25.png)
![TASK](bafc706c3d1cf73533f5c11521c18fce.png)
![TASK转换核心](19eb051dbb01fde17680941f0ff1e74d.png)
![定时器](ba1856a3a53f495ce5c617db01afb53d.png)

RTOS能完成的主要原因是PC寄存器的内容被频繁更换(代码的下一行是存在PC寄存器里面，也就是说PC寄存器的地址是准备执行的代码的地址)，但是PC寄存器只能读不能写入，所以就退而求其次用SP来间接改变PC的寄存器(TASK转换核心)


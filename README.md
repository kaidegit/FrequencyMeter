临时做的一个简易的频率计

基于NUCLEO-G070RB板子，PA0（A0）作为输入口

每次上升沿进入中断计数+1，记录半分钟脉冲数量后串口回传2倍数值作为测得的频率
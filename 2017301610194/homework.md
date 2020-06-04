# 网络及分布式计算作业12



## 习题2

双比特差错： 	
原始数据：

0000

1111

0101

1010

出错后变为：

0000

1001

0101

1010

此时可以检测到出错，但是不能确定是哪一行出现了错误

## 习题6

a) 0000

b) 1111

c) 1001

## 习题7

a) 不失一般性，令第i位出现错误（0<=i<=d+r-1），那么这样得到的数据是K=D∗2^r XOR R+2^i
 ,显然不能被G整除。
 
b) 能。注意，这里的G可以被11（二进制）整除，但是，任何奇数个比特错误（不论是否连续）所造成的偏差必然不可被11（二进制）整除。

------

软五 2017301610194 马如云
[编程题] 聊天
A和B是好友，他们经常在空闲时间聊天，A的空闲时间为[a1 ,b1 ],[a2 ,b2 ]..[ap ,bp ]。B的空闲时间是[c1 +t,d1 +t]..[cq +t,dq +t],这里t为B的起床时间。这些时间包括了边界点。B的起床时间为[l,r]的一个时刻。若一个起床时间能使两人在任意时刻聊天，那么这个时间就是合适的，问有多少个合适的起床时间？
输入描述:
第一行数据四个整数：p,q,l,r（1≤p,q≤50,0≤l≤r≤1000)。接下来p行数据每一行有一对整数ai，bi(0≤ai<bi≤1000)表示a的时间表，接下来p行每行一对整数ci，di(0≤ci,di≤1000)表示b的时间表。保证ai+1>bi,ci+1>di</bi≤1000)表示a的时间表，接下来p行每行一对整数ci，di(0≤ci,di≤1000)表示b的时间表。保证a

输出描述:
输出答案个数

输入例子:
2 3 0 20
15 17
23 26
1 4
7 11
15 17

输出例子:
20
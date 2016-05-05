# LeetCode_ReverseInteger
反转整数，使用了an amazing trick!!!!!!!!
输入x 输出ans
x--------temp--------ans
                      0
x     ans*10+x%10     temp
x/10  ans*10+x%10     temp
.
.
.
0
例如x=1234
x--------temp--------ans
1234   0*10+4=4       4
123    4*10+3=43      43
12     43*10+2=432    432
1      432*10+1=4321  4321
0(stop)

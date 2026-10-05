# 115\_1\_Java\_Week2\_Ch3\_HW\_Mini3\_Assembly

Testing : 

int result = 99 + 7 + 60 ;

MOVI R1, 99

MOVI R2, 7

ADD R0, R1, R2

MOVI R2, 60

ADD R0, R0, R2

STORE \[0], R0



Ans\_1 :因為原本R1 R2已經被相加並存入R0，因此R2的空間可以釋出給其他的輸入取代



Ans\_2 :因為next()、nextInt()等會讀取資料直到遇到空白、Tab或換行為止


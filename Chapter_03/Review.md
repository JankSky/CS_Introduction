## 复习题
#### Q3-1 说出5种机算机可以处理的数据。
数字、文本、图像、音频、视频。

#### Q3-2 位模式的长度如何与其能表示的符号数最相关？
n位的长度，能有2^n种表示。

#### Q3-3 位图方法是如何以位模式来表示一个图像？
使用24位来编码一个像素，R、G、B分别占8位。

#### Q3-4 矢量图方法优于位图方法的优点是什么? 其缺点卫是什么？
矢量图不会因为放大而丢失精度。矢量图不适合存储过于细微精妙的照片图像。

#### Q3-5 将音频数据转换为位模式需要哪些步骤？
采样、量化、编码。

#### Q3-6 比较和对照在无符号、符号加绝对值以及其二进制补码格式中的正整数的表示法。
无符号格式中，正整数就是按正常二进制数存储。后面的两种，高位0表示正，1表示负，其他跟无符号存储形式相同。

#### Q3-7 比较和对照在无符号、符号加绝对值及二进制补码格式中的负整数的表示法。
无符号数无法存储负整数；符号加绝对值高位用1表示负，整数部分用二进制表示；补码格式中，将整数部分用补码表示，高位填1。

#### Q3-8 比较和对照在符号加绝对值、二进制补码格式和余码格式中的0的表示法。
符号加绝对值中，存在正负0，其他只有一种0。

#### Q3-9 讨论在符号加绝对值和二进制补码格式中最左位扮演的角色。
最左为0表示整数，1表示负数。

#### Q3-10 回答以下关于实数浮点表示法的问题：为什么需要规范化、什么是尾数、数字在规范化以后，何种信息被计算机存储在内存中？
为了使表示法的固定部分统一；尾数是指小数点右边的二进制数；符号、指数、尾数储存在内存中。

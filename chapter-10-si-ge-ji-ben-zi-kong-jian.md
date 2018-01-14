# Chapter 10 四个基本子空间

---

1.四个基本子空间 A-mXn

* 列空间 C（A）in R\_m
* 零空间 N（A）in R\_n
* 行空间 （row的线性组合=A转置矩阵的列的所有组合）in R\_m
* A转置的零空间 N（A_T\)--左零空间of A     in_ R\_m

2.

![](/assets/微信图片_20180114090451.png)



basis ? dimension?

2.1

列空间：basis是主列  dimension是 rank r

2.2

行空间：dimension是rank r

A-U-R 变换后  C（R）=！C（A）_** 列空间不同**_，但行空间仍相同,  因此行空间的basis是R的前 r 行/

2.3

零空间：矩阵A化简 A---U---R，我们可以得到特殊解，特殊解是从自由变量中得到，特殊解在零空间中。

N（A）basis：特殊解的集合,共有 n-r个特殊解

2.4

N（A\_T\) dimension: m-r

![](/assets/微信图片_20180114090517.png)

![](/assets/微信图片_20180114090521.png)

如果AT y =0  则y在零空间中

* 求矩阵左零空间，寻找产生零行向量的行组合
* 求零空间，产生零列向量的组合 

![](/assets/微信图片_20180114090524.png)

![](/assets/微信图片_20180114090526.png)

**A=LU变换到 LA=U，L中自由变量的对应行就是左零空间basis**

3.总结

行空间和零空间在Rn中，维数相加得n

列空间和左零空间在Rm中，维数相加得m

4.new vector space M： aLL 3X3 矩阵， 把矩阵称作向量

subspace of M:

![](/assets/微信图片_20180114090528.png)


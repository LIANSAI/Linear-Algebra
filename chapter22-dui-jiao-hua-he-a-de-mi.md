# Chapter22 对角化和A的幂

---

1.对角化

**假设A有n个线性无关的特征向量（大前提）**，将他们按列组成矩阵S，S为特征向量矩阵，那么S-1AS为对角矩阵Λ，Λ为特征值矩阵

。（如果不存在n个线性无关特征向量，S的逆不存在，矩阵就不能对角化）

![](/assets/微信图片_20180204184549.png)

如果对 AS=SΛ 右乘S的逆，则有**A=SΛS-1，这是新的矩阵分解**。以前有消元法中的A=LU矩阵分解，和格拉姆-施密特正交化中的A=QR矩阵

1.1.1  A的幂次方 定理

问题: A=SΛS-1，Ax=λx，将A平方会怎样？

* Ax=λx，那么A2x=λAx=λλx=λ2x，结论是A2的特征值是λ2，特征向量不变。

* 同样的，A2=SΛS-1SΛS-1=SΛ2S-1，同样说明特征值是先前的平方，特征向量不变。

因此，特征值和特征向量提供了理解矩阵幂的一个好方法，如果将矩阵平方，或者取100次方，主元任意分布，A=LU搞不下去，但是A100=SΛ100S-1，特征值是计算矩阵幂的一种方法。**当A的所有特征值的绝对值小于1时，K趋向于无穷，矩阵的幂趋向于0，这样的矩阵称着稳定的矩阵。**

![](/assets/微信图片_20180204184658.png)

这里假设：存在n个线性无关特征向量，如果不存在，矩阵就无法对角化。

1.1.2 矩阵何时可以对角化？

矩阵A有n个线性无关的特征向量时，A可以对角化。A必然存在n个线性无关的特征向量，如果没有重复的特征值。如果存在重复特征值：可能但不一定存在n个线性无关特征向量。

如果矩阵A本来就是对角矩阵（对角矩阵的特征值就是对角矩阵对角线上的元素），那么对角化矩阵Λ与矩阵A相同。如果矩阵A是三角矩阵，如下，特征值是两个相同的2（计算特征值重复的次数，用代数重度，此重数，就是它作为多项式根的次数，即\(2-λ\)2=0的根），求特征向量，零空间仅仅是一维的x=\(1 0\)，因为不存在两个线性无关的特征向量，因此矩阵A是不可对角化的。

2.差分方程

Uk+1=AUk只含有一阶差分，等式右侧由向量和矩阵所组成，称为一阶方程组。图中框起来的就是一阶方程组的解

。如何根据初始向量u0求解？可以把u0看着n若干个A的特征向量的线性组合u0=Sc，n个特征向量是线性无关的，他们能线性组合出任何向量。如下图推理，求出Aku0后，uk的解就出来了





3.斐波那契数列

![](/assets/微信图片_20180204184701.png)![](/assets/微信图片_20180204184703.png)

数列增长速度由特征值决定，较大的一个特征值起决定性作用，因此；

![](/assets/微信图片_20180204184705.png)


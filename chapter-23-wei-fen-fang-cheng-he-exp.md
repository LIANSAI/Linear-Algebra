# Chapter 23 微分方程和exp\(At\)

---

1.Au= du/dt

> 将一阶常系数微分方程转换为线性代数问题的关键在于常系数微分方程的解一定是**指数形式**的。那么我们的需要求解的东西就是指数的系数和指数的幂，而这可以转换为线性代数问题

解的指数形式通常是自然常数e的指数。

![](/assets/import.pnghttp:/img.blog.csdn.net/20151124213942361)、

来看一个例子

![](/assets1/import.pnghttp:/img.blog.csdn.net/20151124214349509)

问题被转换成Au=du/dt

1. 特征值和特征向量

先找A的特征值和特征向量

**求解特征值**  
 两个小技巧：

* 行列式determinant为特征值的积
* 矩阵的迹trace为特征值的和

当然可以直接求解determinant=0得到特征值：

![](/assets2/import.png)

解的形式

![](/assets13/import.png)

所以我们可以将刚才求解的特征值和特征向量带入式子

![](/assets12/import.png)

接下来求解从c1,c2，通过初值u0

![](/assets33/import.png)

得c1=1/3, c2=1/3

当时间趋向于无穷，进入稳态

![](/assets4/import.png)



2.什么时候能抵达稳态？ u\(t\)趋近0

2.1 Stability -- 特征值小于0时

![](/assets234/import.pnghttp:/img.blog.csdn.net/20151124224214221)




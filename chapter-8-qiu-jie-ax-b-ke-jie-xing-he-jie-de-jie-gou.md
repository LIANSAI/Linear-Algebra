# Chapter 8 求解Ax=b 可解性和解的结构

---

1

.![](/assets/微信图片_20180112124401.png)

如果方程组有解,b1,b2,b3需要满足什么条件？

必须b1+b2=b3.如果左侧各行的线性组合得到0那么右侧的常数也需要是0。

![](/assets/微信图片_20180112124411.png)

![](/assets/微信图片_20180112124413.png)

有解条件：

* 如果行的线性组合得到0 row，那么b中的元素组合也必须是0

* Ax=b有解，solvable仅当b属于A的列空间时.

To find complete solution to Ax=b

* X\_particular:set all free variable to zero; Solve Ax=b for pivot variables.
* X_nullspace  所有解可以表示为X\_particular+X\_nullspace._

![](/assets/微信图片_20180112124416.png)

**对于方程组某解，其与零空间内任意向量之和仍为解**

通解：特解（particular solution\)（free variable取 0 0）+特殊解（special soulution\)（一个自由变量设置为1，其他都为0，解得数量和自由变量数量一样）任意零空间的向量\(求Ax=0的解）

![](/assets/微信图片_20180112124418.png)

两个自由变量——两个特殊解

1. Think bigger

考虑：mXn rank为r 的矩阵 A （r&lt;=m, r&lt;=n\)

Case：Full rank

2.1 Full column rank r=n 列满秩

这时没有自由变量

Null space：只有一个零向量

Ax=b的解将只有零个或一个 X=X\_particular

什么样的列满秩矩阵总有解？

b是线性组合

2.2 行满秩 r=m

每一个行都有一个主元，问b取什么时，Ax=b总有解.

**因为消元不会出现零行，所以对任意b，Ax=b都有解**

所以自由变量为n-r个

2.3 r=m=n

可逆矩阵

R=I

nullspace: 只有 0 向量

**Ax=b有解：任意b都有解且解唯一**

1. Summary

![](/assets/微信图片_20180112124423.png)

矩阵的秩决定了方程组解的数目


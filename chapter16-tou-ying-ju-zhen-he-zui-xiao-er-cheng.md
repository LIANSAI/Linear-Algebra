# Chapter16 投影矩阵和最小二乘

---

1.Recap

![](/assets/微信图片_20180117145230.png)

什么样的向量垂直于列空间？A转置的零空间的向量



2.最小二乘法 

![](/assets/微信图片_20180117145313.png)

原题目联立是无解的，但我们可以得到最优解，解法 等号两边同时乘以A的转置矩阵：

![](/assets/微信图片_20180117145315.png)





2.A的转置矩阵乘以A必须是可逆

性质：如果矩阵A各列线性无关，那么A转置A就是可逆的

证明：如果A^TX=0，那么X必须为0

解法：

![](/assets/微信图片_20180117145321.png)



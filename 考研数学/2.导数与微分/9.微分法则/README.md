# 微分法则

* [有理运算法则](#有理运算法则)
* [复合函数微分](#复合函数微分)
* [经典例题](#经典例题)


## 有理运算法则

$$
d(u \pm v) = d(u) \pm d(v)
\\
d(Cu) = Cd(u)
\\
d(uv) = v{d(u)} + u{d(v)}
\\
d(\frac{u}{v}) = \frac{vd(u) - ud(v)}{v ^ 2}
$$

## 复合函数微分

$$
设 y = f(u) 及 u = g(x) 都可导，则复合函数 y = f[g(x)] 的微分为 dy = {{f ^ {\prime} (u)}{g ^ {\prime} (x)}}dx .
$$

## 经典例题

$$
如： y = \ln{(1 + e ^ {x ^ 2})} ， 求dy .
\\
dy = \ d(\ln{(1 + e ^ {x ^ 2})}) = \frac{1}{1 + e ^ {x ^ 2}} \cdot d(1 + e ^ {x ^ 2}) = \frac{1}{1 + e ^ {x ^ 2}} \cdot e ^ {x ^ 2} \cdot d(x ^ 2) = {\frac{1}{1 + e ^ {x ^ 2}} \cdot e ^ {x ^ 2} \cdot 2x}dx = {\frac{2xe ^ {x ^ 2}}{1 + e ^ {x ^ 2}}}dx .
$$




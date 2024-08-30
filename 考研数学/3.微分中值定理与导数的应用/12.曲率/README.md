# 曲率

* [弧微分公式](#弧微分公式)
* [曲率公式](#曲率公式)
* [曲率半径](#曲率半径)
* [经典例题](#经典例题)


## 弧微分公式

$$
ds = \sqrt{1 + (y\prime) ^ 2}dx
$$

## 曲率公式

$$
K = \frac{|y\prime\prime|}{(1 + (y\prime) ^ 2) ^ \frac{3}{2}}
$$

## 曲率半径

$$
\rho = \frac{1}{K} = \frac{(1 + (y\prime) ^ 2) ^ \frac{3}{2}}{|y\prime\prime|}(y \neq 0)
$$

## 经典例题

$$
如：计算等边双曲线 xy = 1 在点 (1 , 1) 处的曲率.
\\
\
\
\because y = \frac{1}{x} ，且 y\prime = -\frac{1}{x ^ 2} ， y\prime\prime = \frac{2}{x ^ 3} ，
\\
\therefore y\prime|_{x = 1} = -1 ， y\prime\prime|_{x = 1} = 2 ，
\\
\
带入曲率公式，得： K = \frac{|2|}{(1 + (-1) ^ 2) ^ \frac{3}{2}} = \frac{\sqrt{2}}{2} .
$$

$$
如：抛物线 y = ax ^ 2 + bx + c 上哪一点处的曲率最大？\
\\
\because y = ax ^ 2 + bx + c ，且 y\prime = 2ax + b ， y\prime\prime = 2a ，
\\
带入曲率公式，得： K = \frac{|2a|}{(1 + (2ax + b) ^ 2) ^ \frac{3}{2}} ，
\\
\because K 的分子是常数，所以只要分母最小， K 就最大，
\\
\therefore 当 2ax + b = 0 时，即 x = -\frac{b}{2a} 时， K最大.
\\
\therefore K = |2a| .
$$

$$
如：设工件内表面的截线为抛物线 y = 0.4x ^ 2 ，现在要用砂轮磨削其内表面，问用直径多大的砂轮才比较合适？
\\
\because 抛物线在其顶点处曲率最大，即在其顶点处曲率半径最小，因此，只需求出抛物线 y = 0.4x ^ 2 在顶点 O (0 , 0) 处的曲率半径，
\\
\because y = 0.4x ^ 2 ，且 y\prime = 0.8x ， y\prime\prime = 0.8 ，
\\
\therefore y\prime|_{x = 0} = 0 ， y\prime\prime|_{x = 0} = 0.8 ，
\\
带入曲率公式，得： K = \frac{|0.8|}{(1 + 0 ^ 2) ^ \frac{3}{2}} = 0.8 ，
\\
\therefore 抛物线 y = 0.4x ^ 2 在顶点 O (0 , 0) 处的曲率为 0.8 ，
\\
\therefore \rho = \frac{1}{K} = \frac{1}{0.8} = 1.25 ，
\\
\therefore 选用砂轮的直径不得超过 2.5 单位长.
$$




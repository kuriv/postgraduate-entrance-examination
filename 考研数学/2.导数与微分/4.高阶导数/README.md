# 高阶导数

* [定理内容](#定理内容)
* [常用高阶导数公式](#常用高阶导数公式)
* [莱布尼兹公式](#莱布尼兹公式)
* [经典例题](#经典例题)


## 定理内容

$$
定义：导数的导数叫做二阶导数，类似地，二阶导数的导数叫做三阶导数，三阶导数的导数叫做四阶导数 \ldots ，二阶及二阶以上的导数统称为高阶导数.
$$

## 常用高阶导数公式

$$
(u \pm v) ^ {(n)} = u ^ {(n)} \pm v ^ {(n)}
\\
\sin ^ {(n)} (kx + b) = k ^ n \cdot \sin(kx + b + \frac{n\pi}{2})
\\
\cos ^ {(n)} (kx + b) = k ^ n \cdot \cos(kx + b + \frac{n\pi}{2})
\\
(a ^ {kx}) ^ {(n)} = k ^ n \cdot a ^ {kx} (\ln ^ {a}) ^ {(n)}
\\
(e ^ {kx + b}) ^ {(n)} = k ^ n \cdot e ^ {kx + b}
\\
[\ln(kx + b)] ^ {(n)} = (-1) ^ {(n - 1)} \cdot k ^ n \cdot \frac{(n - 1)!}{(kx + b) ^ n}
\\
(\frac{1}{kx + b}) ^ {(n)} = (-1) ^ {n} \cdot k ^ n \cdot \frac{n!}{(kx + b) ^ {(n + 1)}}
$$

## 莱布尼兹公式

$$
(uv) ^ {(n)} = {C_n ^ 0}{u ^ {(0)}}{v ^ {(n)}} + {C_n ^ 1}{u ^ {(1)}}{v ^ {(n - 1)}} + {C_n ^ 2}{u ^ {(2)}}{v ^ {(n - 2)}} + \cdots + {C_n ^ n}{u ^ {(n)}}{v ^ {(0)}}
$$

## 经典例题

$$
如：求函数 y = \sqrt{2x - x ^ 2} 的二阶导数.
\\
y\prime = (\sqrt{2x - x ^ 2})\prime = \frac{2 - 2x}{2\sqrt{2x - x ^2}} = \frac{1 - x}{\sqrt{2x - x ^ 2}} ，
\\
y\prime\prime = (\frac{1 - x}{\sqrt{2x - x ^ 2}})\prime = \frac{-\sqrt{2x - x ^ 2} - \frac{(1 - x) ^ 2}{\sqrt{2x - x ^ 2}}}{2x - x ^2} = \frac{-2x + x ^ 2 - (1 - x) ^ 2}{(2x - x ^2)(\sqrt{2x - x ^ 2})} = -\frac{1}{(2x - x ^2)(\sqrt{2x - x ^ 2})} = -\frac{1}{y ^ 3} .
$$

$$
如：设 y = (x ^ 2 + 5x + 10)\sin{2x} ， 求 y ^ {(n)} .
\\
\because y ^ {(n)} = {C_n ^ 0}{(x ^ 2 + 5x + 10) ^ {(0)}}{\sin ^ {(n)} {2x}} + {C_n ^ 1}{(x ^ 2 + 5x + 10) ^ {(1)}}{\sin ^ {(n - 1)} {2x}} + {C_n ^ 2}{(x ^ 2 + 5x + 10) ^ {(2)}}{\sin ^ {(n - 2)} {2x}}
\\
+ \cdots + {C_n ^ n}{(x ^ 2 + 5x + 10) ^ {(n)}}{\sin ^ {(0)} {2x}} ，
\\
\therefore y ^ {(n)} = {(x ^ 2 + 5x + 10)} \cdot {2 ^ n} \cdot {\sin(2x + \frac{n\pi}{2})} + n \cdot {(2x + 5)} \cdot {2 ^ {n - 1}} \cdot {\sin(2x + \frac{(n - 1)\pi}{2})} + \frac{n(n - 1)}{2} \cdot 2 \cdot {2 ^ {n - 2}} \cdot {\sin(2x + \frac{(n - 2)\pi}{2})} .
$$




# 高阶导数

* [常用高阶导数公式](#常用高阶导数公式)

$$
定义：导数的导数叫做二阶导数，类似地，二阶导数的导数叫做三阶导数，三阶导数的导数叫做四阶导数 \ldots ，二阶及二阶以上的导数统称为高阶导数.
\\
如：求函数 y = \sqrt{2x - x ^ 2} 的二阶导数.
\\
y\prime = (\sqrt{2x - x ^ 2})\prime = \frac{2 - 2x}{2\sqrt{2x - x ^2}} = \frac{1 - x}{\sqrt{2x - x ^ 2}} ，
\\
y\prime\prime = (\frac{1 - x}{\sqrt{2x - x ^ 2}})\prime = \frac{-\sqrt{2x - x ^ 2} - \frac{(1 - x) ^ 2}{\sqrt{2x - x ^ 2}}}{2x - x ^2} = \frac{-2x + x ^ 2 - (1 - x) ^ 2}{(2x - x ^2)(\sqrt{2x - x ^ 2})} = -\frac{1}{(2x - x ^2)(\sqrt{2x - x ^ 2})} = -\frac{1}{y ^ 3} .
$$

## 常用高阶导数公式

$$
(sinx) ^ {(n)} = sin(x + n \cdot \frac{\pi}{2})
\\
(cosx) ^ {(n)} = cos(x + n \cdot \frac{\pi}{2})
\\
(e ^ x) ^ {(n)} = e ^ x
\\
[\ln^{(x + 1)}] ^ {(n)} = (-1) ^ {n - 1} \cdot \frac{(n - 1)!}{(x + 1) ^ n}
\\
(u \pm v) ^ {(n)} = u ^ {(n)} \pm v ^ {(n)}
\\
(uv) ^ {(n)} = {\Sigma_{k = 0} ^ n}{C_n ^ k}{u ^ {(k)}}{v ^ {(n - k)}}
$$




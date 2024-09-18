# 第一类换元法

* [定理内容](#定理内容)
* [经典例题](#经典例题)

## 定理内容

$$
凑微分法： \int{f[g(x)]g ^ {\prime} (x)}dx = \int{f[g(x)]}d[g(x)] = \int{f(u)}du .
$$

$$
当被积函数比较复杂时，若果拿出一部分放到 d 后面去能够凑成 \int{f(u)}du 的形式，则凑微分成功.
\\
如 \int{\frac{(\ln{x}) ^ 5}{x}}dx = \int{{(\ln{x}) ^ 5}\frac{1}{x}}dx = \int{(\ln{x}) ^ 5}d(\ln{x}) = \frac{1}{6}(\ln{x}) ^ 6 + C .
$$

## 经典例题

$$
求 \int{2\cos{2x}}dx .
\\
\int{2\cos{2x}}dx = 2\int{\cos{2x}}dx = 2 \cdot \frac{1}{2}\int{\cos{2x}}d(2x) = \sin{2x} + C .
$$

$$
求 \int{\frac{1}{3 + 2x}}dx .
\\
\
\int{\frac{1}{3 + 2x}}dx = \frac{1}{2}\int{\frac{1}{3 + 2x}}d(3 + 2x) = \frac{1}{2}\ln{|3 + 2x|} + C .
$$

$$
求 \int{\frac{x ^ 2}{(x + 2) ^ 3}}dx .
\\
令 u = x + 2 ， x = u - 2 ，则 \int{\frac{x ^ 2}{(x + 2) ^ 3}}dx = \int{\frac{(u - 2) ^ 2}{u ^ 3}}dx = \int{\frac{u ^ 2 - 4u + 4}{u ^ 3}}dx = \int{u ^ {-1}}dx - \int{4u ^ {-2}}dx + \int{4u ^ {-3}}dx
\\
= \ln{|u|} + 4u ^ {-1} - 2u ^ {-2} + C = \ln{|x + 2|} + \frac{4}{x + 2} - \frac{2}{(x + 2) ^ 2} + C .
$$

$$
求 \int{2x{e ^ {x ^ 2}}}dx .
\\
\int{2x{e ^ {x ^ 2}}}dx = \int{2x \cdot e ^ {x ^ 2}}dx = \int{e ^ {x ^ 2}}d(x ^ 2) = e ^ {x ^ 2} + C .
$$

$$
求 \int{{2 ^ x}{e ^ x}}dx .
\\
\int{{2 ^ x}{e ^ x}}dx = \int{(2e) ^ x}dx = \frac{(2e) ^ x}{\ln{2e}} + C = \frac{{2 ^ x}{e ^ x}}{\ln ^ 2 + 1} + C .
$$

$$
求 \int{x\sqrt{1 - x ^ 2}}dx .
\\
\int{x\sqrt{1 - x ^ 2}}dx = -\frac{1}{2}\int{(1 - x ^ 2) ^ {\frac{1}{2}}}d(1 - x ^ 2) = -\frac{1}{2} \cdot \frac{2}{3}(1 - x ^ 2) ^ {\frac{3}{2}} + C = -\frac{1}{3}(1 - x ^ 2) ^ {\frac{3}{2}} + C .
$$

$$
求 \int{\frac{1}{a ^ 2 + x ^ 2}}dx .
\\
\int{\frac{1}{a ^ 2 + x ^ 2}}dx = \int{\frac{1}{a ^ 2} \cdot \frac{1}{1 + (\frac{x}{a}) ^ 2}}dx = \frac{1}{a ^ 2}\int{\frac{1}{1 + (\frac{x}{a}) ^ 2}}dx = \frac{1}{a}\int{\frac{1}{1 + (\frac{x}{a}) ^ 2}}d(\frac{x}{a}) = \frac{1}{a}\arctan{\frac{x}{a}} + C .
$$

$$
求 \int{\frac{1}{\sqrt{a ^ 2 - x ^ 2}}}dx .
\\
\int{\frac{1}{\sqrt{a ^ 2 - x ^ 2}}}dx = \int{\frac{1}{a} \cdot \frac{1}{\sqrt{1 - (\frac{x}{a}) ^ 2}}}dx = \frac{1}{a}\int{\frac{1}{\sqrt{1 - (\frac{x}{a}) ^ 2}}}dx = \int{\frac{1}{\sqrt{1 - (\frac{x}{a}) ^ 2}}}d(\frac{x}{a}) = \arcsin{\frac{x}{a}} + C .
$$

$$
求 \int{\frac{1}{x ^ 2 - a ^ 2}}dx .
\\
\int{\frac{1}{x ^ 2 - a ^ 2}}dx = \int{\frac{1}{2a} \cdot (\frac{1}{x - a} - \frac{1}{x + a})}dx = \frac{1}{2a}(\int{\frac{1}{x - a}}dx - \int{\frac{1}{x + a}}dx) = \frac{1}{2a}(\int{\frac{1}{x - a}}d(x - a) - \int{\frac{1}{x + a}}d(x + a))
\\
= \frac{1}{2a}(\ln{|x - a|} - \ln{|x + a|}) + C = \frac{1}{2a}\ln{|\frac{x - a}{x + a}|} + C .
$$

$$
求 \int{\frac{1}{x(1 + 2\ln{x})}}dx .
\\
\int{\frac{1}{x(1 + 2\ln{x})}}dx = \int{\frac{1}{x} \cdot \frac{1}{1 + 2\ln{x}}}dx = \frac{1}{2}\int{\frac{1}{1 + 2\ln{x}}}d(1 + 2\ln{x}) = \frac{1}{2}\ln{|1 + 2\ln{x}|} + C .
$$

$$
求 \int{\frac{e ^ {3\sqrt{x}}}{\sqrt{x}}}dx .
\\
\int{\frac{e ^ {3\sqrt{x}}}{\sqrt{x}}}dx = \int{\frac{1}{\sqrt{x}} \cdot e ^ {3\sqrt{x}}}dx = 2\int{e ^ {3\sqrt{x}}}d(\sqrt{x}) = \frac{2}{3}\int{e ^ {3\sqrt{x}}}d(3\sqrt{x}) = \frac{2}{3}e ^ {3\sqrt{x}} + C .
$$

$$
求 \int{\sin ^ {3} {x}}dx .
\\
\int{\sin ^ {3} {x}}dx = \int{\sin{x} \cdot \sin ^ {2} {x}}dx = \int{\sin{x} \cdot (1 - \cos ^ {2} {x})}dx = -\int{(1 - \cos ^ {2} {x})}d(\cos{x}) = -\cos{x} + \frac{1}{3}\cos ^ {3} {x} + C .
$$

$$
求 \int{\sin ^ {2} {x} \cos ^ {5} {x}}dx .
\\
\int{\sin ^ {2} {x} \cos ^ {5} {x}}dx = \int{\cos{x} \cdot \sin ^ {2} {x} \cdot \cos ^ {4} {x}}dx = \int{\cos{x} \cdot \sin ^ {2} {x} (1 - \sin ^ {2} {x}) ^ 2}dx = \int{\sin ^ {2} {x} (1 - \sin ^ {2} {x}) ^ 2}d(\sin{x})
\\
= \int{(\sin ^ {2} {x} - 2\sin ^ {4} {x} + \sin ^ {6} {x})}d(\sin{x}) = \frac{1}{3}\sin ^ {3} {x} - \frac{2}{5}\sin ^ {5} {x} + \frac{1}{7}\sin ^ {7} {x} + C .
$$

$$
求 \int{\tan{x}}dx .
\\
\int{\tan{x}}dx = \int{\frac{\sin{x}}{\cos{x}}}dx = \int{\sin{x} \cdot \frac{1}{\cos{x}}}dx = -\int{\frac{1}{\cos{x}}}d(\cos{x}) = -\ln{|\cos{x}|} + C .
$$

$$
求 \int{\cot{x}}dx .
\\
\int{\cot{x}}dx = \int{\frac{\cos{x}}{\sin{x}}}dx = \int{\cos{x} \cdot \frac{1}{\sin{x}}}dx = \int{\frac{1}{\sin{x}}}d(\sin{x}) = \ln{|\sin{x}|} + C .
$$

$$
求 \int{\cos ^ {2} {x}}dx .
\\
\int{\cos ^ {2} {x}}dx = \int{\frac{1}{2}(1 + \cos{2x})}dx = \frac{1}{2}\int{(1 + \cos{2x})}dx = \frac{1}{2}(\int{1}dx + \int{\cos{2x}}dx) = \frac{1}{2}x + \frac{1}{2}\int{\cos{2x}}dx
\\
= \frac{1}{2}x + \frac{1}{4}\int{\cos{2x}}d(2x) = \frac{1}{2}x + \frac{1}{4}\sin{2x} + C .
$$

$$
求 \int{\tan ^ {2} {x}}dx .
\\
\int{\tan ^ {2} {x}}dx = \int{(\sec ^ {2} {x} - 1)}dx = \int{\sec ^ {2} {x}}dx - \int{1}dx = \tan{x} - x + C .
$$

$$
求 \int{\sin ^ {2} {x} \cos ^ {4} {x}}dx .
\\
= \int{\frac{1 - \cos{2x}}{2} \cdot (\frac{1 + \cos{2x}}{2}) ^ 2}dx
\\
= \frac{1}{8}\int{(1 - \cos{2x})(1 + \cos{2x}) ^ 2}dx
\\
= \frac{1}{8}\int{(1 + \cos{2x} - \cos ^ {2} {2x} - \cos ^ {3} {2x})}dx
\\
= \frac{1}{8}\int{(\cos{2x} - \cos ^ {3} {2x})}dx + \frac{1}{8}\int{(1 - \cos ^ {2} {2x})}dx
\\
= \frac{1}{8}\int{(\cos{2x})(1 - \cos ^ {2} {2x})}dx + \frac{1}{8}\int{\sin ^ {2} {2x}}dx
\\
= \frac{1}{16}\int{\sin ^ {2} {2x}}d(\sin{2x}) + \frac{1}{16}\int{(1 - \cos{4x})}dx
\\
= \frac{1}{16} \cdot \frac{1}{3}\sin ^ {3} {2x} + \frac{1}{16}x - \frac{1}{64}\int{\cos{4x}}d(4x)
\\
= \frac{1}{48}\sin ^ {3} {2x} + \frac{1}{16}x - \frac{1}{64}\sin{4x} + C .
$$

$$
求 \int{\sec ^ {6} {x}}dx .
\\
\int{\sec ^ {6} {x}}dx = \int{\sec ^ {2} {x} \sec ^ {4} {x}}dx = \int{(1 + \tan ^ {2} {x}) ^ 2}d(\tan{x}) = \int{(1 + 2\tan ^ {2} {x} + \tan ^ {4} {x})}d(\tan{x}) \
\\
= \tan{x} + \frac{2}{3}\tan ^ {3} {x} + \frac{1}{5}\tan ^ {5} {x} + C .
$$

$$
求 \int{\tan ^ {5} {x} \sec ^ {3} {x}}dx .
\\
\int{\tan ^ {5} {x} \sec ^ {3} {x}}dx = \int{\tan{x} \sec{x} \tan ^ {4} {x} \sec ^ {2} {x}}dx = \int{\tan{x} \sec{x} (\sec ^ {2} {x} - 1) ^ 2 \sec ^ {2} {x}}dx = \int{(\sec ^ {2} {x} - 1) ^ 2 \sec ^ {2} {x}}d(\sec{x})
\\
= \int{(\sec ^ {6} {x} - 2\sec ^ {4} {x} + \sec ^ {2} {x})}d(\sec{x}) = \frac{1}{7}\sec ^ {7} {x} - \frac{2}{5}\sec ^ {5} {x} + \frac{1}{3}\sec ^ {3} {x} + C .
$$

$$
求 \int{\cos{3x}\cos{2x}}dx .
\\
\int{\cos{3x}\cos{2x}}dx = \int{\frac{\cos{5x} + \cos{x}}{2}}dx = \frac{1}{2}\int{(\cos{5x} + \cos{x})}dx = \frac{1}{2}\int{\cos{x}}dx + \frac{1}{2}\int{\cos{5x}}dx = \frac{1}{2}\sin{x} + \frac{1}{10}\int{\cos{5x}}d(5x)
\\
= \frac{1}{2}\sin{x} + \frac{1}{10}\sin{5x} + C .
$$

$$
求 \int{\sin ^ {2} \frac{x}{2}}dx .
\\
\int{\sin ^ {2} \frac{x}{2}}dx = \int{\frac{1}{2}(1 - \cos{x})}dx = \frac{1}{2}\int(1 - \cos{x})dx = \frac{1}{2}(\int{1}dx - \int{\cos{x}}dx) = \frac{1}{2}(x - \sin{x}) + C .
$$

$$
求 \int{\frac{1}{{\sin ^ {2} \frac{x}{2}}{\cos ^ {2} \frac{x}{2}}}}dx .
\\
\int{\frac{1}{{\sin ^ {2} \frac{x}{2}}{\cos ^ {2} \frac{x}{2}}}}dx = \int{\frac{1}{(\sin{\frac{x}{2}}\cos{\frac{x}{2}}) ^ 2}}dx = \int{\frac{1}{(\frac{\sin{x}}{2}) ^ 2}}dx = \int{\frac{1}{\frac{\sin ^ {2} {x}}{4}}}dx = 4\int{\csc ^ {2} {x}}dx = -4\cot{x} + C .
$$

$$
求 \int{\frac{2x ^ 4 + x ^ 2 + 3}{x ^ 2 + 1}}dx .
\\
\int{\frac{2x ^ 4 + x ^ 2 + 3}{x ^ 2 + 1}}dx = \int{\frac{(x ^ 2 + 1)(2x ^ 2 - 1) + 4}{x ^ 2 + 1}}dx = \int{(2x ^ 2 - 1 + \frac{4}{x ^ 2 + 1})}dx = 2\int{x ^ 2}dx - \int{1}dx + 4\int{\frac{1}{x ^ 2 + 1}}dx
\\
= \frac{2}{3}x ^ 3 - x + 4\arctan{x} + C .
$$




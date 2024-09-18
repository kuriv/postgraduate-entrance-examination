# 第二类换元法

* [定理内容](#定理内容)
* [常用换元法](#常用换元法)
* [经典例题](#经典例题)


## 定理内容

$$
换元法：令 x = g(u) ，则 \int{f(x)}dx = \int{f[g(u)]}d[g(u)] = \int{f[g(u)]g ^ {\prime} (u)}du .
$$

$$
当被积函数不容易积分时，比如含有根式或含有反三角函数，可以通过换元的方法从后面拿出一部分放到前面来，就成为 \int{f[g(u)]g ^ {\prime} (u)}du 的形式，
\\
若 \int{f[g(u)]g ^ {\prime} (u)}du 容易积分，则换元成功.
$$

## 常用换元法

$$
三角函数代换：如果被积函数含有 \sqrt{a ^ 2 - x ^ 2} ，可令 x = a\sin{t} 化去根式.
\\
如果被积函数含有 \sqrt{a ^ 2 + x ^ 2} ，可令 x = a\tan{t} 化去根式.
\\
如果被积函数含有 \sqrt{x ^ 2 - a ^ 2} ，可令 x = {a\sec{t}} 化去根式.
$$

$$
恒等变形：当被积函数含有根式 \sqrt{ax ^ 2 + bx + c} 时，可先化为 \sqrt{[\phi(x)] ^ 2 + k ^ 2} ， \sqrt{[\phi(x)] ^ 2 - k ^ 2} ， \sqrt{k ^ 2 - [\phi(x)] ^ 2} ，再作三角函数代换.
$$

$$
根式代换：当被积函数含有根式 \sqrt[n]{ax + b} ， \sqrt{\frac{ax + b}{cx + d}} ， \sqrt{ae ^ {bx} + b} 等时，一般令根式 \sqrt{*} = t .
\\
对既含有 \sqrt[n]{ax + b} ，也含有 \sqrt[m]{ax + b} 的函数，一般取 m ， n 的最小公倍数 l ，令\sqrt[l]{ax + b} = t .
$$

$$
倒代换：当被积函数分母的幂次比分子高两次及两次以上时，作倒代换，令 x = \frac{1}{t} .
$$

$$
复杂函数代换：当被积函数中含有 a ^ x ， e ^ x ， \ln{x} ， \arcsin{x} ， \arctan{x} 等时，可考虑直接令复杂函数等于 t .
$$

## 经典例题

$$
求 \int{\sqrt{a ^ 2 - x ^ 2}}dx .
\\
令 x = a\sin{t} ，则 \sqrt{a ^ 2 - x ^ 2} = \sqrt{{a ^ 2} - {a ^ 2}{\sin ^ {2} {t}}} = \sqrt{a ^ 2(1 - \sin ^ {2} {t})} = \sqrt{{a ^ 2}{\cos ^ {2} {t}}} = a\cos{t} ， d(x) = {a\cos{t}}dt ，
\\
\int{\sqrt{a ^ 2 - x ^ 2}}dx = \int{{a ^ 2}\cos ^ {2} {t}}dt = a ^ 2\int{\cos ^ {2} {t}}dt = \frac{a ^ 2}{2}\int{(1 + \cos{2t})}dt = \frac{a ^ 2}{2}\int{1}dt + \frac{a ^ 2}{2}\int{\cos{2t}}dt = \frac{a ^ 2}{2}t + \frac{a ^ 2}{4}\int{\cos{2t}}d(2t)
\\
= \frac{a ^ 2}{2}t + \frac{a ^ 2}{4}\sin{2t} + C = \frac{a ^ 2}{2}t + \frac{a ^ 2}{4}(2\sin{t}\cos{t}) + C ，
\\
\because x = a\sin{t} ，则 \sin{t} = \frac{x}{a} ， t = \arcsin{\frac{x}{a}} ， \cos{t} = \frac{\sqrt{a ^ 2 - x ^ 2}}{a} ，
\\
\therefore \frac{a ^ 2}{2}t + \frac{a ^ 2}{4}(2\sin{t}\cos{t}) + C = \frac{a ^ 2}{2}\arcsin{\frac{x}{a}} + \frac{a ^ 2}{4}(2 \cdot \frac{x}{a} \cdot \frac{\sqrt{a ^ 2 - x ^ 2}}{x}) + C = \frac{a ^ 2}{2}\arcsin{\frac{x}{a}} + \frac{1}{2}x\sqrt{a ^ 2 - x ^ 2} + C .
$$

$$
求 \int{\frac{1}{\sqrt{x ^ 2 + a ^ 2}}}dx .
\\
令 x = a\tan{t} ，则 \sqrt{x ^ 2 + a ^ 2} = \sqrt{{a ^ 2}{\tan ^ {2} {t}} + a ^ 2} = \sqrt{a ^ 2(1 + \tan ^ {2} {t})} = \sqrt{{a ^ 2}{\sec ^ {2} {t}}} = a\sec{t} ， d(x) = {a\sec ^ {2} {t}}dt ，
\\
\int{\frac{1}{\sqrt{x ^ 2 + a ^ 2}}}dx = \int{\frac{1}{a\sec{t}} \cdot a\sec ^ {2} {t}}dt = \int{\sec{t}}dt = \ln{|\sec{t} + \tan{t}|} + C ，
\\
\because x = a\tan{t} ，则 \tan{t} = \frac{x}{a} ， \sec{x} = \frac{\sqrt{x ^ 2 + a ^ 2}}{a} ，
\\
\therefore \ln{|\sec{t} + \tan{t}|} + C = \ln{|\frac{\sqrt{x ^ 2 + a ^ 2}}{a} + \frac{x}{a}|} + C .
$$

$$
求 \int{\frac{1}{\sqrt{x ^ 2 - a ^ 2}}}dx .
\\
令 x = a\sec{t} ，则 \sqrt{x ^ 2 - a ^ 2} = \sqrt{{a ^ 2}{\sec ^ {2} {t}} - a ^ 2} = \sqrt{a ^ 2(\sec ^ {2} {t} - 1)} = \sqrt{{a ^ 2}{\tan ^ {2} {t}}} = a\tan{t} ， d(x) = a\sec{t}\tan{t}dt ，
\\
\int{\frac{1}{\sqrt{x ^ 2 - a ^ 2}}}dx = \int{\frac{1}{a\tan{t}} \cdot a\sec{t}\tan{t}}dt = \int{\sec{t}}dt = \ln{|\sec{t} + \tan{t}|} + C ，
\\
\because x = a\sec{t} ，则 \sec{t} = \frac{x}{a} ， \tan{t} = \frac{\sqrt{x ^ 2 - a ^ 2}}{a} ，
\\
\therefore \ln{|\sec{t} + \tan{t}|} + C = \ln{|\frac{x}{a} + \frac{\sqrt{x ^ 2 - a ^ 2}}{a}|} + C .
$$

$$
求 \int{\frac{\sqrt{a ^ 2 - x ^ 2}}{x ^ 4}}dx .
\\
令 x = \frac{1}{t} ，则 d(x) = -\frac{1}{t ^ 2}dt ， \int{\frac{\sqrt{a ^ 2 - x ^ 2}}{x ^ 4}}dx = \int{\frac{\sqrt{a ^ 2 - \frac{1}{t ^ 2}}}{\frac{1}{t ^ 4}} \cdot -\frac{1}{t ^ 2}}dt = -\int{\sqrt{{a ^ 2}{t ^ 2} - 1}t}dt ，
\\
= -\frac{1}{2a ^ 2}\int{\sqrt{{a ^ 2}{t ^ 2} - 1}}d({a ^ 2}{t ^ 2} - 1) = -\frac{1}{2a ^ 2} \cdot \frac{2}{3}({a ^ 2}{t ^ 2} - 1) ^ {\frac{3}{2}} + C = -\frac{1}{3a ^ 2}({a ^ 2}{t ^ 2} - 1) ^ {\frac{3}{2}} + C ，
\\
\because x = \frac{1}{t} ，则 t = \frac{1}{x} ，
\\
\therefore -\frac{1}{3a ^ 2}({a ^ 2}{t ^ 2} - 1) ^ {\frac{3}{2}} + C = -\frac{({a ^ 2}{\frac{1}{x ^ 2}} - 1) ^ {\frac{3}{2}}}{3a ^ 2} + C = -\frac{(a ^ 2 - x ^ 2) ^ \frac{3}{2}}{3{a ^ 2}{x ^ 3}} .
$$




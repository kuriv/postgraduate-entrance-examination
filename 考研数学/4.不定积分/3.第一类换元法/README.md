# 第一类换元法

* [定理内容](#定理内容)
* [经典例题](#经典例题)
  * [例题一](#例题一)
  * [例题二](#例题二)
  * [例题三](#例题三)
  * [例题四](#例题四)
  * [例题五](#例题五)
  * [例题六](#例题六)
  * [例题七](#例题七)
  * [例题八](#例题八)
  * [例题九](#例题九)
  * [例题十](#例题十)
  * [例题十一](#例题十一)
  * [例题十二](#例题十二)
  * [例题十三](#例题十三)
  * [例题十四](#例题十四)
  * [例题十五](#例题十五)
  * [例题十六](#例题十六)
  * [例题十七](#例题十七)
  * [例题十八](#例题十八)

## 定理内容

$$
设 f(u) 具有原函数， u = \phi(x) 可导，则有换元公式 \int{f[\phi(x)]\phi(x)\prime}dx = [\int{f(u)du}]_{u = \phi(x)} .
$$

$$
一般地，对于 (\sin{x}) ^ {2k + 1}(\cos{x}) ^ {k} 或 (\sin{x}) ^ {2k}(\cos{x}) ^ {2k + 1} ，可依次作变换 u =\sin{x} 或 u = \cos{x} ，求得结果.
\\
对于 (\sin{x}) ^ {2k}(\cos{x}) ^ {2k} 型函数，可利用三角恒等式 (\sin{x}) ^ 2 = \frac{1}{2}(1 - \cos{2x}) 或 (\cos{x}) ^ 2 = \frac{1}{2}(1 + \cos{2x}) 化成 \cos{2x} 的多项式.
\\
对于 (\tan{x}) ^ {k}(\sec{x}) ^ {2k} 或 (\tan{x}) ^ {2k + 1}(\sec{x}) ^ {k + 1} ，可依次作变化 u = \tan{x} 或 u = \sec{x} ，求得结果.
$$

## 经典例题

### 例题一

$$
求 \int{2\cos{2x}}dx .
\\
\int{2\cos{2x}}dx = 2\int{\cos{2x}}dx = 2 \cdot \frac{1}{2}\int{\cos{2x}}d(2x) = \sin{2x} + C .
$$

### 例题二

$$
求 \int{\frac{1}{3 + 2x}}dx .
\\
\
\int{\frac{1}{3 + 2x}}dx = \frac{1}{2}\int{\frac{1}{3 + 2x}}d(3 + 2x) = \frac{1}{2}\ln ^ {|3 + 2x|} + C .
$$

### 例题三

$$
求 \int{\frac{x ^ 2}{(x + 2) ^ 3}}dx .
\\
令 u = x + 2 ， x = u - 2 ，则 \int{\frac{x ^ 2}{(x + 2) ^ 3}}dx = \int{\frac{(u - 2) ^ 2}{u ^ 3}}dx = \int{\frac{u ^ 2 - 4u + 4}{u ^ 3}}dx = \int{u ^ {-1}}dx - \int{4u ^ {-2}}dx + \int{4u ^ {-3}}dx
\\
= \ln ^ {|u|} + 4u ^ {-1} -2u ^ {-2} + C = \ln ^ {|x + 2|} + \frac{4}{x + 2} - \frac{2}{(x + 2) ^ 2} + C .
$$

### 例题四

$$
求 \int{2xe ^ {x ^ 2}}dx .
\\
\int{2xe ^ {x ^ 2}}dx = \int{2x \cdot e ^ {x ^ 2}}dx = \int{e ^ {x ^ 2}}d(x ^ 2) = e ^ {x ^ 2} + C .
$$

### 例题五

$$
求 \int{x\sqrt{1 - x ^ 2}}dx .
\\
\int{x\sqrt{1 - x ^ 2}}dx = -\frac{1}{2}\int{(1 - x ^ 2) ^ {\frac{1}{2}}}d(1 - x ^ 2) = -\frac{1}{2} \cdot \frac{2}{3}(1 - x ^ 2) ^ {\frac{3}{2}} + C = -\frac{1}{3}(1 - x ^ 2) ^ {\frac{3}{2}} + C .
$$

### 例题六

$$
求 \int{\frac{1}{a ^ 2 + x ^ 2}}dx .
\\
\int{\frac{1}{a ^ 2 + x ^ 2}}dx = \int{\frac{1}{a ^ 2} \cdot \frac{1}{1 + (\frac{x}{a}) ^ 2}}dx = \frac{1}{a}\int{\frac{1}{1 + (\frac{x}{a}) ^ 2}}d(\frac{x}{a}) = \frac{1}{a}\arctan{\frac{x}{a}} + C .
$$

### 例题七

$$
求 \int{\frac{dx}{\sqrt{a ^ 2 - x ^ 2}}} .
\\
\int{\frac{dx}{\sqrt{a ^ 2 - x ^ 2}}} = \int{\frac{1}{\sqrt{a ^ 2 - x ^ 2}}}dx = \int{\frac{1}{a} \cdot \frac{1}{\sqrt{1 - (\frac{x}{a}) ^ 2}}}dx = \int{\frac{1}{\sqrt{1 - (\frac{x}{a}) ^ 2}}}d(\frac{x}{a}) = \arcsin{\frac{x}{a}} + C .
$$

### 例题八

$$
求 \int{\frac{1}{x ^ 2 - a ^ 2}}dx .
\\
\int{\frac{1}{x ^ 2 - a ^ 2}}dx = \int{\frac{1}{2a} \cdot (\frac{1}{x - a} - \frac{1}{x + a})}dx = \frac{1}{2a}(\int{\frac{1}{x - a}}dx - \int{\frac{1}{x + a}}dx) = \frac{1}{2a}(\int{\frac{1}{x - a}}d(x - a) - \int{\frac{1}{x + a}}d(x + a))
\\
= \frac{1}{2a}\ln ^ {|x - a|}\ln ^ {|x + a|} + C = \frac{1}{2a}\ln ^ {|\frac{x - a}{x + a}|} + C .
$$

### 例题九

$$
求 \int{\frac{dx}{x(1 + 2\ln ^ x)}} .
\\
\int{\frac{dx}{x(1 + 2\ln ^ x)}} = \int{\frac{1}{x(1 + 2\ln ^ x)}}dx = \int{\frac{1}{x} \cdot \frac{1}{1 + 2\ln ^ x}}dx = \frac{1}{2}\int{\frac{1}{1 + 2\ln ^ x}}d(1 + 2\ln ^ x) = \frac{1}{2}\ln ^ {|1 + 2\ln ^ {x}|} + C .
$$

### 例题十

$$
求 \int{\frac{e ^ {3\sqrt{x}}}{\sqrt{x}}}dx .
\\
\int{\frac{e ^ {3\sqrt{x}}}{\sqrt{x}}}dx = \int{\frac{1}{\sqrt{x}} \cdot e ^ {3\sqrt{x}}}dx = 2\int{e ^ {3\sqrt{x}}}d(\sqrt{x}) = \frac{2}{3}\int{e ^ {3\sqrt{x}}}d(3\sqrt{x}) = \frac{2}{3}e ^ {3\sqrt{x}} + C .
$$

### 例题十一

$$
求 \int{(\sin{x}) ^ 3}dx .
\\
\int{(\sin{x}) ^ 3}dx = \int{\sin{x} \cdot (\sin{x}) ^ 2}dx = \int{\sin{x} \cdot (1 - (\cos{x}) ^ 2)}dx = -\int{(1 - (\cos{x}) ^ 2)}d(\cos{x}) = -\cos{x} + \frac{1}{3}(\cos{x}) ^ 3 + C .
$$

### 例题十二

$$
求 \int{(\sin{x}) ^ 2(\cos{x}) ^ 5}dx .
\\
\int{(\sin{x}) ^ 2(\cos{x}) ^ 5}dx = \int{\cos{x} \cdot (\sin{x}) ^ 2(\cos{x}) ^ 4}dx = \int{\cos{x} \cdot (\sin{x}) ^ 2(1 - (\sin{x}) ^ 2) ^ 2}dx = \int{(\sin{x}) ^ 2(1 - (\sin{x}) ^ 2) ^ 2}d(\sin{x})
\\
= \int{((\sin{x}) ^ 2 - 2(\sin{x}) ^ 4 + (\sin{x}) ^ 6)}d(sinx) = \frac{1}{3}(\sin{x}) ^ 3 - \frac{2}{5}(\sin{x}) ^ 5 + \frac{1}{7}(\sin{x}) ^ 7 + C .
$$

### 例题十三

$$
求 \int{\tan{x}}dx .
\\
\int{\tan{x}}dx = \int{\frac{\sin{x}}{\cos{x}}}dx = \int{\sin{x} \cdot \frac{1}{\cos{x}}}dx = -\int{\frac{1}{\cos{x}}}d(\cos{x}) = -\ln ^ {|\cos{x}|} + C .
\\
类似，求 \int{\cot{x}}dx .
\\
\int{\cot{x}}dx = \int{\frac{\cos{x}}{\sin{x}}}dx = \int{\cos{x} \cdot \frac{1}{\sin{x}}}dx = \int{\frac{1}{\sin{x}}}d(sinx) = \ln ^ {|\sin{x}|} + C .
$$

### 例题十四

$$
求 \int{(\cos{x}) ^ 2}dx .
\\
\int{(\cos{x}) ^ 2}dx = \int{\frac{\cos{2x} + 1}{2}}dx = \int{\frac{1}{2}(\cos{2x} + 1)}dx = \frac{1}{2}\int{(\cos{2x} + 1)}dx = \frac{1}{2}(\int{1}dx + \int{\cos{2x}}dx) = \frac{1}{2}x + \frac{1}{2}\int{\cos{2x}}dx
\\
= \frac{1}{2}x + \frac{1}{4}\int{\cos{2x}}d(2x) = \frac{1}{2}x + \frac{1}{4}\sin{2x} + C .
$$

### 例题十五

$$
求 \int{(\sin{x}) ^ 2(\cos{x}) ^ 4}dx .
\\
= \int{\frac{1 - \cos{2x}}{2} \cdot (\frac{1 + \cos{2x}}{2}) ^ 2}dx
\\
= \frac{1}{8}\int{(1 - \cos{2x})(1 + \cos{2x}) ^ 2}dx
\\
= \frac{1}{8}\int{(1 + \cos{2x} - (\cos{2x}) ^ 2 - (\cos{2x}) ^ 3)}dx
\\
= \frac{1}{8}\int{(\cos{2x} - (\cos{2x}) ^ 3)}dx + \frac{1}{8}\int{(1 - (\cos{2x}) ^ 2)}dx
\\
= \frac{1}{8}\int{((\cos{2x})(1 - (\cos{2x}) ^ 2))}dx + \frac{1}{8}\int{(\sin{2x}) ^ 2}dx
\\
= \frac{1}{16}\int{(\sin{2x}) ^ 2}d(\sin{2x}) + \frac{1}{16}\int{(1 - \cos{4x})}dx
\\
= \frac{1}{16} \cdot \frac{1}{3}(\sin{2x}) ^ 3 + \frac{1}{16}x - \frac{1}{64}\int{\cos{4x}}d(4x)
\\
= \frac{1}{48}(\sin{2x}) ^ 3 + \frac{1}{16}x - \frac{1}{64}\sin{4x} + C .
$$

### 例题十六

$$
求 \int{(\sec{x}) ^ 6}dx .
\\
\int{(\sec{x}) ^ 6}dx = \int{(\sec{x}) ^ 2(\sec{x}) ^ 4}dx = \int{(1 + (\tan{x}) ^ 2) ^ 2}d(\tan{x}) = \int{(1 + 2(\tan{x}) ^ 2 + (\tan{x}) ^ 4)}d(\tan{x})
\\
= \tan{x} + \frac{2}{3}(\tan{x}) ^ 3 + \frac{1}{5}(\tan{x}) ^ 5 + C .
$$

### 例题十七

$$
求 \int{(\tan{x}) ^ 5(\sec{x}) ^ 3}dx .
\\
\int{(\tan{x}) ^ 5(\sec{x}) ^ 3}dx = \int{\tan{x}\sec{x}(\tan{x}) ^ 4(\sec{x}) ^ 2}dx = \int{\tan{x}\sec{x} \cdot ((\sec{x}) ^ 2 - 1) ^ 2(\sec{x}) ^ 2}dx = \int{((\sec{x}) ^ 2 - 1) ^ 2(\sec{x}) ^ 2}d(\sec{x})
\\
= \int{((\sec{x}) ^ 6 - 2(\sec{x}) ^ 4 + (\sec{x}) ^ 2)}d(\sec{x}) = \frac{1}{7}(\sec{x}) ^ 7 - \frac{2}{5}(\sec{x}) ^ 5 + \frac{1}{3}(\sec{x}) ^ 3 + C .
$$

### 例题十八

$$
求 \int{\cos{3x}\cos{2x}}dx .
\\
\int{\cos{3x}\cos{2x}}dx = \int{\frac{\cos{5x} + \cos{x}}{2}}dx = \frac{1}{2}\int{(\cos{5x} + \cos{x})}dx = \frac{1}{2}\int{\cos{x}}dx + \frac{1}{2}\int{\cos{5x}}dx = \frac{1}{2}\sin{x} + \frac{1}{10}\int{\cos{5x}}d(5x)
\\
= \frac{1}{2}\sin{x} + \frac{1}{10}\sin{5x} + C .
$$




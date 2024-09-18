# 分部积分法

* [定理内容](#定理内容)
* [经典例题](#经典例题)

## 定理内容

$$
\int{u}d(v) = uv - \int{v}d(u) .
$$

$$
微分后会简单些的函数宜选作 u ，积分后会简单些的函数宜选作 v ，即相对位置在左边的宜选作 u 用来求导，相对位置在右边的宜选作 v 用来积分.
\\
反 \ \ \ \ \ 对 \ \ \ \ \ 幂 \ \ \ \ \ 指 \ \ \ \ \ 三
\\
u \leftarrow \cdots\cdots \rightarrow v
$$

## 经典例题

$$
求 \int{x\cos{x}}dx .
\\
\int{x\cos{x}}dx = \int{x}d(\sin{x}) = x\sin{x} - \int{\sin{x}}dx = x\sin{x} + \cos{x} + C .
$$

$$
求 \int{xe ^ x}dx .
\\
\int{xe ^ x}dx = \int{x}d(e ^ x) = xe ^ x - \int{e ^ x}dx = xe ^ x - e ^ x + C = e ^ x(x - 1) + C .
$$

$$
求 \int{x ^ 2e ^ x}dx .
\\
\int{x ^ 2e ^ x}dx = \int{x ^ 2}d(e ^ x) = x ^ 2e ^ x - \int{e ^ x}d(x ^ 2) = x ^ 2e ^ x - 2\int{xe ^ x}dx ，
\\
\because 2\int{xe ^ x}dx = 2\int{x}d(e ^ x) = 2(xe ^ x - \int{e ^ x}dx) = 2(xe ^ x - e ^ x) + C ，
\\
\therefore x ^ 2e ^ x - 2\int{xe ^ x}dx = x ^ 2e ^ x - 2(xe ^ x - e ^ x) + C = e ^ x(x ^ 2 - 2x + 2) + C .
$$

$$
求 \int{x\ln{x}}dx .
\\
\int{x\ln{x}}dx = \int{\ln{x}}d(\frac{1}{2}x ^ 2) = \frac{1}{2}x ^ 2\ln{x} - \int{\frac{1}{2}x ^ 2}d(\ln{x}) = \frac{1}{2}x ^ 2\ln{x} - \frac{1}{2}\int{x}dx = \frac{1}{2}x ^ 2\ln{x} - \frac{1}{4}x ^ 2 + C .
$$

$$
求 \int{\arccos{x}}dx .
\\
\int{\arccos{x}}dx = \int{\arccos{x}}d(x) = x\arccos{x} - \int{x}d(\arccos{x}) = x\arccos{x} + \int{\frac{x}{\sqrt{1 - x ^ 2}}}dx = x\arccos{x} - \frac{1}{2}\int{\frac{1}{\sqrt{1 - x ^ 2}}}d(1 - x ^ 2)
\\
= x\arccos{x} - \frac{1}{2}\int{(1 - x ^ 2) ^ {-\frac{1}{2}}}d(1 - x ^ 2) = x\arccos{x} - \frac{1}{2} \cdot 2 \cdot (1 - x ^ 2) ^ {\frac{1}{2}} + C = x\arccos{x} - \sqrt{1 - x ^ 2} + C .
$$

$$
求 \int{x\arctan{x}}dx .
\\
\int{x\arctan{x}}dx = \int{\arctan{x}}d(\frac{1}{2}x ^ 2) = \frac{1}{2}x ^ 2\arctan{x} - \int{\frac{1}{2}x ^ 2}d(\arctan{x}) = \frac{1}{2}x ^ 2\arctan{x} - \frac{1}{2}\int{x ^ 2 \cdot \frac{1}{1 + x ^ 2}}dx
\\
= \frac{1}{2}x ^ 2\arctan{x} - \frac{1}{2}\int{\frac{x ^ 2}{1 + x ^ 2}}dx = \frac{1}{2}x ^ 2\arctan{x} - \frac{1}{2}\int{\frac{(x ^ 2 + 1) - 1}{1 + x ^ 2}}dx = \frac{1}{2}x ^ 2\arctan{x} - \frac{1}{2}\int{(1 - \frac{1}{1 + x ^ 2})}dx
\\
= \frac{1}{2}x ^ 2\arctan{x} - \frac{1}{2}(x - \arctan{x}) + C = \frac{1}{2}(x ^ 2 + 1)\arctan{x} - \frac{1}{2}x + C .
$$

$$
求 \int{e ^ x\sin{x}}dx .
\\
\because \int{e ^ x\sin{x}}dx = \int{\sin{x}}d(e ^ x) = e ^ x\sin{x} - \int{e ^ x}d(\sin{x}) = e ^ x\sin{x} - \int{e ^ x\cos{x}}dx ，
\\
\int{e ^ x\cos{x}}dx = \int{\cos{x}}d(e ^ x) = e ^ x\cos{x} - \int{e ^ x}d(\cos{x}) = e ^ x\cos{x} + \int{e ^ x\sin{x}}dx ，
\\
\therefore \int{e ^ x\sin{x}}dx = e ^ x\sin{x} - e ^ x\cos{x} - \int{e ^ x\sin{x}}dx ，
\\
\therefore 2\int{e ^ x\sin{x}}dx = e ^ x\sin{x} - e ^ x\cos{x} ，
\\
\therefore \int{e ^ x\sin{x}}dx = \frac{1}{2}e ^ x(\sin{x} - \cos{x}) + C .
$$

$$
求 \int{\sec ^ {3} {x}}dx .
\\
\int{\sec ^ {3} {x}}dx = \int{\sec{x} \cdot \sec ^ {2} {x}}dx = \int{\sec{x}}d(\tan{x}) = \sec{x}\tan{x} - \int{\tan{x}}d(\sec{x}) = \sec{x}\tan{x} - \int{\tan{x} \cdot \sec{x}\tan{x}}dx
\\
= \sec{x}\tan{x} - \int{\sec{x}\tan ^ {2} {x}}dx = \sec{x}\tan{x} - \int{\sec{x}(\sec ^ {2} {x} - 1)}dx = \sec{x}\tan{x} - \int{(\sec ^ {3} {x} - \sec{x})}dx
\\
= \sec{x}\tan{x} - \int{\sec ^ {3} {x}}dx + \int{\sec{x}}dx = \sec{x}\tan{x} + \ln{|\sec{x} + \tan{x}|} - \int{\sec ^ {3} {x}}dx ，
\\
\therefore 2\int{\sec ^ {3} {x}}dx = \sec{x}\tan{x} + \ln{|\sec{x} + \tan{x}|} ，
\\
\therefore \int{\sec ^ {3} {x}}dx = \frac{1}{2}(\sec{x}\tan{x} + \ln{|\sec{x} + \tan{x}|}) + C .
$$

$$
求 \int{e ^ {\sqrt{x}}}dx .
\\
令 \sqrt{x} = t ，则 x = t ^ 2 ， d(x) = 2tdt ，
\\
\int{e ^ {\sqrt{x}}}dx = 2\int{{t}{e ^ t}}dt = 2\int{t}d(e ^ t) = 2[{t}{e ^ t} - \int{e ^ t}d(t)] = 2({t}{e ^ t} - \int{e ^ t}dt) = 2({t}{e ^ t} - e ^ t) + C = 2e ^ t(t - 1) + C = 2e ^ {\sqrt{x}}(\sqrt{x} - 1) + C .
$$

$$
求 \int{(x ^ 3 + 2x +6)e ^ {2x}}dx .
\\
\int{(x ^ 3 + 2x +6)e ^ {2x}}dx = (x ^ 3 + 2x + 6)(\frac{1}{2}e ^ {2x}) - (3x ^ 2 + 2)(\frac{1}{4}e ^ {2x}) + 6x(\frac{1}{8}e ^ {2x}) - 6(\frac{1}{16}e ^ {2x}) + C
\\
=(\frac{1}{2}x ^ 3 - \frac{3}{4}x ^ 2 + \frac{7}{4}x + \frac{17}{8})e ^ {2x} + C .
$$




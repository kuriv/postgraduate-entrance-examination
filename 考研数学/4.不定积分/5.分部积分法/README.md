# 分部积分法

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

## 定理内容

$$
如果被积函数是幂函数与正（余）弦函数、指数函数、对数函数、反三角函数的乘积，就可以考虑应用分部积分法.
\\
\int{u}d(v) = uv - \int{v}d(u) .
\\
应用分部积分法时，恰当选取 u 和 d(v) 是一个关键，一般要考虑 v 容易求得，且 \int{v}d(u) 要比 \int{u}d(v) 容易积出.
$$

## 经典例题

### 例题一

$$
求 \int{x\cos{x}}dx .
\\
\int{x\cos{x}}dx = \int{x}d(\sin{x}) = x\sin{x} - \int{\sin{x}}dx = x\sin{x} + \cos{x} + C .
$$

### 例题二

$$
求 \int{xe ^ x}dx .
\\
\int{xe ^ x}dx = \int{x}d(e ^ x) = xe ^ x - \int{e ^ x}dx = xe ^ x - e ^ x + C = e ^ x(x - 1) + C .
$$

### 例题三

$$
求 \int{x ^ 2e ^ x}dx .
\\
\int{x ^ 2e ^ x}dx = \int{x ^ 2}d(e ^ x) = x ^ 2e ^ x - \int{e ^ x}d(x ^ 2) = x ^ 2e ^ x - 2\int{xe ^ x}dx ，
\\
2\int{xe ^ x}dx = 2\int{x}d(e ^ x) = 2(xe ^ x - \int{e ^ x}dx) = 2(xe ^ x - e ^ x) + C ，
\\
x ^ 2e ^ x - 2\int{xe ^ x}dx = x ^ 2e ^ x - 2(xe ^ x - e ^ x) + C = e ^ x(x ^ 2 - 2x + 2) + C .
$$

### 例题四

$$
求 \int{x\ln ^ x}dx .
\\
\int{x\ln ^ x}dx = \int{\ln ^ x}d(\frac{1}{2}x ^ 2) = \frac{1}{2}x ^ 2\ln ^ x - \int{\frac{1}{2}x ^ 2}d(\ln ^ x) = \frac{1}{2}x ^ 2\ln ^ x - \frac{1}{2}\int{x}dx = \frac{1}{2}x ^ 2\ln ^ x - \frac{1}{4}x ^ 2 + C .
$$

### 例题五

$$
求 \int{\arccos{x}}dx .
\\
\int{\arccos{x}}dx = \int{\arccos{x}}d(x) = x\arccos{x} - \int{x}d(\arccos{x}) = x\arccos{x} + \int{\frac{x}{\sqrt{1 - x ^ 2}}}dx = x\arccos{x} - \frac{1}{2}\int{\frac{1}{\sqrt{1 - x ^ 2}}}d(1 - x ^ 2)
\\
= x\arccos{x} - \frac{1}{2}\int{(1 - x ^ 2) ^ {-\frac{1}{2}}}d(1 - x ^ 2) = x\arccos{x} - \frac{1}{2} \cdot 2 \cdot (1 - x ^ 2) ^ {\frac{1}{2}} + C = x\arccos{x} - \sqrt{1 - x ^ 2} + C .
$$

### 例题六

$$
求 \int{x\arctan{x}}dx .
\\
\int{x\arctan{x}}dx = \int{\arctan{x}}d(\frac{1}{2}x ^ 2) = \frac{1}{2}x ^ 2\arctan{x} - \int{\frac{1}{2}x ^ 2}d(\arctan{x}) = \frac{1}{2}x ^ 2\arctan{x} - \int{\frac{1}{2}x ^ 2 \cdot \frac{1}{1 + x ^ 2}}dx
\\
= \frac{1}{2}x ^ 2\arctan{x} - \frac{1}{2}\int{\frac{x ^ 2}{1 + x ^ 2}}dx = \frac{1}{2}x ^ 2\arctan{x} - \frac{1}{2}\int{\frac{(x ^ 2 + 1) - 1}{1 + x ^ 2}}dx = \frac{1}{2}x ^ 2\arctan{x} - \frac{1}{2}\int{(1 - \frac{1}{1 + x ^ 2})}dx
\\
= \frac{1}{2}x ^ 2\arctan{x} - \frac{1}{2}(x - \arctan{x}) + C = \frac{1}{2}(x ^ 2 + 1)\arctan{x} - \frac{1}{2}x + C .
$$

### 例题七

$$
求 \int{e ^ x\sin{x}}dx .
\\
\int{e ^ x\sin{x}}dx = \int{\sin{x}}d(e ^ x) = e ^ x\sin{x} - \int{e ^ x}d(\sin{x}) = e ^ x\sin{x} - \int{e ^ x\cos{x}}dx ，
\\
\int{e ^ x\cos{x}}dx = \int{\cos{x}}d(e ^ x) = e ^ x\cos{x} - \int{e ^ x}d(\cos{x}) = e ^ x\cos{x} + \int{e ^ x\sin{x}}dx ，
\\
\therefore \int{e ^ x\sin{x}}dx = e ^ x\sin{x} - e ^ x\cos{x} - \int{e ^ x\sin{x}}dx ，
\\
\therefore 2\int{e ^ x\sin{x}}dx = e ^ x\sin{x} - e ^ x\cos{x} ，
\\
\therefore \int{e ^ x\sin{x}}dx = \frac{1}{2}e ^ x(\sin{x} - \cos{x}) + C .
$$

### 例题八

$$
求 \int{(\sec{x}) ^ 3}dx .
\\
\int{(\sec{x}) ^ 3}dx = \int{\sec{x} \cdot (\sec{x}) ^ 2}dx = \int{\sec{x}}d(\tan{x}) = \sec{x}\tan{x} - \int{\tan{x}}d(\sec{x}) = \sec{x}\tan{x} - \int{\tan{x} \cdot \sec{x}\tan{x}}dx
\\
= \sec{x}\tan{x} - \int{\sec{x}(\tan{x}) ^ 2}dx = \sec{x}\tan{x} - \int{\sec{x}((\sec{x}) ^ 2 - 1)}dx = \sec{x}\tan{x} - \int{((\sec{x}) ^ 3 - \sec{x})}dx
\\
= \sec{x}\tan{x} - \int{(\sec{x}) ^ 3}dx + \int{\sec{x}}dx = \sec{x}\tan{x} + \ln ^ {|\sec{x} + \tan{x}|} - \int{(\sec{x}) ^ 3}dx ，
\\
\therefore 2\int{(\sec{x}) ^ 3}dx = \sec{x}\tan{x} + \ln ^ {|\sec{x} + \tan{x}|} ，
\\
\therefore \int{(\sec{x}) ^ 3}dx = \frac{1}{2}(\sec{x}\tan{x} + \ln ^ {|\sec{x} + \tan{x}|}) + C .
$$

### 例题九

$$
求 \int{e ^ {\sqrt{x}}}dx .
\\
令 \sqrt{x} = t ，则 x = t ^ 2 ， d(x) = 2tdt ，
\\
\int{e ^ {\sqrt{x}}}dx = 2\int{{t}{e ^ t}}dt = 2\int{t}d(e ^ t) = 2({t}{e ^ t} - \int{e ^ t}d(t)) = 2({t}{e ^ t} - \int{e ^ t}dt) = 2({t}{e ^ t} - e ^ t) + C = 2e ^ t(t - 1) + C = 2e ^ {\sqrt{x}}(\sqrt{x} - 1) + C .
$$




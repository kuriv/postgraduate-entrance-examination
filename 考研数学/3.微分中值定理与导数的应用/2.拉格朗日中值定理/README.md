# 拉格朗日中值定理

* [定理内容](#定理内容)
* [经典例题](#经典例题)
  * [例题一](#例题一)
  * [例题二](#例题二)
  * [例题三](#例题三)

## 定理内容

$$
定义：如果函数 f(x) 满足在闭区间 [a , b] 上连续，在开区间 (a , b) 内可导，那么在 (a , b) 内至少存在一点 \xi (a \lt \xi \lt b) ，使得 f(\xi)\prime = \frac{f(b) - f(a)}{b - a} .
$$

![拉格朗日中值定理](拉格朗日中值定理.png)

## 经典例题

### 例题一

$$
以下是用罗尔定理证明拉格朗日中值定理的过程：
\\
令 f(x) 为原函数， g(x) 为辅助函数， F(x) 为满足罗尔定理的函数，则 F(x) = f(x) - g(x) ，
\\
构造辅助函数为： y - f(a) = \frac{f(b) - f(a)}{b - a}(x - a) ， 则 y = \frac{f(b) - f(a)}{b - a}(x - a) + f(a) ，
\\
\therefore F(x) = f(x) - g(x) = f(x) - \frac{f(b) - f(a)}{b - a}(x - a) - f(a) ，
\\
由罗尔定理得， F(a) = F(b) ，且 \exists \xi \in (a , b) ，使得 F(\xi)\prime = 0 ，
\\
\therefore F(\xi)\prime = [f(x) - \frac{f(b) - f(a)}{b - a}(x - a) - f(a)]\prime = f(\xi)\prime - \frac{f(b) - f(a)}{b - a} ，
\\
\therefore f(\xi)\prime - \frac{f(b) - f(a)}{b - a} = 0 ，即 f(\xi)\prime = \frac{f(b) - f(a)}{b - a} ，
\\
\therefore 由此可见，罗尔定理是拉格朗日中值定理的特殊情况.
$$

### 例题二

$$
如：求 \lim_{x \to +\infty}(\sin{\sqrt{x + 1}} - \sin{\sqrt{x}}) .
\\
令 f(x) = \sin{\sqrt{x}} ，则 \sin{\sqrt{x + 1}} - \sin{\sqrt{x}} = f(x + 1) - f(x) ，
\\
由拉格朗日中值定理得， f(b) - f(a) = (b - a) \cdot f(\xi)\prime ，
\\
\therefore f(x + 1) - f(x) = ((x + 1) - x) \cdot f(\xi)\prime ，即 f(x + 1) - f(x) = f(\xi)\prime ，
\\
\because f(\xi)\prime = \cos{\sqrt{\xi}} \cdot \frac{1}{2\sqrt{\xi}} ，
\\
\because x < \xi < x + 1 ， x \to \infty ，则 \xi \to \infty ，
\\
\therefore \lim_{x \to +\infty}f(\xi)\prime = 0 ，
\\
\therefore \lim_{x \to +\infty}(\sin{\sqrt{x + 1}} - \sin{\sqrt{x}}) = 0 .
$$

### 例题三

$$
如：求 \lim_{x \to \infty}x ^ 2 (\arctan{\frac{a}{x}} - \arctan{\frac{a}{x + 1}}) .
\\
令 f(x) = \arctan{x} ，则 x ^ 2 (\arctan{\frac{a}{x}} - \arctan{\frac{a}{x + 1}}) = x ^ 2(f(\frac{a}{x}) - f(\frac{a}{x + 1})) ，
\\
由拉格朗日中值定理得， f(b) - f(a) = (b - a) \cdot f(\xi)\prime ，
\\
\therefore f(\frac{a}{x}) - f(\frac{a}{x + 1}) = (\frac{a}{x} - \frac{a}{x + 1}) \cdot f(\xi)\prime ，
\\
\because f(\xi)\prime = \frac{1}{1 + \xi ^ 2} ，
\\
\because \frac{a}{x + 1} < \xi < \frac{a}{x} ， x \to \infty ，则 \xi \to 0 ，
\\
\therefore \lim_{x \to \infty}\frac{1}{1 + \xi ^ 2} = 1 ，
\\
\therefore \lim_{x \to \infty}x ^ 2 (\arctan{\frac{a}{x}} - \arctan{\frac{a}{x + 1}}) = \lim_{x \to \infty}x ^ 2 \cdot (\frac{a}{x} - \frac{a}{x + 1}) \cdot 1 = \lim_{x \to \infty}\frac{a \cdot x ^ 2}{x(x + 1)} = a .
$$




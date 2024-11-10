# 二重积分计算

* [直角坐标系下计算](#直角坐标系下计算)
* [极坐标系下计算](#极坐标系下计算)
* [经典例题](#经典例题)

## 直角坐标系下计算

$$
\
\
\iint_D{f(x , y)}d\sigma = \int_{a} ^ {b}{dx}\int_{\phi_1(x)} ^ {\phi_2(x)}{f(x , y)}dy ，其中 D 为 X 型区域： \phi_1(x) \le y \le \phi_2(x) ， a \le x \le b .
$$

$$
\
\
\iint_D{f(x , y)}d\sigma = \int_{c} ^ {d}{dy}\int_{\psi_1(y)} ^ {\psi_2(y)}{f(x , y)}dx ，其中 D 为 Y 型区域： \psi_1(y) \le y \le \psi_2(y) ， c \le x \le d .
$$

## 极坐标系下计算

$$
\iint_D{f(x , y)}d\sigma = \int_{\alpha} ^ {\beta}d\theta\int_{r_1(\theta)} ^ {r_2(\theta)}{f(r\cos{\theta} , r\sin{\theta})}rdr （极点 O 在区域 D 外部） .
\\
\iint_D{f(x , y)}d\sigma = \int_{\alpha} ^ {\beta}d\theta\int_{0} ^ {r(\theta)}{f(r\cos{\theta} , r\sin{\theta})}rdr （极点 O 在区域 D 边界上） .
\\
\iint_D{f(x , y)}d\sigma = \int_{0} ^ {2\pi}d\theta\int_{0} ^ {r(\theta)}{f(r\cos{\theta} , r\sin{\theta})}rdr （极点 O 在区域 D 内部） .
$$

## 经典例题

$$
如：当 x \to 0 ^ {+} 时， f(x) = \int_{0} ^ {x ^ 2}{dy}\int_{x} ^ {\sqrt{y}}{\sin{\frac{y}{t}}}dt 与 g(x) = a{x ^ b} 是等价无穷小量，求 ab .
\\
\because \int_{0} ^ {x ^ 2}{dy}\int_{x} ^ {\sqrt{y}}{\sin{\frac{y}{t}}}dt = -\int_{0} ^ {x ^ 2}{dy}\int_{\sqrt{y}} ^ {x}{\sin{\frac{y}{t}}}dt = -\int_{0} ^ {x}{dt}\int_{0} ^ {t ^ 2}{\sin{\frac{y}{t}}}dy = \int_{0} ^ {x}{t \cdot \cos{\frac{y}{t}}|_{y = 0} ^ {y = t ^ 2}}dt = \int_{0} ^ {x}{t \cdot (\cos{t} - 1)}dt ，
\\
\because f(x) 与 g(x) 是等价无穷小量 ，
\\
\therefore \lim_{x \to 0 ^ {+}} \frac{\int_{0} ^ {x}{t \cdot (\cos{t} - 1)}dt}{a{x ^ b}} = \lim_{x \to 0 ^ {+}} \frac{x \cdot (\cos{x} - 1)}{ab{x ^ {b - 1}}} = \lim_{x \to 0 ^ {+}} \frac{-\frac{1}{2}x ^ 3}{ab{x ^ {b - 1}}} = 1 ，
\\
\therefore ab = -\frac{1}{2} .
$$

$$
如：设区域 D = \{(x , y)|x ^ 2 + y ^ 2 \le \sqrt{2}\} ，求 \iint_D{(x ^ 2 + \frac{y ^ 2}{2})}dxdy .
\\
由轮换对称性可得， I = \frac{1}{2}[\iint_D{(x ^ 2 + \frac{y ^ 2}{2})}dxdy + \iint_D{(y ^ 2 + \frac{x ^ 2}{2})}dxdy] = \frac{3}{4}\iint_D{(x ^ 2 + y ^ 2)}dxdy ，
\\
\therefore \frac{3}{4}\iint_D{(x ^ 2 + y ^ 2)}dxdy = \frac{3}{4}\int_{0} ^ {2\pi}d\theta\int_{0} ^ {\sqrt[4]{2}}{r ^ 3}dr = \frac{3}{4}\pi .
$$




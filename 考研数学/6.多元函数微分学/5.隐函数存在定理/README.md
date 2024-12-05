# 隐函数存在定理

* [定理内容](#定理内容)
* [经典例题](#经典例题)

## 定理内容

$$
对于由方程 F(x , y) = 0 确定的隐函数 y = f(x) ，当 F_{y} ^ {\prime} (x , y) \neq 0 时， \frac{dy}{dx} = -\frac{F_{x} ^ {\prime} (x , y)}{F_{y} ^ {\prime} (x , y)} .
$$

$$
对于由方程 F(x , y , z) = 0 确定的隐函数 z = f(x , y) ，当 F_{z} ^ {\prime} (x , y , z) \neq 0 时，
\\
\frac{\partial{z}}{\partial{x}} = -\frac{F_{x} ^ {\prime} (x , y , z)}{F_{z} ^ {\prime} (x , y , z)} ， \frac{\partial{z}}{\partial{y}} = -\frac{F_{y} ^ {\prime} (x , y , z)}{F_{z} ^ {\prime} (x , y , z)} .
$$

## 经典例题

$$
如：设函数 z = z(x , y) 由方程 F(x + z{y} ^ {-1} , y + z{x} ^ {-1}) = 0 所确定，其中 F 具有连续偏导数，且 x{F_1 ^ {\prime}} + y{F_2 ^ {\prime}} \neq 0 ，求 x\frac{\partial{z}}{\partial{x}} + y\frac{\partial{z}}{\partial{y}} .
\\
令 G(x , y , z) = F(x + z{y} ^ {-1} , y + z{x} ^ {-1}) ，
\\
\because \frac{\partial{z}}{\partial{x}} = -\frac{G_x ^ {\prime}}{G_z ^ {\prime}} = -\frac{F_1 ^ {\prime} - \frac{z}{x ^ 2}F_2 ^ {\prime}}{\frac{1}{y}F_1 ^ {\prime} + \frac{1}{x}F_2 ^ {\prime}} ， \frac{\partial{z}}{\partial{y}} = -\frac{G_y ^ {\prime}}{G_z ^ {\prime}} = -\frac{-\frac{z}{y ^ 2}F_1 ^ {\prime} + F_2 ^ {\prime}}{\frac{1}{y}F_1 ^ {\prime} + \frac{1}{x}F_2 ^ {\prime}} ，
\\
\therefore x\frac{\partial{z}}{\partial{x}} + y\frac{\partial{z}}{\partial{y}} = \frac{(-x{F_1 ^ {\prime}} + \frac{z}{x}F_2 ^ {\prime}) + (\frac{z}{y}F_1 ^ {\prime} - y{F_2 ^ {\prime}})}{\frac{1}{y}F_1 ^ {\prime} + \frac{1}{x}F_2 ^ {\prime}} = \frac{-{x ^ 2}y{F_1 ^ {\prime}} + {yz}F_2 ^ {\prime} + {xz}F_1 ^ {\prime} - x{y ^ 2}{F_2 ^ {\prime}}}{x{F_1 ^ {\prime}} + y{F_2 ^ {\prime}}}
\\
= \frac{(-{x ^ 2}y + xz)F_1 ^ {\prime} + (yz - x{y ^ 2})F_2 ^ {\prime}}{x{F_1 ^ {\prime}} + y{F_2 ^ {\prime}}} = \frac{x{F_1 ^ {\prime}}(-xy + z) + y{F_2 ^ {\prime}}(z - xy)}{x{F_1 ^ {\prime}} + y{F_2 ^ {\prime}}} = z - xy .
$$




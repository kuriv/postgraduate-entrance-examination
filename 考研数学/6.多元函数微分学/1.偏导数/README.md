# 偏导数

* [偏导数](#偏导数)
* [高阶偏导数](#高阶偏导数)
* [经典例题](#经典例题)

## 偏导数

$$
设函数 z = f(x , y) 在点 (x_0 , y_0) 的某邻域内有定义，如果极限 \lim_{\Delta{x}\to 0} {\frac{f(x_0 + \Delta{x} , y_0) - f(x_0 , y_0)}{\Delta{x}}} 存在，
\\
则称此极限为函数 z = f(x , y) 在点 (x_0 , y_0) 处对 x 的偏导数，记作 \frac{\partial{z}}{\partial{x}}|_{x = x_0 , y = y_0} 或 f_x ^ {\prime} (x_0 , y_0) .
$$

$$
类似地，函数 z = f(x , y) 在点 (x_0 , y_0) 处对 y 的偏导数定义为 f_y ^ {\prime} (x_0 , y_0) = \lim_{\Delta{y}\to 0} {\frac{f(x_0 , y_0 + \Delta{y}) - f(x_0 , y_0)}{\Delta{y}}} .
$$

## 高阶偏导数

$$
如果函数 z = f(x , y) 的偏导数 f_x ^ {\prime} (x , y) 和 f_y ^ {\prime} (x , y) 仍然具有偏导数，则它们的偏导数就称为 z = f(x , y) 的二阶偏导数.
\\
\frac{\partial ^ {2} {z}}{\partial{x} ^ 2} = \frac{\partial}{\partial{x}}(\frac{\partial{z}}{\partial{x}}) = f_{xx} ^ {\prime\prime} (x , y) = z_{xx} ^ {\prime\prime}
\\
\frac{\partial ^ {2} {z}}{\partial{x}\partial{y}} = \frac{\partial}{\partial{y}}(\frac{\partial{z}}{\partial{x}}) = f_{xy} ^ {\prime\prime} (x , y) = z_{xy} ^ {\prime\prime}
\\
\frac{\partial ^ {2} {z}}{\partial{y} ^ 2} = \frac{\partial}{\partial{y}}(\frac{\partial{z}}{\partial{y}}) = f_{yy} ^ {\prime\prime} (x , y) = z_{yy} ^ {\prime\prime}
\\
\frac{\partial ^ {2} {z}}{\partial{y}\partial{x}} = \frac{\partial}{\partial{x}}(\frac{\partial{z}}{\partial{y}}) = f_{yx} ^ {\prime\prime} (x , y) = z_{yx} ^ {\prime\prime}
$$

## 经典例题

$$
已知函数 f(x , y) = \ln(y + |x\sin{y}|) ，求 \frac{\partial{f}}{\partial{x}}_{(0 , 1)} ， \frac{\partial{f}}{\partial{y}}_{(0 , 1)} .
\\
\because \frac{\partial{f}}{\partial{x}}_{(0 , 1)} = \lim_{x \to 0} {\frac{f(x , 1) - f(0 , 1)}{x - 0}} = \lim_{x \to 0} {\frac{\ln(1 + |x|\sin{1})}{x}} = \lim_{x \to 0} \frac{|x|\sin{1}}{x} ，
\\
\therefore \frac{\partial{f}}{\partial{x}}_{(0 , 1)} 不存在 ，
\\
\because \frac{\partial{f}}{\partial{y}}_{(0 , 1)} = \lim_{y \to 1} {\frac{\ln{y}}{y - 1}} = \frac{1}{y} = 1 ，
\\
\therefore \frac{\partial{f}}{\partial{y}}_{(0 , 1)} = 1 .
$$

$$
设函数 f(t) 连续，令 F(x , y) = \int_{0} ^ {x - y}{(x - y - t)f(t)}dt ，求 \frac{\partial{F}}{\partial{x}} ， \frac{\partial{F}}{\partial{y}} ， \frac{\partial ^ {2} {F}}{\partial{x} ^ 2} ， \frac{\partial ^ {2} {F}}{\partial{y} ^ 2} .
\\
\because F(x , y) = \int_{0} ^ {x - y}{(x - y - t)f(t)}dt = x\int_{0} ^ {x - y}{f(t)}dt - y\int_{0} ^ {x - y}{f(t)}dt - \int_{0} ^ {x - y}{tf(t)}dt ，
\\
\therefore \frac{\partial{F}}{\partial{x}} = \int_{0} ^ {x - y}{f(t)}dt + xf(x - y) - yf(x - y) - (x - y)f(x - y) = \int_{0} ^ {x - y}{f(t)}dt ，
\\
\therefore \frac{\partial{F}}{\partial{y}} = -xf(x - y) - \int_{0} ^ {x - y}{f(t)}dt + yf(x - y) + (x - y)f(x - y) = -\int_{0} ^ {x - y}{f(t)}dt ，
\\
\therefore \frac{\partial ^ {2} {F}}{\partial{x} ^ 2} = f(x - y) ，
\\
\therefore \frac{\partial ^ {2} {F}}{\partial{x} ^ 2} = f(x - y) .
$$




# 向量组的线性相关性

* [线性组合](#线性组合)
* [线性表示](#线性表示)
* [线性相关](#线性相关)
* [线性无关](#线性无关)
* [判别定理](#判别定理)

## 线性组合

$$
设有 m 个 n 维向量 \alpha_1 ， \alpha_2 ， \cdots ， \alpha_m 及 m 个数 k_1 ， k_2 ， \cdots ， k_m ，则向量 k_1\alpha_1 + k_2\alpha_2 + \cdots k_m\alpha_m 称为向量组 \alpha_1 ， \alpha_2 ， \cdots ， \alpha_m 的线性组合.
$$

## 线性表示

$$
若向量 \beta 能表示成向量组 \alpha_1 ， \alpha_2 ， \cdots ， \alpha_m 的线性组合，即存在 m 个数 k_1 ， k_2 ， \cdots ， k_m ，使得 \beta = k_1\alpha_1 + k_2\alpha_2 + \cdots k_m\alpha_m ，
\\
则称向量 \beta 能被为向量组 \alpha_1 ， \alpha_2 ， \cdots ， \alpha_m 线性表示.
$$

## 线性相关

$$
对于 m 个 n 维向量 \alpha_1 ， \alpha_2 ， \cdots ， \alpha_m ，若存在一组不全为零的数 k_1 ， k_2 ， \cdots ， k_m ，使得 k_1\alpha_1 + k_2\alpha_2 + \cdots k_m\alpha_m = 0 ，
\\
则称向量组 \alpha_1 ， \alpha_2 ， \cdots ， \alpha_m 线性相关.
$$

## 线性无关

$$
若只有当 k_1 = k_2 = \cdots = k_m = 0 时，才有 k_1\alpha_1 + k_2\alpha_2 + \cdots k_m\alpha_m = 0，则称向量组 \alpha_1 ， \alpha_2 ， \cdots ， \alpha_m 线性无关.
$$

## 判别定理

$$
向量组 \alpha_1 ， \alpha_2 ， \cdots ， \alpha_n (n \ge 2) 线性相关的充要条件是向量组中至少有一个向量可由其余的 n - 1 个向量线性表示.
\\
向量组 \alpha_1 ， \alpha_2 ， \cdots ， \alpha_n (n \ge 2) 线性无关的充要条件是 \alpha_1 ， \alpha_2 ， \cdots ， \alpha_n 中任一向量都不能由其余的 n - 1 个向量线性表示.
$$

$$
若向量组 \alpha_1 ， \alpha_2 ， \cdots ， \alpha_n 线性无关，而 \beta ， \alpha_1 ， \alpha_2 ， \cdots ， \alpha_n 线性相关，则 \beta 可由 \alpha_1 ， \alpha_2 ， \cdots ， \alpha_n 线性表示，且表示法唯一.
$$

$$
若向量组 \beta_1 ， \beta_2 ， \cdots ， \beta_t 可由向量组 \alpha_1 ， \alpha_2 ， \cdots ， \alpha_s 线性表示，且 t \gt s ，则 \beta_1 ， \beta_2 ， \cdots ， \beta_t 线性相关 （以少表多，多的相关） .
\\
若向量组 \beta_1 ， \beta_2 ， \cdots ， \beta_t 可由向量组 \alpha_1 ， \alpha_2 ， \cdots ， \alpha_s 线性表示，且 \beta_1 ， \beta_2 ， \cdots ， \beta_t 线性无关，则 t \le s .
$$

$$
向量组 \alpha_1 ， \alpha_2 ， \cdots ， \alpha_n 线性相关 \Leftarrow\Rightarrow 齐次线性方程组有非零解 \Leftarrow\Rightarrow r(\alpha_1 ， \alpha_2 ， \cdots ， \alpha_n) \lt n .
\\
\alpha_1 ， \alpha_2 ， \cdots ， \alpha_n 线性无关的充分必要条件是齐次线性方程组只有零解.
$$

$$
向量 \beta 可由向量组 \alpha_1 ， \alpha_2 ， \cdots ， \alpha_n 线性表示 \Leftarrow\Rightarrow 非齐次线性方程组有解 \Leftarrow\Rightarrow r([\alpha_1 ， \alpha_2 ， \cdots ， \alpha_n]) = r([\alpha_1 ， \alpha_2 ， \cdots ， \alpha_n ， \beta]) .
\\
向量 \beta 不能由向量组 \alpha_1 ， \alpha_2 ， \cdots ， \alpha_n 线性表示 \Leftarrow\Rightarrow 非齐次线性方程组无解 \Leftarrow\Rightarrow r([\alpha_1 ， \alpha_2 ， \cdots ， \alpha_n]) \neq r([\alpha_1 ， \alpha_2 ， \cdots ， \alpha_n ， \beta]) .
$$

$$
若向量组 \alpha_1 ， \alpha_2 ， \cdots ， \alpha_n 中有一部分向量线性相关，则整个向量组也线性相关.
\\
若向量组 \alpha_1 ， \alpha_2 ， \cdots ， \alpha_n 线性无关，则其任一部分向量组都线性无关.
$$

$$
若一组 n 维向量 \alpha_1 ， \alpha_2 ， \cdots ， \alpha_s 线性无关，那么把这些向量各任意添加 m 个分量所得到的新向量 (n + m 维) 组 \alpha_1 ^ * ， \alpha_2 ^ * ， \cdots ^ * ， \alpha_s ^ * 也是线性无关的.
\\
若 \alpha_1 ， \alpha_2 ， \cdots ， \alpha_s 线性相关，那么它们各去掉相同的若干分量所得到的新向量组也是线性相关的.
$$




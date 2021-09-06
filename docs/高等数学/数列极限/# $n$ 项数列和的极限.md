# $n$ 项数列和的极限
常见题型。两种常用方法: 夹逼定理和定积分定义

解决 $n$ 项数列和的极限问题，常用两种方法：夹逼定理和定积分定义。

例如：括号内为 $n$ 项数列的和, 求 $n$ 趋向无穷时的极限
$$
\lim _{n \rightarrow \infty}\left(\frac{1}{n^{2}+n+1}+\frac{2}{n^{2}+n+2}+\cdots+\frac{n}{n^{2}+n+n}\right)
$$
# 夹逼定理
通过放缩, 计算数列的上限和下限, 证明 "上限的极限=下限的极限", 则 "所求极限=上限的圾限=下限的极限。" 定积分将区间分割成无限小的 $n$ 段, 它们的和的极限 = 区间上的积分。

这里只要求对这两种方法有一定概念, 具体应用会另行训练。


# 定积分定义

 $\lim _{n \rightarrow \infty} \frac{1}{n} \sum_{i=1}^{n} f\left(\frac{i}{n}\right)=\int_{0}^{1} f(x) \mathrm{d} x$

利用定积分的定义求 $n$ 项和的数列极限：

将每项写成 $\frac{1}{n} f\left(\frac{i}{n}\right)$ 的形式。

设 $f(x)$ 在 $[0,1]$ 上连续, 则

$$
\lim _{n \rightarrow \infty} \frac{1}{n} \sum_{i=1}^{n} f\left(\frac{i}{n}\right)=\int_{0}^{1} f(x) \mathrm{d} x
$$

注意 $f(x)$ 中不包含 $n .$

## 【理解】

定积分定义: $n \rightarrow \infty$ 时, $n$ 个矩形面积之和的籷限, 如图。其中每个矩形的㝋都为 $\frac{1}{n}$, 第 $i$ 个矩形的高为 $f\left(\frac{i}{n}\right)$.
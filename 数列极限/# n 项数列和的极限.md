<<<<<<< 601cdfb58b42da94a99940de3f4816b2c0b3e61a:docs/高等数学/数列极限/# $n$ 项数列和的极限.md
<<<<<<< 601cdfb58b42da94a99940de3f4816b2c0b3e61a:docs/高等数学/数列极限/# $n$ 项数列和的极限.md
# $n$ 项数列和的极限
=======
# n 项数列和的极限
---
tags:
  - 基础知识
  - 数列极限
---
>>>>>>> 9.9update:docs/高等数学/数列极限/# n 项数列和的极限.md
常见题型。两种常用方法: 夹逼定理和定积分定义

解决 $n$ 项数列和的极限问题，常用两种方法：夹逼定理和定积分定义。

例如：括号内为 $n$ 项数列的和, 求 $n$ 趋向无穷时的极限
$$
\lim _{n \rightarrow \infty}\left(\frac{1}{n^{2}+n+1}+\frac{2}{n^{2}+n+2}+\cdots+\frac{n}{n^{2}+n+n}\right)
$$
## 夹逼定理
通过放缩, 计算数列的上限和下限, 

证明 "上限的极限=下限的极限",

则 "所求极限=上限的圾限=下限的极限。" 

>夹逼定理: $g(x) \leq f(x) \leq h(x), \lim _{x \rightarrow x_{0}} g(x)=\lim _{x \rightarrow x_{0}} h(x)=A$, 则 $\lim _{x \rightarrow x_{0}} f(x)=A$

### 【定义】 

1. 在 $x_{0}$ 的去心邻域内 $g(x) \leq f(x) \leq h(x)$ \\ \hline \end{tabular}

2. $\lim _{x \rightarrow x_{0}} g(x)=\lim _{x \rightarrow x_{0}} h(x)=A$, 则 $\lim _{x \rightarrow x_{0}} f(x)=A$

    即 $f(x)$ 的上限和下限都趋于 $A$, 则 $f(x)$ 趋于 $A$

### 【注】 
1. 夹逼定理对于数列也成立.

2. 上面的 $A$ 都换为 $+\infty$ 或 $-\infty$, 定理也成立.

### 夹逼定理的放缩方法一: 

观察数列每一项分母中 $n$ 最高次方项和系数都一致，则用最小和最大分母分别替换所有分母, 得出上下限

运用夹逼定理，关键在于通过合适的放缩，找到 $g(x) \leq f(x) \leq h(x)$, 

使得 $\lim _{x \rightarrow x_{0}} g(x)=\lim _{x \rightarrow x_{0}} h(x)=A$.

常用的放缩:

求 $\lim _{n \rightarrow \infty}\left(\frac{1}{n^{2}+n+1}+\frac{2}{n^{2}+n+2}+\cdots+\frac{n}{n^{2}+n+n}\right)$

注意每一项分母的最高次项都是 $n^{2}$, 则

原式的上限：用第一项的分母， $n^{2}+n+1$, 替换所有分母, 得到 $\frac{\sum_{k=1}^{n} k}{n^{2}+n+1}$.

原式的下限：用最后一项的分母, $n^{2}+n+n$, 替换所有分母，得到 $\frac{\sum_{k=1}^{n} k}{n^{2}+n+n}$.



# **定积分定义**

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
=======
# n 项数列和的极限

两种常用方法: **夹逼定理**和**定积分定义**

例如：括号内为 $n$ 项数列的和, 求 $n$ 趋向无穷时的极限
$$
\lim _{n \rightarrow \infty}\left(\frac{1}{n^{2}+n+1}+\cdots+\frac{n}{n^{2}+n+n}\right)
$$
## **夹逼定理**

通过放缩, 计算数列的上限和下限, 

证明 "上限的极限=下限的极限",

则 "所求极限=上限的圾限=下限的极限。" 

>夹逼定理: $g(x) \leq f(x) \leq h(x),$ 
$\lim\limits _{x \rightarrow x_{0}}g(x)=$
$\lim \limits_{x \rightarrow x_{0}} h(x)=A$,
则 $\lim \limits_{x \rightarrow x_{0}} f(x)=A$

### **定义**

1. 在 $x_{0}$ 的去心邻域内 $g(x) \leq f(x) \leq h(x)$
2. $\lim \limits_{x \rightarrow x_{0}} g(x)=\lim \limits_{x \rightarrow x_{0}} h(x)=A$, 则 $\lim \limits_{x \rightarrow x_{0}} f(x)=A$

    即 $f(x)$ 的上限和下限都趋于 $A$, 则 $f(x)$ 趋于 $A$

### [注]
1. 夹逼定理对于数列也成立.

2. 上面的 $A$ 都换为 $+\infty$ 或 $-\infty$, 定理也成立.

### 夹逼定理的放缩方法
1. 观察数列每一项分母中 $n$ 最高次方项和系数都一致，则用最小和最大分母分别替换所有分母, 得出上下限

      运用夹逼定理，关键在于通过合适的放缩，找到 $g(x) \leq f(x) \leq h(x)$, 

      使得 $\lim _{x \rightarrow x_{0}} g(x)=\lim _{x \rightarrow x_{0}} h(x)=A$.

      **常用的放缩**:

      求 $\lim \limits_{n \rightarrow \infty}\left(\frac{1}{n^{2}+n+1}+\frac{2}{n^{2}+n+2}+\cdots+\frac{n}{n^{2}+n+n}\right)$

      注意每一项分母的最高次项都是 $n^{2}$, 则

      **原式的上限**：用第一项的分母， $n^{2}+n+1$, 替换所有分母, 得到 $\frac{\sum_{k=1}^{n} k}{n^{2}+n+1}$.

      **原式的下限**：用最后一项的分母, $n^{2}+n+n$, 替换所有分母，得到 $\frac{\sum_{k=1}^{n} k}{n^{2}+n+n}$.



## **定积分定义**

 $\lim _{n \rightarrow \infty} \frac{1}{n} \sum_{i=1}^{n} f\left(\frac{i}{n}\right)=\int_{0}^{1} f(x) \mathrm{d} x$

利用定积分的定义求 $n$ 项和的数列极限：

将每项写成 $\frac{1}{n} f\left(\frac{i}{n}\right)$ 的形式。

设 $f(x)$ 在 $[0,1]$ 上连续, 则

$$
\lim _{n \rightarrow \infty} \frac{1}{n} \sum_{i=1}^{n} f\left(\frac{i}{n}\right)=\int_{0}^{1} f(x) \mathrm{d} x
$$

注意 $f(x)$ 中不包含 $n .$

### [理解]

定积分定义: $n \rightarrow \infty$ 时, $n$ 个矩形面积之和的籷限, 如图。其中每个矩形的㝋都为 $\frac{1}{n}$, 第 $i$ 个矩形的高为 $f\left(\frac{i}{n}\right)$.

### 处理 (n+1)

上下同除 $(n+1)$, 再利用 $\lim _{n \rightarrow \infty} \frac{n}{n+1}=1$

经常出现在需要同时使用夹逼定理和定积分定义的数列求和问题中。例如：

**原式的上限**： $U=\sum_{k=1}^{n} \frac{1}{n+k} .$ 

**原式的下限**： $L=\sum_{k=1}^{n} \frac{1}{n+k+1}$.

则应用定积分定义, $\quad U=\frac{1}{n} \sum_{k=1}^{n} \frac{1}{1+\frac{k}{n}}=\int_{0}^{1} \frac{1}{1+x} \mathrm{~d} x$.

但如果将 $L$ 上下同除 $n$, 则得到 $L=\frac{1}{n} \sum_{k=1}^{n} \frac{1}{1+\frac{k+1}{n}}$, 无法直接应用定积分定义。

??? 正确做法
    <h3>
     上下同除 $(n+1)$,得到

     $L=\frac{1}{n+1} \sum_{k=1}^{n} \frac{1}{1+\frac{k}{n+1}} \geq \frac{1}{n+1} \sum_{k=1}^{n} \frac{1}{1+\frac{k}{n}}=\frac{n}{n+1} \frac{1}{n} \sum_{k=1}^{n} \frac{1}{1+\frac{k}{n}}=\frac{n}{n+1} U$

     注意 $\lim _{n \rightarrow \infty} \frac{n}{n+1}=1$, 即 $n$ 和 $n+1$ 在 $n$ 趋向无穷时是一样的。

     因为 $U \geq L \geq \frac{n}{n+1} U$, 且 $\lim _{n \rightarrow \infty} U=\lim _{n \rightarrow \infty} \frac{n}{n+1} U$, 所以根据夹逼定理 $\lim _{n \rightarrow \infty} U=\lim _{n \rightarrow \infty} L=\lim _{n \rightarrow \infty} \frac{n}{n+1} U$.
>>>>>>> merged something to improve clerity:docs/高等数学/数列极限/# n 项数列和的极限.md

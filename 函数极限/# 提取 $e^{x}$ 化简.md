# 提取 $e^{x}$ 化简

### $\lim\limits_{x \rightarrow+\infty} \ln \left(e^{x}+C\right)=\lim \limits_{x \rightarrow+\infty} x$.

$\lim\limits_{x\to+\infty} \ln \left(A e^{x}+B\right)$ 

$=\lim \limits_{x \rightarrow+\infty} \ln \left[e^{x}\left(A+B e^{-x}\right)\right]$ 

$=\lim\limits _{x \rightarrow+\infty}\left[x+\ln \left(A+B e^{-x}\right)\right]$

 $=\lim \limits_{x \rightarrow+\infty} x+\ln A$
 21cxswd`
其中 $A, B$ 为常数, $A>0$ 。

## 【理解】
 当 $x \rightarrow+\infty$ 时, $e^{x}$ 远大于 1 , 所以 $\ln \left(A e^{x}+B\right) \rightarrow \ln \left(A e^{x}\right)=x+\ln A$.

 //我觉得有一个重要的地方就是要转换出$e^{-x}=0$消去
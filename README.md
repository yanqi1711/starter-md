等比数列求和公式是通过数学归纳法或者代数推导得到的。我们来简单推导一下。

首先，等比数列的通项公式可以表示为：

\[ a_n = a_1 \cdot r^{n-1} \]

其中，\( a_1 \) 是首项，\( r \) 是公比，\( n \) 是项数。

为了求前 \( n \) 项的和 \( S_n \)，我们可以写出：

\[ S_n = a_1 + a_1 r + a_1 r^2 + \ldots + a_1 r^{n-1} \]

接下来，我们将整个等式乘以公比 \( r \)：

\[ r S_n = a_1 r + a_1 r^2 + a_1 r^3 + \ldots + a_1 r^n \]

现在，将上面两个等式相减：

\[
S_n - r S_n = a_1 - a_1 r^n
\]

整理之后，我们得到：

\[
S_n (1 - r) = a_1 (1 - r^n)
\]

接下来，解出 \( S_n \)：

\[
S_n = \frac{a_1 (1 - r^n)}{1 - r} \quad (r \neq 1)
\]

所以，等比数列前 \( n \) 项的和公式为：

\[
S_n = \frac{a_1 (1 - r^n)}{1 - r}
\]

如果公比 \( r = 1 \)，那么每一项都是相等的，前 \( n \) 项的和显然为：

\[
S_n = n a_1
\]

这样，我们就得到了等比数列的求和公式。


等差数列前 \( n \) 项和的公式为：

\[
S_n = \frac{n}{2} \times (a_1 + a_n)
\]

其中：
- \( S_n \) 表示前 \( n \) 项和；
- \( a_1 \) 是等差数列的首项；
- \( a_n \) 是等差数列的第 \( n \) 项；
- \( n \) 是项数。

如果已知首项 \( a_1 \) 和公差 \( d \)，也可以用以下公式计算前 \( n \) 项和：

\[
S_n = \frac{n}{2} \times (2a_1 + (n-1)d)
\]

其中：
- \( d \) 是等差数列的公差。

这两个公式都可以有效地用于计算等差数列的前 \( n \) 项和。

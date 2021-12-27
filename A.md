Pls enter filename.md format and coding what you want to express to us.
And "#" is a excellent tool for us to disguise different title.
# This is the header 1
This is the header 1
==========
## This is the header 1.1
This is the header 2 
---------
### This is the header 1.1.1 

This is the text.

---
Three line represent the different part

---

**A** use double ** to control + B
*A*   use single * to control + I
~~B~~ use double ~~ to delete
==A== use double == to enhance
- [x] thing that have been done
- [ ] thing that have not been done

---
list
* list without order
  * sub list 
    * next
      * next

1. list with order
   1. first
   2. second
      1. go on

asdf <!>

> use others words
> and this is the standard grammar

---
demo
``` python
print("Hello world!")
```

``` javascript {.line-numbers}
function add(x,y)
{
    return x+y
}
```

---
[Blog](https://orangex4.cool/)
![Photo](https://orangex4.cool/images/icons/profile.jpg)

---
使用本地用相对地址:
[B](B.md)
![A](1.jpg)
# this is the header 2

---
use control + shift +alt + v can paste the image for the clipboard 
![](https://pic3.58cdn.com.cn/nowater/webim/big/n_v2c3fb50922f8847deba2da88e48b80c85.png)
control + alt + v can't use this time 

---
**can't emerge the table**
| A   | A        |
| --- | -------- |
| X   | Y        |
|A| W        |
|U ||

| 表头 | 表头 |
| ---- | ---- |
| 内容 | 内容|
| ^    | 内容 |

<!-- you can't see me-->
<!-- you can't see me
just like this -->

---
Latex grammar
circle $x^5+y^{2}+z_1=1$

$$
\begin{cases}
   x=\rho\cos\theta \\
   y=\rho\sin\theta \\
\end{cases}
$$

$$x^{-1}$$
<!-- //-1   -> ^{-1} 
    //comma -> \alpha_1,\alpha_2,\cdots,\alpha_n-->

$$\alpha_1,\alpha_2,\cdots,\alpha_n$$
$\frac{1}{2}$
<!-- "displaystyle"transform the display from line to block-->
$$\displaystyle\frac{x+1}{22}$$
$$\sqrt[n]{\frac{a}{x}}$$
$$\sqrt{x+1}$$

---
<!--what the different from this is the space ,
"\!"        can make no space from different letter
"\,"        can make the little space 
"\;"        can make the middle space 
"\ "        can make the large  space 
"\quad"     can make more big space 
"\qquad"    can make the biggest space-->
$$a\!b$$
$$ab$$
$$a\,b$$
$$a\;b$$
$$a\ b$$
$$a\quad b$$
$$a\qquad b$$

---
<!-- click the "space" on the keyboard make no sense to the math formula
{\rm d} can change the type of the words-->
$$\sum_{k=1}^n\frac{1}{k} \quad \displaystyle\sum_{k=1}^n\frac{1}{k}$$
$$\prod_{i=1}^n\frac{1}{i} \quad \displaystyle\prod_{i=1}^n\frac{1}{i}$$
$$\displaystyle \int_0^1x{\rm d}x $$
$$\displaystyle \iint_{D_{xy}}f(x,y){\rm d}A   $$
$$\displaystyle \iiint_{\Omega_xyz}f(x,y,z)dxdydz$$ 
$$\lim_{x \to 0}\frac{x}{sinx}$$

---
$$\displaystyle \left(\sum_{i=1}^n \frac{1}{i}\right)^2$$
$$\displaystyle \left[\prod_{i=1}^n \frac{1}{i}\right]^2$$
$$\displaystyle \left\{\int_0^1x{\rm d}x \right\}^2$$
$$\displaystyle \left \langle\lim_{x\to \infty}\frac{tanx}{\pi} \right\rangle^2$$

<!--

\\angel ⇒ \langle \rangle
\\set ⇒ \{ \}
\\bracket ⇒ \left( \right)
\\square_bracket ⇒ \left[ \right]
\\curly_bracket ⇒ \left\{ \right}
-->

$$
\begin{aligned}
y &=(x+5)^2-(x+1)^2 \\
&=(x^2+10x+25)-(x^2+2x+1) \\
&=8x+24 \\
\end{aligned}
$$

$
\begin{aligned}
y &=(x+5)^2-(x+1)^2 \\
&=(x^2+10x+25)-(x^2+2x+1) \\
&=8x+24 \\
\end{aligned}
$

<!-- functions -->
$$
\begin{cases}
k_{11}x_1+k_{12}x_2+\cdots+k_{1n}x_n=b_1 \\
k_{21}x_1+k_{22}x_2+\cdots+k_{2n}x_n=b_2 \\
\cdots \\
k_{n1}x_1+k_{n2}x_2+\cdots+k_{nn}x_n=b_n \\
\end{cases}
$$

<!-- \\case -->
$$\begin{cases}
x+1=2 \\
s+2=1 \\
\end{cases}$$

---
$$kinds \quad of \quad special \quad letter \quad name \quad table$$
![](https://pic3.58cdn.com.cn/nowater/webim/big/n_v20f223dde6f2a43a285f9693cccb0af43.png)

---
matrix
<!--
\\p22matrix ⇒ \begin{pmatrix}1&1\\1&1\end{pmatrix}
\\b22matrix ⇒ \begin{bmatrix}1&1\\1&1\end{bmatrix}
\\v22matrix ⇒ \begin{vmatrix}1&1\\1&1\end{vmatrix}
\\c3vector ⇒ \begin{pmatrix}1\\1\\1\end{pmatrix}
\\r3vector ⇒ \begin{pmatrix}1&1&1\end{pmatrix}
-->
$$
\begin{pmatrix}
1 & 1 & \cdots & 1 \\
1 & 1 & \cdots & 1 \\
\vdots & \vdots & \ddots & \vdots \\
1 & 1 & \cdots & 1 \\
\end{pmatrix}
$$

$$
\begin{bmatrix}
1 & 1 & \cdots & 1 \\
1 & 1 & \cdots & 1 \\
\vdots & \vdots & \ddots & \vdots \\
1 & 1 & \cdots & 1 \\
\end{bmatrix}
$$ 

行列式: 

$$
\begin{vmatrix}
1 & 1 & \cdots & 1 \\
1 & 1 & \cdots & 1 \\
\vdots & \vdots & \ddots & \vdots \\
1 & 1 & \cdots & 1 \\
\end{vmatrix}
$$

Latex Sympy Calculator can use rightly , maybe there are sth. wrong with my python

1. can't install the lib 
2. import wrong 
3. target 
4. control +shift +alt +v 

![](https://pic3.58cdn.com.cn/nowater/webim/big/n_v2cf8e5f3caf1f4c84befd791ba3d935b0.png)


{% include mathjax_support %}
{% include command %}

![](2021-11-27-21-17-59.png)

We analyzed the problem sketched in the above figure in [this section](EndForceCantilever.md) and found that the bending moment varies along the length of the beam as

$$
\begin{equation}
M(X_1)=(l-X_1)f
\end{equation}
$$

In this section, we solve the constitutive equation for beams, which is the differential equation 
$$
\begin{equation}
E I y''(x)=M(x),
\end{equation}
$$
and obtain the function $y(\cdot)$. The term $E I$ is sometimes called the bending rigidity.

Integrating the constitutive equation two times we get 

$$
\begin{align}
E I y''(X_1)&=(l-X_1)f,\\
y''(X_1)&=\frac{f}{E I}(l-X_1),\\
y'(X_1)&=\frac{f}{E I}\left(lX_1-\frac{X_1^2}{2}\right)+C_1,\\
y(X_1)&=\frac{f}{E I}\left(l\frac{X_1^2}{2}-\frac{X_1^3}{6}\right)+C_1 X_1+C_0,\\
\end{align}
$$
where $C_1$, $C_0$ are, as of yet, unknown real constants. We next determine the constants $C_1,~ C_0$ by using the fact that $y(0)=0$ and $y'(0)=0$. From the last displayed equation, we get that $y(0)=C_0$. This equation together with the condition that  $y(0)=0$ implies that $C_0=0$. From the second to last displayed equation, we get that $y'(0)=C_1$. This equation together with the condition that $y'(0)=0$ implies that $C_1=0$. Substituting the constants with their values, which we just determined, in the last displayed equation we get that 

$$
\begin{align}
y\left(X_1\right)&=\frac{f}{E I}\left(l\frac{X_1^2}{2}-\frac{X_1^3}{6}\right).\\
\end{align}
$$

Let's find the end deflection of the cantilever.  

$$
\begin{align}
y(l)&=\frac{f}{E I}\left(\frac{l^3}{2}-\frac{l^3}{6}\right)\\
&=\frac{f}{E I}\left(\frac{l^3}{3}\right)\\
\end{align}
$$

The last result is typically written as 

$$
\begin{align}
\delta = \frac{f l^3}{3E I}
\end{align}
$$

{% include mathjax_support %}
{% include command %}


![](2021-09-30-20-40-00.png)


We compute the twist on the right face of the shaft by using the following equation

$$
\begin{align}
\theta(L)
&=
\frac{1}{G}
\int_{0}^{L}\frac{T(X)dX}{J(X)}
\end{align}
$$

$$
\begin{align}
T(X)&=
\left\{
\begin{array}{ll}
2250, & 0\le X<0.8,\\
250, & 0.8\le X<1.2.\\
\end{array}
\right.
\end{align}
$$



$$
\begin{align}
J(X)&=
\left\{
\begin{array}{ll}
\pi r_o^4/2, & 0\le X<0.6\\
\pi (r_o^4-r_i^4)/2, & 0.6\le X<0.8\\
\pi (r_f^4)/2, & 0.8\le X<1.2,\\ 
\end{array}
\right.
\end{align}
$$

$$
\begin{align}
J(X)&=
\left\{
\begin{array}{ll}
9.04377~\times 10^{-7}, & 0\le X<0.6\\
1.27235~\times 10^{-6}, & 0.6\le X<0.8\\
7.95216~\times 10^{-8}, & 0.8\le X<1.2.\\ 
\end{array}
\right.
\end{align}
$$


Evaluating the integral we get
$$
\begin{align}
\theta(L)&=0.0403109\\
&=2.30964^{\circ}
\end{align}
$$

You can find the mathematica file for evaluating the above integral [here](./WFiles/SP4.nb).
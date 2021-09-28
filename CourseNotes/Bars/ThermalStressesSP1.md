{% include mathjax_support %}
{% include command %}

# Solved problem 1

### Problem statement

A rod 2 m long at a temperature of $10^\circ\,\rm C$. Find the expansion of this bar when the temperature is raised to $80^\circ\,\rm C$. Take $E=1.0\times 10^5\rm MPa$ and $\alpha=12 \times 10^{-6}$. 


### Solution

We start with the following 1D thermoelastic constitutive law

$$
\begin{equation}
\sigma_{11}(X)=E(X)(u'(X)-\alpha \Delta T (X)).
\end{equation}
$$


Recall that $\sigma_{11}(X)=F(X)/A(X)$, and in the current problem Young's modulus,  cross-sectional area, co-efficient of thermal expansion, and temperature increments are all constants. 

$$
\begin{equation}
F(X)=EA(u'(X)-\alpha \Delta T).
\end{equation}
$$


Since there are no body forces the force along the bar's length is also a constant. 

$$
\begin{equation}
F=EA(u'(X)-\alpha \Delta T).
\end{equation}
$$


Furthermore, since there is no force acting at the bar's right face this constant force is in fact zero. Thus, it follows from the last equation that

$$
\begin{align}
EA(u'(X)-\alpha \Delta T)&=0\\
u'(X)&=\alpha \Delta T.\\
u(L)-u(0)&=\int_{0}^{X}\alpha \Delta T\, dX\\
&=\alpha \Delta T L\\
\end{align}
$$

The quantity $u(L)-u(0)$ is infact the change in length of the bar. Thus the expansion of the bar is 

$$
\delta =\alpha \Delta T L.
$$

Putting in the numbers we get 


$$
\delta =1.68\rm\, mm.
$$



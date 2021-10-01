{% include mathjax_support %}
{% include command %}

### Problem statement

A hollow cylinder of  outer diamter 600 mm and inner diameter 44 mm is made of steel of G=77 GPa. What is the rotation of the end of the shaft of L=0.6 m length when a torque of T=2250 N.m is applied to its end. 


### Solution. 

We begin by computing $J$, the 
$$
\begin{align}
J
&=\frac{\pi}{2}(r_0^4-r_i^4).\\
&=9.04377~\times 10^{-7}~\rm m^4.
\end{align}
$$

The angle of twist  is

$$
\begin{align}
\theta
&=\frac{T L}{G J}\\
&=0.0193862
\end{align}
$$

In degrees the angle of twist reads $1.11075^{\circ}$.

The MMA notebook for the above calculation is [here](./WFiles/SP2.nb)


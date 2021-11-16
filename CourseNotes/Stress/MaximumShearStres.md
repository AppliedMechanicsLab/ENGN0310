{% include mathjax_support %}
{% include command %}
 # Maximum shear stress and its directions.


As usual we will denote the normal to an internal infinitesimal surface plane ($\delta \Gamma$) as $\hat{\boldsymbol{n}}$.  
 

![](2021-11-14-15-53-30.png)

In component form we can write 
$$
\begin{align}
\hat{\boldsymbol{n}}&=
\begin{bmatrix}
\cos(\phi)\\
\sin(\phi)\\
0
\end{bmatrix}\\
\hat{\boldsymbol{m}}&=
\begin{bmatrix}
-\sin(\phi)\\
\cos(\phi)\\
0
\end{bmatrix}
\end{align}
$$



The quantity $(\boldsymbol{t}\cdot\hat{\boldsymbol{n}})$ in many books is our textbook is referred to as the normal stress. We will denote this quantity as $\sigma$. Thus, the normal traction vector can be expressed as,
$$
\begin{align}
\boldsymbol{t}_n&=
\sigma \hat{\boldsymbol{n}}
\end{align}
$$

Note that  $\sigma$ is distinct from $t_n$, which defined to be the norma of $\boldsymbol{t}_n$. Due to its definition $t_n$ is always positive, while $\sigma$ can be positive or negative.


The shear component of the traction vector, $\boldsymbol{t}_s$ is $\boldsymbol{t}-\boldsymbol{t}_n$, which in component form reads,


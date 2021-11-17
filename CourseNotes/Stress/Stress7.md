{% include mathjax_support %}
{% include command %}


# Mohr circle

In a [previous section](./Stress4.md) we derived that the normal stress $\sigma$ on a plane with the outward normal $\hat{\boldsymbol{n}}$ is



$$
\begin{align}
\sigma(\phi)&=c
+
a\cos(2\phi)+
b\sin (2\phi ),\\
a&:=\frac{\sigma_{11}-\sigma_{22}}{2},\\
b&:=\sigma_{12},\\
c&=\frac{\sigma_{11}+\sigma_{22}}{2}.
\end{align}
$$

The angle $\phi$ is the angle that the vector $\hat{\boldsymbol{n}}$ makes with the $\hat{\boldsymbol{E}}_1$ direction.

Similarly in a [previous section](./Stress5.md) we derived that the shear stress $\tau$ on a plane with the outward normal $\hat{\boldsymbol{n}}$ is

$$
\begin{align}
    \tau(\phi)&=-a \sin(2\phi)+b \cos(2\phi),\\
\end{align}
$$

The curve $\gamma: [0,2\pi)\to \mathbb{T}^2$[^1]
$$
\gamma(\phi)=(\sigma(\phi),\tau(\phi))
$$
is called the Mohr's circle since its graph is a circle of radius $r:=\sqrt{a^2+b^2}$ and centered at $(c,0)$. This fact can be shown using the expressions for $\sigma(\phi)$ and $\tau(\phi)$ that appear in  terms of stress components to get that

$$
\begin{align}
(\sigma(\phi)-c)^2+\tau(\phi)^2&=r^2.
\end{align}
$$

A mathematica code to plot the Mohr's circle is [here](./WFiles/MohrCircle.nb)


[^1]: Think of $\mathbb{T}^2$ as the two-dimensional plane $\mathbb{R}^2$. It is distinct from $\mathbb{R}^2$ in the fact that the points in it have units of $\rm N/m^2$, whereas the  points in $\mathbb{R}^2$ are non-dimensional.


##### Remarks

* As $\phi$ goes from $0$ to $2\pi$ we go around the Mohr's circle twice. 
* Thus, if $\phi$ increases by $\Delta \phi$ the point $(\sigma(\phi),\tau(\phi))$ move on the circle by $2\Delta \phi$.
* As $\phi$ goes from $0$ to $2\pi$ the point $(\sigma(\phi),\tau(\phi))$ moves in the anti-clockwise direction on the circle. 
*  The points where the circle intersects the x-axis corresponds to the directions of the maximum and minimum value of   $\sigma(\cdot)$.
* The highest and lowest points on the circle correspond to the directions of the maximum and minimum value of $\tau(\cdot)$.
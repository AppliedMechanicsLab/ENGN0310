{% include mathjax_support %}
{% include command %}


Polar moment of inertia is given by 

$$
J=\int_{A} \rho^2 \, dA
$$

where $\rho$ is the distance of the infinitesimal area element $dA$ from some arbitrary axis. 

When considering a circular cross-section, this axis is usually taken to be the center of the circle. So, for a circle of radius $R$, the distance $\rho$ is simply the radial distance $r$ ($0 \leq r \leq R$) from the center. Each infinitesimal area element $dA$ is $rd\theta dr$. Hence, 

$$
J=\int_{0}^{r}\int_{0}^{2\pi} r^2 \, rd\theta dr
$$

which evaluates to

$$
J=\frac{\pi}{2}r^4
$$



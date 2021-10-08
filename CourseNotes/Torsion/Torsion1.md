{% include mathjax_support %}
{% include command %}


In the previous sections on bars, we presented the following as the more fundamental version of constitutive equation (Hooke's law):

$$
F(X)=E(X)A(X)u'(X)
$$


In an analogous manner, we can postulate that for torsion,

$$
T(X)=G(X)J(X)\phi'(X)
$$ 

where 
* $T(X)$ is the torque
* $G(X)$ is the shear modulus 
* $J(X)$ is the polar moment of inertia
* $\phi(X)$ is the angle of twist

at material particle $X$ in the shaft. 
>Note: You can refer to [this page](Torsion-J.mD) for some notes on polar moment of inertia J(X) 

<!-- If we take the torque, shear modulus, and polar moment of inertia to be constant throughout the shaft (so that $T(X) = T, G(X) = G$, and $J(X)=J$), we get that  -->

Rearranging the above equation, we can write

$$
\begin{align*}
\phi'(X)& = \frac{T(X)}{G(X) J(X)}\\
\Leftrightarrow \frac{d\phi(X)}{d X}&= \frac{T(X)}{G(X) J(X)}\\
\Leftrightarrow~ d\phi(X)&= \frac{T(X)}{G(X) J(X)} dX
\end{align*}
$$

Integrating the above equation along the shaft's length from $0$ to $X$, we obtain

$$
\begin{align*}
\phi(X)-\phi(0) =& \int_{0}^{X}\frac{T(Y)}{G(Y) J(Y)} dY
% =\frac{TX}{GJ} 
\end{align*}
$$

If we take $\phi(0)=0$, we get that the angle of twist at material particle $X$ in the shaft is
$$
\begin{align*}
\phi(X)=& \int_{0}^{X}\frac{T(Y)}{G(Y) J(Y)} dY
\end{align*}
$$

The equation can be simplified to the following when the torque, shear modulus, and polar moment of inertia is constant throughout the shaft so that $T(X) = T, G(X) = G$, and $J(X)=J$; we then get that 

$$
\begin{align*}
\phi(X)=& \frac{T}{GJ}\int_{0}^{X} dY
\end{align*}
$$

so that in such case, the angle of twist at material particle X is simply 

$$
\begin{align*}
\phi(X)=& \frac{TX}{GJ}
\end{align*}
$$

Taking this integration to $X=L$ instead and denoting the angle of twist at the end face $\phi(L)$ as $\theta$, we obtain 

$$
\theta = \frac{T L}{G J}
$$

Note that we can consider a vector form of this equation like we did with bars in the previous sections. Defining $\hat{\boldsymbol{E}_{\rm a}}$ in the same that we did for bars, we can write

$$
\boldsymbol{T}= \frac{G J}{L}\boldsymbol{\theta}.
$$

where $\boldsymbol{T} = T \hat{\boldsymbol{E}_{\rm a}}$ and $\boldsymbol{\theta}=\theta \hat{\boldsymbol{E}_{\rm a}}$.


<!-- 
---------

Modulus of rigidity.
Shear modulus of Steel is 82.74 GPa.
Young's modulus of Steel 206.843 GPa

Shear modulus of Titanium is 44 GPa.
Young's modulus of Titanius 116 GPa/

Polycarbonate 2.3 GPa.
Rubber 300 kPa. 

Data obtained indicates variation in mechanical properties due to curing
temperature for Young’s modulus of 1.32–2.97 MPa, ultimate tensile strength of
3.51–7.65 MPa, compressive modulus of 117.8–186.9 MPa

PDMS= 0.667656 MPA
G=E/(2(1+\nu))
Bulk modulus 3 K E/(9K-E)

-2G<E-2G

-1<E/2G-1<0.5
-1<E/2G<3/2
-1<E/2G<3/2
2G>-E/2
E<3 G

$$
I_{p}=\int_{A} \rho^2 \, dA
$$

Torsional section modulus. 

$Z_p=J/r_{\rm max}$

$\int r^2 2\pi r dr $

$2\pi \int r^3 dr $

$2\pi  r^4/4  $

$\frac{\pi}{2}  r^4  $

$\tau_{max}=\frac{T}{J}r_{\rm max}$.
$\tau=\tau_{\rm max} \frac{r}{R}$
Square =$a^4/6$
Rectangle due it on the board.


Example problem:

A hollow ste



el shaft transmists a torque if 1200 Nm. d_0 =4 cm. Angle of twist over 2 m. 


A solid aluminum saft. -->
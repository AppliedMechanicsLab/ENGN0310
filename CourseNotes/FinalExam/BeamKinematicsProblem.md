{% include mathjax_support %}
{% include command %}


We studied the problem of bending in class, where we have been using the constitutive equation that 

$$
\begin{equation}
EIy''(X_1)=M(X_1)
\end{equation}
$$

where 
* $M(X_1)$ is the bending moment and is defined as $\boldsymbol{M}(X_1,\hat{\boldsymbol{E}}_1)\cdot \hat{\boldsymbol{E}}_3$,
* $E$ is the Young's modulus, 
* $I$ is the second bending moment of inertia, or the second moment of area. It is defined as
 $$
 I=\int_{\Gamma(X_1)}X_2^2\, d\Gamma.
 $$ Here  $\Gamma(X_1)$ is the cross-sectional surface at $X_1$, which in the current case we will take to not depend on $X_1$, i.e., the beam is of uniform cross-sections along its length.
* $y(X_1)$ is the deflection of the beam's neutral axis at $X_1$.

and $X_1$ is the coordinate of a material particle in the direction of the beam's length. The $X_2$, $X_3$ co-ordinates of the origin $\mathcal{O}$ and of the centroids of the beam's cross-sections are the same. That is, the neutral axis passes through the centroids of the beam's cross-sections. 

In the following we will derive the previous equation from the theory of linear elasticity for the case when the beam is composed of a linear elastic material of Poisson's ration $\nu=0$.

Take the displacement field in the  beam  to be

$$
\begin{align}
\breve{x}_1(X_1,X_2,X_3) &= X_1-X_2 y'(X_1) \\
\breve{x}_2(X_1,X_2,X_3)&=X_2+y(X_1)\\
\breve{x}_3(X_1,X_2,X_3)&=X_3
\end{align}
$$

* **(5pts) (a)** What is the displacement field? That is, what are the functions
    $\breve{u}_1(X_1,X_2,X_3)$, $\breve{u}_2(X_1,X_2,X_3)$, and $\breve{u}_3(X_1,X_2,X_3)$? Recall that 
    
    $$
    \breve{u}_i(X_1,X_2,X_3)=\breve{x}_i(X_1,X_2,X_3)-X_i,
    $$
    
    where $i=1,~2,~3$.

* **(10 pts) (b)** What is the strain field $\breve{\boldsymbol{\epsilon}}(X_1,X_2,X_3)$?
    Determining the strain field is equivalent to determining the components 

    $$
    \breve{\epsilon}_{ij}(X_1,X_2,X_3)
    $$
 
    where $i$, $j=1,~2,~3$. In other words, find the strain field by  determining the nine functions  $\breve{\epsilon}\_{11}(X_1,X_2,X_3)$, $\breve{\epsilon}\_{12}(X_1,X_2,X_3)$,....$\breve{\epsilon}\_{32}(X_1,X_2,X_3)$, $\breve{\epsilon}\_{33}(X_1,X_2,X_3)$. 
    
    Recall the definition of the strain components:

    $$
    \begin{align}
    \breve{\epsilon}_{11}(X_1,X_2,X_3)&=
    \frac{\partial \breve{u}_1(X_1,X_2,X_3)}{\partial X_1}\\
    \breve{\epsilon}_{22}(X_1,X_2,X_3)&=
    \frac{\partial \breve{u}_2(X_1,X_2,X_3)}{\partial X_2}
    \\
    \breve{\epsilon}_{33}(X_1,X_2,X_3)&=
    \frac{\partial \breve{u}_3(X_1,X_2,X_3)}{\partial X_3}\\
    \breve{\epsilon}_{12}(X_1,X_2,X_3)&=
    \frac{1}{2}
    \left(
    \frac{\partial \breve{u}_1(X_1,X_2,X_3)}{\partial X_2}
    +
    \frac{\partial \breve{u}_2(X_1,X_2,X_3)}{\partial X_1}
    \right)
    \\
    \breve{\epsilon}_{21}(X_1,X_2,X_3)&=\breve{\epsilon}_{12}(X_1,X_2,X_3)
    \\
    \breve{\epsilon}_{13}(X_1,X_2,X_3)&=
    \frac{1}{2}
    \left(
    \frac{\partial \breve{u}_1(X_1,X_2,X_3)}{\partial X_3}
    +
    \frac{\partial \breve{u}_3(X_1,X_2,X_3)}{\partial X_1}
    \right)
    \\
    \breve{\epsilon}_{31}(X_1,X_2,X_3)&=\breve{\epsilon}_{13}(X_1,X_2,X_3)
    \\
    \breve{\epsilon}_{23}(X_1,X_2,X_3)&=
    \frac{1}{2}
    \left(
    \frac{\partial \breve{u}_2(X_1,X_2,X_3)}{\partial X_3}
    +
    \frac{\partial \breve{u}_3(X_1,X_2,X_3)}{\partial X_2}
    \right)\\
    \breve{\epsilon}_{32}(X_1,X_2,X_3)&=\breve{\epsilon}_{23}(X_1,X_2,X_3)
    \end{align}
    $$


* **(20 pts) (c)** Let us assume that the beam is composed of a linear elastic solid. What is the stress field $\breve{\boldsymbol{\sigma}}(X_1,X_2,X_3)$? Determining the stress field is equivalent to determining the components 

    $$
    \breve{\sigma}_{ij}(X_1,X_2,X_3)
    $$
  
   where $i$, $j=1,~2,~3$. In other words, compute the stress field by determining the nine functions $\breve{\sigma}\_{11}(X_1,X_2,X_3)$, $\breve{\sigma}\_{12}(X_1,X_2,X_3)$,....$\breve{\sigma}\_{32}(X_1,X_2,X_3)$, $\breve{\sigma}\_{33}(X_1,X_2,X_3)$. 
   
    Recall the definition of a linear elastic solid. The stress and strain components in a linear elastic solid are given by the Hooke's Law, which states that

    $$
    \begin{align}
    \breve{\sigma}_{11}(X_1,X_2,X_3)&=2\mu \breve{\epsilon}_{11}(X_1,X_2,X_3)+\lambda \text{Tr}(\breve{\boldsymbol{\epsilon}}(X_1,X_2,X_3))\\
    \breve{\sigma}_{22}(X_1,X_2,X_3)&=2\mu \breve{\epsilon}_{22}(X_1,X_2,X_3)+\lambda \text{Tr}(\breve{\boldsymbol{\epsilon}}(X_1,X_2,X_3))\\
    \breve{\sigma}_{33}(X_1,X_2,X_3)&=2\mu \breve{\epsilon}_{33}(X_1,X_2,X_3)+\lambda \text{Tr}(\breve{\boldsymbol{\epsilon}}(X_1,X_2,X_3))\\
    \breve{\sigma}_{23}(X_1,X_2,X_3)&=2\mu \breve{\epsilon}_{23}(X_1,X_2,X_3)\\
    \breve{\sigma}_{13}(X_1,X_2,X_3)&=2\mu \breve{\epsilon}_{13}(X_1,X_2,X_3)\\
    \breve{\sigma}_{12}(X_1,X_2,X_3)&=2\mu \breve{\epsilon}_{12}(X_1,X_2,X_3)\\
    \breve{\sigma}_{32}(X_1,X_2,X_3)&=\breve{\sigma}_{23}(X_1,X_2,X_3)\\
    \breve{\sigma}_{31}(X_1,X_2,X_3)&=\breve{\sigma}_{13}(X_1,X_2,X_3)\\
    \breve{\sigma}_{21}(X_1,X_2,X_3)&=\breve{\sigma}_{12}(X_1,X_2,X_3)
    \end{align}
    $$

    where 

    $$
    \text{Tr}(\breve{\boldsymbol{\epsilon}}(X_1,X_2,X_3))=
    \breve{\epsilon}_{11}(X_1,X_2,X_3)+
    \breve{\epsilon}_{22}(X_1,X_2,X_3)+\breve{\epsilon}_{33}(X_1,X_2,X_3)
    $$ 

    and $\mu$ is the same as $G$, the shear modulus. We will use the simplification that $\nu=0$ later. 

* **(10 pts) (d)** As we have been doing let us take the  beam to be aligned in the $\hat{\boldsymbol{E}}_1$ direction. Consider an imaginary cut at some $X_1$.  What is the traction vector on the surfacxe $\Gamma(X_1,\hat{\boldsymbol{E}}_1)$? That is, determine 
$\breve{\boldsymbol{\sigma}}(X_1,X_2,X_3)^{T}\hat{\boldsymbol{E}}_1$. As can be seen by the presence of $X_1$, $X_2$, and $X_3$, the traction vector will not be constant on the cross-section. It will vary from point to point on the cross-section. Find the left hand side in the below equation by determining the right hand side in the below equation 

    $$
    \begin{equation}
    \left[\breve{\boldsymbol{t}}(X_1,X_2,X_3;\hat{\boldsymbol{E}}_1)\right]
    =\left[\breve{\boldsymbol{\sigma}}(X_1,X_2,X_3)\right]^{\sf T}\left[\hat{\boldsymbol{E}}_1\right]
    \end{equation}
    $$  

* **(15 pts) (e)** Compute the moment  about the centeroid of $\Gamma(X_1)$ of all the forces acting on $\Gamma(X_1, \hat{\boldsymbol{E}}_1)$. That is compute,

    $$
    \boldsymbol{M}(X_1,\hat{\boldsymbol{E}}_1)=\int_{\Gamma(X_1)}\boldsymbol{X}\times \breve{\boldsymbol{t}}(X_1,X_2,X_3;\hat{\boldsymbol{E}}_1)\, d\Gamma 
    $$

    Use the definition of the $I$, which is

    $$
    I =\int_{\Gamma(X_1)} X_2^2\, d\Gamma,
    $$

    to simplify your answer.

    For computing the integral take $\boldsymbol{X}\times \breve{\boldsymbol{t}}(X_1,X_2,X_3;\hat{\boldsymbol{E}}_1)$ as the cross product between $\left[\boldsymbol{X}\right]$, which is

    $$
    \begin{bmatrix}
    \boldsymbol{X}
    \end{bmatrix}=
    \begin{bmatrix} 
    X_1\\
    X_2\\
    X_3
    \end{bmatrix},
    $$

    and $\left[\breve{\boldsymbol{t}}(X_1,X_2,X_3;\hat{\boldsymbol{E}}_1)
\right]$.

You can further simplify your answer by writing 

$$
\begin{align}
\lambda&=\frac{E\nu}{(1+\nu)(1-2\nu)}\\
\mu&=\frac{E}{2(1+\nu)}\\
\end{align}
$$
and setting $\nu=0$.
X{% include mathjax_support %}
{% include command %}



# ENGN0310: Practice Final Solutions




> Contact Andrew_Bagnoli@brown.edu if you have questions about the problems below.   




#### Problem 1. 

![](PF9.PNG)

Figure 1

The bar in the figure above is made of a material with an ultimate tensile strength of $220MPa$ and an ultimate shear strength of $100MPa$, where the cross-sectional area is $A = 100mm^2$. If the ultimate strength of the weld is $.8$ of that of the base material, for both shear and normal stress, then what is the maximum allowable applied force $P$ and how will the bar fail? The angle of the weld is $\theta = 65^{o}$.

**Solution:**

There are four possible equations for the maximum force, shear failure in the bar $P_{shear,b} = 2A\tau_{max} = 20kN$, axial failure in the bar $P_{axial,b} = A \sigma_{max} = 22kN$, shear failure in the weld $P_{shear,w} = \frac{.8A\tau_{max}}{sin(\theta)cos(\theta)} = 20.89kN $, and axial failure in the weld, $P_{axial,w} = \frac{.8A\sigma_{max}}{sin(\theta)^2} = 21.43kN$. So the maximum value of $P$ is $20kN$ and failure will occur in shear in the bar.

#### Problem 2. 

![](PF1.PNG)

Figure 2

(a) Given the loading in figure 2 what is the stress tensor. 

**Solution:**

$$\boldsymbol{\sigma} = \begin{pmatrix} -50MPa & -62.5MPa\\ -62.5MPa & -75MPa\end{pmatrix}$$

(b) For this given stress tensor what is the maximum and minimum values of the scalar part of normal component of the traction vector, and what are the corresponding angles. 

**Solution:**

The scalar part of the normal component of the traction vector is $\sigma(\theta) = \sigma_{11}cos(\theta)^2 + \sigma_{22}sin(\theta)^2 + \sigma_{12}sin(2\theta)$. The maximum is $\sigma(\theta = 2.455rads) = 1.238MPa$ and the minimum is $\sigma(\theta = 0.884rads) = -126.24MPa$.

(c) For this given stress tensor what is the maximum and minimum values of the scalar part of shear component of the traction vector, and what are the corresponding angles. 

**Solution:**

The scalar part of the normal component of the traction vector is $\tau(\theta) = -\frac{\sigma_{11} - \sigma_{22}}{2}sin(2\theta) + \sigma_{12}cos(2\theta)$. The maximum is $\tau(\theta = 1.669rads) = 63.738MPa$ and the minimum is $\tau(\theta = 0.098rads) = -63.738MPa$.

(d)  For this given stress tensor draw the Mohr Circle.

**Solution:**

The radius of the Mohr's Circle is $R = \sqrt{\left(\frac{\sigma_{11} - \sigma_{22}}{2}\right)^2 + \sigma_{12}^2} = 3=63.738MPa$ and the center is $(C,0) = \left(\frac{\sigma_{11} + \sigma_{22}}{2} , 0\right) = \left(-62.5MPa , 0\right)$.

#### Problem 3.

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
 \begin{equation}
 I=\int_{\Gamma(X_1)}X_2^2\, d\Gamma.
 \end{equation}
 $$ 
 Here  $\Gamma(X_1)$ is the cross-sectional surface at $X_1$, which in the current case we will take to not depend on $X_1$, i.e., the beam is of uniform cross-sections along its length.
* $y(X_1)$ is the deflection of the beam's neutral axis at $X_1$.

and $X_1$ is the coordinate of a material particle in the direction of the beam's length. The $X_2$, $X_3$ co-ordinates of the origin $\mathcal{O}$ and of the centroids of the beam's cross-sections are the same. That is, the neutral axis passes through the centroids of the beam's cross-sections. 

In the following we will derive the previous equation from the theory of linear elasticity for the case when the beam is composed of a linear elastic material of Poisson's ration $\nu=0$.

Take the displacement field in the beam  to be

$$
\begin{align}
\breve{x}_1(X_1,X_2,X_3) &= X_1-X_2 y'(X_1) \\
\breve{x}_2(X_1,X_2,X_3)&=X_2+y(X_1)\\
\breve{x}_3(X_1,X_2,X_3)&=X_3
\end{align}
$$

*  **(a)** What is the displacement field? That is, what are the functions

    $\breve{u}_1(X_1,X_2,X_3)$, $\breve{u}_2(X_1,X_2,X_3)$, and $\breve{u}_3(X_1,X_2,X_3)$? Recall that 
    
    $$
    \begin{align}
    \breve{u}_i(X_1,X_2,X_3)=\breve{x}_i(X_1,X_2,X_3)-X_i
    \end{align}
    $$
    
    where $i=1,~2,~3$.

*  **(b)** What is the strain field $\breve{\boldsymbol{\epsilon}}(X_1,X_2,X_3)$?
    Determining the strain field is equivalent to determining the components 

    $$
    \begin{align}
    \breve{\epsilon}_{ij}(X_1,X_2,X_3)
    \end{align}
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


* **(c)** Let us assume that the beam is composed of a linear elastic solid. What is the stress field $\breve{\boldsymbol{\sigma}}(X_1,X_2,X_3)$? Determining the stress field is equivalent to determining the components 

    $$
    \begin{align}
    \breve{\sigma}_{ij}(X_1,X_2,X_3)
    \end{align}
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
    \begin{align}
    \text{Tr}(\breve{\boldsymbol{\epsilon}}(X_1,X_2,X_3))=
    \breve{\epsilon}_{11}(X_1,X_2,X_3)+
    \breve{\epsilon}_{22}(X_1,X_2,X_3)+\breve{\epsilon}_{33}(X_1,X_2,X_3)
    \end{align}
    $$ 

    and $\mu$ is the same as $G$, the shear modulus. We will use the simplification that $\nu=0$ later. 

* **(d)** As we have been doing let us take the  beam to be aligned in the $\hat{\boldsymbol{E}}_1$ direction. Consider an imaginary cut at some $X_1$.  What is the traction vector on the surfacxe $\Gamma(X_1,\hat{\boldsymbol{E}}_1)$? That is, determine 
$\breve{\boldsymbol{\sigma}}(X_1,X_2,X_3)^{T}\hat{\boldsymbol{E}}_1$. As can be seen by the presence of $X_1$, $X_2$, and $X_3$, the traction vector will not be constant on the cross-section. It will vary from point to point on the cross-section. Find the left hand side in the below equation by determining the right hand side in the below equation 

    $$
    \begin{equation}
    \left[\breve{\boldsymbol{t}}(X_1,X_2,X_3;\hat{\boldsymbol{E}}_1)\right]
    =\left[\breve{\boldsymbol{\sigma}}(X_1,X_2,X_3)\right]^{\sf T}\left[\hat{\boldsymbol{E}}_1\right]
    \end{equation}
    $$  

* **(e)** Compute the moment  about the centeroid of $\Gamma(X_1)$ of all the forces acting on $\Gamma(X_1, \hat{\boldsymbol{E}}_1)$. That is compute,

    $$
    \begin{align}
    \boldsymbol{M}(X_1,\hat{\boldsymbol{E}}_1)=\int_{\Gamma(X_1)}\boldsymbol{X}\times \breve{\boldsymbol{t}}(X_1,X_2,X_3;\hat{\boldsymbol{E}}_1)\, d\Gamma 
    \end{align}
    $$

    Use the definition of the $I$, which is

    $$
    \begin{align}
    I =\int_{\Gamma(X_1)} X_2^2\, d\Gamma,
    \end{align}
    $$

    to simplify your answer.

    For computing the integral take $\boldsymbol{X}\times \breve{\boldsymbol{t}}(X_1,X_2,X_3;\hat{\boldsymbol{E}}_1)$ as the cross product between $\left[\boldsymbol{X}\right]$, which is

    $$
    \begin{align}
    \begin{bmatrix}
    \boldsymbol{X}
    \end{bmatrix}=
    \begin{bmatrix} 
    X_1\\
    X_2\\
    X_3
    \end{bmatrix}
    \end{align}
    $$

    and 
    
    $$
    \begin{align}
    \left[\breve{\boldsymbol{t}}(X_1,X_2,X_3;\hat{\boldsymbol{E}}_1)\right]
    \end{align}
    $$

You can further simplify your answer by writing 

$$
\begin{align}
\lambda&=\frac{E\nu}{(1+\nu)(1-2\nu)}\\
\mu&=\frac{E}{2(1+\nu)}\\
\end{align}
$$
and setting $\nu=0$.

**Solution:**

* **(a)** $$\breve{u}_i(X_1,X_2,X_3) = (-X_2y'(X_1),y(X_1),0)$$

* **(b)** $$\breve{\epsilon}_{ij}(X_1,X_2,X_3) = \begin{pmatrix} -X_2y''(X_1) & 0 & 0\\ 0 & 0 & 0 \\ 0 & 0 & 0\end{pmatrix}$$

* **(c)** $$\breve{\sigma}_{ij}(X_1,X_2,X_3) = \begin{pmatrix} -X_2(2\mu + \lambda)y''(X_1) & 0 & 0\\ 0 & -X_2\lambda y''(X_1) & 0 \\ 0 & 0 & -X_2\lambda y''(X_1)\end{pmatrix}$$

* **(d)** $$\left[\breve{\boldsymbol{t}}(X_1,X_2,X_3;\hat{\boldsymbol{E}}_1)\right] = \begin{pmatrix} -X_2(2\mu + \lambda)y''(X_1) \\ 0 \\ 0 \end{pmatrix}$$

* **(e)** $$\boldsymbol{M}(X_1,\hat{\boldsymbol{E}}_1) = \begin{pmatrix} 0 \\ -(2\mu + \lambda)y''(X_1)\int_{\Gamma(X_1)} X_2X_3\, d\Gamma \\ (2\mu + \lambda)y''(X_1)\int_{\Gamma(X_1)} X_2^2 d\Gamma \end{pmatrix} \Rightarrow \boldsymbol{M}(X_1,\hat{\boldsymbol{E}}_1) \cdot \hat{\boldsymbol{E}}_3 = M(X_3) = EIy''(X_1)$$


#### Problem 4. 

![](PF2.PNG)

Figure 3

(a) For the problem in figure 3 prepare the shear and bending moment diagrams.

**Solution:**

![](PFS1.PNG)

$V(X_1) = 5600 - 952.4X_1^2$

![](PFS2.PNG)

$M(X_1) = -5600X_1 - 317.5X_1^3$

![](PF3.PNG)

Figure 4

(b) For the problem in figure 4 prepare the shear and bending moment diagrams.

**Solution:**

![](PFS3.PNG)

$$V(X_1)=
\begin{cases}
450 & ~ X_1 \leq 3m\\
450 - 300 (-3 + X_1)  & ~3m\leq X_1 \leq 6m\\
1800 - 300 (-3 + X_1)  & ~6m\leq X_1
\end{cases}$$

![](PFS4.PNG)

$$M(X_1)=
\begin{cases}
-450X_1 & ~ X_1 \leq 3m\\
150 (63 - 18 X_1 + X_1^2)  & ~3m\leq X_1 \leq 6m\\
150 (9 - 9 X_1 + X_1^2)  & ~6m\leq X_1
\end{cases}$$

#### Problem 5. 

![](PF4.PNG)

Figure 5

a) If the beam in figure 5 is made of a material with an ultimate normal strength $250MPa$ and has a rectangular cross section with a width of $30mm$ and height $20mm$, then what is the maximum allowable value of $P$?

**Solution:**

$P_{max} = \max{\frac{-\sigma_{max}I}{(6 - X_1)X_2}} = 55.6N$ at $(X_1,X_2) = (0,-\frac{h}{2})$

![](PF5.PNG)

Figure 6

b) If the beam in figure 5 is made of a material with an ultimate normal strength $250MPa$ and has a cross section given in figure 6, where $H = 50mm$, $h = 40mm$, $a = 10mm$, and $b = 50mm$, then what is the maximum allowable value of $P$? Note: For an I beam like figure 6 $I = \frac{ah^3}{12} + \frac{b\left(H^3 - h^3\right)}{12}$. and the centroid is at the origin. 

**Solution:**

$P_{max} = \max{\frac{-\sigma_{max}I}{(6 - X_1)X_2}} = 512.5N$ at $(X_1,X_2) = (0,-\frac{H}{2})$.

#### Problem 6. 

![](PF6.PNG)

Figure 7

a) Find the maximum displacement of the bar in figure 7. 

**Solution:**

$y(X_1) = \frac{wX_1^2}{24RI}(6L^2 - 4LX_1 +X_1^2)$ and $y_{max} = \frac{wL^4}{8EI}$.

![](PF7.PNG)

Figure 8

b) Find the maximum displacement of the bar in figure 8.

**Solution:**

$$y(X_1) = \begin{cases}
-\frac{L^2 P X_1}{12}  & ~ X_1 \leq L\\
-\frac{P}{12}  (2 L - X_1) (L^2 - 2 L X_1 + 2 X_1^2)  & ~L\leq X_1 \leq 2L\\
\frac{P}{12}  (2 L - X_1) (15 L^2 - 14 L X_1 + 2 X_1^2)  & ~2L\leq X_1
\end{cases}$$

and $y_{max} = \frac{3 L^3 P}{4}$.

![](PF8.PNG)

Figure 9

c) Find the maximum displacement of the bar in figure 9. Note that $M_1$, $M_2$, and $R_1$ are reaction forces and $M$ is an applied moment. 

**Solution:**

$R_1 = \frac{6 a b M}{(a + b)^3}$, $M_1 = \frac{(2 a - b) b M}{(a + b)^2}$ , and $ M_2 = \frac{a (2 b - a) M}{(a + b)^2}$ using the directions in figure 9 but keeping the standard sign convention for this class where $\hat{\boldsymbol{E}}_3$ is into the page. Then 

$$y(X_1) = \begin{cases}
-\frac{b M X_1^2 (-2 a^2 - a b + b^2 + 2 a X_1)}{2 (a + b)^3}  & ~ X_1 \leq a\\
\frac{a M (a + b - X_1)^2 \left(a (a + b) - 2 b X_1\right)}{2 (a + b)^3}  & ~a\leq X_1
\end{cases}$$

Then $y_{max} = \frac{(2 a - b)^3 b M}{54 a^2}$ when $(2 - \sqrt{3})a\leq b \leq (2 + \sqrt{3})a$ and otherwise $y_{max} = \frac{a (a - 2 b)^3 M}{54 a^2}$.



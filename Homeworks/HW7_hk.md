{% include mathjax_support %}
{% include command %}



# ENGN0310: Homework 7
## Due Wednesday 11:59 pm, November 17th, 2021


> Please upload your assignment to Canvas.<br/>
> Contact Sayaka_Kochiyama@brown.edu if you have questions about the problems.   



#### Some helpful concepts needed for solving the HW problems


--------
* Maximum and minimum normal stress 

$$
\begin{equation}
\sigma_{\rm max,min}=\frac{\sigma_{11}+\sigma_{22}}{2} \pm \sqrt{\left(\frac{\sigma_{11}-\sigma_{22}}{2}\right)^2+\tau_{12}^2}
\end{equation}
$$

* The planes of maximum and minimum normal stress

$$
\begin{equation}
\tan 2\theta_p=\frac{2\tau_{12}}{\sigma_{11}-\sigma_{22}}
\end{equation}
$$

 <br/>
    <center>
     <img src="HW6_S1.png" alt="drawing" width="300"/>
    </center>
<br/>

> Hint: At the plane of $\theta_p$, the shearing stress equals to zero.

* Maximum and minimum shearing stress 

$$
\begin{equation}
\tau_{\rm max}=\sqrt{\left(\frac{\sigma_{11}-\sigma_{22}}{2}\right)^2+\tau_{12}^2}
\end{equation}
$$

$$
\begin{equation}
\tau_{\rm min}=0
\end{equation}
$$

* The planes of maximum shearing stress

$$
\begin{equation}
\tan 2\theta_s=-\frac{\sigma_{11}-\sigma_{22}}{2\tau_{12}}
\end{equation}
$$

 <br/>
    <center>
     <img src="HW6_S2.png" alt="drawing" width="300"/>
    </center>
<br/>



----------


<u> Problem 1 (20 pts) </u> (Moved from HW6, Problem 6)
* For the given state of stress, determine (a) (10 pts) the maximum and minimum in-plane shearing stress, (b) (10 pts) the orientation of the planes of the maximum and minimum in-plane shearing stress.

 <br/>
    <center>
     <img src="HW6_P6.png" alt="drawing" width="300"/>
    </center>

<u> Problem 2 (60 pts) </u> 

We studied the problem of torsion earlier in the semester. In solving torsion problems we used the equation

$$
\begin{equation}
T(X)=G(X)J(X)\phi'(X)
\label{eq:TorsionCE}
\end{equation}
$$
where 

where 
* $T(X)$ is the torque
* $G(X)$ is the shear modulus 
* $J(X)$ is the polar moment of inertia
* $\phi(X)$ is the angle of twist

at material particle $X$ in the shaft. 

In the following we will derive $\eqref{eq:TorsionCE}$. 

Take the displacement field in a circular shaft of radius $a$ and length $L$ to be

$$
\begin{align}
\u{x}_1(X_1,X_2,X_3)&= X_1-X_2\phi(X_3) \\
\u{x}_2(X_1,X_2,X_3)&=X_2+X_1\phi(X_3)\\
\u{x}_3(X_1,X_2,X_3)&=X_3
\end{align}
$$

* (5pts) What is the displacement field. That what are the functions $\u{u}_1(X_1,X_2,X_3)$, $\u{u}_2(X_1,X_2,X_3)$, and $\u{x}_3(X_1,X_2,X_3)$. Recall that $\u{x}_i(X_1,X_2,X_3)=\u{x}_i(X_1,X_2,X_3)-X_i$, where $i=1,~2,~3$.

* (10 pts) What is the strain field $\u{\boldsymbol{\epsilon}}(X_1,X_2,X_3)$? Determining the strain field is equivalent to determining the components   $\u{\epsilon}_{ij}(X_1,X_2,X_3)$, where $i$, $j=1,~2,~3$. That is, determine the nine functions  $\u{\epsilon}_{11}(X_1,X_2,X_3)$, $\u{\epsilon}_{12}(X_1,X_2,X_3)$,....$\u{\epsilon}_{32}(X_1,X_2,X_3)$, $\u{\epsilon}_{33}(X_1,X_2,X_3)$. Recall the definition of the strain components. 

$$
\begin{align}
\u{\epsilon}_{11}(X_1,X_2,X_3)&=
\frac{\partial \u{u}_1(X_1,X_2,X_3)}{\partial X_1}\\
\u{\epsilon}_{22}(X_1,X_2,X_3)&=
\frac{\partial \u{u}_2(X_1,X_2,X_3)}{\partial X_2}
\\
\u{\epsilon}_{33}(X_1,X_2,X_3)&=
\frac{\partial \u{u}_3(X_1,X_2,X_3)}{\partial X_3}\\
\u{\epsilon}_{12}(X_1,X_2,X_3)&=
\frac{1}{2}
\left(
\frac{\partial \u{u}_1(X_1,X_2,X_3)}{\partial X_2}
+
\frac{\partial \u{u}_2(X_1,X_2,X_3)}{\partial X_1}
\right)
\\
\u{\epsilon}_{21}(X_1,X_2,X_3)&=\u{\epsilon}_{12}(X_1,X_2,X_3)
\\
\u{\epsilon}_{13}(X_1,X_2,X_3)&=
\frac{1}{2}
\left(
\frac{\partial \u{u}_1(X_1,X_2,X_3)}{\partial X_3}
+
\frac{\partial \u{u}_3(X_1,X_2,X_3)}{\partial X_1}
\right)
\\
\u{\epsilon}_{31}(X_1,X_2,X_3)&=\u{\epsilon}_{13}(X_1,X_2,X_3)
\\
\u{\epsilon}_{23}(X_1,X_2,X_3)&=
\frac{1}{2}
\left(
\frac{\partial \u{u}_2(X_1,X_2,X_3)}{\partial X_3}
+
\frac{\partial \u{u}_3(X_1,X_2,X_3)}{\partial X_2}
\right)\\
\u{\epsilon}_{32}(X_1,X_2,X_3)&=\u{\epsilon}_{23}(X_1,X_2,X_3)
\end{align}
$$


* (20 pts) Let us assume that the shaft is composed of a linear elastic solid. What is the stress field $\boldsymbol{\sigma}(X_1,X_2,X_3)$? Determining the stress field is equivalent to determining the components   $\u{\sigma}_{ij}(X_1,X_2,X_3)$, where $i$, $j=1,~2,~3$. That is, determine the nine functions  $\u{\sigma}_{11}(X_1,X_2,X_3)$, $\u{\sigma}_{12}(X_1,X_2,X_3)$,....$\u{\sigma}_{32}(X_1,X_2,X_3)$, $\u{\sigma}_{33}(X_1,X_2,X_3)$. Recall the definition of a linear elastic solid. The stress and strain components in a linear elastic solid are give by the Hooke's Law, which states that

$$
\begin{align}
\u{\sigma}_{11}(X_1,X_2,X_3)&=2\mu \u{\epsilon}_{11}(X_1,X_2,X_3)+\lambda \text{Tr}(\u{\boldsymbol{\epsilon}}(X_1,X_2,X_3))\\
\u{\sigma}_{22}(X_1,X_2,X_3)&=2\mu \u{\epsilon}_{22}(X_1,X_2,X_3)+\lambda \text{Tr}(\u{\boldsymbol{\epsilon}}(X_1,X_2,X_3))\\
\u{\sigma}_{33}(X_1,X_2,X_3)&=2\mu \u{\epsilon}_{33}(X_1,X_2,X_3)+\lambda \text{Tr}(\u{\boldsymbol{\epsilon}}(X_1,X_2,X_3))\\
\u{\sigma}_{23}(X_1,X_2,X_3)&=2\mu \u{\epsilon}_{23}(X_1,X_2,X_3)\\
\u{\sigma}_{13}(X_1,X_2,X_3)&=2\mu \u{\epsilon}_{13}(X_1,X_2,X_3)\\
\u{\sigma}_{12}(X_1,X_2,X_3)&=2\mu \u{\epsilon}_{12}(X_1,X_2,X_3)\\
\u{\sigma}_{32}(X_1,X_2,X_3)&=\u{\sigma}_{23}(X_1,X_2,X_3)\\
\u{\sigma}_{31}(X_1,X_2,X_3)&=\u{\sigma}_{13}(X_1,X_2,X_3)\\
\u{\sigma}_{21}(X_1,X_2,X_3)&=\u{\sigma}_{12}(X_1,X_2,X_3)
\end{align}
$$
where 
$$
\text{Tr}(\u{\boldsymbol{\epsilon}}(X_1,X_2,X_3))=
\u{\epsilon}_{11}(X_1,X_2,X_3)+
\u{\epsilon}_{22}(X_1,X_2,X_3)+\u{\epsilon}_{33}(X_1,X_2,X_3)
$$, and $\mu$ is the same as $G$, the shear modulus. In the current case we are going to take that the shear modulus is constant throughout the shaft.

* (10 pts) Let's take shaft to be aligned in the $\hat{\boldsymbol{E}}_3$ direction. Consider an imaginary cut at some $X_3$. The cross-sectional surface on the left part will have  $\hat{\boldsymbol{E}}_3$ as its outward normal. What is the traction vector on the shaft's right face. That is determine 
$\boldsymbol{\sigma}(X_1,X_2,X_3)^{T}\hat{\boldsymbol{E}}_3$. As can be seen by the presenc e of $X_1$, $X_2$, and $X_3$ the traction vector will not be constant on the cross-section. It will vary from point to point on the cross-section. Find the left hand side in the below equation by determining the righ hand side in the below equation 

$$
\begin{equation}
\left[\boldsymbol{t}(X_1,X_2,X_3;\hat{\boldsymbol{E}}_3)\right]
=\left[\boldsymbol{\sigma}(X_1,X_2,X_3)\right]^{\sf T}\left[\hat{\boldsymbol{E}}_3\right]
\end{equation}
$$  

* (20 pts) Compute the torque on the cross-sectional surface discussed in the previous part as

$$
\boldsymbol{T}(X_3)=\int_{\Gamma}\boldsymbol{X}\times \boldsymbol{t}(X_1,X_2,X_3;\hat{\boldsymbol{E}}_3)\, d\Gamma 
$$
where 
$$
\Gamma =\{(X_1,X_2)~|~X_1^2+X_2^2<a^2\}
$$

For computing the integral take $\boldsymbol{X}\times \boldsymbol{t}(X_1,X_2,X_3;\hat{\boldsymbol{E}}_3)$ as the cross product between $\left[\boldsymbol{X}\right]$, which is
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
and $\left[\boldsymbol{t}(X_1,X_2,X_3;\hat{\boldsymbol{E}}_3)
\right]$.

<u> Problem 3 (20pts)  Mohr circle. </u>

Draw the Mohr circles for 

* (10 pts) the stress state given in Pb. 1 
* (10 pts) and HW 6, pb. 2, which is 


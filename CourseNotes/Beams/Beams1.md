{% include mathjax_support %}
{% include command %}

# Deflected shape of a beam




Beams are a type of straight, high aspect ratio structures, like shafts. They can have complicated shapes. However, to get things started, let us take them to be straight cylinders. 

Without loss of generality, let us take the beams in their undeformed configuration to lie in the $\hat{\boldsymbol{E}}_1$ direction, i.e., the axes of the cylinders to be parallel to the $\hat{\boldsymbol{E}}_1$ direction. 


As we have been doing repeatedly, let $\boldsymbol{X}$ be a materials particle. We can express  $\boldsymbol{X}$ as $X_1\hat{\boldsymbol{E}}_1+X_2\hat{\boldsymbol{E}}_2+X_3\hat{\boldsymbol{E}}_3$. After deformation, the particle $\boldsymbol{X}$ has the position vector $\boldsymbol{x}=x_1\hat{\boldsymbol{E}}_1+x_2\hat{\boldsymbol{E}}_2+x_3\hat{\boldsymbol{E}}_3$. The displcement of $\boldsymbol{X}$ is $\boldsymbol{u}=u_1\hat{\boldsymbol{E}}_1+u_2\hat{\boldsymbol{E}}_2+u_3\hat{\boldsymbol{E}}_3$. We define the displacement to be the set of three functions $\breve{u}_1(\cdot,\cdot,\cdot)$, $\breve{u}_2(\cdot,\cdot,\cdot)$, and $\breve{u}_3(\cdot,\cdot,\cdot)$  that are defined such that 

$$
\begin{align}
x_1&=\breve{u}_1(X_1,X_2,X_3)+X_1\\
x_2&=\breve{u}_2(X_1,X_2,X_3)+X_2\\
x_3&=\breve{u}_3(X_1,X_2,X_3)+X_3
\end{align}
$$


Let's take  $\boldsymbol{Y}$ be those material particles that exist specifically on beam's central axis[^2]. Taking the  origin to be the center of the cylinder's left face, we get that $\boldsymbol{Y}$ can be expressed as $Y_1\hat{\boldsymbol{E}}_1$. After deformation, $\boldsymbol{Y}$ has the position vector $\boldsymbol{y}$.
<!-- 
The position vector of $\boldsymbol{Y}$ after deformation be $\boldsymbol{y}$. -->

In elementary beam theory, the deformation is assumed to be such that post deformation, the cylinder's central axis lies in a plane. For right cylinders, the central axis is also the "neutral axis"[^2].  Without loss of generality, let us  take that plane to be the $(\hat{\boldsymbol{E}}_1,\hat{\boldsymbol{E}}_2) plane$. Consequently, we can express $\boldsymbol{y}$ as $y_1\hat{\boldsymbol{E}}_1+y_2\hat{\boldsymbol{E}}_2$. In  elementary   beam theory, $y_1$ is assumed to be equal to $Y_1$[^1]. The deflection of a beam is the function $\breve{y}_2(\cdot)$ that is defined such that.  

$$
y_2=\breve{y}_2(X_1)
$$

When it is clear from context, we will refer to the function $\breve{y}_2(\cdot)$ simply as $y(\cdot)$.

[^1]: This assumption is almost never valid and gives rise to several contradictions, such as the presence of axial forces along the beam's length. Thus, making a beam not really a beam but a beam and a bar.)

[^2]: We will define the neutral axis later. For now it suffices to comments that the "neutral axis" is actually a plane, such that material above it experiences compression in the axial direction and below it the materials experiences tension in the axial direction. As we stated before,we will give a more precise definition of the neutral axis later.

Like shafts, beams  transmit force moments along their length. However, unlike shafts, the moments they transmit are not in the direction of their long axis, but are perpendicular to their long axis. In conjunction with our assumption that the beam's deformation is constrained to plane, this implies that the moment on the cross-section at $X_1$ with the outward normal in the $\hat{\boldsymbol{E}}_1$ direction is $M(X)\boldsymbol{E}_3$. 

The constitutive law of elementary beams is that

$$
\begin{align}
E I y''(X_1)=M(X_1)
\end{align}
$$  


The deformed shape  of the beam is described by providing the deflection of the beam's "neutral axis."  If there exists a plane  such that each of the beam's cross-sections are symmetric about it, then that plane is taken to be the beam's neutral axis. (It is not always possible to find such symmetry plane. However, the neutral axis exists even when such a symmetry plane does not exist. Therefore, this is only a special definition of the neutral axis. We will give its general definition later.)  

<!-- And the neutral axis to be the  plane.  -->


<!-- 
Let $\boldsymbol{X}$ be the position vector of a material particle on "neutral axis" of the beam.  The neutral axis is an axis running along the length of the beam. -->
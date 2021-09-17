# Vector form of the Hooke's law for the bar

In the [introductory section on bars](Bars.md) we introduced the Hooke's law for the bar to be

$$
\begin{align}
\frac{F L}{A \delta}=E
\end{align}
$$

The above equation is a scalar equation. We would like write it in a vector form. 

In the following we focus our attention when the bar just streches along its own axis (with no rotation.) That is, we focus on the case in which  the bar remains aligned with $\hat{\boldsymbol{E}}\_{\rm a}$ before and after deformation.

Let the position vector of the $\Gamma^{\mathscr{h}}$'s centroid before any forces are applied to the bar be $\boldsymbol{X}(\mathcal{C})$ (red arrow in the top panel of the below figure). The difference between the position vectors of the centroids of the right and left faces is called the length vector. When the position vector considered are reference position vector then the length vector is called initial, or reference, length vector. When the position vector considered are current position vectors then the length vector is called deformed, or current, length vector.  Say we choose the origin of the physical space $\mathcal{E}^3$ to be located at the centroid of the bar's left face. Then the reference position vector of the bar's left face is is simply the null vector $\boldsymbol{0}$. In this case $\mathcal{X}(\mathcal{C})$ is also the initial length, or reference length,  vector. If the initial, undeformed length of the bar is L, then $\boldsymbol{X}(\mathcal{C})=L\hat{\boldsymbol{E}}\_{\rm a}$. Say after  the application of force the position vector of the centeroid of the bar's right face is is $\boldsymbol{x}(\mathcal{C})$.  The centeroid of its left face remain at the origin, thus its current position is $\boldsymbol{0}$ as well.  The deformed length is therefore  $\boldsymbol{x}(\mathcal{C})$. If the current, or deformed length is $l$, then $\boldsymbol{x}(\mathcal{C})=l\hat{\boldsymbol{E}}\_{\rm a}$. The difference between the current and reference length vectors is called the change in length vector $\boldsymbol{\delta}$.   

For the current case we have that
$$
\begin{equation}
\boldsymbol{\delta}=(l-L)\hat{\boldsymbol{E}}\_{\rm a}
\end{equation}
$$

Say the force on the bar's right face is $\boldsymbol{F}$, then Hooke's law states that
$$
\boldsymbol{F}=\frac{E A}{L} \boldsymbol{\delta}
$$ 

Since the focus our attention when the bar just streches along its own axis, we can write $\boldsymbol{F}=F\hat{\boldsymbol{E}}\_a$, and $\boldsymbol{\delta}=\delta\hat{\boldsymbol{E}}\_a$. Then it follows from the last displayed equation that
$$
F=\frac{E A}{L} \delta,
$$ 
which matches our earlier scalar versin of the Hooke's law.

<!-- vector $\boldsymbol{u}(\mathcal{C})=\boldsymbol{x}(\mathcal{C})-\boldsymbol{X}(\mathcal{C})$ is called the displacement vector of $\mathcal{C}$. Since we don't talk about any other materials particles other the right face's centroid we write $\boldsymbol{x}(\mathcal{C})$, $\boldsymbol{X}(\mathcal{C})$, and $\boldsymbol{u}(\mathcal{C})$ simply as $\boldsymbol{x}$, $\boldsymbol{X}$, and $\boldsymbol{u}$, respectively. 

The vector  -->


We have been talking about the change in length $\delta$ as the difference between the final length, $l$, and initial length, $L$, i.e., $\delta=l-L$. However, the change in length can be defined in an alternate manner--a manner that is more abstract, but that which can be generalized to more complicated cases, like torsion and bending. For that reason, we will explore that alternate means of defining $\delta$ below. 


![](ClassNotes-7.jpg)
<!-- HK_TODO: In the figure u(C) needs to be chnaged to bold \dekta -->


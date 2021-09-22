{% include mathjax_support %}
{% include command %}

# Displacement field within a bar of constant cross-sectional area

In deriving the displacement field within the bar, we will assume that "plane cross-sections remain plane." 

<!-- 
HK_DONE: Need to explain what it means to say plane sections remain plane. Done in class. 

HK_DONE: Need to present the vector form of the Hook'e law.

Consider the following surface 
$$
\begin{equation}
\{X_2\hat{\boldsymbol{E}}_2+\}
\end{equation}
$$   -->

Let $\boldsymbol{u}$ be the displacement field of a bar. In the [previous section](./Bars2.md), we learned that $\boldsymbol{u}(\boldsymbol{X})$ is the displacement of the material particle $\boldsymbol{X}$. The displacement vector tells us how much the material particle has moved on the application of the force. Recall that we are referring to material particles by their position vectors in the reference configuration.  

In the following, we focus our attention on when the bar just stretches along its own axis (with no rotation.) That is, we focus on the case in which  the bar remains aligned with $\hat{\boldsymbol{E}}\_{\rm a}$ before and after deformation. In this case, we can work with the scalar displacement field $u$, which is defined as 

$$
\begin{equation}
u(X):=\boldsymbol{u}(X\hat{\boldsymbol{E}}_{\rm a})⋅ \hat{\boldsymbol{E}}_{\rm a}
\end{equation}
$$

The scalar displacement field can be used as follows. Say the material particle $\boldsymbol{X}$ can be expressed as $\boldsymbol{X}=X \hat{\boldsymbol{E}}\_{a}$. Then, its  displacement can be computed as $u(X) \hat{\boldsymbol{E}}_{\rm a}$. 

![](2021-09-21-16-29-16.png)

Now, let us focus on a small slice of the bar. Let the position vector of the material particle on (the centroid of) the left face of the slice be $X \hat{\boldsymbol{E}}\_{a}$ and, the position vector of the material particle on (the centroid of) the right face of the slice be  $(X+\Delta X) \hat{\boldsymbol{E}}\_{a}$. The reference length vector of the slice is, of course, $\Delta X \hat{\boldsymbol{E}}\_{a}$. Let the scalar displacement field in the bar be   $u$. Then, the current position vector of the left particle is $(X+u(X))\hat{\boldsymbol{E}}\_{a}$ and of the right particle is $(X+\Delta X+u(X+\Delta X))\hat{\boldsymbol{E}}\_{a}$. Thus, the current length vector of the slice is $(\Delta X+u(X+\Delta X)-u(X))\hat{\boldsymbol{E}}\_{a}$. The change in length vector is $(u(X+\Delta X)-u(X))\hat{\boldsymbol{E}}\_{a}$

On applying the [vector form of the Hooke's law](VectorFormHookesLaw.md) to the slice, we have that the force vector on the right face of the slice is

$$
\begin{align}
\boldsymbol{F}=\frac{E A}{\Delta X}(u(X+\Delta X)-u(X))\hat{\boldsymbol{E}}\_{a}
\end{align}
$$ 

From force equilibrium, we know that the force vector on the right face of the slice is the same as the force vector acting on the right face, $\Gamma^{\mathscr{h}}$, of the bar. The force on the right face of the bar, of course, is $F \hat{\boldsymbol{E}}\_a$, where $F= (E A/L) \delta$, and $\delta = l-L$. Combining this information with the last displayed equation, we get that

$$
\begin{align}
F \hat{\boldsymbol{E}}\_{a} &=\frac{E A}{\Delta X}(u(X+\Delta X)-u(X))\hat{\boldsymbol{E}}\_{a}\\
\frac{E A}{L} \delta&=\frac{E A}{\Delta X}(u(X+\Delta X)-u(X))\\
 \frac{\delta}{L}&=\frac{u(X+\Delta X)-u(X)}{\Delta X}\\
 \lim_{\Delta X\to 0}\frac{\delta}{L}&=\lim_{\Delta X\to 0}\frac{u(X+\Delta X)-u(X)}{\Delta X}\\
 \frac{\delta}{L}&=u'(X)
\end{align}
$$


Integrating the above differential equation, we get that

$$
\begin{align}
 u(X)&=\frac{\delta}{L} X+ \text{constant}
\end{align}
$$

Say the left face is not allowed to move during the deformation; then, that would imply that the constant in the above equation is naught. In summary, we get the displacement field to be 

$$
\begin{align}
 u(X)&=\delta \frac{X}{L} 
\end{align}
$$




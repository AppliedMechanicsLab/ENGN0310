{% include mathjax_support %}
{% include command %}

#  Material properties and cross-sectional area varying along the length

#### Force-displacement relationship

Previously, we derived [the force-displacement relationship](./Bars4.md) when the cross-section area of the bar is varying along its length. In that case, we got that

$$
\begin{align}
\boldsymbol{F}&=
\left(
\int_{0}^{L}\frac{dX}{E A(X)}
\right)^{-1}
\boldsymbol{\delta}
\label{eq:HookesLaw}
\end{align}
$$

In the case that the Young's modulus also varies along the length, we get that  

$$
\begin{align}
\boldsymbol{F}&=
\left(
\int_{0}^{L}\frac{dX}{E(X) A(X)}
\right)^{-1}
\boldsymbol{\delta}
\end{align}
$$

We will not be deriving the above equation. However, the steps on the derivation/proof for the above equation are almost the same as the one we used for deriving $\eqref{eq:HookesLaw}$ in section [Force-displacement law for the case of variable cross-sectional area](./Bars4.md).  


#### Displacement field

Previously we derived [the displacement field](./Bars5_2.md) when the cross-section area of the bar is varying along its length. In that case, we got that


$$
\begin{equation}
u(X)=F\int_{0}^{X} \frac{\, d\, Y}{E A(Y)}
\end{equation}
\label{eq:OldDispField}
$$

In the case that the Young's modulus also varies along the length, we get that  


$$
\begin{equation}
u(X)=F\int_{0}^{X} \frac{\, d\, Y}{E(Y) A(Y)}
\label{eq:NewDispField}
\end{equation}
$$


We will not be discussing the derivation of $\eqref{eq:NewDispField}$. However, the steps in deriving $\eqref{eq:NewDispField}$ are almost exactly the same as those used in deriving $\eqref{eq:OldDispField}$, see section [Explicit expression for the case of variable cross-section](./Bars5_2.md)

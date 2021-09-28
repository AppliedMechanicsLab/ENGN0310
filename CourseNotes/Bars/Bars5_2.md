{% include mathjax_support %}
{% include command %}

# Displacement field inside a bar of variable cross-section

For deriving the displacement field inside a bar of varible cross-section we will use the more general version of the constitutive equation for the bar (which is discussed in [this](./BodyForce1.md) section), which is

$$
\begin{equation}
\sigma_{11}:=F(A)/A(X)=E(X) u'(X).
\end{equation}
$$

Rearranging the terms in the above equation, and then integrating both sides from $0$ to $X$ we get

$$
\begin{align}
u(X)&=\int_{Y=0}^{Y=X}\frac{F(Y)}{A(Y)E(Y)}\, dY.
\end{align}
$$

From force equilibrium it follows that in the case of no body forces the axial force is constant along the bar's length, and is equal to the force acting on the bar's right face. 

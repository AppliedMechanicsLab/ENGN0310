{% include mathjax_support %}
{% include command %}

# Displacement field inside a bar of variable cross-section

For deriving the displacement field inside a bar of a variable cross-section we will use the more general version of the constitutive equation for the bar (which is discussed in [this](./BodyForce1.md) section), which is

$$
\begin{equation}
\sigma_{11}:=F(A)/A(X)=E(X) u'(X).
\end{equation}
$$

The expression $F(X)$ appearing in the above equation is defined such that $F(X)\uv{E}\_a$ is the force acting on the cross-section with the outward normal  $\uv{E}\_a$ and area $A(X)$. The terms $E(X)$ and $u(X)$ are, respectively, the Young's modulus and scalar displacement of the bar at the material particle $X$. For now we are only considering the case in which the material properties are constant along the bar's length. Thus we take $E(X)$ to simply be the constant $E$.

Rearranging the terms in the above equation, and then integrating both sides from $0$ to $X$ we get

$$
\begin{align}
u(X)&=\frac{1}{E}\int_{Y=0}^{Y=X}\frac{F(Y)}{A(Y)}\, dY.
\end{align}
$$

 From force equilibrium it follows that in the case when there are no body forces the axial force is constant along the bar's length, and is equal to the force acting on the bar's right face. Say the force on the bar's right face ($\Gamma^{\mathscr{h}}$) is $F\u{E}\_a$ then from the last equation we get 


$$
\begin{align}
u(X)&=\frac{F}{E}\int_{0}^{X}\frac{dY}{A(Y)}.
\end{align}
$$

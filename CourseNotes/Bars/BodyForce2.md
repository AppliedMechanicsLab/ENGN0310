{% include mathjax_support %}
{% include command %}

# General force equilibrium in 1D

![](2021-09-21-16-29-16.png)




In the [previous section](./BodyForce1.md) we presented that 

$$
\begin{align}
\sigma_{11}(X)=E(X)u'(X)
\label{eq:LinearElasticity1D}
\end{align}
$$


The equation $F =E A \delta/L$ can be shown to derive from $\eqref{eq:LinearElasticity1D}$. In that $\eqref{eq:LinearElasticity1D}$ is a more fundamental law. Equation $\eqref{eq:LinearElasticity1D}$ itself derives from the constitutive equation of the the   linear theory of elasticity. 





#### Force equilibrium

$-F(X)\u{E}_1$
$F(X+\Delta X)\u{E}_1$

$F(X+\Delta X)-F(X)\u{E}_1+\int_{Y=X}^{X+\Delta X}b(Y) \u{E}_1\, dY=0$

$$
\begin{align}
\frac{F(X+\Delta X)-F(X)}{\Delta X}+
\frac{1}{\Delta X}\int_{Y=X}^{X+\Delta X}b(Y) \, dY&=0\\
F'(X)+b(X)&=0
\end{align}
$$

$$
\begin{align}
(\sigma_{11}(X)A(X))'+b(X)&=0\\
(\sigma_{11}(X)A(X))'+b(X)&=0
\end{align}
$$



Now, let us focus on a small slice of the bar. Let the position vector of the material particle on (the centeroid of) the left face of the slice be $X \hat{\boldsymbol{E}}\_{a}$ and, the position vector of the material particle on (the centeroid of) the right face of the slice be  $(X+\Delta X) \hat{\boldsymbol{E}}\_{a}$. The reference length vector of the slice is, of course, $\Delta X \hat{\boldsymbol{E}}\_{a}$. Let the scalar displacement field in the bar be   $u$. Then the current position vector of the left particle is $(X+u(X))\hat{\boldsymbol{E}}\_{a}$ and of the right particle is $(X+\Delta X+u(X+\Delta X))\hat{\boldsymbol{E}}\_{a}$. Thus, the current length vector of the slice is $(\Delta X+u(X+\Delta X)-u(X))\hat{\boldsymbol{E}}\_{a}$. The change in length vector is $(u(X+\Delta X)-u(X))\hat{\boldsymbol{E}}\_{a}$

On applying the [vector form of the Hooke's law](VectorFormHookesLaw.md) to the slice we have that the force vector on the right face of the slice is
$$
\begin{align}
\boldsymbol{F}=\frac{E A}{\Delta X}(u(X+\Delta X)-u(X))\hat{\boldsymbol{E}}\_{a}
\end{align}
$$ 

From force equilibrium we know that the force vector on the right face of the slice is the same as the force vector acting on the right face, $\Gamma^{\mathscr{h}}$, of the bar. The force on the right face of the bar, of course, is $F \hat{\boldsymbol{E}}\_a$, where $F= (E A/L) \delta$, and $\delta = l-L$. Combing this information with last displayed equation we get that

$$
\begin{align}
F \hat{\boldsymbol{E}}\_{a} &=\frac{E A}{\Delta X}(u(X+\Delta X)-u(X))\hat{\boldsymbol{E}}\_{a}\\
\frac{E A}{L} \delta&=\frac{E A}{\Delta X}(u(X+\Delta X)-u(X))\\
 \frac{\delta}{L}&=\frac{u(X+\Delta X)-u(X)}{\Delta X}\\
 \lim_{\Delta X\to 0}\frac{\delta}{L}&=\lim_{\Delta X\to 0}\frac{u(X+\Delta X)-u(X)}{\Delta X}\\
 \frac{\delta}{L}&=u'(X)
\end{align}
$$


$(E(X)A(X)u'(X))'+B(X)=0$
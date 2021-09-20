{% include mathjax_support %}
{% include command %}

# Displacement field inside a bar of variable cross-section

As before instead of directly working with a bar of variable cross-section. Let us work with a auxillary bar, a bar in which the cross-sectional area is  piece-wise constant. That is, we 

As the number of pieces becomes large the shape of this bar 
![](2021-09-19-20-55-06.png)




Now, let us focus on one of the constant cross-sectional area segments. Let the position vector of the material particle on (the centeroid of) the left face of the piece  be $X \hat{\boldsymbol{E}}\_{a}$ and, the position vector of the material particle on (the centeroid of) the right face of the slice be  $(X+\Delta X) \hat{\boldsymbol{E}}\_{a}$. The reference length vector of the slice is, of course, $\Delta X \hat{\boldsymbol{E}}\_{a}$. Let the scalar displacement field in the bar be   $u$. Then the current position vector of the left particle is $(X+u(X))\hat{\boldsymbol{E}}\_{a}$ and of the right particle is $(X+\Delta X+u(X+\Delta X))\hat{\boldsymbol{E}}\_{a}$. Thus, the current length vector of the slice is $(\Delta X+u(X+\Delta X)-u(X))\hat{\boldsymbol{E}}\_{a}$. The change in length vector is $(u(X+\Delta X)-u(X))\hat{\boldsymbol{E}}\_{a}$

On applying the Hooke's law to the slice we have that the force vector on the righ face of the slice is
$$
\begin{align}
\boldsymbol{F}=\frac{E A(X)}{\Delta X}(u(X+\Delta X)-u(X))\hat{\boldsymbol{E}}\_{a}
\end{align}
$$ 

From force equalibrium we know that the force vector on the righ face of the slice is the same as the force vector acting on the right face, $\Gamma^{\mathscr{h}}$, of the bar. The force on the right face of the bar of course is $F \hat{\boldsymbol{E}}\_a$, where $F= (E A/L) \delta$, and $\delta = l-L$. Combing this information with last displayed equation we get that
$$
\begin{align}
F \hat{\boldsymbol{E}}\_{a} &=\frac{E A(X)}{\Delta X}(u(X+\Delta X)-u(X))\hat{\boldsymbol{E}}\_{a}\\
F  &=\frac{E A(X)}{\Delta X}(u(X+\Delta X)-u(X))\\
 \frac{F}{E A(X)}&=\frac{u(X+\Delta X)-u(X)}{\Delta X}\\
 \lim_{\Delta X\to 0}\frac{F}{E A(X)}&=\lim_{\Delta X\to 0}\frac{u(X+\Delta X)-u(X)}{\Delta X}\\
 \frac{F}{E A(X)}&=u'(X)
\end{align}
$$



$$
u(X)=\int_{0}^{X} \frac{F\, d\, Y}{E A(Y)}
$$

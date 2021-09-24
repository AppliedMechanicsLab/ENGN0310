{% include mathjax_support %}
{% include command %}

### A more fundamental Hooke's Law

We started presenting following equation as the constitutive law (force deflection relation) for the bar
$$
\begin{equation}
F=\frac{E A}{L}\delta
\label{eq:HookesLawScalarForm}
\end{equation}
$$

We then presented a vector form of the above equation. Specifically, we presented
$$
\begin{equation}
\boldsymbol{F}=\frac{E A}{L}\boldsymbol{\delta},
\labe{eq:HookesLawVectorForm}
\end{equation}
$$
where $\boldsymbol{\delta}=\boldsymbol{l}-\boldsymbol{L}$, $\u{l}=l\uv{E}_a$, and $\u{L}=L\uv{E}_a$.

The force-displacement relations and the displacement field, both for constant and variable area/property bars were derived using the above equations. However, so far the force inside the bar has always remained constnat. 
 
Now we consider the case in which the force too varies along the bar. This usually happens when there is a body forces acting on the bar. body forces can arise due to gravity, dynamics, magnetic field, etc. For solving the problem of  a bar is subject to  body we will need to use more fundamental constitutive law, than the laws given in $\eqref{eq:HookesLawScalarForm}$ and $\eqref{eq:HookesLawVectorForm}$. 
Defining
$$
\begin{equation}
\sigma_{11}(X)=F(X)/A(X)
\end{equation}
$$
we present this law, which is a particularization of the constitutive equation from the linear theory of elasticity, as 
$$
\begin{equation}
\sigma_{11}(X)=E(X) u'(X)
\label{eq:}
\end{equation}
$$

The laws $\eqref{eq:HookesLawScalarForm}$ and $\eqref{eq:HookesLawVectorForm}$ can be shown derive from 


![](2021-09-21-16-29-16.png)






## Bar with body force

In the previous section we derived that 

$$
\begin{align}
F=
\end{align}
$$


## Torsion

The Hooke's Law for Torsion is 

$$
\begin{align}
\frac{T L}{J \theta}=\text{constant}=G
\end{align}
$$

<!-- 
HK_DONE: Need to explain what it means to say plane sections remain plane. Done in class. 

HK_DONE: Need to present the vector form of the Hook'e law.

Consider the following surface 
$$
\begin{equation}
\{X_2\hat{\boldsymbol{E}}_2+\}
\end{equation}
$$   -->
A more fundamental law. Derives from Linear elasticity. The law we had for Bar is surely. Consistent with the below law. 
$\sigma (X)= E(X)u'(X)$


$(E(X)A(X)u'(X))'+B(X)=0$

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

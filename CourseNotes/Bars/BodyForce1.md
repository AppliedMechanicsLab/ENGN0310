{% include mathjax_support %}
{% include command %}

# A more fundamental Hooke's Law

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
\label{eq:LinearElasticityConstitutiveLaw1D}
\end{equation}
$$

The laws $\eqref{eq:HookesLawScalarForm}$ and $\eqref{eq:HookesLawVectorForm}$ can be shown to derive from $\eqref{eq:LinearElasticityConstitutiveLaw1D}$.




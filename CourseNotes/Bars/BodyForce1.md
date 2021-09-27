{% include mathjax_support %}
{% include command %}

# A more fundamental Hooke's Law

We started by presenting the following equation as the constitutive law (force deflection relation) for the bar in this [section](./Bars.md): 

$$
\begin{equation}
F=\frac{E A}{L}\delta.
\label{eq:HookesLawScalarForm}
\end{equation}
$$


We then [presented a vector form of the above equation](./VectorFormHookesLaw.md). Specifically, we presented

$$
\begin{equation}
\boldsymbol{F}=\frac{E A}{L}\boldsymbol{\delta},
\label{eq:HookesLawVectorForm}
\end{equation}
$$


where $\boldsymbol{\delta}=\boldsymbol{l}-\boldsymbol{L}$, $\u{l}=l\uv{E}\_{\rm a}$, and $\u{L}=L\uv{E}\_{\rm a}$.

The force-displacement relations and the displacement field for
* constant area 
    * [force-displacement (constant area) ](./Bars.md) 
    * [displacement field (constant area)](./Bars3.md)
* variable area 
    * [force-displacement (variable area)](./Bars4.md) 
    * [displacement field (variable area)](./Bars5.md)
* [variable area and property bars](./Bars6.md) 

were derived using the above equations. However, so far, the force inside the bar has always remained constant. 
 
Now we consider the case in which the force also varies along the bar. This usually happens when there is a body force acting on the bar. Body forces can arise due to gravity, dynamics, magnetic field, etc. To solve problems involving bars subject to  body forces, we will need to use a more fundamental form of the constitutive law than those given in $\eqref{eq:HookesLawScalarForm}$ and $\eqref{eq:HookesLawVectorForm}$. 


Let the axial force in the bar vary as $\u{F}(X)=F(X)\uv{E}\_{\rm a}$. The value $\u{F}(X)$ at $X=L$ equals the force applied to the right face of the bar.  Defining 

$$
\begin{equation}
\sigma_{11}(X)=F(X)/A(X)
\label{eq:Stress1DDef}
\end{equation}
$$

a more general version of the constitutive equation for the bar is

$$
\begin{equation}
\sigma_{11}(X)=E(X) u'(X)
\label{eq:LinearElasticityConstitutiveLaw1D}
\end{equation}
$$

The laws $\eqref{eq:HookesLawScalarForm}$ and $\eqref{eq:HookesLawVectorForm}$ can be shown to derive from $\eqref{eq:LinearElasticityConstitutiveLaw1D}$.




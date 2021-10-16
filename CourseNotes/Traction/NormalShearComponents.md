{% include mathjax_support %}
{% include command %}

# Normal and shear components of the traction vector


The notation $\left[\left
\langle \boldsymbol{t}\right\rangle(AA'(\hat{\boldsymbol{n}}))\right]$ is very explicit, but also looks untidy. Let's give this expression an alias as $\boldsymbol{\mathsf{t}}$, and also denote the expression $\left[
\hat{\boldsymbol{n}}\right]$  as $\hat{\boldsymbol{\mathsf{n}}}$.

The traction $\boldsymbol{\mathsf{t}}$ can be written as 
$$
\begin{align}
\boldsymbol{\mathsf{t}}&=\boldsymbol{\mathsf{t}}_{n}+\boldsymbol{\mathsf{t}}_s,\\
\boldsymbol{\mathsf{t}}&=t_n  \hat{\boldsymbol{\mathsf{n}}}+t_s  \hat{\boldsymbol{\mathsf{m}}},
\end{align}
$$
where is $\hat{\boldsymbol{\mathsf{m}}}$ is some direction vector that is perpendicular to $\hat{\boldsymbol{\mathsf{n}}}$, i.e., it lies in the plane $AA'(\hat{\boldsymbol{n}})$. 

It can be shown that 

$$
\begin{align}
\boldsymbol{\mathsf{t}}_{n}&=
\left(\boldsymbol{\mathsf{t}}^{\mathsf{T}}\hat{\boldsymbol{\mathsf{n}}}\right)\hat{\boldsymbol{\mathsf{n}}},\\
\boldsymbol{\mathsf{t}}_{s}&=\boldsymbol{\mathsf{t}}-\boldsymbol{\mathsf{t}}_{n}
\end{align}
$$

The state of stress on $AA'$ is 

*  _pure shear_ when $\boldsymbol{\mathsf{t}}_{n}=\boldsymbol{\mathsf{0}}$
*   _pure tension_ when $\boldsymbol{\mathsf{t}}_{s}=\boldsymbol{\mathsf{0}}$ and $t_n>0$.
*  _pure compression_ when $\boldsymbol{\mathsf{t}}_{s}=\boldsymbol{\mathsf{0}}$ and $t_n<0$.
*  _tensile_ $t_n>0$.
*  _compressive_ $t_n<0$.

The above statents don't change if performed the analysis on $AA'(\hat{\boldsymbol{n}})$, or $AA'(-\hat{\boldsymbol{n}})$. 

### Examples.
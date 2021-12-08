{% include mathjax_support %}
{% include command %}


A column is rigid and attached at the base to a torwsional spring of stiffness $k$. The torsional sping proides a moment of $-k \theta\hat{\boldsymbol{E}}_3$ (in N-m). We apply a force at the top of the column of $P \hat{\boldsymbol{E}}_2$. Say that after the column has rotated. Applied moment of the 


$$
\begin{align}
\boldsymbol{M}_{\mathcal{O}-P}&=
\left(-l \cos(\theta) \hat{\boldsymbol{E}}_2+l\sin(\theta)\hat{\boldsymbol{E}}_1\right)\times P  \hat{\boldsymbol{E}}_2\\
&=P l \sin(\theta) \hat{\boldsymbol{E}}_3\\
\boldsymbol{M}_{\mathcal{O}-k}&=-k \theta\hat{\boldsymbol{E}}_3
\end{align}
$$

From the balance of moment about the point $\mathcal{O}$ we get that

$$
\begin{align}
P l \sin(\theta) \hat{\boldsymbol{E}}_3-k \theta\hat{\boldsymbol{E}}_3&=\boldsymbol{0},\\
\sin(\theta)=\frac{k}{P L}\theta
\end{align}
$$
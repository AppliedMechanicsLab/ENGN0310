{% include mathjax_support %}
{% include command %}

# Definition of moments on cross-sections. 


#### Definition of $\boldsymbol{M}(X_1,\hat{\boldsymbol{E}}_1)$

The quantity $\boldsymbol{M}(X_1,\hat{\boldsymbol{E}}_1)$ is called the moment of the surface $\Gamma(X_1,\hat{\boldsymbol{E}}_1)$. It is defined to be the moment about the centeroid of the surface $\Gamma(X_1)$ of the forces acting on the surface  $\Gamma(X_1,\hat{\boldsymbol{E}}_1)$. 


A mathematical definition of $\boldsymbol{M}(X_1,\hat{\boldsymbol{E}}_1)$ is 

$$
\begin{align}
\boldsymbol{M}(X_1,\hat{\boldsymbol{E}}_1)
&=
\int_{\Gamma(X_1)}(\boldsymbol{X}-X_1\boldsymbol{E}_1)\times \boldsymbol{t}(\boldsymbol{X},\hat{\boldsymbol{E}}_1)\, d\Gamma\\
% &=\int_{\Gamma(X_1)}(X_2\boldsymbol{E}_2+X_3\boldsymbol{E}_3)\times \boldsymbol{t}(X_1,\hat{\boldsymbol{E}}_1)\, d\Gamma
\end{align}
$$


In the above equation the $\boldsymbol{t}(\boldsymbol{X},\hat{\boldsymbol{E}}\_1)$ is, as we have define before, the traction vector at the materials point $\boldsymbol{X}$ in the direction $\boldsymbol{E}\_1$.  

#### Definition $\boldsymbol{M}(X_1,-\hat{\boldsymbol{E}}_1)$

The quantity $\boldsymbol{M}(X_1,-\hat{\boldsymbol{E}}_1)$ is called the moment of the surface $\Gamma(X_1,-\hat{\boldsymbol{E}}_1)$. It is defined to be the moment about the centeroid of the surface $\Gamma(X_1)$ of the forces acting on the surface  $\Gamma(X_1,-\hat{\boldsymbol{E}}_1)$.


A mathematical definition of $\boldsymbol{M}(X_1,-\hat{\boldsymbol{E}}_1)$ is 

$$
\begin{align}
\boldsymbol{M}(X_1,\hat{\boldsymbol{E}}_1)
&=
\int_{\Gamma(X_1)}(\boldsymbol{X}-X_1\boldsymbol{E}_1)\times \boldsymbol{t}(\boldsymbol{X},-\hat{\boldsymbol{E}}_1)\, d\Gamma
% \\
% &=\int_{\Gamma(X_1)}(X_2\boldsymbol{E}_2+X_3\boldsymbol{E}_3)\times \boldsymbol{t}(X_1,-\hat{\boldsymbol{E}}_1)\, d\Gamma
\end{align}
$$

In the above equation the $\boldsymbol{t}(\boldsymbol{X},\hat{\boldsymbol{E}}_1)$ is, as we have define before, the traction vector at the materials point $\boldsymbol{X}$ in the direction $\boldsymbol{E}_1$.



<!-- Consider a  sequene of surface $\Delta S_{\epsilon}(\boldsymbol{X},\boldsymbol{E}\_1)$ all of which passed through   $\boldsymbol{X}$ and had $\boldsymbol{E}\_1$ be normal to themselves at $\boldsymbol{X}$ And furthermore if area of the surface  $\Delta S_{\epsilon}(\boldsymbol{X},\boldsymbol{E}\_1)$ was $A(\epsilon)$ such that as $\epsilon \to 0$ $A(\epsilon)=O(\epsilon)$ then the force on the surface $\Delta S_{\epsilon}(\boldsymbol{X},\boldsymbol{E}\_1)$ as $\epsilon \to 0$ is equal to $\boldsymbol{t}(\boldsymbol{X},\hat{\boldsymbol{E}}\_1)A(\epsilon)+o(\epsilon)$. -->

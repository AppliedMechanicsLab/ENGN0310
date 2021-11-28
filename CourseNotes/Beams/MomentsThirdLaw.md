# Proof of $\boldsymbol{M}(X_1,\hat{\boldsymbol{E}}_1)=-\boldsymbol{M}(X_1,-\hat{\boldsymbol{E}}_1)$

The definitions of $\boldsymbol{M}(X_1,\hat{\boldsymbol{E}}_1)$, and $\boldsymbol{M}(X_1,-\hat{\boldsymbol{E}}_1)$ are given in [this section](./MomentsOnCrosssection.md).  



$$
\begin{align}
\boldsymbol{M}(X_1,\hat{\boldsymbol{E}}_1)&=
\int_{\Gamma(X_1)}(\boldsymbol{X}-X_1\boldsymbol{E}_1)\times \boldsymbol{t}(\boldsymbol{X},\hat{\boldsymbol{E}}_1)\, d\Gamma
\end{align}
$$


and 


$$
\begin{align}
\boldsymbol{M}(X_1,-\hat{\boldsymbol{E}}_1)&=
\int_{\Gamma(X_1)}(\boldsymbol{X}-X_1\boldsymbol{E}_1)\times \boldsymbol{t}(\boldsymbol{X},-\hat{\boldsymbol{E}}_1)\, d\Gamma
\end{align}
$$


In the last two equations $\boldsymbol{t}(\boldsymbol{X},\hat{\boldsymbol{E}}_1)$, and $\boldsymbol{t}(\boldsymbol{X},-\hat{\boldsymbol{E}}_1)$ are, as we have defined before, respectively, the traction vectors at the material point $\boldsymbol{X}$ in the $\boldsymbol{E}_1$, and $-\boldsymbol{E}_1$.

From Newton's third law we have that $\boldsymbol{t}(\boldsymbol{X},\hat{\boldsymbol{E}}_1)$ is the negative of $-\boldsymbol{t}(\boldsymbol{X},-\hat{\boldsymbol{E}}_1)$, i.e., to say that 

$$
\boldsymbol{t}(\boldsymbol{X},-\hat{\boldsymbol{E}}_1)=-\boldsymbol{t}(\boldsymbol{X},\hat{\boldsymbol{E}}_1)
$$

Substituting $\boldsymbol{t}(\boldsymbol{X},-\hat{\boldsymbol{E}}_1)$ in the euqation for $\boldsymbol{M}(X_1,-\hat{\boldsymbol{E}}_1)$ as $-\boldsymbol{t}(\boldsymbol{X},\hat{\boldsymbol{E}}_1)$ we get that

$$
\begin{align}
\boldsymbol{M}(X_1,-\hat{\boldsymbol{E}}_1)&=
-\int_{\Gamma(X_1)}(\boldsymbol{X}-X_1\boldsymbol{E}_1)\times \boldsymbol{t}(\boldsymbol{X},\hat{\boldsymbol{E}}_1)\, d\Gamma,
\end{align}
$$

from which it follows that 
$$
\begin{align}
\boldsymbol{M}(X_1,-\hat{\boldsymbol{E}}_1)&=-\boldsymbol{M}(X_1,\hat{\boldsymbol{E}}_1)
\end{align}
$$
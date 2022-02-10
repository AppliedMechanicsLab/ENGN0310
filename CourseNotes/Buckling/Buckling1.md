{% include mathjax_support %}
{% include command %}


A column is rigid and attached at the base to a torsional spring of stiffness $k$. The torsional spring provides a moment of $-k \theta\hat{\boldsymbol{E}}_3$ (in $\rm{N \cdot m}$). Say that after the column has rotated, we apply a force of $P \hat{\boldsymbol{E}}_2$ at the top of the column. Then, we have that

<!-- Say that after the column has rotated. Applied moment of the  -->


$$
\begin{align}
\boldsymbol{M}_{\mathcal{O}-P}&=
\left(-l \cos(\theta) \hat{\boldsymbol{E}}_2+l\sin(\theta)\hat{\boldsymbol{E}}_1\right)\times P  \hat{\boldsymbol{E}}_2\\
&=P l \sin(\theta) \hat{\boldsymbol{E}}_3\\
\boldsymbol{M}_{\mathcal{O}-k}&=-k \theta\hat{\boldsymbol{E}}_3
\end{align}
$$

From the balance of moment about the point $\mathcal{O}$, we get that

$$
\begin{align}
P l \sin(\theta) \hat{\boldsymbol{E}}_3-k \theta\hat{\boldsymbol{E}}_3&=\boldsymbol{0},\\
\sin(\theta)=\frac{k}{P L}\theta
\end{align}
$$


Let's consider a pinned joint. 
Moment arm between $\mathcal{M}$ and $P$ is $l\hat{\boldsymbol{E}}_1$ minus ($X_1\hat{\boldsymbol{E}}_1+y(X_1)\hat{\boldsymbol{E}}_2$). This comes out to be $(l-X_1)\hat{\boldsymbol{E}}_1-y(X_1)\hat{\boldsymbol{E}}_2$. The force in vector form is of course $-P \hat{\boldsymbol{E}}_1$. The momemnt is now


$$
\begin{align}
\boldsymbol{M}(X_1,-\hat{\boldsymbol{E}}_1)+
((l-X_1)\hat{\boldsymbol{E}}_1-y(X_1)\hat{\boldsymbol{E}}_2)
\times (-P \hat{\boldsymbol{E}}_1)&=\boldsymbol{0}\\
-\boldsymbol{M}(X_1,\hat{\boldsymbol{E}}_1)+
y(X_1)\hat{\boldsymbol{E}}_2
\times P \hat{\boldsymbol{E}}_1&=\boldsymbol{0}\\
-\boldsymbol{M}(X_1,\hat{\boldsymbol{E}}_1)-
y(X_1)
 P \hat{\boldsymbol{E}}_3&=\boldsymbol{0}\\
\boldsymbol{M}(X_1,\hat{\boldsymbol{E}}_1)\cdot \hat{\boldsymbol{E}}_3+
y(X_1)
 P &=0\\
M(X_1)+
y(X_1)
 P&=0\\
E I y''(X_1)+
y(X_1)
 P&=0\\
 y''(X_1)+
y(X_1)
\frac{P}{E I}&=0\\
 y''(X_1)+
\lambda^2 y(X_1)&=0
 \end{align}
$$


$$y(X_1)=A \cos(\lambda X_1)+B \sin(\lambda X_1)$$

From $y(0)=0$ we get $A=0$.
From $y(L)=0$ we get 

$$
\begin{align}
B \sin(\lambda L)&=0\\
\lambda L &= n\pi\\
\lambda_n  &= \frac{n\pi}{L}
\end{align}
$$

$$
\begin{align}
\frac{P_n}{EI}&=\lambda_n^2\\
P_n&= E I \lambda_n^2\\
P_n&= \frac{n^2 \pi^2 E I}{L^2} 
\end{align}
$$


where Euler Buckling load is

$$
\begin{align}
P_{\rm cr}&= \frac{\pi^2 E I}{L^2} 
\end{align}
$$
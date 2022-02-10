{% include mathjax_support %}
{% include command %}
# Strain tensor


Consider the material particle $\boldsymbol{X}$. The components of $\boldsymbol{X}$ are $X_1,X_2,~X_3$ that are defined such that 

$$
\boldsymbol{X}=X_1 \hat{\boldsymbol{E}}_1+X_2 \hat{\boldsymbol{E}}_2+X_3 \hat{\boldsymbol{E}}_3.
$$

After deformation, the position vector of the material particle $\boldsymbol{X}$ is $\boldsymbol{x}$. The components of $\boldsymbol{x}$ are $x_1,x_2,~x_3$ that are defined such that

$$
\boldsymbol{x}=x_1 \hat{\boldsymbol{E}}_1+x_2 \hat{\boldsymbol{E}}_2+x_3 \hat{\boldsymbol{E}}_3.
$$


The displacement of the material particle $\boldsymbol{X}$ is $\boldsymbol{u}$ that is defined such that $\boldsymbol{x}=\boldsymbol{X}+\boldsymbol{u}$. 

We define the displacent field component $\breve{u}_1(\cdot, \cdot, \cdot)$, which are functions of three variables, such that 

$$
\begin{equation}
\boldsymbol{u}=\breve{u}_1(X_1,X_2,X_3)\hat{\boldsymbol{E}}_1+\breve{u}_2(X_1,X_2,X_3)\hat{\boldsymbol{E}}_2+\breve{u}_3(X_1,X_2,X_3)\hat{\boldsymbol{E}}_3
\end{equation}
$$



The strain field is the three variable function $\breve{\boldsymbol{\epsilon}}(\cdot,\cdot,\cdot)$ that is defined such that

$$
\begin{align}
\left[\breve{\boldsymbol{\epsilon}}(Y_1,Y_2,Y_3)\right]&=
\begin{bmatrix}
\breve{\epsilon}_{11}(Y_1,Y_2,Y_3) & \breve{\epsilon}\_{12}(Y_1,Y_2,Y_3) & \breve{\epsilon}\_{13}(Y_1,Y_2,Y_3)\\
\breve{\epsilon}_{21}(Y_1,Y_2,Y_3) & \breve{\epsilon}\_{22}(Y_1,Y_2,Y_3) & \breve{\epsilon}\_{23}(Y_1,Y_2,Y_3)\\
\breve{\epsilon}_{31}(Y_1,Y_2,Y_3) & \breve{\epsilon}\_{32}(Y_1,Y_2,Y_3) & \breve{\epsilon}\_{33}(Y_1,Y_2,Y_3)
\end{bmatrix}
\end{align}
$$
where 
$$
\begin{align}
\breve{\epsilon}_{11}(Y_1,Y_2,Y_3)&=
\frac{\partial \breve{u}_1(Y_1,Y_2,Y_3)}{\partial X_1}\\
\breve{\epsilon}_{22}(Y_1,Y_2,Y_3)&=
\frac{\partial \breve{u}_2(Y_1,Y_2,Y_3)}{\partial X_2}
\\
\breve{\epsilon}_{33}(Y_1,Y_2,Y_3)&=
\frac{\partial \breve{u}_3(Y_1,Y_2,Y_3)}{\partial X_3}\\
\breve{\epsilon}_{12}(Y_1,Y_2,Y_3)&=
\frac{1}{2}
\left(
\frac{\partial \breve{u}_1(Y_1,Y_2,Y_3)}{\partial X_2}
+
\frac{\partial \breve{u}_2(Y_1,Y_2,Y_3)}{\partial X_1}
\right)
\\
\breve{\epsilon}_{21}(Y_1,Y_2,Y_3)&=\breve{\epsilon}_{12}(Y_1,Y_2,Y_3)
\\
\breve{\epsilon}_{13}(Y_1,Y_2,Y_3)&=
\frac{1}{2}
\left(
\frac{\partial \breve{u}_1(Y_1,Y_2,Y_3)}{\partial X_3}
+
\frac{\partial \breve{u}_3(Y_1,Y_2,Y_3)}{\partial X_1}
\right)
\\
\breve{\epsilon}_{31}(Y_1,Y_2,Y_3)&=\breve{\epsilon}_{13}(Y_1,Y_2,Y_3)
\\
\breve{\epsilon}_{23}(Y_1,Y_2,Y_3)&=
\frac{1}{2}
\left(
\frac{\partial \breve{u}_2(Y_1,Y_2,Y_3)}{\partial X_3}
+
\frac{\partial \breve{u}_3(Y_1,Y_2,Y_3)}{\partial X_2}
\right)\\
\breve{\epsilon}_{32}(Y_1,Y_2,Y_3)&=\breve{\epsilon}_{23}(Y_1,Y_2,Y_3)
\end{align}
$$

The strain tensor $\boldsymbol{\epsilon}$ at the material particle $\boldsymbol{X}$ is simplify $\breve{\boldsymbol{\epsilon}}(X_1,X_2,X_3)$  
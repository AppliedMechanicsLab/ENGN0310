{% include mathjax_support %}
{% include command %}

Problem 1. The matrix representation of the stress tensor at a material particle $\boldsymbol{X}$ is 

$$
\left[\boldsymbol{\sigma}(\boldsymbol{X})\right]=\begin{bmatrix}
120 & 45\\
45 & 60
\end{bmatrix}~\text{MPa}
$$

the traction vector $\boldsymbol{t}$, the normal component of the traction vector, the shear component of the traction vector on the surfaces passing throught $\boldsymbol{X}$ and having the outward normal $\hat{\boldsymbol{n}}$

1. $~~\hat{\boldsymbol{E}}_1$
2. $-\hat{\boldsymbol{E}}_1$
3. $~~\hat{\boldsymbol{E}}_2$
4. $-\hat{\boldsymbol{E}}_2$

a. The traction vector on $~~\hat{\boldsymbol{E}}_1$ is 

$$
\begin{align}
\left[\boldsymbol{t}\right]&=\begin{bmatrix}
120 & 45\\
45 & 60
\end{bmatrix}
\begin{bmatrix}
1 \\
0
\end{bmatrix}
~\text{MPa}\\
&=\begin{bmatrix}
120 \\
45
\end{bmatrix}
~\text{MPa}
\end{align}
$$

The normal component of the traction vector on $~~\hat{\boldsymbol{E}}_1$ is 
$$
\begin{align}
\boldsymbol{t}_{n}&=
\left(\boldsymbol{t} \cdot \hat{\boldsymbol{n}}\right)\hat{\boldsymbol{n}}\\
\left[\boldsymbol{t}_{n}\right]
&=\left(\left[\boldsymbol{t}\right]^{\rm T} \left[ \hat{\boldsymbol{n}}\right]\right)\left[\hat{\boldsymbol{n}}\right]\\
&=\begin{bmatrix}
120 \\
0
\end{bmatrix}
~\text{MPa}\\
\boldsymbol{t}_{n}&=120~\hat{\boldsymbol{E}}_1~\text{MPa}
\end{align}
$$


The shear component of the traction vector on $~~\hat{\boldsymbol{E}}_1$ is 
$$
\begin{align}
\boldsymbol{t}_{s}&=
\boldsymbol{t} -\boldsymbol{t}_n\\
\left[\boldsymbol{t}_{s}\right]
&=\left[\boldsymbol{t}\right] -\left[\boldsymbol{t}_n\right]\\
&=\begin{bmatrix}
0 \\
45
\end{bmatrix}
~\text{MPa}\\
\boldsymbol{t}_{s}&=45~\hat{\boldsymbol{E}}_2~\text{MPa}
\end{align}
$$



b. The traction vector on $~~\hat{\boldsymbol{E}}_2$ is 

$$
\begin{align}
\left[\boldsymbol{t}\right]&=\begin{bmatrix}
120 & 45\\
45 & 60
\end{bmatrix}
\begin{bmatrix}
0 \\
1
\end{bmatrix}
~\text{MPa}\\
&=\begin{bmatrix}
45 \\
60
\end{bmatrix}
~\text{MPa}
\end{align}
$$

The normal component of the traction vector on $~~\hat{\boldsymbol{E}}_2$ is 
$$
\begin{align}
\boldsymbol{t}_{n}&=
\left(\boldsymbol{t} \cdot \hat{\boldsymbol{n}}\right)\hat{\boldsymbol{n}}\\
\left[\boldsymbol{t}_{n}\right]
&=\left(\left[\boldsymbol{t}\right]^{\rm T} \left[ \hat{\boldsymbol{n}}\right]\right)\left[\hat{\boldsymbol{n}}\right]\\
&=\begin{bmatrix}
0 \\
60
\end{bmatrix}
~\text{MPa}\\
\boldsymbol{t}_{n}&=60~\hat{\boldsymbol{E}}_2~\text{MPa}
\end{align}
$$


The shear component of the traction vector on $~~\hat{\boldsymbol{E}}_1$ is 
$$
\begin{align}
\boldsymbol{t}_{s}&=
\boldsymbol{t} -\boldsymbol{t}_n\\
\left[\boldsymbol{t}_{s}\right]
&=\left[\boldsymbol{t}\right] -\left[\boldsymbol{t}_n\right]\\
&=\begin{bmatrix}
45 \\
0
\end{bmatrix}
~\text{MPa}\\
\boldsymbol{t}_{s}&=45~\hat{\boldsymbol{E}}_1~\text{MPa}
\end{align}
$$

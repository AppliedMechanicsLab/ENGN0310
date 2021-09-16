# Vector form of the Hooke's law for the bar

In the [introductory section on bars](Bars.md) we introduced the Hooke's law for the bar to be

$$
\begin{align}
\frac{F L}{A \delta}=A
\end{equation}
$$


We have been talking about the change in length $\delta$ as the difference between the final length, $l$, and initial length, $L$, i.e., $\delta=l-L$. However, the change in length can be defined in an alternate manner--a manner that is more abstract, but that which can be generalized to more complicated cases, like torsion and bending. For that reason, we will explore that alternate means of defining $\delta$ below. 


![](ClassNotes-7.jpg)
<!-- HK_TODO: Also introduce the concept of a material particle-->

<!-- HK_TODO: need to introduce the keywords of referece position vector, and current poistion vector -->
Let the position vector of the $\Gamma^{\mathscr{h}}$'s centroid, $\mathcal{C}$, before any forces are applied to the bar, be $\boldsymbol{X}(\mathcal{C})$ (red arrow in the top panel of the above figure). On choosing the origin of the physical space $\mathcal{E}^3$ to be located at the centroid of the bar's left face, we get that $\boldsymbol{X}(\mathcal{C})=L\hat{\boldsymbol{E}}\_{\rm a}$, and after the application of force the position vector of the centroid becomes $\boldsymbol{x}(\mathcal{C})$. If the length of bar after deformation is $l$, then we can express the position vector of $\mathcal{C}$ in the deformed configuration as $\boldsymbol{x}(\mathcal{C})=l\hat{\boldsymbol{E}}\_{\rm a}$. The vector $\boldsymbol{u}(\mathcal{C})=\boldsymbol{x}(\mathcal{C})-\boldsymbol{X}(\mathcal{C})$ is called the displacement of the bar's right face. This displacement vector can be written as

$$
\begin{equation}
\boldsymbol{u}(\mathcal{C})=(l-L) \hat{\boldsymbol{E}}_{\rm a}.
\end{equation}
$$

We define $\delta$ to be

$$
\begin{equation}
\delta := \boldsymbol{u}(\mathcal{C})⋅ \hat{\boldsymbol{E}}_{\rm a},
\end{equation}
$$

where the dot in the above equation denotes the "dot product between vectors." It follows from the last two equations that

$$
\begin{equation}
\delta = l-L,
\end{equation}
$$ 

which matches our rudimentary definition for $\delta$. 

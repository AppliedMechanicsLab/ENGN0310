{% include mathjax_support %}
{% include command %}
.tab {
  padding-left: 2px;
}



# ENGN0310: Homework 1
## Due Friday 11:59 pm, September 17th, 2021




> Please upload your assignment to Canvas.<br/>
> Contact Sayaka_Kochiyama@brown.edu if you have questions about the problems.   




#### Some helpful concepts needed for solving the HW problems


--------


From class, we know that

$$
\begin{equation}
\frac{T L}{J\theta}=G
\end{equation}
$$

where $T$ is the torque applied to the shaft, $L$ is the length of the bar, $J$ is the polar moment of inertia, $\theta$ is the angle of twist at the shaft's right end face (in $\rm{rad}$), and $G$ is the Shear modulus of the shaft. 

Notice that this is analogous to the Hook's law we explored in the previous assignments.

$$
\begin{equation}
\frac{F L}{A\delta}=E
\end{equation}
$$

Remember that (2) was a direct consequence of the following expression for displacement at material particle X, which takes into account the variable force, Young's modulus, and cross-sectional area along its length:


$$
\begin{equation}
u(X)=\int_0^X \frac{F(Y)}{E(Y) A(Y)} dY
\end{equation}
$$

When you take F, E, A as constant values and take integration over the entire length of the bar ($0$ to $L$), you retrieve

$$
\begin{equation}
u(L)=\frac{F}{E A}\int_0^L dY = \frac{FL}{EA}
\end{equation}
$$

where the displacement at L corresponds to the elongation $\delta$ (i.e., $u(L)=\delta$.)

Similar argument can be made about (1). It derives from the following expression for angle of twist $\theta$ at material particle X

$$
\begin{equation}
\theta(X)=\int_0^X \frac{T(Y)}{G(Y) J(Y)} dY.
\end{equation}
$$

When you take $T$, $G$, and $J$ to be constant along the shaft's length and take the integration from $0$ to $L$, you retrieve (1).

----------



| Materials      | $G ~(\rm{GPa})$ |
|----------------|-----------------|
| Steel          | 77             |
| Titanium alloy | 44             |




 <u> Problem 1 (10 pts) </u>

* Consider a solid cylindrical steel shaft of length 15 cm,  whose cross-section is a circle of diameter $2~\rm{cm}$. If the angle of twist at the right face is $\pi/3~\rm{rad}$, what is the torque applied to the shaft?
<br/>

<u> Problem 2 (10 pts) </u>

* Determine the angle of twist $\theta$ when the applied torque is $800~\rm{N \cdot m}$ in a $25~\rm{cm}$ long steel bar, whose cross section is a square with 3cm side.
<br/>

<u> Problem 3 (10 pts total) </u>
* (5 pts) (i) What is the ratio of Shear modulus $G$ of the materials of two shafts if the shafts are of the same size and their angle of twist are in the ratio 5/3 when subjected to equal torque?

* (5 pts) (ii) Determine the angle of twist $\theta$ (in degrees) in each of the bars if one is made of steel, the other is made of titanium alloy, and the applied torque is $240~\rm{N\cdot m}$. You can take $L/J = 2.0\times10^{8}~\rm{m^{-3}}.$
<br/>

<u> Problem 4 (15 pts total) </u>

* A $30~\rm{m}$ long shaft with a circular cross-sectional area of diameter $6~\rm{mm}$ is subjected to a torque of $T = 5~\rm{kN \cdot m}$. 

    * (10pts) (i) If the shaft gets twisted by 30&deg;, what is its shear modulus? 
    * (5pts)(ii) Now, consider that the shaft has an inner core of $3~\rm{mm}$ diameter as shown below. What is the percentage of the torque carried out by this inner core? You can assume that the core is also made out of the same material.
<br/>

<u> Problem 5 (15 pts total) </u>

* A $2~\rm{m}$ long shaft with a rectangular cross-section of sides $2~\rm{cm}$ and $3~\rm{cm}$ is subjected to a force couple as shown below. 

    * (5pts) (i) What is the torque $T$ acting on the shaft?    
    * (5pts) (ii) What is the shaft's polar moment of inertia $J$?
    * (5pts) (iii) If the shaft gets twisted by 30&deg;, what is its shear modulus?


<u> Problem 6 (20 pts total) </u>
* Consider a smaller steel shaft $AB$ attached to a larger steel shaft $BC$, and the torque acting at point $A$ as shown. 

    * (5pts) (i) What are the polar moment of inertia $J$ in shaft $AB$ and shaft $BC$ respectively?
    * (5pts) (ii) Determine the angle of twist at point $B$.
    * (5pts) (iii) Determine the angle of twist at point $A$.
    * (5pts) (iv) Now, consider a case where shaft $BC$ is made of titanium alloy instead of steel. What is the angle of twist at point $A$?



<u> Problem 7 (20 pts total) </u>
* Now, consider a similar problem but with two torques acting at points $A$ and $B$ as shown. 

    * (5pts) (i) What are torques acting in shaft $AB$ and shaft $BC$ respectively?
    * (5pts) (ii) Determine the angle of twist at point $B$.
    * (5pts) (iii) Determine the angle of twist at point $A$.
    * (5pts) (iv) Now, consider a case where shaft $BC$ is made of titanium instead of steel. What is the angle of twist at point $A$?


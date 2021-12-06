{% include mathjax_support %}
{% include command %}

# ENGN0310: Homework 9 (100 pts)
## Due Saturday 11:59 pm, December 11th, 2021

### Problem 1 (30pts total)
<!-- ![](2021-12-04-21-45-25.png) -->

Consider the geometry shown where $a=3~\rm{m}$ and $b=2~\rm{m}$ ($L=5~\rm{m}$). If the yield stress of the material is $180~\rm{MPa}$, what is the maximum force $F$ that can be applied without exceeding the yield stress? Assume that the beam has a $1~\rm{cm}\times1~\rm{cm}$ square cross-sectional area. You can approach this problem in the following step.

<br/>
    <center>
     <img src="HW9-fig1.png" alt="drawing" width="400"/>
    </center> 
<br/>

(a)(5pts) Find $M(X_1, \hat{\boldsymbol{E}_1})$ along the length of the beam in terms of $F$ and the reactions $R_A, R_B, M_0$ where $\boldsymbol{R_A}=-R_A\hat{\boldsymbol{E}_2}$, $\boldsymbol{R_B}=-R_B\hat{\boldsymbol{E}_2}$, and $\boldsymbol{M_0}=M_0\hat{\boldsymbol{E}_3}$.

(b)(10pts) Using 4 boundary conditions, solve the governing differential equation to find $y(X_1)$ (in terms of all or some of $E, I, F, R_A, R_B, M_0$).

(c)(5pts) There should be one more boundary condition that you have not yet utilized. Using this and the equilibrium conditions, solve for $R_A, R_B$, and $M_0$ in terms of $F$. 

(d)(10pts) Using the results above, find the maximum $F$ that can be applied without exceeding the yield stress.


<!-- 
ome new geometry: a design problems. What is the maximum force your can apply with out exceeding yield stress.  -->

### Problem 2 (30pts total)
Consider the simply supported beam shown below. If $F=20~\rm{kN}$ and the maximum allowable deflection of the beam is $2~\rm{mm}$, find the maximum $b$. Take $a=1~\rm{m}$, $E=200~\rm{GPa}$, and assume that the beam has a rectangular cross-sectional area where $h=100~\rm{mm}$ and its dimension in the $\hat{\boldsymbol{E}_3}$ direction is $50~\rm{mm}$.

<br/>
    <center>
     <img src="HW9-fig2.png" alt="drawing" width="400"/> 
    </center>
<br/>
<!-- 
![](2021-12-04-21-48-39.png)
![](2021-12-04-21-48-04.png) -->

(a)(10pts) Find the expression for deflection $y(X_1)$ in terms of $F, E, I, a, b$

(b)(10pts) Find the position $X_1$ at which the deflection is maximum (leave it in terms of $a, b$). 
>Hint: Consider two scenarios, (i) $a \leq b$ and (ii) $a \geq b$

(c)(10pts) Solve for the maximum allowable $b$ so that the deflection does not exceed $2~\rm{mm}$.

### Problem 3 (20pts total)

(a) (10pts) Prepare the shear force diagram and bending moment diagram for the configuration below, where $a=3~\rm{m}$, $b=2~\rm{m}$, and $\boldsymbol{M_0}=1500~\rm{N\cdot m} \hat{\boldsymbol{E}_3}$. 
 
<br/>
    <center>
     <img src="HW9-fig3a.png" alt="drawing" width="400"/>
    </center>
<br/>

(b)  (10pts) Prepare the shear force diagram and bending moment diagram for the configuration below, where $L=5~\rm{m}$ and $F=12~\rm{kN}$.

<br/>
    <center>
     <img src="HW9-fig3b.png" alt="drawing" width="400"/>
    </center>
<br/>


<!-- 

Geometries from 7.11 and 7.19 on pages 108-109
![](2021-12-04-21-53-21.png)
![](2021-12-04-21-53-36.png) -->


### Problem 4 (20pts total)

(a) (10pts) Which of the following two configurations are statically indeterminate? Explain why.

<br/>
    <center>
     <img src="HW9-fig4a.png" alt="drawing" width="600"/>
    </center>
<br/>


(b) (10pts) Repeat (a) for the following set of configurations.

<br/>
    <center>
     <img src="HW9-fig4b.png" alt="drawing" width="600"/>
    </center>
<br/> 
<!-- ![](2021-12-04-22-16-01.png) -->
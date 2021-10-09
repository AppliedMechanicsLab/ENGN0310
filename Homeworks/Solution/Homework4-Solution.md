{% include mathjax_support %}
{% include command %}



# ENGN0310: Homework 4 Solution


| Materials      | $G ~(\rm{GPa})$ |
|----------------|-----------------|
| Steel          | 77             |
| Titanium alloy | 44             |




<u> Problem 1 (10 pts) </u>

* Determine the angle of twist $\theta$ when the applied torque is $800~\rm{N \cdot m}$ in a $25~\rm{cm}$ long steel bar, whose cross section is a circle of $4~\rm{cm}$ diameter.
<br/>


   **Solution:**

   The polar moment of inertia [$J$ for a circular cross-section](../../CourseNotes/Torsion/Torsion-J.md) of radius $a$ can be calculated as 

   $$
   \begin{align*}
   J = \frac{\pi}{2}a^4
   \end{align*}
   $$

   Computing $J$ for $a = 2~\rm{cm}$ and simply plugging in $T=800~\rm{N \cdot m}$, $L=25~\rm{cm}$, and $G=77~\rm{GPa}$ for steel,

   $$
   \begin{align*}
   \theta&= \frac{T L}{J G}\\ 
   &= 0.0103347 ~\rm{rad}
   \end{align*}
   $$

   In degrees, $\theta =  0.592137^{\circ}$.
   


<u> Problem 2 (10 pts) </u>

* Consider a solid cylindrical steel shaft of length $15~\rm{cm}$,  whose cross-section is a circle of diameter $2~\rm{cm}$. If the angle of twist at the right face is $\pi/3~\rm{rad}$, what is the torque applied to the shaft?
<br/>

   **Solution:**

   Computing $J$ for $a = 1~\rm{cm}$ and simply plugging in $\theta=\pi/3$, $L=15~\rm{cm}$, and $G=77~\rm{GPa}$ for steel,

   $$
   \begin{align*}
   T&=\frac{G J \theta}{L}\\
   &=8.44~\rm{kN}

   \end{align*}
   $$

<u> Problem 3 (10 pts total) </u>
* (5 pts) (i) What is the ratio of Shear modulus $G$ of the materials of two shafts if the shafts are of the same size and their angle of twist are in the ratio 5/3 when subjected to equal torque?


* (5 pts) (ii) Consider two shafts of different diameters, one made of steel and the other made of titanium alloy. Determine the diameter of each shaft if for both shafts, the applied torque is $240~\rm{N\cdot m}$, length of the shaft is $6~\rm{m}$, and the angle of twist at the end face is $45^{\circ}.$
<br/>

   **Solution:**

   (i) Since $\theta$ is inversely proportional to $G$, the ratio of $G$ of the two materials are 3/5.

   (ii) We can solve for radius as
   
    $$
    \begin{align*}
    J &= \frac{T L}{G\theta} = \frac{\pi}{2}a^4\\
    a &= \sqrt[\leftroot{-3}\uproot{3}4]{\frac{2 TL} {\pi G\theta}}\\
    a &= \left(\frac{2 TL} {\pi G\theta}\right)^{1/4}
    \end{align*}
    $$

    Titanium alloy:

    $$
    \begin{equation*}
    \frac{\delta}{L}=\frac{\sigma}{E} = \frac{50~\rm{MPa}}{120~\rm{GPa}} = 4.16\times10^{-4}
    \end{equation*}
    $$


<u> Problem 4 (15 pts total) </u>

* A $8~\rm{m}$ long shaft with a circular cross-sectional area of diameter $6~\rm{cm}$ is subjected to a torque of $T = 5~\rm{kN \cdot m}$. 

    * (10pts) (i) If the shaft gets twisted by $30^{\circ}$, what is its shear modulus? 
    * (5pts)(ii) Now, consider that the shaft has an inner core of $3~\rm{cm}$ diameter as shown below. What is the percentage of the torque carried out by this inner core? You can assume that the core is also made out of the same material, and that the inner core undergo the same angle of twist ($30^{\circ}$ at the right end).

 <br/>
    <center>
     <img src="HW4_Prob4fig.png" alt="drawing" width="300"/>
    </center>
<br/>

<u> Problem 5 (15 pts total) </u>

* A $3~\rm{m}$ long shaft with a with a circular cross-sectional area of diameter $5~\rm{cm}$ is subjected to a force couple as shown below, where $F = 15~\rm{kN}$. 

    * (5pts) (i) What is the torque $T$ acting on the shaft?    
    * (5pts) (ii)  If the shaft gets twisted by $30^{\circ}$, what is its shear modulus?
    * (5pts) (iii))  Determine the angle of twist half-way along the length of the shaft.

 <br/>
    <center>
     <img src="HW4_Prob5fig_ver2.png" alt="drawing" width="300"/>
    </center>


<u> Problem 6 (20 pts total) </u>
* A smaller steel shaft $\rm{AB}$ of diameter $\rm{d_{AB}}= 50~\rm{mm}$ and length $\rm{L_{AB}}= 1~\rm{m}$ is attached to a larger steel shaft $\rm{BC}$ of diameter $\rm{d_{BC}}= 75~\rm{mm}$ and length $\rm{L_{BC}}= 2~\rm{m}$.  Consider the torque  $\boldsymbol{T}=T \hat{\boldsymbol{E}}_{\rm{a}}$, $T = 3~\rm{kN \cdot m} $ acting at $\rm{A}$ as shown. 

    * (5pts) (i) What are the polar moment of inertia $J$ in shaft $\rm{AB}$ and shaft $\rm{BC}$ respectively?
    * (5pts) (ii) Determine the angle of twist at point $\rm{B}$.
    * (5pts) (iii) Determine the angle of twist at point $\rm{A}$.
    * (5pts) (iv) If the shaft $\rm{BC}$ is made of titanium alloy instead of steel, what is the angle of twist at $\rm{A}$?

 <br/>
    <center>
     <img src="HW4_Prob6fig.png" alt="drawing" width="250"/>
    </center>



<u> Problem 7 (20 pts total) </u>
* Now, consider a similar problem but with two torques $T_A = 6~\rm{kN \cdot m}$ and $T_B =12~\rm{kN \cdot m}$ acting at $\rm{A}$ and $\rm{B}$ as shown. All other dimensions/quantities remain the same.

    * (5pts) (i) What are the torques acting in shaft $\rm{AB}$ and shaft $\rm{BC}$ respectively?
    * (5pts) (ii) Determine the angle of twist at point $\rm{B}$.
    * (5pts) (iii) Determine the angle of twist at point $\rm{A}$.
    * (5pts) (iv) If the shaft $\rm{BC}$ is made of titanium alloy instead of steel, what is the angle of twist at $\rm{A}$?
 
 <br/>
    <center>
     <img src="HW4_Prob7fig.png" alt="drawing" width="250"/>
    </center>


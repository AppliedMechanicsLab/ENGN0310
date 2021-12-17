{% include mathjax_support %}
{% include command %}

#### Problem 1. 

**Solution:**

By rotating the bar by $30^{o}$ we can get isolate the normal stress in the $\hat{\boldsymbol{E}}\_1$  direction and the shear stress in the $\hat{\boldsymbol{E}}\_2$, so then $\sigma_{max}A = P_{max} \sin{30^{o}}\Rightarrow P_{max} = \frac{(40~\rm MPa)(.0019 ~\rm m^2)}{\sin{30^{o}}} = 152~\rm kN$ and $\tau_{max}A = P_{max} \cos{30^{o}}\Rightarrow P_{max} = \frac{(15~\rm MPa)(.0019~\rm m^2)}{\cos{30^{o}}} = 32.9~\rm kN$. So the maximum value of $P$ is $32.9~\rm kN$ and failure in the weld will occur in shear. 

#### Problem 2. 


**Solution:**

(a)

$$\boldsymbol{\sigma} = \begin{pmatrix} 175~\rm MPa & 50 ~\rm MPa\\ 50~\rm MPa & -90~\rm MPa\end{pmatrix}$$

(b)

The scalar part of the normal component of the traction vector is $\sigma(\theta) = \sigma_{11}cos(\theta)^2 + \sigma_{22}sin(\theta)^2 + \sigma_{12}sin(2\theta)$. In order to determine where this function is maximized we need to set the derivative with respect to $\theta$ to $0$, so $100 \cos{2 \theta} - 530 \cos{\theta}\sin{\theta} = 0$, which will occur at $\theta = \{ -1.390~\rm rads,.180 ~\rm rads \}$ on the range from $\theta \in [-\frac{\pi}{2},\frac{\pi}{2}]$. PLugging these values back into the equation we find that the maximum is $\sigma(\theta = .180 ~\rm rads) = 184.12~\rm MPa$ and the minimum is $\sigma(\theta = -1.390~\rm rads) = -99.12~\rm MPa$. Note that $.180 ~\rm rads = 10.34^{o}$ and  $-1.390~\rm rads =-79.66^{o}$.

(c) 

The scalar part of the normal component of the traction vector is $\tau(\theta) = -\frac{\sigma_{11} - \sigma_{22}}{2}sin(2\theta) + \sigma_{12}cos(2\theta)$. In order to determine where this function is maximized we need to set the derivative with respect to $\theta$ to $0$, so $-265 \cos{2 \theta} - 100 \sin{2\theta} = 0$, which will occur at $\theta = \{-0.604~\rm rads, .966 ~\rm rads \}$ on the range from $\theta \in [-\frac{\pi}{2},\frac{\pi}{2}]$. Plugging these values back into the equation we find that the minimum is $\tau(\theta = .966~\rm rads) = -141.62 ~\rm MPa$ and the maximum is $\tau(\theta = -0.604~\rm rads) = 141.62~\rm MPa$. Note that $.966 ~\rm rads = 55.34^{o}$ and  $-0.604~\rm rads =-34.66^{o}$.

(d) 

The radius of the Mohr's Circle is $R = \sqrt{\left(\frac{\sigma_{11} - \sigma_{22}}{2}\right)^2 + \sigma_{12}^2} =141.62 ~\rm MPa$ and the center is $(C,0) = \left(\frac{\sigma_{11} + \sigma_{22}}{2} , 0\right) = \left(42.5~\rm MPa , 0\right)$.

#### Problem 3. 

**Solution:**

(1) From the definition we have that

$$
\breve{u}_i(X_1,X_2,X_3) = ((\lambda_{1} - 1)X\_{1}, (\lambda_{2} - 1)X\_{2}, (\lambda_{3} - 1)X\_{3})
$$

(2) Using the definition for writing the values of the strain tensor in terms of the displacement vector we get that 

$$\breve{\epsilon}_{ij}(X_1,X_2,X_3) = \begin{pmatrix} \lambda_{1} - 1 & 0 & 0\\ 0 & \lambda_{2} - 1 & 0 \\ 0 & 0 & \lambda_{3} - 1\end{pmatrix}$$

(3) Using the definition for writing the values of the stress tensor in terms of the strain tensor we get that 

$$\breve{\sigma}_{ij}(X_1,X_2,X_3) = \begin{pmatrix} 2\mu(\lambda_{1} - 1) + \lambda(\lambda_{1} + \lambda_{2} + \lambda_{3} - 3) & 0 & 0\\ 0 & 2\mu(\lambda_{2} - 1) + \lambda(\lambda_{1} + \lambda_{2} + \lambda_{3} - 3) & 0 \\ 0 & 0 & 2\mu(\lambda_{3} - 1) + \lambda(\lambda_{1} + \lambda_{2} + \lambda_{3} - 3)\end{pmatrix}$$

(4) Since we have that the traction vectors both the top and bottom faces are $0$, then we have that $\left[\breve{\boldsymbol{t}}(X_1,X_2,X_3;\hat{\boldsymbol{E}}_2)\right] = \boldsymbol{0}$ and $\left[\breve{\boldsymbol{t}}(X_1,X_2,X_3;\hat{\boldsymbol{E}}_3)\right] = \boldsymbol{0}$, so 

$$\left[\breve{\boldsymbol{t}}(X_1,X_2,X_3;\hat{\boldsymbol{E}}_2)\right]  = \breve{\sigma} \cdot \hat{\boldsymbol{E}}_2 = \begin{pmatrix} 0 \\ 2 \mu (-1 + \lambda_2) + \lambda (-3 + \lambda_1 + \lambda_2 + \lambda_3) \\ 0 \end{pmatrix} = \begin{pmatrix} 0 \\ 0 \\ 0 \end{pmatrix}$$

and 

$$\left[\breve{\boldsymbol{t}}(X_1,X_2,X_3;\hat{\boldsymbol{E}}_3)\right] = \breve{\sigma} \cdot \hat{\boldsymbol{E}}_3  = \begin{pmatrix} 0 \\ 0 \\ 2 \mu (-1 + \lambda_3) + \lambda (-3 + \lambda_1 + \lambda_2 + \lambda_3) \end{pmatrix} = \begin{pmatrix} 0 \\ 0 \\ 0 \end{pmatrix}$$

These equations should lead to the result that $\lambda_{2} - 1 = \lambda_{3} - 1 = \frac{\lambda - \lambda \lambda_ 1}{2 (\mu + \lambda)}$


(5) Then replacing $\lambda_{2} - 1$ and $\lambda_{3} - 1$ we have that 

$$\left[\breve{\boldsymbol{t}}(X_1,X_2,X_3;\hat{\boldsymbol{E}}_1)\right] = \breve{\sigma} \cdot \hat{\boldsymbol{E}}_1 = \begin{pmatrix} \frac{\mu  (2 \mu  + 3 \lambda) (-1 + \lambda_1)}{\mu + \lambda} \\ 0 \\ 0 \end{pmatrix}$$

(6) Since the integral $\int_{\Gamma(X_1)} \, d\Gamma = A(X_1)$, then we have that 

 $$\boldsymbol{F}(X_1,\hat{\boldsymbol{E}}_1) = \begin{pmatrix} \frac{A(X_1) \mu  (2 \mu  + 3 \lambda) (-1 + \lambda_1)}{\mu + \lambda} \\ 0 \\ 0 \end{pmatrix}$$

(7)  Using the defintions given for $\mu $ and $\lambda$ we have that $\frac{\mu  (2 \mu  + 3 \lambda) }{\mu + \lambda} = E$, so

$$\boldsymbol{F}(X_1,\hat{\boldsymbol{E}}_1) \cdot \hat{\boldsymbol{E}}_1 = F(X_1) = A(X_1) E(X_1) u'(X_1)$$



#### Problem 4. 


**Solution:**


(a) Solving for the reaction force and moment, both taken to be in the postive directions, we find that $R + 10~{\rm kN} + 2~{\rm m}(1~{\rm \frac{kN}{m}}) = 0 \Rightarrow R = -12~{\rm kN}$ and that $M + 10~{\rm kN}(1~{\rm m}) + 2~{\rm m}(1~{\rm \frac{kN}{m}})(3.5~{\rm m}) = 0 \Rightarrow M = -17~\rm kNm$. Then the moment in the first section of the bar, from $0 ~{\rm m}$ to $1~{\rm m}$, is given by $\boldsymbol{M}(X_1,\hat{\boldsymbol{E}}_1) + M \hat{\boldsymbol{E}}_3 - RX_1\hat{\boldsymbol{E}}_1 = \boldsymbol{0} \Rightarrow M(X_1) = (17 - 12X_1){\rm kNm}$. The moment in the second section of the bar, from $1 ~{\rm m}$ to $2.5 ~{\rm m}$, is given by $\boldsymbol{M}(X_1,\hat{\boldsymbol{E}}_1) + M \hat{\boldsymbol{E}}_3 - RX_1\hat{\boldsymbol{E}}_1 - 10~{\rm kN}(X_1 - 1~{\rm m})\hat{\boldsymbol{E}}_3 = \boldsymbol{0} \Rightarrow M(X_1) = (7 - 2X_1){\rm kNm}$. The moment in the third section of the bar, from $2.5 ~{\rm m}$ to $4.5~ {\rm m}$, is given by $\boldsymbol{M}(X_1,-\hat{\boldsymbol{E}}_1) + \frac{(4.5~{\rm m} - X_1)}{2}(4.5~{\rm m} - X_1)\hat{\boldsymbol{E}}_3 = \boldsymbol{0} \Rightarrow M(X_1) = \frac{1}{2}  (4.5~ {\rm m} - X_1)^2{\rm kNm}$.

$$M(X_1)({\rm kNm}) = \begin{cases}
17 - 12X_1  & ~ X_1 \leq 1 ~\rm m\\
7 - 2 X_1  & 1 ~{\rm m}\leq X_1 \leq 2.5 ~\rm m\\
\frac{1}{2}  (4.5~ {\rm m} - X_1)^2  & 2.5 ~{\rm m} \leq X_1
\end{cases}$$

![](FS2.PNG)

(b) The maximum value of $M(X_1)$ from $0 ~{\rm m}$ to $4.5 ~{\rm m}$ is $17kNm$ at $0 ~{\rm m}$. Since its positve the value of $X_2$ that will maximize the stress is clearly $\frac{h}{2}$. $I = \frac{h^4}{12}$ for this cross section. $\sigma_{max} = \frac{M_{max}\frac{h}{2}}{I} = \frac{(17~\rm kNm)(.0125~\rm m)}{3.255 \times 10^{-8} ~\rm m^4} = 6528 ~\rm MPa$.


#### Problem 5. 


**Solution:**


(a) Assuming that the reaction forces are all pointing in the positive directions, and $A$ is taken to be the pin on the left hand side, then $R_A + R_B + F = 0$ and $3LR_B + 2LF + M = 0$ leads to $R_A = \frac{M - FL}{3L}$ and $R_B = \frac{-2FL - M}{3L}$.

(b) Taking the first imaginary cut in the range $x\in(0,L)$ and removing the right side then we have that $\boldsymbol{M}(X_1,\hat{\boldsymbol{E}}_1) - X_1 R_A\hat{\boldsymbol{E}}_3 = \boldsymbol{0} \Rightarrow M(X_1) = X_1\left( \frac{M - FL}{3L}\right) $. Taking the second imaginary cut in the range $x\in(L,2L)$ and removing the right side then we have that $\boldsymbol{M}(X_1,\hat{\boldsymbol{E}}_1) + M\hat{\boldsymbol{E}}_3 - X_1 R_A\hat{\boldsymbol{E}}_3 = \boldsymbol{0} \Rightarrow M(X_1) = X_1\left( \frac{M - FL}{3L}\right) - M$. Taking the third imaginary cut in the range $x\in(2L,3L)$ and removing the left side then we have that $\boldsymbol{M}(X_1,-\hat{\boldsymbol{E}}_1) +(3L -  X_1) R_B\hat{\boldsymbol{E}}_3 = \boldsymbol{0} \Rightarrow M(X_1) =(3L - X_1)\left( \frac{-2FL - M}{3L} \right)$.



$$M(X_1) = \begin{cases}
X_1\left( \frac{M - FL}{3L}\right)  &  X_1 \leq  L\\
X_1\left( \frac{M - FL}{3L}\right) - M &  L \leq X_1 \leq 2  L\\
(3L - X_1)\left( \frac{-2FL - M}{3L} \right)  & 2  L \leq X_1
\end{cases}$$

(c) Integrating the moment equation twice we get that  

$$EIy(X_1) = \begin{cases}
c_{12} + c_{11} X_1 + \frac{(-F L + M) X_1^3}{18 L}  &  X_1 \leq  L\\

c_{22} + c_{21} X_1 - \frac{X_1^2 (9 L M + F L X_1 - M X_1)}{18 L} &  L \leq X_1 \leq 2  L\\

c_{32} + c_{31} X_1 + \frac{X_1^2 (2 F L + M) (-9 L + X_1)}{18 L} & 2L \leq X_1
\end{cases}$$

Then applying the six boundary conditions, $y_1(0) = 0$, $y_3(3L) = 0$, $y_1(L) = y_2(L)$, $y_1'(L) = y_2'(L)$, $y_3(2L) = y_3(2L)$, and $y_2'(2L) = y_3'(2L)$ then solving for the costants we get that 
$c_{11} = \frac{1}{18} (8 F L^2 + 3 L M)$,$ c_{12} = 0$ , $ c_{21} = \frac{1}{18} (8 F L^2 + 21 L M)$ , $c_{22} = -\frac{(L^2 M)}{2}$ , $c_{31} = \frac{1}{18} (44 F L^2 + 21 L M)$ , and $c_{32} = \frac{1}{6} (-8 F L^3 - 3 L^2 M)$. Then plugging in the values for the constants into the displacement equation we get that 


$$EIy(X_1) = \begin{cases}
\frac{X_1}{18L}(8 F L^3 + 3 L^2 M - F L X_1^2 + M X_1^2)  &  X_1 \leq   L\\

\frac{1}{18L} (21 L^2 M X_1 + M X_1^3 - LX_1^2 (9 M + F X_1) + L^3 (-9 M + 8 F X_1)) &  L \leq X_1 \leq 2  L\\

-\frac{1}{18L} (3 L - X_1) (L^2 (8 F L + 3 M) - 6 L (2 F L + M) X_1 + (2 F L + M) X_1^2)  & 2  L \leq X_1
\end{cases}$$


#### Problem 6. 


**Solution:**

Assuming that $A$ is the left hand side and the reaction forces/moments are pointing in the positive direction then the force and moment balances give us the equations $R_A + R_B + F = 0$ and $M_A + M_B + aF + (a + b)R_B = 0$. Since this bar is statically indeterminant we need to solve for the displacement and apply the extra two boundary conditions in order to get the final two equations necesary to solve for the reaction forces/moments. Doing an imaginary cut for $X_1 \in (0 , a)$ and removing the right side and doing a moment balance around the cut face we get that $\boldsymbol{M}(X_1,\hat{\boldsymbol{E}}_1) - X_1 R_A\hat{\boldsymbol{E}}_3 + M_A\hat{\boldsymbol{E}}_3 = \boldsymbol{0} \Rightarrow M(X_1) = X_1 R_A - M_A$. Doing an imaginary cut for $X_1 \in (a , a + b)$ and removing the right side and doing a moment balance around the cut face we get that $\boldsymbol{M}(X_1,\hat{\boldsymbol{E}}_1) - X_1 R_A\hat{\boldsymbol{E}}_3 + M_A\hat{\boldsymbol{E}}_3 - (X_1 - a) F\hat{\boldsymbol{E}}_3 = \boldsymbol{0} \Rightarrow M(X_1) = X_1 R_A + (X_1 - a) F - M_A$. 

$$M(X_1) = \begin{cases}
X_1 R_A - M_A  &  X_1 \leq a\\

X_1 R_A + (X_1 - a) F - M_A & a \leq X_1 \\

\end{cases}$$


Integrating twice we get that 

$$EIy(X_1) = \begin{cases}
c_{12} + c_{11} X_1 + \frac{1}{6} X_1^2 (-3 M_A + R_A X_1)  &  X_1 \leq a\\

c_{22} + c_{21} X_1 +\frac{1}{6} X_1^2(-3 (a F + M_A) + (F + R_A) X_1) & a \leq X_1 \\

\end{cases}$$

Applying the first four boundary conditions, $y_1(0) = 0$, $y_1'(0) = 0$, $y_1(a) = y_2(a)$, and $y_1'(a) = y_2'(a)$ then solving for the constants we find that $c_{11} = 0$ ,$ c_{12} = 0$ , $c_{21} = \frac{a^2 F}{2}$, and $c_{22} = -\frac{a^3 F}{6}$. So then 


$$EIy(X_1) = \begin{cases}
\frac{1}{6} X_1^2 (-3 M_A + R_A X_1)  &  X_1 \leq a\\

\frac{1}{6} (-a^3 F + 3 a^2 F X_1 + X_1^2 (-3 (a F + M_A) + (F + R_A) X_1)) & a \leq X_1 \\

\end{cases}$$

Then to get our other two equations to find the reaction forces/moments we apply our final two boundary conditions, $y_2(a + b) = 0$ and $y_2'(a + b) = 0$ to get that $b^3 F - 3 a^2 M_A - 3 b (2 a + b) M_A + (a + b)^3 R_A = 0$ and $b^2 F - 2 a M_A - 2 b M_A + (a + b)^2 R_A = 0$. Then using these two equations and our force and moment balance equaitons, $R_A + R_B + F = 0$ and $M_A + M_B + aF + (a + b)R_B = 0$, we find that $R_A = -\frac{3 a b^2 F + b^3 F}{(a + b)^3}$,  $R_B = -\frac{a^3 F + 3 a^2 b F}{(a + b)^3}$, $ M_A = -\frac{a b^2 F}{(a + b)^2)}$ and, $ M_B = \frac{a^2 b F}{(a + b)^2}$. Plugging these reaction force/moment values into our equation for the moment we get that 

$$M(X_1) = \begin{cases}
\frac{b^2 F (a (a + b) - (3 a + b) X_1)}{(a + b)^3}  &  X_1 \leq  \rm a\\

-\frac{a^2 F (a^2 + 3 a b + 2 b^2 - (a + 3 b) X_1)}{(a + b)^3} & \rm{a} \leq X_1 \\

\end{cases}$$

Plugging these reaction force/moment values into our equation for the displacement we get that

$$EIy(X_1) = \begin{cases}
\frac{b^2 F X_1^2 (3 a (a + b) - (3 a + b) X_1)}{6 (a + b)^3}  &  X_1 \leq  \rm a\\

-\frac{a^2 F (a + b - X_1)^2 (a (a + b) - (a + 3 b) X_1)}{6 (a + b)^3)} & \rm{a} \leq X_1 \\

\end{cases}$$
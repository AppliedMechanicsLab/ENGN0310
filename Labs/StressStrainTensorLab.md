{% include mathjax_support %}
{% include command %}

# Lab2: Stress-strain measuring lab


## 1. Introduction and objective
Stress/strain tensors are concepts that help us describe the stress state and deformation  of the material.

<!-- , much like how in 1D-case of a bar under uniaxial tension, we were able to fully describe its state through essentially two values, stress ($\frac{F}{A})$ and mean strain ($\frac{\delta}{L}$).

___
Note that we call $\frac{\delta}{L}$ "mean strain" due to the following reason:

You've learned in class the definition of strain, for instance on face whose outward normal is $\hat{\boldsymbol{E}}_1$ and in direction  $\hat{\boldsymbol{E}}_1$, as

$$
\epsilon_{11}=\frac{\partial u_{1}}{\partial x_{1}}
$$

If we assume that the displacement field is given by 

$$
u_{1}=
$$
___

Now recall that in 1D-case, we only needed Young's modulus to relate $\frac{F}{A}$ to $\frac{\delta}{L}$. How do we relate stress tensor to strain tensor?  -->

To describe the relation between stress and strain tensors, we need two material properties. You are already familiar with the Young's modulus $E$. We will now introduce another material property, Poisson's ratio, which is a measure of the deformation of a material in a direction perpendicular to specific loading.


In this lab, you will be given a silicone strip with three squares drawn on it, as shown below. We will put this under uni-axial tension to 1) become familiar with the concept of stress/strain tensors, and 2) see and measure the Poisson's effect in action.

<img src="SiliconeStrip.png" alt="drawing" width="250"/>
<img src="Schematic-01.png" alt="drawing" width="220"/>

For the purpose of this lab, don't worry about the angled (dotted) square. Just focus on the largest (red) and the smallest (blue) one.




Through tensile test and image analysis, you will find the
1. Stress field
2. Strain field
3. Young's modulus
4. Poisson's ratio

of the silicone strip.

<br>

## 2. Location 

Brown Design Workshop 


## 3. Theory

Stress components are related to strain components as
<img src="Stress-StrainTensor1.png" alt="drawing" width="500"/>

This is equivalent to writing

<img src="Stress-StrainTensor2.png" alt="drawing" width="380"/>


Don't worry if this looks complicated.
When the dimension of the material is much smaller in one direction compared to others, the stress in that direction is negligible compared to those in the other two directions. In such case, you can assume a plane-stress condition, in which you can take $\sigma_{13}=\sigma_{23}=\sigma_{33}=0$. 

Under this assumption, the stress tensor-strain tensor relationship can be simplified to:


$$
\begin{bmatrix}
\sigma_{11} \\
\sigma_{22}\\
\sigma_{12}
\end{bmatrix}

=
\frac{E}{1-\nu^2}
\begin{bmatrix}
1 & \nu & 0 \\
\nu & 1 &  0 \\
0 & 0 & 1-\nu
\end{bmatrix}

\begin{bmatrix}
\epsilon_{11} \\
\epsilon_{22} \\
\epsilon_{12} 
\end{bmatrix}
$$

and 

$$
\begin{bmatrix}
\epsilon_{11} \\
\epsilon_{22} \\
\epsilon_{12} 
\end{bmatrix}

=
\frac{1}{E}
\begin{bmatrix}
1 & -\nu & 0 \\
-\nu & 1 &  0 \\
0 & 0 & 1+\nu
\end{bmatrix}

\begin{bmatrix}
\sigma_{11} \\
\sigma_{22}\\
\sigma_{12} 
\end{bmatrix}
$$

$$
\epsilon_{33}=\frac{-\nu}{E}(\sigma_{11}+\sigma_{22})
$$


where $E$ is Young's modulus, and $\nu$ is the Poisson's ratio. You will obtain both $E$ and $\nu$ from the experiment.

<br>

## 4. Equipment and Materials

1. Instron 500N 5942 testing machine
2. Silicone strip
    * Length:
    $150~\rm mm$ 
    * Width: $2.54~\rm mm$
    * Thickness: $3.175 \rm mm$
    * Young' Modulus: $1-5~\rm MPa$
    * Poisson's ratio $0.48-0.495$
3. Phone
4. Others: vernier caliper and regular ruler.

    (All materials/equipments will be provided except for the phone)

<br>   

## 5. Experimental Procedure 

### <b> Steps :  </b>

  (a) You will each be given a silicone strip. Measure its length, width, and thickness using the vernier caliper and the ruler provided.

  (b) Clamp the ends of the strip to the Instron machine.
  
  (c) Set up the Instron machine for tensile  testing at displacement rate of $10~\rm mm/min$ (see [operation of Instron](Instron.md)).

  (d) Using the camera provided, take a picture of the strip before starting the tensile test. Make sure you don't move the camera until after you finish taking picture of the deformed strip in the next step.

  (d) Start test, and take the picture of the strip at $10~\rm N$.

  <center>
  <img src="Initial.png" alt="drawing" width="600"/>
</center>

  

<center>
  <img src="Final.png" alt="drawing" width="600"/>
</center>

<br>
<br>

## 6.1 Tasks and Analysis -Large square-
The objective is to describe the stress/strain field of the region specified by the large square, and to find material properties of the silicone strip. In completing Task 6.1, you can assume that the stress/strain field is uniform everywhere within the large square, so that a single stress/strain tensor can be used to describe all points within the large square.

### <b> Task 1A: Compute each component of stress tensor </b>
As discussed in Theory section, we can take $\sigma_{13}=\sigma_{23}=\sigma_{33}=0$. What are the values of the remaining components,  $\sigma_{11}, \sigma_{12}$, and $\sigma_{22}$? 
>Hint: You can take $\sigma_{12}=0$ and $\sigma_{22}=0$. Can you explain why?

<br>
 

### <b> Task 2A: Find the values of $\epsilon_{11}$ and $\epsilon_{22}$. </b>
Use ImageJ to analyze the deformation, as you've done before in the previous lab. What are the values of $\epsilon_{11}$ and $\epsilon_{22}$? Note that $\epsilon_{12}=0$. Explain why. 

***
Now you will find the material properties of the sample
***
### <b> Task 3A:  Compute Young's modulus </b>
Compute Young's modulus from the $\epsilon_{11}$ measurement. Remember that when we take $\sigma_{22}=0$,

$$
\epsilon_{11}=\frac{\sigma_{11}}{E}
$$



### <b> Task 4A:  Compute Poisson's ratio </b>
You can do this by noticing that when $\sigma_{22}=0$,

$$
\epsilon_{22}=-\nu\frac{\sigma_{11}}{E}
$$

In general, rubber is considered a nearly incompressible material, meaning its Poisson ratio values is very close to 0.5. Is the value from your experiment close to 0.5?

### <b> Task 5A:  Complete the strain tensor </b>
Is there any other non-zero component of the strain tensor that you have not considered yet? Compute any that you think should be non-zero using the stress-strain relation given above in the Theory section.

<br>

## 6.2 Tasks and Analysis -Small square-

***
You will now compute the stress/strain tensor components for the small square. 

In the above analysis with a larger square, the assumption was that the stress/strain field was uniform within the square, so that any point on the square could be described by a single stress tensor/strain tensor.



Now, we'll be more precise and notice that this assumption of stress/strain field being uniform -in particular the assumption that $\sigma_{22}=0$ everywhere on the large square-- is unlikely. We will take a smaller region within the larger square as a representative region whose stress/strain field differs from what we derived earlier from the larger square. You can assume that the stress/strain field is uniform within the smaller region (small square).
***

### <b> Task 1B: Find the values of $\epsilon_{11}$ and $\epsilon_{22}$. </b>
Use ImageJ to analyze the deformation and find $\epsilon_{11}$, and $\epsilon_{22}$. Note that you can take $\epsilon_{12}=0$ since the assumption that $\sigma_{12}=0$ still holds.
<br>
 

### <b> Task 2B:  Stress tensor components and $\nu$ </b>
The assumption $\sigma_{13}=\sigma_{23}=\sigma_{33}=0$ is still valid. 

* We will now assume that $\sigma_{22}$ is a non-zero value. Write a sentence or two on why this might be reasonable assumption to take for the case of a small square (you won't get points taken off for not getting this).

* Now take $E$ computed in Task 3A as the true value. With this and from the relations 

$$
\begin{align*}
\sigma_{11}&=\frac{E}{1-\nu^2}(\epsilon_{11}+\nu\epsilon_{22})\\
\sigma_{22}&=\frac{E}{1-\nu^2}(\nu\epsilon_{11}+\epsilon_{22})
\end{align*}
$$

Find the values of $\sigma_{22}$ and $\nu$. How does the value of $\nu$ compare to what you found in Task 4A? If you find a significant difference, what do you think led to the difference despite that $\nu$ is supposed to be a material property, whose value is expected to remain the same everywhere on the material?


### <b> Task 3B:  Rest of the strain tensor components </b>
Are there any non-zero components of the strain tensor that has not been considered yet? Compute the values if there is any.


<br>

## 7. Lab report guidelines
1. The lab report should be written as a single, professional-prepared document for each student. 
Please organize your report using the structure given on the next Section: Lab report organization. 
Please use International System of Units (SI), for example using meter and kilogram instead of inch and pounds.

2. There should be a **cover page** that contains the title of the lab, name of the author, name of the group members, date, and the name of the class. 

3. **Plots should look professional**. There should be no auto-generated Excel plots. Any figures should have a caption explaining the purpose of the figure and labeled axes with units, all in readably large text. Specific things to avoid are shadow on line plots, having grid lines on only one axis, and unnecessary overuse of color. Points will be deducted if your plots do not look professional. 

4. Tabulated raw data should be included in the appendices, not in the body of the report. Additional figures not essential to the body of the report may be included in the appendices as well. Make sure to cite (refer to) every picture (appendix and body alike) in your report.

5. A good resource for lab report preparation is the Mayfield Handbook of Technical and Scientific Writing (https://www.mit.edu/course/21/21.guide/).
<!--(http://www.mhhe.com/mayfieldpub/tsw/home.htm)-->

6. Lab reports should be submitted electronically on Canvas in PDF format. No paper reports will be accepted.

<br>

## 8. Lab report organization 

1. **Introduction**: Write a brief statement describing the purpose of the lab.

2. **Methods and Materials**: Describe the experimental setup and procedural details for the experiment.

3. **Results and Discussion**: Answer all questions in the tasks and comment on the associated theoretical aspect. 

4. **Conclusion**: Write a brief statement describing your conclusions and what you learned in the lab.

5. **Appendices**: Include tables of your raw data, detailed calculations, and other information/figures that you deem pertinent but non-essential to the body of your report.


<br>

## [9. Lab calendar](https://calendar.google.com/calendar/embed?src=c_ftk0rj4uauudpfmcmm22plq5ig%40group.calendar.google.com&ctz=America%2FNew_York)

<iframe src="https://calendar.google.com/calendar/embed?src=c_ftk0rj4uauudpfmcmm22plq5ig%40group.calendar.google.com&ctz=America%2FNew_York" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>


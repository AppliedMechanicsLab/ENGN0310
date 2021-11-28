{% include mathjax_support %}
{% include command %}


## Structural mechanics

### <span style="color:#5faeb6; font-style:italic">Bars </span>

*  <span style="color:#3f6184; font-weight:normal"> Bars with constant cross-section </span>
    * [<span style="color:#3f6184">Force-displacement law for the case of constant cross-sectional area</span>](Bars/Bars.md)
    * [<span style="color:#3f6184">Force-displacement law in vector form</span>](./Bars/VectorFormHookesLaw.md)
    * Displacement field
        - [Definition. What is a displacement field?](Bars/Bars2.md)
        - [Explicit expression for the case of constant cross-section](Bars/Bars3.md)
* Bars with variable cross-section 
    * [Two springs in series](./Bars/SpringsInSeries.md)
    *   [Force-displacement law for the case of Variable cross-sectional area](Bars/Bars4.md)
    -  [Explicit expression for the case of variable cross-section](Bars/Bars5_2.md)
    -  [<span style="color:#5faeb6; font-style:italic">Solved problem: Titanium&Steel stepped composite bar (with downloadable Mathematica file)</span> ](./Bars/SegmentedComposite.md)
    -  [ <span style="color:#5faeb6; font-style:italic"> Solved problem: Titanium&Steel stepped composite bar with two forces (with downloadable Mathematica file) </span>](./Bars/SegmentedComposite2.md) 
* [Bars with both cross-sectional area and material property varying along their length](Bars/Bars6.md)
    -   [<span style="color:#5faeb6; font-style:italic"> Solved problem: Truncated cone (with downloadable Mathematica file) </span>](./Bars/TruncatedCone.md) 
* Bars with body force
  -  [Most general version of the constitutive law for the bar](Bars/BodyForce1.md)
  -   [Equilibrium in 1D](Bars/BodyForce2.md)
    -  [<span style="color:#5faeb6; font-style:italic">Solved Problem: A free hanging bar with constant area</span>](Bars/HangingBar1.md)
    -  [<span style="color:#5faeb6">_Solved Problem: A free hanging bar with constant area and end force_</span>](Bars/HangingBar3.md) <!--:#778899-->
    - :construction::construction: [_Solved Problem: A free hanging bar with variable area_](Bars/HangingBar2.md)     
* Thermal expansion
    *  [Constitutive law](./Bars/ThermalExpansion1.md)
    *  [<span style="color:#5faeb6; font-style:italic">Solved problem 1</span>](./Bars/ThermalStressesSP1.md)
    *   [<span style="color:#5faeb6; font-style:italic">Solved problem 2 (with downloadable Mathematica file)</span>](./Bars/ThermalStressesSP2.md)
    *   [<span style="color:#5faeb6; font-style:italic">Solved problem 3 (with downloadable Mathematica file)</span>](./Bars/ThermalStressesSP3.md)
    *  [<span style="color:#5faeb6; font-style:italic">Solved problem 4</span>](./Bars/ThermalStressesSP4.md)
* Tensegrity
*  [Stress Concentrators in Bars](Bars7.md)

### <span style="color:#5faeb6; font-style:italic">Shafts (Torsion)</span>

@@include[TorsionToC.md](includes/TorsionToC.md)

    

 ### <span style="color:#5faeb6; font-style:italic">Beams </span>
* :construction::construction: [Definitions of moments on a cross-section. Definition of $\boldsymbol{M}(X_1,\hat{\boldsymbol{E}}_1)$, and $\boldsymbol{M}(X_1,-\hat{\boldsymbol{E}}_1)$](Beams/MomentsOnCrosssection.md)
* :construction::construction: [Proof of $\boldsymbol{M}(X_1,\hat{E}_1)=-\boldsymbol{M}(X_1,-\hat{E}_1)$](Beams/MomentsOnCrosssection.md)
* [Deflected shape](Beams/Beams1.md)
    * [Solved problem: beam loaded with end moment](Beams/EndMoment.md) 
* [Deflected shape with body forces](Beams/Beams2.md)
* [Internal stresses](Beams/Beams3.md)
* [Flextural strength](Beams/Beams4.md)

## Solid Mechanics

### Traction

* [Introduction](Traction/Introduction.md)
* [Matrix representation of Traction vectors](Traction/TractionsInBars.md)
* [Normal and shear components of the traction vector](Traction/NormalShearComponents.md)
* [Shear tractions](Traction/ShearTraction1.md)
* [Maximum Normal and Shear Stresses in an Axially Loaded Bar](Traction/Max.md)
* [Solved Problems](Traction/SPTraction.md)

### Stress

* :construction::construction: [Traction corresponding to a stress tenor](Stress/Traction.md)
* :construction::construction: [Shear and traction component of the traction vector given a stress tensor](Stress/Stress2.md)
* :construction::construction: [Matrix representation of the normal component of the traction vector in plane stress](Stress/Stress3.md) 
* :construction::construction: [Maximum normal stress](Stress/Stress4.md)
* :construction::construction: [Matrix representation of the shear component of the traction vector in plane stress](Stress/Stress5.md) 
* :construction: [Maximum shear stress](Stress/Stress6.md)
* :construction: :construction: [Mohr circle](Stress/Stress7.md)


### Strain

* [Strain definition](Strain/Strain1.md)

### Hooke's Law



## Appendix

### Mathematical analysis results

*  [Proof of  $ \lim_{\epsilon\to 0}\frac{1}{\epsilon}\int_{a}^{a+\epsilon}f(\xi)\, d\xi=f(a)$](Bars/Leibnitz.md)

### Notation
    
* [Kronecker delta symbol](https://appliedmechanicslab.github.io/appliedmechanicslab/course_notes/ENGN1370/KroneckerDeltaSymbol.html)
* [Einstein summation convention](https://appliedmechanicslab.github.io/appliedmechanicslab/course_notes/ENGN1370/ESC.html)

{% include mathjax_support %}
{% include command %}


## Structural mechanics

### Bars 

*  Bars with constant cross-section
    * [Force-displacement law for the case of constant cross-sectional area](Bars/Bars.md)
    * [Force-displacement law in vector form](./Bars/VectorFormHookesLaw.md)
    * Displacement field
        - [Definition. What is a displacement field?](Bars/Bars2.md)
        - [Explicit expression for the case of constant cross-section](Bars/Bars3.md)
* Bars with variable cross-section 
    * [Two springs in series](./Bars/SpringsInSeries.md)
    *   [Force-displacement law for the case of Variable cross-sectional area](Bars/Bars4.md)
    * Displacement field
        -  [Explicit expression for the case of variable cross-section](Bars/Bars5_2.md)
    -  [Solved problem: Titanium&Steel stepped composite bar (with downloadable Mathematica file)](./Bars/SegmentedComposite.md)
    -  [Solved problem: Titanium&Steel stepped composite bar with two forces (with downloadable Mathematica file)](./Bars/SegmentedComposite2.md) 
* [Bars with both cross-sectional area and material property varying along their length](Bars/Bars6.md)
    -   [Solved problem: Truncated cone (with downloadable Mathematica file)](./Bars/TruncatedCone.md) 
* Bars with body force
  -  [Most general version of the constitutive law for the bar](Bars/BodyForce1.md)
  -   [Equilibrium in 1D](Bars/BodyForce2.md)
    -  [Solved Problem: A free hanging bar with constant area](Bars/HangingBar1.md)
    -  [Solved Problem: A free hanging bar with constant area and end force](Bars/HangingBar3.md) <!--:#778899-->
    <!-- - :construction::construction: [_Solved Problem: A free hanging bar with variable area_](Bars/HangingBar2.md)      -->
* Thermal expansion
    *  [Constitutive law](./Bars/ThermalExpansion1.md)
    *  [Solved problem 1](./Bars/ThermalStressesSP1.md)
    *   [Solved problem 2 (with downloadable Mathematica file)](./Bars/ThermalStressesSP2.md)
    *   [Solved problem 3 (with downloadable Mathematica file)](./Bars/ThermalStressesSP3.md)
    *  [Solved problem 4](./Bars/ThermalStressesSP4.md)
*  [Stress Concentrators in Bars](Bars7.md)

### Shafts (Torsion)

 *  [Torsion introduction](./Torsion/Torsion1.md)
 * [Solved Problem 1 (with downloadable Mathematica file)](./Torsion/SP1.md)
 * [Solved Problem 2 (with downloadable Mathematica file)](./Torsion/SP2.md)
 * [Solved Problem 3 (with downloadable Mathematica file)](./Torsion/SP3.md)
 * [Solved Problem 4 (with downloadable Mathematica file)](./Torsion/SP4.md)
 * [Solved Problem 5 (with downloadable Mathematica file)](./Torsion/SP5.md)
 * [Solved Problem 6 (with downloadable Mathematica file)](./Torsion/SP6.md)
 * [Solved Problem 7 (with downloadable Mathematica file)](./Torsion/SP7.md)
 * [Solved Problem 8](./Torsion/SP8.md)


    

### Beams 
* [Notation for cross-sections and surfaces](Beams/CrossSectiosnSurfacesDef.md)
* [Definitions of moments on a cross-section](Beams/MomentsOnCrosssection.md)
<!-- *  :construction: :construction: [Equality of two cross-sectional moments if the beam region between those cross-sections is free of any applied/external moments and forces](Beams/ConstancyOfMoments.md)    -->
*  [Proof of $\boldsymbol{M}(X_1,\hat{E}_1)=-\boldsymbol{M}(X_1,-\hat{E}_1)$](Beams/MomentsThirdLaw.md)
* Moments along the length of the beam
    * [Cantilever loaded with end moment](Beams/EndMomentMoment.md)
    * [Cantilever loaded with end force](Beams/EndForceCantilever.md)     
* [Deflected shape](Beams/Beams1.md)
    *  [Cantilever loaded with end moment](Beams/EndMomentShape.md) 
    * [Cantilever loaded with end force](Beams/EndForceShape.md) 
    * [Deflected shape with distributed load](Beams/SSBUniformDistribution.md)
    * [SSB point load](Beams/SSBPointLoad.md)


### Columns 

* [Introduction to elastic instabilities](./Buckling/Buckling1.md)

<!-- * [Column buckling: pin-pin joints](./Buckling/Buckling2.md)
* [Column buckling: anchored-pin joints](./Buckling/Buckling2.md) -->

## Solid Mechanics

### Traction

* [Introduction](Traction/Introduction.md)
* [Matrix representation of Traction vectors](Traction/TractionsInBars.md) 
* [Normal and shear components of the traction vector](Traction/NormalShearComponents.md)
<!-- * [Shear tractions](Traction/ShearTraction1.md) -->
* [Maximum Normal and Shear Stresses in an Axially Loaded Bar](Traction/Max.md)
* [Solved Problems](Traction/SPTraction.md)

### Stress

*  [Traction corresponding to a stress tenor](Stress/Traction.md)
* [Normal and Shear component of the traction vector given a stress tensor](Stress/Stress2.md)
* [Matrix representation of the normal component of the traction vector in plane stress](Stress/Stress3.md) 
* [Maximum and minimum normal stress](Stress/Stress4.md)
* [Matrix representation of the shear component of the traction vector in plane stress](Stress/Stress5.md) 
* [Maximum shear stress](Stress/Stress6.md)
* [Mohr circle](Stress/Stress7.md)


### Strain

* [Strain definition](Strain/Strain1.md)




## Appendix

### Mathematical analysis results

*  [Proof of  $ \lim_{\epsilon\to 0}\frac{1}{\epsilon}\int_{a}^{a+\epsilon}f(\xi)\, d\xi=f(a)$](Bars/Leibnitz.md)

### Notation
    
* [Kronecker delta symbol](https://appliedmechanicslab.github.io/appliedmechanicslab/course_notes/ENGN1370/KroneckerDeltaSymbol.html)
* [Einstein summation convention](https://appliedmechanicslab.github.io/appliedmechanicslab/course_notes/ENGN1370/ESC.html)


<!-- <span style="color:#5faeb6; font-style:italic">Solved problem 1</span> -->
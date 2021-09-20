
# Lab1: Uniaxial tensile testing lab

## 1. Introduction and objective
The design of material of structures so that they function properly requires an understanding of the mechancial behavior of the materials being used. Generally, to determine how materials behave when they are subjected to loads, we perform experiments using testing machines (see the figure below). 
The usual procedure is to take a small specimen of the material, put the specimen in testing machines, apply the loads, and then measure the deformations(like the changes in length and diameters).

<img src="Instron.jpeg" alt="drawing" width="600"/>

In this lab, we will test the mechancial behavior of the materials via uniaxial tensile testing. We will test the rubber rods with different length and area ( see schematics below).

<img src="lab1rod.jpeg" alt="drawing" width="600"/>


Through the lab, we are going to answer:
1. how does the length of the specimen change when applying different loads?

2. how to determine the strain of a point of the specimen? and how the strain of a point relates to the corresponding displacement?

3. For specimens of the same material but in different geometry, will they have the same mechanical behaviors?


## 2. Location
Brown Design Workshop

## 3. Theory
* [Hooke's law for the bar](../CourseNotes/Bars/Bars.md)

* [Displacement field within the bar](../CourseNotes/Bars/Bars3.md)

## 4. Equipment and Materials

1. Instron 500N 5942 testing machine
2. Buna-N rubber cord
    * Length:
    $100, 150, 200~\rm mm$ 
    * Diameter: $6.35, 9.525, 12.7~\rm mm$
    * Young' Modulus: $4~\rm MPa$
    * Tensile strength: $4.9987~\rm MPa$
3. Recording system: phone and tripod


## 5. Experimental setup and data analysis

### Task 1: Measure the force and the displacement of a rubber bar under uniaxial tensile testing (the whole steps see illustration below)

#### Steps
  (a) Choose the rubber bar of length of $150 ~\rm mm$ and diameter of $9.525 ~\rm mm$.

  (b)Clamp the two bar ends follwing the marks on the bar using the fixture.

  (c) Proceed to load with specific displacement at $3, 6, 9, 12, 15, 18, 21, 24 ~\rm mm$.

  (d) Record the corresponding force to each applied displacement.
#### Data analysis
 * Plot the force vs. displacement. Is the data linear? Add a straight line to fit the plot.

### Task 2: Validate the Hooke's for the rubber 

#### Steps
  (a) Choose 9 rubber bars of length $L$ of $100, 150, 200~\rm mm$ and diameter $D$ of $6.35, 9.525, 12.7~\rm mm$.

  (b) For each bar, clamp the two bar ends follwing the marks on the bar and stretch the bar to the displacememt of $\delta=15~\rm mm$, record the resulting force $F$.

  (c) Repeat Step (b) for each rubbar bar.

#### Data analysis
   * For each bar, calculate the term $\frac{FL}{A\delta}$, where $A$ is the area of cross section the rubber bar and $A=(\frac{D}{2})^2\pi$

   * Plot the value of $\frac{FL}{A\delta}$ vs. bar number. Is $\frac{FL}{A\delta}$ constant? 
   Add a horizontal line to fit the plot.


### Task 3: Determine the displacement field of rubber bar under uniaxial tensile test
  (a) Choose the rubber bar of length $L$ of $200 ~\rm mm$ and diameter of $6.35 ~\rm mm$. The bar was marked at different position. You will later measure the displacements of each marked position.

  (b)Clamp the two bar ends follwing the marks on the bar using the fixture of Instron machine.
  
  (c) Fix a camera at a certain distance from the bar. You can choose any camera you'd like as long as you can transfer the images to your computer. Your Phone would be a good choice and we will provide a tripod to hold the camera. Next to your bar, place a ruler or an object of known length, make sure that both the bar and your ruler or object are in focus on your camera. (You will use the image of the ruler or object later to calibrate your pixel to mm conversion). 

  (d) Take a picture of the bar before loading.

  (c) Stretch the bar to the displacememt of $\delta=20~\rm mm$, record the corresponding force, and take a piture of the deformed bar.

#### Data analysis
   * Now you have two pictures of undeformed and deformed bar, you can measure the displacement of each marked position using ImageJ following steps below

     * Download and open ImageJ (download from http://rsbweb.nih.gov/ij/download.html) . Open your the image. Click Analyze in the dropdown menu, followed by Set Scale. You can put in the scale to convert pixels to mm or cm use a fixed object (ruler) for the scale conversion.

     * From here, draw line on your image using the line segment (5th) icon. Hit Measure under Analyze after drawing a line to find out the length, angle, etc. of the segment using the measurement scale you specified.

   * Plot displacement vs. position of each marked position. Set the bottom marked postion as the original point. From the class, we know the displacement field of the bar under unaixal tensile test is $u(X)=\delta\frac{X}{L}$. Are the 



## 6. Lab report guidelines
1. There should be a cover page that contains the title of the lab, name of the author, name of the group members, date, and the name of the class. 

2. Plots should look professional. There should be no auto-generated Excel plots. Any figures should have a caption explaining the purpose of the figure and labeled axes with units, all in readably large text. Specific things to avoid are shadow on line plots, having grid lines on only one axis, and unnecessary overuse of color. Points will be deducted if your plots do not look professional!

3. Tabulated raw data should be included in the appendices, not in the body of the report. Additional figures not essential to the body of the report may be included in the appendices as well. Make sure to cite (refer to) every picture (appendix and body alike) in your report.

4. A good resource for lab report preparation is the Mayfield Handbook of Technical and Scientific Writing (http://www.mhhe.com/mayfieldpub/tsw/home.htm).

5. Lab reports should be submitted electronically on Canvas in PDF format. No paper reports will be accepted.

## 7. Lab report organization 

## [8. Lab calendar](https://calendar.google.com/calendar/embed?src=c_ftk0rj4uauudpfmcmm22plq5ig%40group.calendar.google.com&ctz=America%2FNew_York)

<iframe src="https://calendar.google.com/calendar/embed?src=c_ftk0rj4uauudpfmcmm22plq5ig%40group.calendar.google.com&ctz=America%2FNew_York" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>

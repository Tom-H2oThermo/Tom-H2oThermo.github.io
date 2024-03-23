---
nav_order: 2
title: 'The Basics'

parent: 'Home Page'

layout: page
permalink: /home-page/the_basics/
---

THe H2O Steam Properties program is based upon the International Association for the Properties of Water and Steam (IAPWS) formulations for industrial use. The IAPWS most current documentation may be found on the IAPWS.org website. The following IAPWS documents were used in the program development and are referenced in this manual and in the programs interactive help files.

## References

1. IAPWS R7-97(2012): Revised Release on the IAPWS Industrial Formulation 1997 for the Thermodynamic Properties of Water and Steam. (IAPWS-IF97). (Revised August 2007).
2. IAPWS SR2-01(2014): Revised Supplementary Release on Backward Equations for Pressure as a Function of Enthalpy and Entropy p(h,s) to the IAPWS Industrial Formulation 1997 for the Thermodynamic Properties of Water and Steam. (Revised June 2014).
3. IAPWS SR3-03(2014): Revised Supplementary Release on Backward Equations for the Functions T(p,h), v(p,h) and T(p,s), v(p,s) for Region 3 of the IAPWS Industrial Formulation 1997 for the Thermodynamic Properties of Water and Steam. (Revised June 2014).
4. IAPWS SR4-04(2014): Revised Supplementary Release on Backward Equations p(h,s) for Region 3, Equations as a Function of h and s for the Region Boundaries, and an Equation Tsat(h,s) for Region 4 of the IAPWS Industrial Formulation 1997 for the Thermodynamic Properties of Water and Steam. (Revised June 2014).
5. IAPWS SR5-05(2016): Revised Supplementary Release on Backward Equations for Specific Volume as a Function of Pressure and Temperature v(p,T) for Region 3 of the IAPWS Industrial Formulation 1997 for the Thermodynamic Properties of Water and Steam. (Revised September 2016).
6. IAPWS R12-08: Release on the IAPWS Formulation 2008 for the Viscosity of Ordinary Water Substance.
7. IAPWS R15-11: Release on the IAPWS Formulation 2011 for the Thermal Conductivity of Ordinary Water Substance.
8. IAPWS R1-76(2014): Revised Release on the Surface Tension of Ordinary Water Substance. (Revised June 2014).
9. ASME International Steam Tables for Industrial Use, Third Edition (2014). Introductory text from this document is incorporated into this manual in order to provide general background guidance to the user.

## Using the H2oProperties Functions

All of the primary H2oProperties functions begin with “= H2o.” (upper or lower case). A list of the available H2oProperties functions will be shown. Excel Intellisense provides guidance to the user as the function is entered.

![image](/assets/images/About1.png) <br>

The letters following H2o, one or two depending on the function, indicate the inputs while the final letter or letters, one or two depending on the function, representing the desired result. For example, =H2o.PTH indicates the inputs are pressure (P) and temperature (T) and the desired result is enthalpy (H).  In the example above, the return thermodynamic parameter is shown along with the return parameter’s units of measure depending on whether the default SI units are used (0), US customary units (1), metric bara (2) or metric kPa (3).

Once an opening parenthesis is entered, then the various input parameters are shown. The parameters in square brackets are optional. By default the units are SI and metastable conditions are false. When steam undergoes a sudden expansion in a steam turbine, passing from the superheated state to saturation conditions (region 4), the onset of moisture will be delayed until approximately the 5% (95% quality) steady state moisture conditions. This optional parameter may be of engineering use for saturated steam turbine applications.<br>

![image](/assets/images/About2.png)<br>
By clicking on the *fx* to the left of formula bar, a detailed view of the function that provides guidance for each input parameter and the units for the returned parameter.

![image](/assets/images/About3.png)<br>
By clicking on the “Help on this function” link in the lower left of this Function Arguments window, a help page opens with additional information specific to this individual function.

![image](/assets/images/About4.png)<br>
If invalid input parameters are entered, an error message is returned to provide some guidance as to what the problem may be.

![image](/assets/images/About5.png)
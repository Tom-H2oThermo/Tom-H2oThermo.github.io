---
nav_order: 5
title: 'Evaporative Cooling'

parent: 'Examples'
grand_parent: 'Home Page'
layout: page
permalink: /examples/evaporative-cooling/
---

The following graph, developed using the H2o Properties for Excel add-in, shows the difference in enthalpy between the moisture in the air and 0% quality saturated liquid, both calculated at the ambient temperature, for various relative humidities. This is useful for purposes such as sizing of a wet cooling tower. The dryer the air, the greater the potential for evaporative cooling.

![image](/assets/images/Cooling_Tower.png)
Relative humidity is defined as RH=P<sub>w</sub>/P<sub>ws</sub> where P<sub>w</sub> is the water vapor pressure in the air and P<sub>ws</sub> is the vapor pressure in the air at 100% relative humidity, when the air cannot hold any more moisture.

Example: Assume an ambient temperature of 25 <sup>o</sup>C and a relative humidity of 45%, using metric bara units

- The saturation pressure is calculated using the function H2oProperties function H2o.TP(25,2) where 25 is input temperature (in units of <sup>o</sup>C) and the 2 selects the metric bara units. This returns a value of 0.031697469 bara.
- The water vapor pressure in the air is therefore: P<sub>w</sub> = RH x P<sub>ws</sub> = 0.014263861 bara
- The enthalpy of the 100% quality saturated vapor in the air is calculated using the function H2oProperties function H2o.PQH(0.014263861,1,2) = 2523.348 kJ/kg. Note. The first input parameter is P<sub>w</sub>, the second is the quality (100%), and the third selects the metric bara units.
- The enthalpy at 0% quality saturated liquid is calculated using the function H2oProperties function H2o.PQH(00.031697469,0,2) = 104.838 kJ/kg. Note. The first input parameter is P<sub>ws</sub>, the second is the quality (0%), and the third selects the metric bara units.
- The evaporative cooling potential is the difference between these two enthalpies.  
    Δ<sub>enthalpy</sub> = (2523.348 – 104.838) kJ/kg = 2418.51 kJ/kg
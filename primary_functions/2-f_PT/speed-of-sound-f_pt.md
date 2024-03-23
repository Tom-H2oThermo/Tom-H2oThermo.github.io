---
nav_order: 6
title: 'Speed of Sound f(P, T)'

parent: 'Primary Functions'
grand_parent: 'Home Page'
layout: minimal
permalink: /primary_functions/speed-of-sound-f_pt/
---

Function Call “=H2o.PTW(pressure, temperature, units, metastable)”

**Input Parameters**

- Pressure: (0)MPa, (1)psia, (2)bara, (3)kPa
- Temperature: (0)K, (1)°F, (2)°C, (3)°C
- Units: (0)SI, (1)US Customary, (2)Metric bara, (3) Metric kPa
- Metastable: false=normal, true=metastable

**Return Value**

- Speed of Sound : (0)m/s, (1)ft/s, (2)m/s, (3)m/s

Default values: Units: (0)SI; Metastable: false

Metastable conditions may occur during a sudden steam expansion that crosses over from superheated to saturated conditions. The metastable calculations are valid from the saturated-vapor line to the 5% equilibrium moisture line for pressures from the triple-point pressure up to 10 MPa.

Reference Document: IAPWS R7-97
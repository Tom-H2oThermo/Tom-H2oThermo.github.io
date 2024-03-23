---
nav_order: 5
title: 'Specific Volume f(P, T)'

parent: 'Primary Functions'
grand_parent: 'Home Page'
layout: minimal
permalink: /primary_functions/specific-volume-f_pt/
---

Function Call “=H2o.PTV(pressure, temperature, units, metastable)”

**Input Parameters**

- Pressure: (0)MPa, (1)psia, (2)bara, (3)kPa
- Temperature: (0)K, (1)°F, (2)°C, (3)°C
- Units: (0)SI, (1)US Customary, (2)Metric bara, (3) Metric kPa
- Metastable: false=normal, true=metastable

**Return Value**

- Specific Volume: (0)m³/kg, (1)ft³/lbm, (2)m³/kg, (3)m³/kg

Default values: Units: (0)SI; Metastable: false

Metastable conditions may occur during a sudden steam expansion that crosses over from superheated to saturated conditions. The metastable calculations are valid from the saturated-vapor line to the 5% equilibrium moisture line for pressures from the triple-point pressure up to 10 MPa.

Reference Document: IAPWS R7-97
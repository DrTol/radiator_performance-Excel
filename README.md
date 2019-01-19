# Radiator Return Temperature Calculator
This VBA function/Excel tool calculates the radiator return temperature as based on the performance/rating measures making use of LMTD.  
## Table of Contents
- [Features](README.md#features)
- [How2Use](README.md#how2use)
- [License](README.md#license)
- [Acknowledgement](README.md#acknowledgement)
- [How2Cite](README.md#how2cite)
- [References](README.md#references)

## Features
The main idea here is to develop simple and reliable emprical models for residential radiator units so to be used in system level modelling (i.e. at district heating simulations). Hence, this VBA function estimate the radiator behaviour in terms of return temperature at different operational conditions (e.g. changing heat demand rate at different degrees of supply temperature).

## How2Use
An example Excel file is given: [Example_RadiatorReturnTemperature.xlsm](https://github.com/DrTol/radiator_performance-Excel/blob/master/Example_RadiatorReturnTemperature.xlsm), which illustrates how to use the function developed [TrLMTD_VBA](https://github.com/DrTol/radiator_performance-Excel/blob/master/TrLMTD_VBA)

## License
You are free to use, modify and distribute the code as long as authorship is properly acknowledged. The same applies for the original work 'XSteam' by Holmgren M. 

## Acknowledgement 
In memory of my father Bekir Tol..

We would like to acknowledge all of the open-source minds in general for their willing of share (as apps or comments/answers in forums), which has encouraged our department to publish our tools developed during the PhD study here in GitHub.

This Excel/VBA tool makes use of other original open-source project: 
- [XSteam_VBA by Holmgren M.](https://www.me.ua.edu/me215/f07.woodbury/ExcelStuff/XSteam-v2a.xlsm) | Author Description: XSteam provides accurate steam and water properties from 0 - 1000 bar and from 0 - 2000 deg C according to the standard IAPWS IF-97. For accuracy of the functions in different regions see IF-97 (www.iapws.org).

## How2Cite:
1. Tol, Hİ. radiator_performance-Excel. DOI: XXX. GitHub Repository 2018; https://github.com/DrTol/radiator_performance-Excel
2. Tol, Hİ. District heating in areas with low energy houses - Detailed analysis of district heating systems based on low temperature operation and use of renewable energy. PhD Supervisors: Svendsen S. & Nielsen SB. Technical University of Denmark 2015; 204 p. ISBN: 9788778773685.

## References
- Phetteplace GE. Optimal design of piping systems for district heating. Hanover, N.H.: U.S. Army Cold Regions Research and Engineering Laboratory; 1995.
- Bøhm B. Energy-economy of Danish district heating systems: A technical and economic analysis. Lyngby, Denmark: Laboratory of Heating and Air Conditioning, Technical University of Denmark; 1988.
- Benonysson A. Dynamic modelling and operational optimization of district heating systems. Lyngby, Denmark: Laboratory of Heating and Air Conditioning, Technical University of Denmark; 1991.
- Heat Emission from Radiators and Heating Panels, link: https://www.engineeringtoolbox.com/heat-emission-radiators-d_272.html
- British Standards Institution. BS EN 442-2:2014: Radiators and convectors - Part 2: Test methods and rating 2014:82.
- Soumerai H. Practical thermodynamic tools for heat exchanger design engineers. New York: Wiley-Interscience; 1987.
- Radson. Kv-calculator_-_03-2012(1).xls 2012:2.
- Schlapmann D. Heat output and surface temperature of room heat emitters [Warmeleitung und oberflachentemperatureen von raumheizkorpern] (German). Heiz Luft Haustechnik 1976;27:317–21.
- Kilkis İB. Equipment oversizing issues with hydronic heating systems. ASHRAE J 1998;40:25–30.

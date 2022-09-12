# PVsOenix-r-d included;
This repository contains code of PvsOenix R&D [https://pvsoenix.com/randd](#http-pvsoenix-com--randd); contribution done by [Sanjida Nusrat Ananna](#Sanjida-Nusrat-Ananna). This file describes the basic mathematical models of the parameter based photovoltaic cells in order to make flexible electricity- models and methods of making flexible electricity with a view to having a positive impact on environment by [reducing carbon emission](reducing-carbob-emission) instead of not eliminating it. 
[Continued...](#Continued...)
## The three parameter based PV models
```
The three parameters are $A_1$, $I_d$ and $I_{ph}$\
$$I_{PV} = I_{ph} - I_d$$\
$$I_{ph} = iccs\frac{g}{g_s}(1-∆icc(T_s - T ))$$\
$$I_d =I_{sat}(e^{\dfrac{\frac{v}{TAk}}{q}}- 1)$$\
$$I_{sat} =\frac{I_{ph}}{e^\dfrac{\frac{V_{oc}}{TAk}}{q} }- 1$$\
$$V_{oc} = V_{ocs} - ∆voc( T_s - T )$$
```
## The four parameter based PV models
```
The four parameters are $R_s$, $A$, $I_D$ and $I_{ph}$\
$$I_{PV} = I_{ph} - I_d$$\
$$I_{ph} = iccs\frac{g}{g_s}(1-\Delta icc(T_s - T))$$\
$$I_d = I_{sat}({e^\dfrac{\frac{v+IR_{s}}{TAk}}{q}}- 1)$$\
$$I_{sat} = \frac{I_{ph}}{e^\dfrac{\frac{V_{oc}}{TAk}}{q}}-1$$\
$$V_{oc} =V_{ocs}-\Delta voc(T_s - T)$$
```
## The five parameter based PV models
```
The five parameters are $R_s$ ,  $R_{sh}$, $A$, $I_d$ and $I_{ph}$\
$$I_{PV} = I_{ph} - I_d - I_{sh}$$\
$$I_{ph} = iccs\frac{g}{g_s}(1-\Delta icc(T_s - T))$$\
$$I_{sat} = \frac{{I_{ph}}-\frac{V_{oc}}{R_{sh}}}{e^\dfrac{\frac{V_{oc}}{TAk}}{q}}-1$$\
$$I_d = I_{sat}({e^\dfrac{\frac{v+IR_s}{TAk}}{q}}-1)$$\
$$V_{oc} = V_{ocs}-\Delta voc(T_s - T)$$\
$$I_{sh} = \frac{v+ IR_s}{R_{sh}}$$
```
## Equivalent PV cell models
## Solar thermal power plant

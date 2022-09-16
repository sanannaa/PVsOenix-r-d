# PVsOenix-r-d included;
This repository contains code of PvsOenix R&D [https://pvsoenix.com/randd](https://github.com/snananna/PVsOenix-r-d/blob/main/PVsOenix-r-d.html); contribution done by [Sanjida Nusrat Ananna](#Sanjida-Nusrat-Ananna). This file describes the basic mathematical models of the parameter based photovoltaic cells in order to make flexible electricity- models and methods of making flexible electricity with a view to having a positive impact on environment by **reducing carbon emission** instead of eliminating it. 
# 1. How can we make flexible electricity through our PV models and possible methods of scaling down the coal?
### a) By creating three parameter-based photovoltaic model in large scale:
- ** Continued..**
## The three parameter based PV model
```
The three parameters are $A_1$, $I_d$ and $I_{ph}$\
$$I_{PV} = I_{ph} - I_d$$\
$$I_{ph} = iccs\frac{g}{g_s}(1-∆icc(T_s - T ))$$\
$$I_d =I_{sat}(e^{\dfrac{\frac{v}{TAk}}{q}}- 1)$$\
$$I_{sat} =\frac{I_{ph}}{e^\dfrac{\frac{V_{oc}}{TAk}}{q} }- 1$$\
$$V_{oc} = V_{ocs} - ∆voc( T_s - T )$$
```
##### Derived equations after running this code on $$TeXit$$- The file image enclosed below; 
![PVsOenix-Three-Parameter-Based-Equations](https://github.com/snananna/PVsOenix-r-d/blob/main/photo_2022-05-12_02-06-39.jpg?raw=true)
##### Derived equations after running this code on $$TeXstudio$$
The three parameters are $A_1$, $I_d$ and $I_{ph}$\
$$I_{PV} = I_{ph} - I_d$$\
$$I_{ph} = iccs\frac{g}{g_s}(1-∆icc(T_s - T ))$$\
$$I_d =I_{sat}(e^{\dfrac{\frac{v}{TAk}}{q}}- 1)$$\
$$I_{sat} =\frac{I_{ph}}{e^\dfrac{\frac{V_{oc}}{TAk}}{q} }- 1$$\
$$V_{oc} = V_{ocs} - ∆voc( T_s - T )$$
![Three parameter-based PV model]( <p align="center" <img src=""https://raw.githubusercontent.com/snananna/PVsOenix-r-d/a5fcf7aefb62aa1d7c45a297f8477eb304cb6f2a/TPM.svg" alt=" The three parameter-based PV model">
    </P>
<p align="center">
   Figure a(1) : The three parameter-based photovoltaic cell
</p>                
## The four parameter based PV model
```
The four parameters are $R_s$, $A$, $I_D$ and $I_{ph}$\
$$I_{PV} = I_{ph} - I_d$$\
$$I_{ph} = iccs\frac{g}{g_s}(1-\Delta icc(T_s - T))$$\
$$I_d = I_{sat}({e^\dfrac{\frac{v+IR_{s}}{TAk}}{q}}- 1)$$\
$$I_{sat} = \frac{I_{ph}}{e^\dfrac{\frac{V_{oc}}{TAk}}{q}}-1$$\
$$V_{oc} =V_{ocs}-\Delta voc(T_s - T)$$
```
#### Derived equations after running this code on $$TeXit$$- The file image enclosed below; 
![Four-Parameter-based-PV-models](https://github.com/snananna/PVsOenix-r-d/blob/main/photo_2022-05-12_02-03-14.jpg?raw=true)
##### Derived equations after running this code on $$TeXstudio$$
The four parameters are $R_s$, $A$, $I_D$ and $I_{ph}$\
$$I_{PV} = I_{ph} - I_d$$\
$$I_{ph} = iccs\frac{g}{g_s}(1-\Delta icc(T_s - T))$$\
$$I_d = I_{sat}({e^\dfrac{\frac{v+IR_{s}}{TAk}}{q}}- 1)$$\
$$I_{sat} = \frac{I_{ph}}{e^\dfrac{\frac{V_{oc}}{TAk}}{q}}-1$$\
$$V_{oc} =V_{ocs}-\Delta voc(T_s - T)$$
![Four parameter-based PV model]( <p align="center" <img src=""https://raw.githubusercontent.com/snananna/PVsOenix-r-d/a5fcf7aefb62aa1d7c45a297f8477eb304cb6f2a/FPM.svg"  alt=" The four parameter-based PV model">
    </P>
<p align="center">
 Figure b(1) : The four parameter-based photovoltaic cell
</p>
## The five parameter based PV model
```
The five parameters are $R_s$ ,  $R_{sh}$, $A$, $I_d$ and $I_{ph}$\
$$I_{PV} = I_{ph} - I_d - I_{sh}$$\
$$I_{ph} = iccs\frac{g}{g_s}(1-\Delta icc(T_s - T))$$\
$$I_{sat} = \frac{{I_{ph}}-\frac{V_{oc}}{R_{sh}}}{e^\dfrac{\frac{V_{oc}}{TAk}}{q}}-1$$\
$$I_d = I_{sat}({e^\dfrac{\frac{v+IR_s}{TAk}}{q}}-1)$$\
$$V_{oc} = V_{ocs}-\Delta voc(T_s - T)$$\
$$I_{sh} = \frac{v+ IR_s}{R_{sh}}$$
```
#### Derived equations after running this code on $$TeXit$$- The file image enclosed below;
![Five-Parameter-based-PV-models]
##### Derived equations after running this code on $$TeXstudio$$
The five parameters are $R_s$ ,  $R_{sh}$, $A$, $I_d$ and $I_{ph}$\
$$I_{PV} = I_{ph} - I_d - I_{sh}$$\
$$I_{ph} = iccs\frac{g}{g_s}(1-\Delta icc(T_s - T))$$\
$$I_{sat} = \frac{{I_{ph}}-\frac{V_{oc}}{R_{sh}}}{e^\dfrac{\frac{V_{oc}}{TAk}}{q}}-1$$\
$$I_d = I_{sat}({e^\dfrac{\frac{v+IR_s}{TAk}}{q}}-1)$$\
$$V_{oc} = V_{ocs}-\Delta voc(T_s - T)$$\
$$I_{sh} = \frac{v+ IR_s}{R_{sh}}$$
</p>
![Five parameter-based PV model]( <p align="center" <img src=""https://raw.githubusercontent.com/snananna/PVsOenix-r-d/b7f8c973a236665440a497b1c3283c23185ad619/FiPM.svg" alt=" The five parameter-based PV model">
    </P>
<p align="center">
Figure c(1) : The five parameter-based photovoltaic cell
</p>
## Equivalent PV cell model
![Equvalent PV Cell](https://github.com/snananna/PVsOenix-r-d/blob/main/Screenshot%20(1076).png?raw=true)
## Solar thermal power plant
* [PowerPoint version by Ananna](#PowerPoint-version-by-Ananna)
![Solar thermal power plant](https://github.com/snananna/PVsOenix-r-d/blob/main/Slide1.JPG?raw=true) 
* [Website products by Pallob](#Website-products-by-Pallob)
![Solar thermal power plant](https://github.com/snananna/PVsOenix-r-d/blob/main/Solar1.png?raw=true)

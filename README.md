# PVsOenix-r-d (https://pvsoenix.com/randd) included; 
# The three parameter based PV Models
The three parameters are $A_1$, $I_d$ and $I_{ph}$
\begin{align}
I_{PV} &= I_{ph}- I_d\\
I_{ph} &=iccs\frac{g}{g_s}(1-\Delta icc(T_s - T))\\
I_d & =I{sat}(e^{\dfrac{\frac{v}{TAk}}{q}}- 1)\\
I_{sat} & =\frac{I_{ph}}{e^\dfrac{\frac{V_{oc}}{TAk}}{q} }- 1\\
V_{oc} & = V_{ocs} - \Delta voc(T_s - T)
\end{align}
# The four parameter based PV models
The four parameters are $R_s$, $A$, $I_D$ and $I_{ph}$\\
\begin{align}
I_{PV} &= I_{ph} - I_d\\
I_{ph} &= iccs\frac{g}{g_s}(1-\Delta icc(T_s - T))\\
I_d & = I_{sat}({e^\dfrac{\frac{v+IR_{s}}{TAk}}{q}}- 1)\\
I_{sat} & = \frac{I_{ph}}{e^\dfrac{\frac{V_{oc}}{TAk}}{q}}-1\\
V_{oc} & =V_{ocs}-\Delta voc(T_s - T)\\
\end{align}
The five parameters are $R_s$ ,  $R_{sh}$, $A$, $I_d$ and $I_{ph}$\\
\begin{align}
I_{PV} &= I_{ph} - I_d - I_{sh}\\
I_{ph} &= iccs\frac{g}{g_s}(1-\Delta icc(T_s - T))\\
I_{sat} &= \frac{{I_{ph}}-\frac{V_{oc}}{R_{sh}}}{e^\dfrac{\frac{V_{oc}}{TAk}}{q}}-1\\
I_d &= I_{sat}({e^\dfrac{\frac{v+IR_s}{TAk}}{q}}-1)\\
V_{oc} &= V_{ocs}-\Delta voc(T_s - T)\\
I_{sh} &= \frac{v+ IR_s}{R_{sh}}
\end{align}
# Equivalent PV cell model
# Solar thermal power plant. 

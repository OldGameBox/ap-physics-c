![[Pasted image 20260528070127.png]]
![[Pasted image 20260528070133.png]]
### 7 Composite Insulation System

$$\begin{aligned} \text{(a) } R_1 &= \frac{d_1}{k_1 A} = \frac{0.040}{0.12 \times 12} = 0.0278 \text{ K/W} \\ R_2 &= \frac{d_2}{k_2 A} = \frac{0.080}{0.020 \times 12} = 0.3333 \text{ K/W} \\ \text{(b) } R_{tot} &= R_1 + R_2 = 0.0278 + 0.3333 = 0.3611 \text{ K/W} \\ \text{(c) } \frac{Q}{t} &= \frac{\Delta T}{R_{tot}} = \frac{30 - (-5)}{0.3611} = 96.9 \text{ W} \end{aligned}$$

### 8 Radiation and Emissivity

$$\begin{aligned} \text{(a) } A &= 4 \pi r^2 = 4 \pi (0.80)^2 = 8.04 \text{ m}^2 \\ \text{(b) } P &= e \sigma A T^4 = 0.72 (5.67 \times 10^{-8})(8.04)(420)^4 = 10216 \text{ W} \\ \text{(c) } P_{new} &= 0.95 \sigma A T^4 = 10216 \times \frac{0.95}{0.72} = 13480 \text{ W} \end{aligned}$$

### 9 Net Radiative Cooling

$$\begin{aligned} \text{(a) } P_{net} &= e \sigma A (T^4 - T_{env}^4) = 0.88(5.67 \times 10^{-8})(3.0)(650^4 - 295^4) = 25586 \text{ W} \\ \text{(b) } P_{net,new} &= e \sigma A (T^4 - T_{env,new}^4) = 0.88(5.67 \times 10^{-8})(3.0)(650^4 - 340^4) = 24720 \text{ W} \end{aligned}$$

As the environmental temperature increases, the surroundings radiate more thermal energy back to the plate. This consequently decreases the net rate of heat transfer from the plate to the environment.

### 10 Cooling Model with Differential Equations

$$\begin{aligned} \text{(a) } \int \frac{dT}{T - T_{env}} &= \int -k \,dt \implies \ln(T - 22) = -0.045t + C \\ T(0) &= 150 \implies C = \ln(128) \implies T(t) = 22 + 128e^{-0.045t} \\ \text{(b) } T(20) &= 22 + 128e^{-0.045(20)} = 74.0^\circ\text{C} \\ \text{(c) } 60 &= 22 + 128e^{-0.045t} \implies e^{-0.045t} = \frac{38}{128} \implies t = 27.0 \text{ min} \end{aligned}$$

### 11 Variable Force on a Piston

$$\begin{aligned} \text{(a) } F(x) &= P(x)A = (1.2 \times 10^5 + 3.5 \times 10^4 x^2)(0.015) = 1800 + 525x^2 \\ \text{(b) } W &= \int_{x_i}^{x_f} F(x) \,dx = \int_{0}^{0.30} (1800 + 525x^2) \,dx \\ \text{(c) } W &= \left[ 1800x + 175x^3 \right]_{0}^{0.30} = 1800(0.30) + 175(0.30)^3 = 544.7 \text{ J} \end{aligned}$$

### 12 Thermal Energy Balance in a Metal-Ice System

$$\begin{aligned} \text{(a) } Q_{Cu,max} &= m_{Cu}c_{Cu}\Delta T = 0.400(385)(350 - 0) = 53900 \text{ J} \\ Q_{melt,all} &= m_{ice}L_f = 0.800(3.34 \times 10^5) = 267200 \text{ J} \\ Q_{Cu,max} &< Q_{melt,all} \implies \text{Not all ice melts} \\ \text{(b) } T_f &= 0^\circ\text{C} \\ \text{(c) } \Delta S_{Cu} &= m_{Cu}c_{Cu}\ln\left(\frac{T_f}{T_i}\right) = 0.400(385)\ln\left(\frac{273.15}{623.15}\right) = -127.0 \text{ J/K} \\ \Delta S_{ice} &= \frac{Q_{melted}}{T_{ice}} = \frac{53900}{273.15} = 197.3 \text{ J/K} \\ \Delta S_{total} &= \Delta S_{Cu} + \Delta S_{ice} = -127.0 + 197.3 = 70.3 \text{ J/K} \end{aligned}$$
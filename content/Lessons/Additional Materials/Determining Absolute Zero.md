### Purpose
Use pressure-temperature data for a fixed-volume gas to estimate absolute zero. To determine the temperature where pressure would become zero, we will generate our own graph, determine a best-fit line, and extrapolate to the temperature.

### Theoretical Background
Looking at the provided data and physical explanation, the only variables that change are temperature and pressure of the gas. Therefore, we can assume that the volume and amount particles of gas remain the same.

For a fixed amount of gas at constant volume:
$$\begin{gather}\frac{P}{T}=\text{constant}\end{gather}$$
Since kelvin temperature is related to Celsius temperature by:
$$\begin{gather}T_{K}=T_{C}+273.15\end{gather}$$
a graph if pressure $P$ versus Celsius temperature $T_{C}$ should be approximately linear. If the line is extended until $P=0$, the x-intercept estimates absolute zero.

### Data

| Temperature, $T_{C}$ | Pressure, $P$ |
| -------------------- | ------------- |
| -50                  | 81.2          |
| -25                  | 89.0          |
| 0                    | 98.3          |
| 25                   | 107.2         |
| 50                   | 116.0         |
| 75                   | 125.1         |
| 100                  | 133.9         |


![[Pasted image 20260526080603.png]]

##### Equation of the best-fit line
$$\begin{gather}P=0.3543 \cdot T_{C} \,+\,98.39\end{gather}$$
##### Finding the x-intercept
$$\begin{gather}P=0 \\0.3543 \cdot T_{C} = -98.39 \\T_{C} = -277.7\,^{\circ}C\end{gather}$$
##### Calculating percent error
$$\begin{aligned}\%\text{error} & = \left| \frac{{T_{exper.} - T_{theor.}}}{T_{theor.}} \right| \times 100\% = \\ & = \left| \frac{{-277.7 + 273.15}}{-273.15} \right| \times 100\% = \\ & = 1.67\%\end{aligned}$$

##### Why this experiment supports using the kelvin temperature scale?
This experiment demonstrates a direct, linear relationship between gas pressure and Celsius temperature, showing that pressure decreases predictably as temperature drops. By extrapolating this line to the point where pressure reaches zero ($P = 0$), we find a theoretical absolute minimum temperature, which closely matches the established value for absolute zero. The Kelvin scale directly reflects this physical reality by shifting the zero point to this absolute minimum, making gas pressure directly proportional to temperature.

### Analysis
##### 1. What physical variable was held constant in this experiment?
- Volume, amount of gas particles
##### 2. Why should pressure decrease as temperature decreases?
- As temperature drops, gas molecules lose kinetic energy and move more slowly. This results in fewer and less forceful collisions with the container walls, which lowers the pressure.
##### 3. Why is it reasonable to extrapolate the trend even though no data was collected near $-273\, ^{\circ}C$?
- According to Gay-Lussac's Law, ideal gases maintain a strictly linear relationship between pressure and temperature. Because the data points collected at manageable temperatures form a highly predictable straight line, it is reasonable to extend that line to find the theoretical zero-pressure point.
##### 4. Why would a real gas stop behaving ideally before reaching absolute zero? 
- At extremely low temperatures, gas molecules slow down significantly, causing intermolecular attractive forces to take effect. Additionally, the actual volume occupied by the gas molecules themselves becomes significant relative to the container volume, or the gas may liquefy entirely.
##### 5. How would random measurement error affect the x-intercept?
- Random error creates slight, unpredictable variations in individual data points both above and below the true values. While this causes minor fluctuations in the slope of the best-fit line, its overall impact on the x-intercept is minimized because the errors tend to cancel each other out across the entire data set.

### Conclusion
This experiment successfully estimated absolute zero to be **-277.7°C** by extrapolating the linear relationship between the pressure and temperature of a fixed-volume gas. This experimental value yielded a low percent error of **1.67%**, validating the high predictability of Gay-Lussac's Law under the tested conditions. Ultimately, the results strongly support the implementation of the Kelvin scale, as its zero point directly corresponds to this absolute minimum where molecular motion and gas pressure theoretically cease.
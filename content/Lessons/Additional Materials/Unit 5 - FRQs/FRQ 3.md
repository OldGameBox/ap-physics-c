## Part a
#### Experimental Procedure
1. Measure wheel mass $M$ using an electronic balance.
2. Measure wheel radius $R$ using a meterstick.
3. Spin the wheel to an initial angular velocity.
4. Push the friction pad against the wheel rim using a spring scale.
5. Read the spring scale to measure the applied normal force $F_N$.
6. Use a rotary motion sensor to measure angular velocity $\omega$ as a function of time $t$.
7. Determine angular acceleration $\alpha$ from the slope of the angular velocity versus time data.
8. Repeat the experiment for multiple different values of applied normal force $F_N$.
## Part b
#### Linear Graph Analysis
$$F_f = \mu_k F_N$$

$$\tau_f = F_f R = \mu_k F_N R$$

$$\tau_f = I \alpha = M R^2 \alpha$$

$$\mu_k F_N R = M R^2 \alpha$$

$$\alpha = \frac{\mu_k}{M R} F_N$$

Plot angular acceleration $\alpha$ on the vertical axis. Plot normal force $F_N$ on the horizontal axis. The resulting graph produces a straight line through the origin. The slope $m$ of the line equals $\frac{\mu_k}{M R}$. Calculate $\mu_k$ by multiplying the measured slope $m$ by the values $M$ and $R$.

## Part c i
#### Graph Quantities
Horizontal axis: Number of Spokes $N_s$
Vertical axis: Square of Time $(\Delta t)^2$

| Number of Spokes $N_s$ | Time for 8 Rotations $\Delta t$ ($\text{s}$) | Square of Time $(\Delta t)^2$ ($\text{s}^2$) |
| ---------------------- | -------------------------------------------- | -------------------------------------------- |
| 2                      | 10.8                                         | 116.6                                        |
| 4                      | 12.9                                         | 166.4                                        |
| 6                      | 15.2                                         | 231.0                                        |
| 8                      | 16.5                                         | 272.3                                        |

## Part c ii
![[Code_Generated_Image(1).png]]

## Part d
#### Calculations
$$\Delta \theta = 8 \times 2\pi = 16\pi$$

$$\Delta \theta = \frac{1}{2} \alpha (\Delta t)^2$$

$$\alpha = \frac{32 \pi}{(\Delta t)^2}$$

$$\tau_0 = I_{total} \alpha$$

$$\tau_0 = (I_2 + N_s I_s) \frac{32 \pi}{(\Delta t)^2}$$

$$(\Delta t)^2 = \frac{32 \pi I_s}{\tau_0} N_s + \frac{32 \pi I_2}{\tau_0}$$

The vertical intercept $b$ corresponds to the constant term.

$$b = \frac{32 \pi I_2}{\tau_0}$$

$$I_2 = \frac{b \tau_0}{32 \pi}$$

Substitute intercept value $b = 63.6 \text{ s}^2$ and torque $\tau_0 = 0.50 \text{ N}\cdot\text{m}$.

$$I_2 = \frac{(63.6)(0.50)}{32 \pi}$$

$$I_2 = 0.316 \text{ kg}\cdot\text{m}^2$$
## Part a
The angular speed is the same for both pulleys.
#### Justification
Both systems start from rest. They have the same initial hanging mass $M_2$. Both pulleys have identical rotational inertia $I = \frac{1}{2} M_1 R^2$. The torque $\tau$ equals $F R$. The problem states tension equals the weight below the point. At $t = 0$, the hanging weight for both systems is $M_2 g$. This creates equal initial torque. Equal torque on equal inertia produces equal initial angular acceleration. At a short time $\Delta t$, their angular speeds remain equal.

## Part b
#### i. Derivation of Angular Acceleration
$$\alpha_2 (t) = \frac{d\omega_2}{dt}$$

$$\alpha_2 (t) = \frac{d}{dt} \left[ \frac{M_2 c}{2 \lambda R} (e^{ct} - e^{-ct}) \right]$$

$$\alpha_2 (t) = \frac{M_2 c^2}{2 \lambda R} (e^{ct} + e^{-ct})$$
#### ii. Expression for Constant c
The initial torque is $\tau_0 = M_2 g R$.

The rotational inertia is $I = \frac{1}{2} M_1 R^2$.

Initial acceleration $\alpha_2 (0)$ follows $\tau_0 = I \alpha_2 (0)$.

$$\alpha_2 (0) = \frac{M_2 g R}{\frac{1}{2} M_1 R^2} = \frac{2 M_2 g}{M_1 R}$$

From the derivative at $t = 0$:

$$\alpha_2 (0) = \frac{M_2 c^2}{2 \lambda R} (e^0 + e^0) = \frac{M_2 c^2}{\lambda R}$$

Equating the two expressions:

$$\frac{M_2 c^2}{\lambda R} = \frac{2 M_2 g}{M_1 R}$$

$$c = \sqrt{\frac{2 \lambda g}{M_1}}$$

Final expression for $\alpha_2 (t)$:

$$\alpha_2 (t) = \frac{M_2 (\frac{2 \lambda g}{M_1})}{2 \lambda R} (e^{ct} + e^{-ct}) = \frac{M_2 g}{M_1 R} (e^{ct} + e^{-ct})$$

## Part c
The angular acceleration is greater for Pulley 3.
#### Justification
The derived formula shows $\alpha(t)$ is proportional to $\frac{M_{hanging}}{M_{pulley}} (e^{ct} + e^{-ct})$. Pulley 3 has mass $2 M_1$ and initial hanging mass $2 M_2$. The ratio $\frac{2 M_2}{2 M_1}$ equals $\frac{M_2}{M_1}$. The growth constant $c$ remains $\sqrt{\frac{2 \lambda g}{2 M_1}}$. This $c$ value for Pulley 3 is smaller than for Pulley 2 because of the $2 M_1$ term in the denominator. A smaller $c$ results in slower exponential growth over time. Pulley 2 has a larger $c$ and reaches higher acceleration values as time increases.
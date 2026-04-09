## Part a i
#### Determine Total Rotational Inertia

$I_{disk} = \frac{1}{2}MR^{2}$

$I_{cylinder} = M(\frac{R}{2})^{2} = \frac{1}{4}MR^{2}$

$I_{total} = I_{disk} + I_{cylinder} = \frac{1}{2}MR^{2} + \frac{1}{4}MR^{2} = \frac{3}{4}MR^{2}$

#### Find Angular Acceleration

$\omega(t) = \omega_{f}(1 - e^{-\frac{t}{T}})$

$\alpha(t) = \frac{d\omega}{dt} = \omega_{f}(\frac{1}{T})e^{-\frac{t}{T}}$

#### Calculate Maximum Net Torque

$\tau(t) = I_{total}\alpha(t) = (\frac{3}{4}MR^{2})(\frac{\omega_{f}}{T}e^{-\frac{t}{T}})$

Maximum torque occurs at $t = 0$ because $e^{0} = 1$.

$\tau_{max} = \frac{3MR^{2}\omega_{f}}{4T}$

## Part a ii

#### Component Selection
Both tangential and radial components.
#### Justification

The cylinder moves in a circular path with changing speed. The radial component provides centripetal acceleration to maintain the circular path. The tangential component provides angular acceleration to change the speed. Friction provides both necessary accelerations because no other horizontal forces act on the cylinder.

## Part b

#### Determine Time for Given Angular Speed

$\omega(t) = \frac{\omega_{f}}{3}$

$\frac{\omega_{f}}{3} = \omega_{f}(1 - e^{-\frac{t}{T}})$

$\frac{1}{3} = 1 - e^{-\frac{t}{T}}$

$e^{-\frac{t}{T}} = \frac{2}{3}$

#### Calculate Tangential Acceleration

$a_{tan} = \alpha r = (\frac{R}{2})(\frac{\omega_{f}}{T}e^{-\frac{t}{T}})$

$a_{tan} = (\frac{R}{2})(\frac{\omega_{f}}{T})(\frac{2}{3}) = \frac{R\omega_{f}}{3T}$

#### Calculate Radial Acceleration

$a_{rad} = \omega^{2}r = (\frac{\omega_{f}}{3})^{2}(\frac{R}{2})$

$a_{rad} = \frac{\omega_{f}^{2}R}{18}$

#### Calculate Linear Acceleration Magnitude

$a = \sqrt{a_{tan}^{2} + a_{rad}^{2}}$

$a = \sqrt{(\frac{R\omega_{f}}{3T})^{2} + (\frac{R\omega_{f}^{2}}{18})^{2}}$

$a = \frac{R\omega_{f}}{3} \sqrt{\frac{1}{T^{2}} + \frac{\omega_{f}^{2}}{36}}$
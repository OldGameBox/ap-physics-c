## (a)(i) Velocity Derivation
$$\sum F = ma \implies -mg - bv = m \frac{dv}{dt}$$
$$\int_{v_0}^{v} \frac{dv}{g + \frac{b}{m}v} = \int_{0}^{t} -dt$$
$$\frac{m}{b} \ln\left| \frac{g + \frac{b}{m}v}{g + \frac{b}{m}v_0} \right| = -t \implies v(t) = \left( v_0 + \frac{mg}{b} \right) e^{-\frac{b}{m}t} - \frac{mg}{b}$$
## (a)(ii) Acceleration Sketch
![[Pasted image 20260311093945.png]]
## (b) Maximum Height Time Derivation
The sphere reaches its maximum height when its instantaneous velocity $v(t)$ equals zero. Using the velocity equation derived in part (a)(i), we set $v(t_h) = 0$ and solve for the time variable.
$$0 = \left( v_0 + \frac{mg}{b} \right) e^{-\frac{b}{m}t_h} - \frac{mg}{b}$$
$$\frac{mg/b}{v_0 + mg/b} = e^{-\frac{b}{m}t_h}$$
$$t_h = \frac{m}{b} \ln\left( \frac{v_0 + \frac{mg}{b}}{\frac{mg}{b}} \right) \implies t_h = \frac{m}{b} \ln\left( 1 + \frac{bv_0}{mg} \right)$$
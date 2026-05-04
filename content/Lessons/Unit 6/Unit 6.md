## 6.1 Rotational Kinetic Energy
Rotational kinetic energy ($K_{rot}$) is the energy an object possesses due to its rotation around an axis. It is the rotational analog of translational kinetic energy.

- **The Formula:**
    
    $$K_{rot} = \frac{1}{2}I\omega^2$$
    
    - $I$: Rotational inertia (moment of inertia) in $kg \cdot m^2$.
        
    - $\omega$: Angular velocity in $rad/s$.
        
- **Energy Viewpoints:**
    
    - **Translational:** Focuses on the center of mass (CoM) moving through space ($K_{trans} = \frac{1}{2}mv^2$).
        
    - **Rotational:** Focuses on the particles rotating around the CoM.
        
    - **Total Energy:** For an object both moving and spinning, $K_{total} = K_{trans} + K_{rot}$.
        

---

## 6.2 Torque and Work

Just as a force doing work changes translational kinetic energy, a **torque** doing work changes rotational kinetic energy.

- **Rotational Work-Energy Theorem:** The work done by a constant torque ($\tau$) over an angular displacement ($\Delta\theta$) equals the change in rotational kinetic energy.
    
    $$W = \tau\Delta\theta = \Delta K_{rot}$$
    
- **Non-Constant Torque:** If the torque changes over the displacement, work is the area under a **Torque vs. Angular Position** graph ($W = \int \tau \, d\theta$).
    
- **Example:** Pulling a string wrapped around a pulley. The tension provides a torque that increases the pulley's $\omega$, thereby increasing its $K_{rot}$.
    

---

## 6.3 Angular Momentum and Angular Impulse

Angular momentum ($L$) is the measure of an object's "rotational motion."

- **Defining $L$:**
    
    - **Point Mass:** $L = mvr\sin(\phi)$ or $L = r \times p$. (Even an object moving in a straight line has angular momentum relative to a specific reference point!)
        
    - **Rigid Body:** $L = I\omega$.
        
- **Angular Impulse-Momentum Theorem:**
    
    A net external torque applied over time causes a change in angular momentum.
    
    $$\vec{\tau}_{net}\Delta t = \Delta \vec{L}$$
    
    - Analogous to $F\Delta t = \Delta p$.
        
- **Graphical Analysis:** The area under a **Net Torque vs. Time** graph represents the change in angular momentum ($\Delta L$).
    

---

## 6.4 Conservation of Angular Momentum

In a **closed system** where the net external torque is zero ($\tau_{ext} = 0$), the total angular momentum remains constant.

- **The Law:** $L_i = L_f \rightarrow I_i\omega_i = I_f\omega_f$
    
- **Conceptual Examples:**
    
    - **Figure Skater:** When a skater pulls their arms in, their rotational inertia ($I$) decreases. To conserve $L$, their angular velocity ($\omega$) must increase.
        
    - **Bicycle Wheels:** The spinning wheel has a large $L$. Changing its direction requires a significant external torque, which explains the stability of a moving bike.
        

---

## 6.5 Rolling Motion

Rolling is a combination of translation and rotation.

- **Rolling Without Slipping:** Occurs when $v = R\omega$. The point of contact is momentarily at rest relative to the surface.
    
- **Conservation of Energy in Rolling:**
    
    When an object rolls down an incline, potential energy transforms into _both_ types of kinetic energy:
    
    $$U_g = K_{trans} + K_{rot} = \frac{1}{2}mv^2 + \frac{1}{2}I\omega^2$$
    
- **Slipping/Skidding:** If $v \neq R\omega$, the object is slipping. Kinetic friction will act to change both $v$ and $\omega$ until the "no-slip" condition ($v = R\omega$) is met.
    
- **Lab Example:** Comparing a solid sphere and a hollow hoop rolling down a ramp. The sphere has a smaller $I$ (more mass near the center), so it takes less energy to rotate and more is available for speed ($v$), making it reach the bottom faster.
    

---

## 6.6 Motion of Orbiting Satellites

Orbits are a specific application of angular momentum and energy conservation.

- **Angular Momentum in Orbits:**
    
    In a central force field (gravity), the torque is zero because the force is parallel to the radius. Therefore, **$L$ is conserved**.
    
    - In an elliptical orbit, as the satellite gets closer to the planet ($r$ decreases), its speed ($v$) must increase to keep $L = mvr$ constant.
        
- **Energy in Orbits:**
    
    - **Total Energy ($E_{total}$):** $K + U_g = \frac{1}{2}mv^2 - \frac{Gm_1m_2}{r}$.
        
    - For a circular orbit, $E_{total}$ is constant and negative (bound system).
        
- **Escape Speed:** The minimum speed needed for an object to break free from a planet's gravity ($E_{total} \geq 0$).

    $$v_{escape} = \sqrt{\frac{2GM}{R}}$$
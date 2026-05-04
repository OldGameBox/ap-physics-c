## 5.1 Rotational Kinematics

Rotational kinematics describes the motion of rigid bodies spinning around a fixed axis without considering the forces that cause the motion.

- **The Variables:**
    
    - **Angular Displacement ($\theta$):** The angle through which an object has rotated (measured in radians).
        
    - **Angular Velocity ($\omega$):** The rate of change of angular displacement ($\omega = \frac{d\theta}{dt}$).
        
    - **Angular Acceleration ($\alpha$):** The rate of change of angular velocity ($\alpha = \frac{d\omega}{dt}$).
        
- **Constant Acceleration Equations:** If $\alpha$ is constant, we use the "Big Three" rotational analogs:
    
    1. $\omega_f = \omega_i + \alpha t$
        
    2. $\theta = \theta_i + \omega_i t + \frac{1}{2}\alpha t^2$
        
    3. $\omega_f^2 = \omega_i^2 + 2\alpha\Delta\theta$
        
- **Calculus Connection:** If $\alpha$ is non-constant, you must integrate to find velocity or position (e.g., $\Delta\omega = \int \alpha \, dt$).
    

---

## 5.2 Connecting Linear and Rotational Motion

Every point on a rotating rigid body has a "linear" (tangential) component to its motion that depends on its distance ($r$) from the axis of rotation.

- **The Bridge Equations:**
    
    - **Arc Length ($s$):** $s = r\theta$
        
    - **Tangential Velocity ($v_t$):** $v = r\omega$
        
    - **Tangential Acceleration ($a_t$):** $a_t = r\alpha$
        
- **Important Distinction:** All points on a rigid body share the same $\omega$ and $\alpha$, but points further from the center have a higher $v_t$ and $a_t$.
    

---

## 5.3 Torque ($\tau$)

Torque is the rotational equivalent of force; it is the "twist" applied to an object.

- **The Formula:**
    
    $$\tau = rF\sin(\theta)$$
    
    - $r$: The distance from the pivot to the point where the force is applied (lever arm).
        
    - $F$: The magnitude of the applied force.
        
    - $\theta$: The angle between the force vector and the lever arm.
        
- **Direction:** Torque is a vector. By convention, counter-clockwise (CCW) is positive, and clockwise (CW) is negative.
    

---

## 5.4 Rotational Inertia ($I$)

Also known as the **Moment of Inertia**, this represents an object's resistance to changes in its rotational motion.

- **Point Mass:** $I = mr^2$
    
- **System of Particles:** $I_{total} = \sum m_i r_i^2$
    
- **Common Shapes:**
    
    - **Hoop:** $I = MR^2$
        
    - **Solid Cylinder/Disk:** $I = \frac{1}{2}MR^2$
        
    - **Solid Sphere:** $I = \frac{2}{5}MR^2$
        
- **Parallel Axis Theorem:** Used to find the inertia about an axis parallel to the center of mass axis: $I = I_{cm} + MD^2$.
    

---

## 5.5 Rotational Equilibrium

For an object to be in **total equilibrium**, two conditions must be met:

1. **Translational Equilibrium:** $\sum \vec{F} = 0$ (No linear acceleration).
    
2. **Rotational Equilibrium:** $\sum \vec{\tau} = 0$ (No angular acceleration).
    

- **Static Equilibrium:** The object is at rest ($\omega = 0$ and $v = 0$).
    
- **Example Case (The Balancing Beam):** For a beam supported by a wall or a fulcrum, you must sum the torques around a chosen pivot point (usually the pivot with the most unknown forces) and set them to zero.
    

---

## 5.6 Newton's Second Law for Rotation

The rotational version of $F=ma$. It connects the net torque applied to the resulting angular acceleration.

- **The Formula:**
    
    $$\sum \tau = I\alpha$$
    
- **Multi-Radius Systems:** When pulleys have multiple tracks of different radii, the torque applied to each track contributes to the overall angular acceleration of the system.
    
- **Mass Distributions:** If two objects have the same mass but different distributions (like a hoop vs. a disk), the one with the higher rotational inertia (the hoop) will accelerate more slowly under the same torque.
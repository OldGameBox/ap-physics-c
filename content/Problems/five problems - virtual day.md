---
tags:
  - dynamics
  - u2
complete:
difficulty: 1
description: Solutions for problems 1-5 involving force, kinematics, and vectors.
---
## assignment
- **Problem 1**: A graph of $v \propto t^2$ is given. Determine which graph represents net force $F$ vs. time $t$.
	- ![[Pasted image 20260224142231.png]]
- **Problem 2**: A $1\,\text{kg}$ block and a $2\,\text{kg}$ block are connected by a string and pulled by force $F$. Find the tension in the string.
	- ![[Pasted image 20260224142250.png]]
- **Problem 3**: A $100\,\text{N}$ weight is suspended by a horizontal cord and a slanted cord at $30^\circ$ to the ceiling. Find the tension in the slanted cord.
	- ![[Pasted image 20260224142306.png]]
- **Problem 4**: A particle mass $m$ has speed $v = bt^2 + c$. Find the magnitude of net force $F$ at $t = t_1$.
	- ![[Pasted image 20260224142318.png]]
- **Problem 5**: A mass $m$ moves on a curved path from $X$ to $Y$. Identify the correct vector diagram for $v$, $a$, and $F$.
	- ![[Pasted image 20260224142332.png]]
## solution
- ### problem 1
	- **Identify relationship**: The graph shows $v \propto t^2$.
	- **Derive acceleration**: Acceleration is the derivative of velocity ($a = \frac{dv}{dt}$). If $v = kt^2$, then $a = 2kt$.
	- **Relate to force**: By Newton's Second Law, $F = ma$. Since $m$ is constant, $F \propto a$. Therefore, $F \propto t$.
	- **Graph selection**: A linear relationship $F \propto t$ starting from the origin is represented by graph **(E)**.
- ### problem 2
	- **Determine system acceleration**: Total mass $m_{total} = 1\,\text{kg} + 2\,\text{kg} = 3\,\text{kg}$. Acceleration $a = \frac{F}{3}$.
	- **Isolate the trailing block**: The tension $T$ is the only horizontal force pulling the $1\,\text{kg}$ block.
	- **Calculate tension**: $T = m_1 a = (1\,\text{kg})(\frac{F}{3}) = \frac{1}{3}F$.
	- **Result**: Choice **(E)**.
- ### problem 3
	- **Analyze vertical components**: The weight ($100\,\text{N}$) is balanced only by the vertical component of the slanted cord tension ($T_s$).
	- **Apply trigonometry**: $T_s \sin(30^\circ) = 100\,\text{N}$.
	- **Solve**: $T_s (0.5) = 100\,\text{N} \implies T_s = 200\,\text{N}$.
	- **Result**: Choice **(D)**.
- ### problem 4
	- **Find acceleration**: Use the derivative of the velocity function $v(t) = bt^2 + c$.
	- **Differentiate**: $a(t) = \frac{dv}{dt} = 2bt$.
	- **Apply Newton's Second Law**: $F = ma = m(2bt)$.
	- **Evaluate at $t_1$**: $F = 2mbt_1$.
	- **Result**: Choice **(E)**.
- ### problem 5
	- **Velocity vector**: Must always be tangent to the path in the direction of motion.
	- **Force and Acceleration**: According to $F = ma$, the vectors $F$ and $a$ must point in the same direction.
	- **Curved motion**: For an object to turn, the net force/acceleration must have a component pointing toward the concave side (inside) of the curve.
	- **Graph selection**: In diagram **(B)**, $v$ is tangent, and both $F$ and $a$ point in the same direction toward the inside of the turn.
	- **Result**: Choice **(B)**.
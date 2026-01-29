---
tags:
  - u1
  - kinematics
complete: true
difficulty: 1
description: How to find instantaneous acceleration and displacement from a given velocity function?
---
## assignment
- An object moving in a straight line has a [[velocity]] (in $\frac{\text{m}}{\text{s}}$) that varies with time (in $\text{s}$) according to the following function:
- $$v(t)=4+0.5t^{2}$$
- ### part 1
	- Find the **instantaneous** [[acceleration]] at $t=2\,\text{s}$.
- ### part 2
	- Find the [[displacement]] of the object between $t=0\,\text{s}$ and $t=6\,\text{s}$.

## solution
- ### part 1
	- To find [[acceleration]] from a [[velocity]] **function**, we must find the **derivative** of the function ($a=\frac{dv}{dt}$)
	- Using the *power rule* on $v(t)=4+0.5t^{2}$:
	- $$a(t)=0+(2)(0.5)t^{2-1}=1t$$
	- Now, we substitute $t=2\,\text{s}$:
	- $$a(2)=(1)(2)=2\frac{\text{m}}{\text{s}^2}$$
- ### part 2
	- To find [[displacement]] ($\Delta x$) from a [[velocity]] function, we must **integrate** the function *over the given time interval*.
	- $$\begin{gather} \Delta x=\int^{6}_{0}(4+0.5t^{2})dt \\ \Delta x=\left[ 4t+\frac{1}{6}t^{3} \right]^{6}_{0}=[24+36]-[0]=60\,\text{m} \end{gather}$$

## personal notes

>remember: acceleration is just the slope (derivative) of the velocity, and displacement is just the area (integral) under the velocity curve. the math is straightforward as long as I don't mess up the power rule or the fractions in the integral!


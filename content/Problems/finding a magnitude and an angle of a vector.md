---
tags:
  - u1
  - vectors
complete: true
difficulty: 1
description: How to find a magnitude & an angle of a given vector
---
## assignment
- Given vector $\vec{V}$, find $||\vec{v}||$ *([[magnitude]])* and $\theta$ *(angle)*.
- $$\begin{gather}\vec{V}=\begin{pmatrix}8,6\end{pmatrix}\\ \vec{V}= 8\hat{i}+6\hat{j}\end{gather}$$
- ![[Pasted image 20260127224329.png|300]]

## solution
- ### step 1 - finding [[magnitude]]
	- Since the given *vector* is *2-dimensional*, we can use **Pythagorean theorem** to identify **magnitude**.$$A^{2}=B^{2}+C^{2}$$
	- Using this formula, let's *substitute* $B$ for $\hat{i}$ coordinate - $8$, and $C$ for $\hat{j}$ - 6. Then, derive A, which will be our **magnitude**.$$||\vec{V}||=A=\sqrt{ 8^{2} +6^{2}}=10\, units$$
- ### step 2 - finding angle
	- Since we are already given *2 coordinates* of the *vector*, we can simply use **arctangent** do find the **angle** of the *vector*.
	- However, before calculation an angle, we must establish a **reference axis** from which the rotation begins. For now, let's select *positive $\hat{i}$ - axis*.
	- Then, we must establish an **opposite axis** - the axis we are *"opening"* the angle toward. For now, let's select *positive $\hat{j}$ - axis*.
	- Now, to find the *angle $\theta$* we use **components** of our **reference and opposite axis**:$$\begin{gather}
\theta=\arctan\left( \frac{\text{Component of Target Axis}}{\text{Component of Reference Axis}} \right) \\
\theta=\arctan\left( \frac{6}{8} \right) \approx 36.87^\circ
\end{gather}$$
	- **Interpretation**: given **vector** $\vec{V}$ is $36.87^\circ$ *counter-clockwise* from the *positive $\hat{i}$-axis*.
	- ##### generalized method
		1. **Identify Reference:** Pick the axis you want to start from. Its magnitude becomes your **denominator**.
		2. **Identify Target:** Pick the axis you are rotating toward. Its magnitude becomes your **numerator**.
		3. **Calculate**: $$\theta=\arctan\left( \frac{\text{Component of Target Axis}}{\text{Component of Reference Axis}} \right)$$

## personal notes

>pretty easy.
>the generalized method of finding an angle of a vector is pretty simple as well.
>have to remember the complete interpretation of an angle of a vector!

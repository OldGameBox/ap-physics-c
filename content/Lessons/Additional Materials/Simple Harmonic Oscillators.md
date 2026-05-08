### Simple Harmonic Motion: Analysis of a Simple Pendulum
##### Purpose
The objective of this experiment is to identify the physical factors that influence the period of a simple pendulum and to determine the specific mathematical relationship between those variables and the resulting motion. By comparing experimental data with the theoretical model for simple harmonic oscillators, the accuracy of the simple pendulum model in a real-world environment can be evaluated.
### Theoretical Background
The motion of a simple pendulum is a form of simple harmonic motion. Theoretically, the period of a pendulum is defined by the following equation:
$$T = 2\pi \sqrt{\frac{L}{g}}$$
In this expression:
- $T$ represents the period.
- $L$ represents the length of the pendulum.
- $g$ represents the acceleration due to gravity (approximately $9.81 \, \text{m/s}^2$).
Based on this model, the period should depend exclusively on the length of the string and the local gravitational field; it should remain independent of the mass of the bob and the amplitude of the swing (for small angles).
### Stage 1: Variable Identification
##### Procedure
To determine which variables influence the period, three independent variables were tested: the mass of the pendulum bob, the initial release angle (amplitude), and the length of the string.
1. The length was held constant at $29.2 \, \text{cm}$ while the mass was varied between $50 \, \text{g}$ and $100 \, \text{g}$, and the release angle was varied between $20^\circ$ and $30^\circ$.
2. The process was repeated for a shorter length of $22.1 \, \text{cm}$ to observe consistency.
3. For each trial, the frequency was measured and the period was calculated.
##### Data and Results
**Table 1: Effects of Mass and Angle on Period**

| **Trial Condition** | **Angle (∘)** | **Length (cm)** | **Mass (g)** | **Period (s)** |
| ------------------- | ------------- | --------------- | ------------ | -------------- |
| **Mass Change**     | $20$          | $29.2$          | $50$         | $0.53$         |
|                     | $30$          | $29.2$          | $50$         | $0.53$         |
|                     | $20$          | $29.2$          | $100$        | $0.53$         |
|                     | $30$          | $29.2$          | $100$        | $0.53$         |
| **Length Change**   | $20$          | $22.1$          | $50$         | $0.45$         |
|                     | $30$          | $22.1$          | $50$         | $0.46$         |
|                     | $20$          | $22.1$          | $100$        | $0.45$         |
|                     | $30$          | $22.1$          | $100$        | $0.45$         |

##### Analysis and Argument
The experimental data demonstrates that when the mass was doubled from $50 \, \text{g}$ to $100 \, \text{g}$, the period remained constant at $0.53 \, \text{s}$ (for the $29.2 \, \text{cm}$ trials). Similarly, increasing the release angle from $20^\circ$ to $30^\circ$ produced no significant change in the period. Within the limits of experimental uncertainty, mass and amplitude do not affect the period. However, changing the length from $29.2 \, \text{cm}$ to $22.1 \, \text{cm}$ resulted in a clear reduction in the period from $0.53 \, \text{s}$ to approximately $0.45 \, \text{s}$. Therefore, length is the only variable tested that influences the period.
### Stage 2: Quantitative Relationship
##### Procedure
After identifying length as the primary variable, a series of trials were conducted to determine the exact mathematical relationship between length ($L$) and period ($T$). The length was varied across six increments from $0.088 \, \text{m}$ to $0.291 \, \text{m}$. Mass and release angle were held constant throughout this stage to ensure a fair test.
##### Data and Results
**Table 2: Relationship Between Pendulum Length and Period**

|**Length (m)**|**Frequency (Hz)**|**Period (T in s)**|**L​ (Calculated)**|
|---|---|---|---|
|$0.291$|$1.8$|$0.53$|$0.539$|
|$0.254$|$2.2$|$0.48$|$0.504$|
|$0.215$|$2.3$|$0.45$|$0.464$|
|$0.174$|$2.5$|$0.39$|$0.417$|
|$0.131$|$2.9$|$0.34$|$0.362$|
|$0.088$|$3.7$|$0.27$|$0.297$|

![[Pasted image 20260508075938.png]]
##### Analysis
The initial plot of Period vs. Length resulted in a curved line, suggesting that the relationship is non-linear. However, when the period was plotted against the square root of the length ($\sqrt{L}$), the data points formed a nearly linear trend. This confirms the proportional relationship:
$$T \propto \sqrt{L}$$
Equivalently, squaring both sides yields:
$$T^2 \propto L$$
These findings align perfectly with the theoretical model, which predicts that a longer pendulum requires more time to complete an oscillation because the period is proportional to the square root of its length.
### Error Analysis and Improvements
##### Sources of Error
The experimental results were not perfectly aligned with theoretical values due to the limitations of a non-ideal system.
- **Friction and Drag:** Air resistance and friction at the pivot point slowed the pendulum, introducing slight variances in the measured period.
- **Measurement Inaccuracy:** Small errors in measuring the string length manually likely contributed to the total uncertainty.
- **Center of Mass:** Length was likely measured to the top of the bob rather than the center of mass, which creates a systematic offset in the data.
##### Proposed Improvements
To increase precision in future iterations:
1. **Mechanical Release:** A fixed release mechanism should be used to ensure the starting angle is identical for every trial.
2. **Improved Length Measurement:** Measurements should be taken from the pivot point to the calculated center of mass of the bob to reduce the percentage of error.
### Conclusion
This investigation confirmed that for a simple pendulum, the period is independent of both the mass of the bob and the amplitude of oscillation. The experimental data clearly established that the length of the pendulum is the determining factor of its period, with the relationship being non-linear. Specifically, the period is proportional to the square root of the length ($T \propto \sqrt{L}$), which is in direct agreement with the theoretical equation for simple harmonic motion.
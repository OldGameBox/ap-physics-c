### Simple Harmonic Motion: Analysis of a Simple Pendulum
##### Purpose
This experiment aims to establish the physical factors that affect a basic pendulum's period and to determine the precise mathematical link between those variables and the motion that results. By comparing experimental data with the theoretical model for simple harmonic oscillators, the accuracy of the simple pendulum model in a real-world environment can be evaluated.
### Theoretical Background
The motion of a simple pendulum is a form of simple harmonic motion. Theoretically, the period of a pendulum is defined by the following equation:
$$T = 2\pi \sqrt{\frac{L}{g}}$$
In this expression:
- $T$ represents the period.
- $L$ represents the length of the pendulum.
- $g$ represents the acceleration due to gravity (approximately $9.81 \, \text{m/s}^2$).
According to this theory, the period should only be influenced by the local gravitational field and the string's length. It should not be affected by the bob's mass or the swing's amplitude.
### Stage 1: Variable Identification
##### Procedure
Three separate factors were tried to find out which ones affect the period: the pendulum bob's mass, the angle of release at the start, and the string's length.
1. The release angle was varied between $20^\circ$ and $30^\circ$, the mass was varied between $50^g$ and $100^g$, and the length was fixed at $29.2cm$.
2. To check for consistency, the procedure was repeated for a shorter length of $22.1\text{cm}$.
3. The time was computed and the frequency was measured for every trial.
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
The experimental data shows that the period stayed constant at $0.53◦ \text{s}$ (for the $29.2◦ \text{cm}$ trials) when the mass was doubled from $50◦ \text{g}$ to $100◦ \text{g}$. Similarly, there was no significant difference in the period when the release angle was increased from $20^\circ$ to $30^\circ$. Mass and amplitude have no effect on the period within the bounds of experimental uncertainty. However, the period was clearly reduced from $0.53\text{s}$ to around $0.45\text{s}$ when the length was changed from $29.2\text{cm}$ to $22.1\text{cm}$. As a result, the only variable examined that affects the period is length.
### Stage 2: Quantitative Relationship
##### Procedure
To find the precise mathematical relationship between length ($L$) and period ($T$), a number of experiments were carried out after length was determined to be the main variable. Six increments were used to change the length, ranging from $0.088\text{m}$ to $0.291\text{m}$. To guarantee a fair test, mass and release angle were kept constant during this phase.
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
This aligns perfectly with the theoretical model, which predicts that a longer pendulum requires more time to complete an oscillation because the period is proportional to the square root of its length.
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
This experiment verified that the period of a basic pendulum is independent of both the oscillation amplitude and the bob's mass. The experimental results demonstrated that the pendulum's length determines its period, with a non-linear relationship. In particular, the period is directly consistent with the theoretical equation for simple harmonic motion since it is proportional to the square root of the length ($T \propto \sqrt{L}$).
### Glossary of Thermodynamics Terms

##### System & Surroundings

A system is the specific portion of the universe isolated for thermodynamic analysis. Conversely, the surroundings encompass everything external to that system capable of exchanging energy with it.

##### State Variable & Path Variable

State variables, including pressure $P$, volume $V$, and temperature $T$, depend solely on the current equilibrium state of the system. Path variables, such as heat $Q$ and work $W$, are process-dependent quantities determined by the transition path between states.

##### Thermal Equilibrium

Thermal equilibrium represents a condition where interacting systems reach an identical temperature. Consequently, net heat transfer between these systems drops to zero.

##### Pressure & Temperature

Pressure represents the force per unit area exerted by continuous gas particle collisions against the container walls. Temperature serves as a macroscopic indicator proportional to the average translational kinetic energy of those particles.

##### Internal Energy

Internal energy $U$ comprises the total microscopic energy stored within a system. This incorporates the cumulative sum of all constituent particle kinetic and potential energies.

##### Heat & Work

Heat $Q$ represents energy transferred spontaneously between systems due exclusively to a temperature gradient. Work $W$ refers to energy transferred through macroscopically organized mechanical interactions, such as gas expansion or compression.

##### Entropy

Entropy $S$ constitutes a fundamental state function quantifying energy dispersal within a physical system. It scales logarithmically with the number of accessible microscopic configurations corresponding to a macroscopic state.

##### Thermodynamic Processes

An isothermal process occurs at a constant temperature, while an isobaric process maintains a constant pressure. An isochoric process features a constant volume with zero boundary work, and an adiabatic process involves zero net heat exchange ($Q=0$).

##### Quasi-static & Reversible Processes

A quasi-static process occurs infinitely slowly, ensuring the system remains infinitesimally close to thermodynamic equilibrium at every step. A reversible process is an idealized pathway that can be perfectly inverted without increasing total universal entropy.

##### Absolute Zero

Absolute zero ($0\text{ K}$ or $-273.15^\circ\text{C}$) marks the theoretical lower limit of thermodynamic temperature. At this point, the fundamental translational kinetic energy of ideal gas particles reaches zero.

##### Boltzmann Constant

The Boltzmann constant ($k_B = 1.38 \times 10^{-23}\text{ J/K}$) establishes a fundamental scaling factor in physics. It directly bridges macroscopic absolute temperature with the microscopic kinetic energy of individual particles.

##### Heat Transfer Mechanisms

Conduction transfers thermal energy via direct molecular collisions within or between materials. Convection involves bulk fluid displacement driven by buoyancy or external forces, while radiation transfers energy through electromagnetic waves without requiring a physical medium.

##### Heat Capacities & Latent Heats

Specific heat capacity $c$ dictates the energy required to modify the temperature of $1\text{ kg}$ of a substance by $1\text{ K}$. Latent heat $L$ (comprising fusion $L_f$ and vaporization $L_v$) defines the energy per unit mass exchanged during isothermal phase transitions.

##### Phase Change & Thermal Expansion

A phase change marks a structural transition between solid, liquid, or gas states where temperature remains constant as intermolecular bonds alter. Thermal expansion describes the geometric growth of matter under heating, governed by the linear expansion coefficient $\alpha$.

### The Laws of Thermodynamics

##### Zeroth Law

The Zeroth Law asserts that if system A is in thermal equilibrium with system B, and B is in equilibrium with system C, then A is in equilibrium with C. This transitive relationship establishes a rigorous foundation for defining temperature scales and manufacturing thermometers.

##### First Law

The First Law enforces the conservation of energy, written as $\Delta U = Q + W_{\text{on}}$, where $W_{\text{on}}$ is work executed on the system. Alternatively, using work done by the system yields $\Delta U = Q - W_{\text{by}}$, emphasizing that internal energy changes solely via heat and work.

##### Second Law

The Second Law dictates that the cumulative entropy of an isolated system, and thus the entire universe, can never decrease over time. For any spontaneous, real-world physical process, this net entropy change satisfies the inequality $\Delta S_{\text{universe}} \ge 0$.

##### Third Law

The Third Law states that as the absolute temperature of a perfect, flawless crystal approaches $0\text{ K}$, its thermodynamic entropy approaches a minimum constant value. Consequently, it is physically impossible to cool any real system to absolute zero using a finite sequence of operations.

### The Ideal Gas Law from a Physics Perspective

##### Macroscopic and Microscopic Formulations

The macroscopic chemistry formulation utilizes moles via $PV = nRT$, where $R$ represents the universal gas constant. The physics perspective shifts to individual particles using $PV = Nk_BT$, where $N$ counts the exact number of gas molecules.

##### Connecting Scales

The conversion between macroscopic and microscopic variables depends on Avogadro's number through the identity $N = nN_A$. This relation reveals that both versions describe identical physical laws, as demonstrated by the substitution $R = N_A k_B$.

##### Misconceptions and Physical Realities

Absolute temperature must always be entered in Kelvin, and volume must be converted into cubic meters ($\text{m}^3$) for proper SI consistency. Furthermore, ideal gas pressure stems from discrete impulse collisions rather than a continuous pushing force, and individual particles retain kinetic energy despite zero mutual potential energy.

### Kinetic Theory of Gases

##### Energy and Temperature Links

Kinetic theory uses Newtonian mechanics and statistics to prove that absolute temperature strictly measures average translational kinetic energy. For an ideal monatomic gas, this relationship is explicitly formalized by the expression $\overline{K}_{\text{trans}} = \frac{3}{2}k_BT$.

##### Internal Energy Calculation

Because ideal gas particles lack mutual intermolecular potential energy, internal energy $U$ depends entirely on total translational kinetic energy. This yields the state equation $U = \frac{3}{2}Nk_BT = \frac{3}{2}nRT$ for a monatomic gas sample.

##### Pressure and Molecular Speed

Pressure can be directly linked to microscopic particle properties through the expression $PV = \frac{1}{3}Nm\overline{v^2}$, where $\overline{v^2}$ is the mean-squared speed. This highlights that gas pressure intensifies when particles are more numerous, more massive, moving faster, or more closely confined.

### Calculus-Based Work in Thermodynamics

##### Work Integral Formulations

Thermodynamic work is fundamentally calculated as the geometric area bounded beneath a process curve plotted on a pressure-volume graph. The work performed by an expanding gas is expressed as $W_{\text{by}} = \int_{V_i}^{V_f} P(V)\,dV$, which implies that work done on the gas equals $W_{\text{on}} = -\int_{V_i}^{V_f} P(V)\,dV$.

##### Variable Pressure Processes

When pressure varies dynamically as a function of volume, integration is required to compute total work. For instance, an isothermal ideal gas expansion tracking $P(V) = \frac{C}{V}$ evaluates mathematically into a logarithmic work relationship.

##### Linear p–V Path Approximation

For transitions tracking a straight line on a p–V diagram, work can be solved without integration by treating the area as a geometric trapezoid. The resulting calculation simplifies to $W_{\text{by}} = \frac{P_i + P_f}{2}(V_f - V_i)$, provided units are converted properly to Pascals and cubic meters.

### Entropy and the Second Law

##### Reversible Process Integration

The exact change in entropy during a reversible thermodynamic process is evaluated using the line integral $\Delta S = \int \frac{dQ_{\text{rev}}}{T}$. For processes occurring at a fixed, constant temperature, this expression naturally simplifies to $\Delta S = \frac{Q_{\text{rev}}}{T}$.

##### Temperature Adjustments and Heat Capacities

When a substance undergoes heating or cooling without experiencing a phase change, its entropy shifts continuously alongside temperature. Assuming a constant specific heat capacity, this total entropy variation calculates precisely via $\Delta S = mc \ln\left(\frac{T_f}{T_i}\right)$.

##### Isothermal Gas Expansion

During an isothermal expansion, an ideal gas absorbs heat to maintain its temperature while its volume increases. This structural dispersion increases the system's microscopic configurations, resulting in a positive entropy change calculated by $\Delta S = nR \ln\left(\frac{V_f}{V_i}\right)$.

### Heat Transfer

##### Fundamental Heat Equation

Sensible heat transfer changes a substance's temperature without inducing a phase transition. This energy quantity is modeled by the linear relationship $Q = mc\Delta T$, which dictates that heat flows naturally from higher temperatures to lower temperatures.

##### Conduction and Fourier's Law

Conduction governs thermal energy transmission via localized molecular vibrations moving down a structural gradient. The corresponding steady-state heat transfer rate is mathematically evaluated using Fourier's law, $\frac{Q}{t} = \frac{kA\,\Delta T}{L}$.

##### Convection and Radiation

Convection relies on bulk fluid motion driven by density variations to carry thermal energy across space. Radiation requires no material medium, conveying thermal energy via electromagnetic emission governed by the Stefan-Boltzmann law, $P = \varepsilon\sigma A T^4$.

### Phase Changes and Latent Heat

##### Characteristics of Phase Change

Phase changes involve transitioning between solid, liquid, or gas states where temperature fundamentally pauses at a constant plateau. The thermal energy absorbed or released during these periods goes exclusively toward rearranging intermolecular bonds rather than modifying kinetic speed.

##### Latent Heat Formulations

The energy required to transition a given mass through a phase boundary is modeled by the formula $Q = mL$. This utilizes the latent heat of fusion $L_f$ for melting and freezing, or the latent heat of vaporization $L_v$ for boiling and condensation.

##### Heating Curves

Heating curves map temperature shifts against total heat added, breaking the process down into five distinct physical stages. These alternative between sloped regions governed by $Q = mc\Delta T$ and flat isothermal phase-change plateaus governed by $Q = mL$.

### Thermal Expansion

##### Linear Expansion in One Dimension

Heating a solid object intensifies atomic vibrations, which pushes its average structural equilibrium spacing outward. For a single dimension, this change in length scales linearly with temperature according to the relation $\Delta L = \alpha L_0\,\Delta T$.

##### Area Expansion in Two Dimensions

When a flat, two-dimensional sheet undergoes thermal expansion, its surface area expands proportionally across both dimensions. This geometric growth is modeled using the mathematical approximation $\Delta A \approx 2\alpha A_0\,\Delta T$.

##### Physical Applications

Accounting for thermal expansion is essential for modern infrastructure engineering to prevent catastrophic mechanical warping. Structural features like bridge joints, railroad gaps, and concrete pavement seams are deliberately integrated to accommodate fluctuating material volumes safely.

### Graph Interpretation

##### p–V Diagrams and Boundary Work

On a classic p–V diagram, the mathematical area beneath a process path tracks mechanical work. Graphical tracks running left-to-right (expansion) mean positive work is done by the gas, whereas right-to-left tracks (compression) mean work is negative.

##### Cyclic Process Loops

A closed loop mapped on a p–V plot represents a complete heat engine cycle returning to its initial state. The net mechanical work delivered per full cycle equals the total area enclosed within the boundaries of the loop.

##### Heating Curve Plateaus

When a temperature-versus-time heating curve flattens into a horizontal line, it indicates that a phase change is actively occurring. Despite a continuous external heat input, the temperature stalls because energy is dedicated entirely to breaking intermolecular structural bonds.

### Problems

![[photo_2026-05-27_08-00-24.jpg]]
![[photo_2026-05-27_08-00-28.jpg]]
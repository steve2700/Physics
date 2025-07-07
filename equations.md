# Essential Physics Equations Reference

## Table of Contents
1. [Classical Mechanics](#classical-mechanics)
2. [Thermodynamics](#thermodynamics)
3. [Electromagnetism](#electromagnetism)
4. [Quantum Mechanics](#quantum-mechanics)
5. [Special Relativity](#special-relativity)
6. [Fluid Dynamics](#fluid-dynamics)
7. [Waves and Optics](#waves-and-optics)
8. [Statistical Physics](#statistical-physics)
9. [Solid State Physics](#solid-state-physics)
10. [Nuclear Physics](#nuclear-physics)

---

## Classical Mechanics

### Newton's Laws
```
F = ma                          (Newton's Second Law)
F₁₂ = -F₂₁                     (Newton's Third Law)
```

### Kinematics
```
v = v₀ + at                     (Velocity)
s = v₀t + ½at²                  (Position)
v² = v₀² + 2as                  (Velocity-Position)
```

### Energy and Work
```
W = F·d = Fd cos θ              (Work)
KE = ½mv²                       (Kinetic Energy)
PE = mgh                        (Gravitational Potential Energy)
E = KE + PE                     (Total Mechanical Energy)
```

### Momentum
```
p = mv                          (Linear Momentum)
J = Δp = F·Δt                   (Impulse)
```

### Rotational Motion
```
τ = r × F = rF sin θ            (Torque)
L = r × p = Iω                  (Angular Momentum)
I = Σmᵢrᵢ²                      (Moment of Inertia)
KE_rot = ½Iω²                   (Rotational Kinetic Energy)
```

### Oscillations
```
x(t) = A cos(ωt + φ)            (Simple Harmonic Motion)
ω = √(k/m)                      (Angular Frequency)
T = 2π/ω = 2π√(m/k)             (Period)
f = 1/T = ω/2π                  (Frequency)
```

### Gravitation
```
F = G(m₁m₂)/r²                  (Newton's Law of Gravitation)
g = GM/r²                       (Gravitational Field)
U = -G(m₁m₂)/r                  (Gravitational Potential Energy)
```

---

## Thermodynamics

### Laws of Thermodynamics
```
ΔU = Q - W                      (First Law)
ΔS ≥ 0                          (Second Law - Entropy)
S = 0 at T = 0                  (Third Law)
```

### Ideal Gas
```
PV = nRT                        (Ideal Gas Law)
PV = NkT                        (Boltzmann Form)
```

### Heat and Temperature
```
Q = mcΔT                        (Heat Capacity)
Q = mL                          (Latent Heat)
```

### Thermodynamic Processes
```
W = ∫P dV                       (Work Done)
η = W/Q_h = 1 - Q_c/Q_h         (Efficiency)
COP = Q_c/W                     (Coefficient of Performance)
```

### Entropy
```
S = k ln Ω                      (Boltzmann Entropy)
dS = dQ/T                       (Entropy Change)
```

---

## Electromagnetism

### Coulomb's Law
```
F = k(q₁q₂)/r² = (1/4πε₀)(q₁q₂)/r²    (Coulomb's Law)
```

### Electric Field and Potential
```
E = F/q = kQ/r²                 (Electric Field)
V = kQ/r                        (Electric Potential)
E = -∇V                         (Field-Potential Relation)
```

### Gauss's Law
```
∮E·dA = Q_enc/ε₀                (Gauss's Law)
```

### Capacitance
```
C = Q/V                         (Capacitance)
U = ½CV² = ½QV = Q²/2C          (Energy Stored)
```

### Current and Resistance
```
I = Q/t = nqvA                  (Current)
V = IR                          (Ohm's Law)
R = ρL/A                        (Resistance)
P = IV = I²R = V²/R             (Power)
```

### Magnetic Field
```
F = q(v × B)                    (Lorentz Force)
F = IL × B                      (Force on Current)
B = μ₀I/2πr                     (Magnetic Field of Wire)
```

### Electromagnetic Induction
```
ε = -dΦ/dt                      (Faraday's Law)
Φ = ∫B·dA                       (Magnetic Flux)
ε = BLv                         (Motional EMF)
```

### Maxwell's Equations
```
∇·E = ρ/ε₀                      (Gauss's Law)
∇·B = 0                         (No Magnetic Monopoles)
∇×E = -∂B/∂t                    (Faraday's Law)
∇×B = μ₀J + μ₀ε₀∂E/∂t          (Ampère-Maxwell Law)
```

### Electromagnetic Waves
```
c = 1/√(μ₀ε₀) = 3×10⁸ m/s       (Speed of Light)
c = fλ                          (Wave Equation)
I = ½cε₀E₀²                     (Intensity)
```

---

## Quantum Mechanics

### Fundamental Equations
```
E = hf = ħω                     (Planck-Einstein Relation)
p = h/λ = ħk                    (de Broglie Relation)
ΔxΔp ≥ ħ/2                     (Heisenberg Uncertainty)
```

### Schrödinger Equation
```
iħ∂ψ/∂t = Ĥψ                   (Time-Dependent)
Ĥψ = Eψ                        (Time-Independent)
```

### Wave Function
```
|ψ|² = ψ*ψ                     (Probability Density)
∫|ψ|²dτ = 1                    (Normalization)
⟨x⟩ = ∫ψ*xψ dτ                 (Expectation Value)
```

### Operators
```
p̂ = -iħ∇                       (Momentum Operator)
Ĥ = -ħ²/2m ∇² + V              (Hamiltonian)
L̂ = r̂ × p̂                      (Angular Momentum)
```

### Hydrogen Atom
```
E_n = -13.6 eV/n²              (Energy Levels)
r_n = n²a₀                     (Bohr Radius)
a₀ = ħ²/me² = 0.529 Å          (Bohr Radius)
```

### Spin
```
S = ½ħ                         (Spin Angular Momentum)
μ = -gμ_BS/ħ                   (Magnetic Moment)
```

---

## Special Relativity

### Lorentz Transformation
```
γ = 1/√(1 - v²/c²)             (Lorentz Factor)
t' = γ(t - vx/c²)              (Time Transformation)
x' = γ(x - vt)                 (Space Transformation)
```

### Relativistic Mechanics
```
E = γmc²                       (Total Energy)
E₀ = mc²                       (Rest Energy)
p = γmv                        (Relativistic Momentum)
E² = (pc)² + (mc²)²            (Energy-Momentum Relation)
```

### Time Dilation and Length Contraction
```
Δt = γΔt₀                      (Time Dilation)
L = L₀/γ                       (Length Contraction)
```

---

## Fluid Dynamics

### Continuity Equation
```
∂ρ/∂t + ∇·(ρv) = 0            (Mass Conservation)
A₁v₁ = A₂v₂                    (Incompressible Flow)
```

### Euler's Equation
```
∂v/∂t + (v·∇)v = -∇p/ρ + g     (Euler's Equation)
```

### Bernoulli's Equation
```
½ρv² + p + ρgh = constant     (Bernoulli's Equation)
```

### Navier-Stokes Equation
```
∂v/∂t + (v·∇)v = -∇p/ρ + ν∇²v + g    (Navier-Stokes)
```

### Reynolds Number
```
Re = ρvL/μ = vL/ν              (Reynolds Number)
```

---

## Waves and Optics

### Wave Equation
```
∂²y/∂t² = v²∂²y/∂x²            (Wave Equation)
y(x,t) = A sin(kx - ωt + φ)    (Sinusoidal Wave)
v = fλ = ω/k                   (Wave Speed)
```

### Interference
```
δ = |r₁ - r₂|                  (Path Difference)
Constructive: δ = nλ           (n = 0,1,2,...)
Destructive: δ = (n + ½)λ      (n = 0,1,2,...)
```

### Diffraction
```
a sin θ = nλ                   (Single Slit Minima)
d sin θ = nλ                   (Diffraction Grating)
```

### Snell's Law
```
n₁ sin θ₁ = n₂ sin θ₂          (Snell's Law)
n = c/v                        (Refractive Index)
```

### Thin Lens Equation
```
1/f = 1/d₀ + 1/dᵢ              (Thin Lens Equation)
M = -dᵢ/d₀                     (Magnification)
```

---

## Statistical Physics

### Boltzmann Distribution
```
P(E) = (1/Z)e^(-E/kT)          (Boltzmann Distribution)
Z = Σe^(-Eᵢ/kT)                (Partition Function)
```

### Maxwell-Boltzmann Distribution
```
f(v) = 4π(m/2πkT)^(3/2) v²e^(-mv²/2kT)    (Velocity Distribution)
⟨v⟩ = √(8kT/πm)                (Average Speed)
v_rms = √(3kT/m)               (RMS Speed)
```

### Fermi-Dirac Distribution
```
f(E) = 1/(e^((E-μ)/kT) + 1)    (Fermi-Dirac Distribution)
```

### Bose-Einstein Distribution
```
f(E) = 1/(e^((E-μ)/kT) - 1)    (Bose-Einstein Distribution)
```

---

## Solid State Physics

### Crystal Structure
```
a⃗ = n₁a⃗₁ + n₂a⃗₂ + n₃a⃗₃        (Lattice Vectors)
G⃗ = h b⃗₁ + k b⃗₂ + l b⃗₃        (Reciprocal Lattice)
```

### Band Theory
```
E = ħ²k²/2m*                   (Effective Mass)
σ = neμ                        (Conductivity)
```

### Phonons
```
ω = v|k|                       (Phonon Dispersion)
C_V = 3Nk(ħω/kT)²e^(ħω/kT)/(e^(ħω/kT)-1)²    (Einstein Model)
```

---

## Nuclear Physics

### Radioactive Decay
```
N(t) = N₀e^(-λt)               (Exponential Decay)
t₁/₂ = ln(2)/λ                 (Half-Life)
A = λN                         (Activity)
```

### Nuclear Reactions
```
Q = (M_initial - M_final)c²    (Q-Value)
```

### Binding Energy
```
BE = [ZM_H + (A-Z)M_n - M_nucleus]c²    (Binding Energy)
```

### Nuclear Radius
```
R = r₀A^(1/3)                  (Nuclear Radius)
r₀ ≈ 1.2 fm                    (Nuclear Radius Constant)
```

---

## Constants and Conversions

### Fundamental Constants
```
c = 2.998 × 10⁸ m/s           (Speed of Light)
h = 6.626 × 10⁻³⁴ J·s         (Planck's Constant)
ħ = h/2π = 1.055 × 10⁻³⁴ J·s  (Reduced Planck's Constant)
e = 1.602 × 10⁻¹⁹ C           (Elementary Charge)
k = 8.988 × 10⁹ N·m²/C²       (Coulomb's Constant)
ε₀ = 8.854 × 10⁻¹² F/m        (Permittivity of Free Space)
μ₀ = 4π × 10⁻⁷ H/m            (Permeability of Free Space)
G = 6.674 × 10⁻¹¹ N·m²/kg²    (Gravitational Constant)
k_B = 1.381 × 10⁻²³ J/K       (Boltzmann Constant)
R = 8.314 J/(mol·K)           (Gas Constant)
N_A = 6.022 × 10²³ mol⁻¹      (Avogadro's Number)
m_e = 9.109 × 10⁻³¹ kg        (Electron Mass)
m_p = 1.673 × 10⁻²⁷ kg        (Proton Mass)
m_n = 1.675 × 10⁻²⁷ kg        (Neutron Mass)
```

### Unit Conversions
```
1 eV = 1.602 × 10⁻¹⁹ J
1 u = 931.5 MeV/c²
1 Å = 10⁻¹⁰ m
1 barn = 10⁻²⁴ cm²
1 atm = 101,325 Pa
0°C = 273.15 K
```

---

*This reference contains the most essential equations across all major areas of physics. Each equation is presented in its most commonly used form with standard notation.*

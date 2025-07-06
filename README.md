# Important Physics Topics: Calculations and Real-World Applications

## Table of Contents
1. [Mechanics and Motion](#mechanics-and-motion)
2. [Energy and Work](#energy-and-work)
3. [Waves and Sound](#waves-and-sound)
4. [Electricity and Magnetism](#electricity-and-magnetism)
5. [Thermodynamics](#thermodynamics)
6. [Optics and Light](#optics-and-light)
7. [Modern Physics](#modern-physics)
8. [Fluid Mechanics](#fluid-mechanics)

---

## Mechanics and Motion

### Newton's Laws of Motion

**First Law (Law of Inertia):** An object at rest stays at rest, and an object in motion stays in motion at constant velocity, unless acted upon by an external force.

**Second Law:** F = ma (Force equals mass times acceleration)

**Third Law:** For every action, there is an equal and opposite reaction.

### Key Calculations

**Velocity and Acceleration:**
- v = u + at (final velocity = initial velocity + acceleration × time)
- s = ut + ½at² (displacement equation)
- v² = u² + 2as (velocity-displacement relationship)

**Force and Motion:**
- F = ma
- Weight: W = mg (where g = 9.8 m/s² on Earth)

### Real-World Applications

**Car Safety Systems:**
When a car traveling at 60 km/h (16.7 m/s) crashes into a wall, the deceleration can be enormous. If the car stops in 0.1 seconds:

```
a = (v - u)/t = (0 - 16.7)/0.1 = -167 m/s²
```

This is about 17 times the force of gravity! Airbags and crumple zones extend the stopping time to reduce this deadly acceleration.

**Rocket Propulsion:**
The Saturn V rocket that took astronauts to the Moon demonstrates Newton's third law. The rocket burns fuel to expel hot gases downward at high velocity, creating an upward thrust force.

**Satellite Orbits:**
The International Space Station orbits Earth at about 27,600 km/h. The gravitational force provides the centripetal force needed for circular motion:

```
F_gravitational = F_centripetal
GMm/r² = mv²/r
```

This balance keeps the ISS in stable orbit at approximately 408 km above Earth.

---

## Energy and Work

### Fundamental Concepts

**Work:** W = F × d × cos(θ)
- Work is done when a force causes displacement
- Measured in Joules (J)

**Kinetic Energy:** KE = ½mv²
**Potential Energy:** PE = mgh (gravitational)
**Conservation of Energy:** Total energy remains constant in isolated systems

### Key Calculations

**Power:** P = W/t = F × v
- Measured in Watts (W)

**Efficiency:** η = (Useful energy output)/(Total energy input) × 100%

### Real-World Applications

**Hydroelectric Power:**
The Hoover Dam generates electricity using gravitational potential energy. Water falling from height h converts PE to KE:

```
PE = mgh
For 1000 kg of water falling 221 m:
PE = 1000 × 9.8 × 221 = 2.17 × 10⁶ J
```

This energy is converted to electrical energy through turbines and generators.

**Roller Coasters:**
At the top of a hill, a roller coaster car has maximum potential energy. As it descends, PE converts to KE:

```
At top: PE = mgh, KE = 0
At bottom: PE = 0, KE = ½mv²
Therefore: mgh = ½mv²
Solving for velocity: v = √(2gh)
```

**Wind Energy:**
Wind turbines capture kinetic energy from moving air masses. The power available in wind is:

```
P = ½ρAv³
```
Where ρ is air density, A is swept area, and v is wind speed. This cubic relationship explains why wind speed is so crucial for wind power generation.

---

## Waves and Sound

### Wave Properties

**Wave Equation:** v = fλ
- v = velocity, f = frequency, λ = wavelength

**Sound Speed:** v = 343 m/s in air at 20°C

### Key Calculations

**Frequency and Period:** f = 1/T
**Doppler Effect:** f' = f(v ± v_observer)/(v ± v_source)

### Real-World Applications

**Medical Ultrasound:**
Ultrasound uses high-frequency sound waves (2-18 MHz) to image internal body structures. The waves reflect off tissue boundaries, and the time delay reveals depth:

```
Distance = (velocity × time)/2
For tissue (v ≈ 1540 m/s), if echo returns in 0.1 ms:
Distance = (1540 × 0.0001)/2 = 0.077 m = 7.7 cm
```

**Radar and GPS:**
Radio waves travel at the speed of light (3 × 10⁸ m/s). GPS satellites use precise timing to determine location:

```
Distance = c × t
If signal takes 0.067 seconds to reach satellite:
Distance = 3 × 10⁸ × 0.067 = 20,100 km
```

**Earthquake Detection:**
Seismographs detect P-waves (primary) and S-waves (secondary) that travel at different speeds through Earth. The time difference helps locate earthquake epicenters:

```
Distance = (t_S - t_P) × v_P × v_S/(v_P - v_S)
```

---

## Electricity and Magnetism

### Fundamental Laws

**Ohm's Law:** V = IR
**Power:** P = VI = I²R = V²/R
**Coulomb's Law:** F = kq₁q₂/r²

### Key Calculations

**Electrical Energy:** E = Pt = VIt
**Capacitance:** C = Q/V
**Magnetic Force:** F = BIL (on current-carrying conductor)

### Real-World Applications

**Household Electricity:**
A typical home uses about 30 kWh per day. For a 100W light bulb running 8 hours:

```
Energy = Power × Time = 100W × 8h = 800 Wh = 0.8 kWh
Cost = 0.8 kWh × $0.12/kWh = $0.096 per day
```

**Electric Motors:**
Electric vehicles use motors that convert electrical energy to mechanical energy. A Tesla Model S motor produces about 375 kW:

```
At 400V and 94% efficiency:
Current = P/(V × η) = 375,000/(400 × 0.94) = 996 A
```

**Electromagnetic Induction:**
Generators in power plants use Faraday's law to produce electricity. When a coil rotates in a magnetic field:

```
EMF = -N(dΦ/dt) = -N × B × A × ω × sin(ωt)
```

This principle powers everything from bicycle dynamos to massive power station generators.

---

## Thermodynamics

### Laws of Thermodynamics

**First Law:** ΔU = Q - W (Energy conservation)
**Second Law:** Entropy of isolated systems always increases
**Third Law:** Entropy approaches zero as temperature approaches absolute zero

### Key Calculations

**Heat Transfer:** Q = mcΔT
**Ideal Gas Law:** PV = nRT
**Efficiency:** η = 1 - T_cold/T_hot (Carnot engine)

### Real-World Applications

**Internal Combustion Engines:**
A car engine operates on the Otto cycle. For a typical engine with compression ratio 10:1:

```
Theoretical efficiency = 1 - (1/r)^(γ-1)
η = 1 - (1/10)^(1.4-1) = 1 - (0.1)^0.4 = 60%
```

Actual efficiency is lower due to friction, heat loss, and incomplete combustion.

**Refrigerators:**
Refrigerators move heat from cold interior to warm exterior. The coefficient of performance (COP):

```
COP = T_cold/(T_hot - T_cold)
For typical refrigerator: COP = 278K/(298K - 278K) = 13.9
```

**Heat Pumps:**
Heat pumps can be 3-4 times more efficient than electric heating because they move heat rather than generate it:

```
COP_heating = T_hot/(T_hot - T_cold)
For heat pump: COP = 298K/(298K - 273K) = 11.9
```

---

## Optics and Light

### Fundamental Principles

**Snell's Law:** n₁sin(θ₁) = n₂sin(θ₂)
**Lens Equation:** 1/f = 1/u + 1/v
**Mirror Equation:** Same as lens equation

### Key Calculations

**Magnification:** m = v/u = h'/h
**Critical Angle:** θc = sin⁻¹(n₂/n₁)

### Real-World Applications

**Optical Fibers:**
Internet data travels through optical fibers using total internal reflection. For silica fiber (n = 1.46) in air:

```
Critical angle = sin⁻¹(1/1.46) = 43.2°
```

Light rays entering at angles greater than this are trapped and can travel long distances with minimal loss.

**Camera Lenses:**
Camera focal length determines field of view. For a 35mm camera:

```
Field of view = 2 × tan⁻¹(d/2f)
For 50mm lens: FOV = 2 × tan⁻¹(36/100) = 39.6°
```

**Microscopes:**
Microscope resolution is limited by light wavelength:

```
Resolution = 1.22λ/(2NA)
For visible light (λ = 500 nm) and NA = 1.4:
Resolution = 1.22 × 500 × 10⁻⁹/(2 × 1.4) = 218 nm
```

This is why electron microscopes (shorter wavelength) can resolve much smaller details.

---

## Modern Physics

### Quantum Mechanics

**Planck's Equation:** E = hf
**de Broglie Wavelength:** λ = h/p
**Uncertainty Principle:** Δx × Δp ≥ ℏ/2

### Relativity

**Time Dilation:** t' = t/√(1 - v²/c²)
**Length Contraction:** L' = L√(1 - v²/c²)
**Mass-Energy:** E = mc²

### Real-World Applications

**GPS Satellites:**
GPS satellites experience both special and general relativistic effects. Without relativistic corrections:

```
Special relativity: Δt = -7.2 μs/day (time runs slower)
General relativity: Δt = +45.9 μs/day (time runs faster)
Net effect: +38.7 μs/day
```

Without these corrections, GPS accuracy would degrade by about 11 km per day!

**Nuclear Power:**
Nuclear fission releases energy according to E = mc². When uranium-235 fissions:

```
Mass defect ≈ 0.2 amu = 0.2 × 931.5 MeV = 186.3 MeV per fission
For 1 kg of U-235: Energy = 8.2 × 10¹³ J
```

This is millions of times more energy than chemical reactions.

**Photoelectric Effect:**
Solar panels use the photoelectric effect. For silicon (work function 1.12 eV):

```
Maximum kinetic energy = hf - φ
For 600 nm light: KE = (1240 eV⋅nm)/600 nm - 1.12 eV = 0.95 eV
```

---

## Fluid Mechanics

### Fundamental Principles

**Pressure:** P = F/A
**Buoyancy:** F_buoyant = ρ_fluid × V_displaced × g
**Continuity Equation:** A₁v₁ = A₂v₂
**Bernoulli's Equation:** P + ½ρv² + ρgh = constant

### Real-World Applications

**Airplane Flight:**
Airplane wings generate lift through pressure differences. Using Bernoulli's equation:

```
Lift = ½ρ(v₂² - v₁²) × A
For typical conditions: Lift ≈ 1000 N/m² wing area
```

**Blood Pressure:**
Blood pressure measurements use fluid mechanics. Normal blood pressure (120/80 mmHg):

```
Systolic: 120 mmHg = 120 × 133.3 Pa = 16,000 Pa
Diastolic: 80 mmHg = 80 × 133.3 Pa = 10,664 Pa
```

**Hydraulic Systems:**
Hydraulic brakes multiply force using Pascal's principle:

```
F₂/F₁ = A₂/A₁
If brake pedal area = 5 cm², brake pad area = 50 cm²:
Force multiplication = 50/5 = 10 times
```

---

## Conclusion

These physics principles and calculations form the foundation of our technological world. From the smartphone in your pocket to the GPS guiding your car, from the electricity powering your home to the medical devices saving lives, physics is everywhere. Understanding these concepts not only satisfies our curiosity about how the world works but also enables us to design better technologies, solve complex problems, and make informed decisions about the future.

The mathematical relationships described here are not just abstract formulas—they represent the fundamental rules that govern our universe. By mastering these concepts, we gain the tools to understand, predict, and manipulate the physical world around us, opening doors to innovation and discovery that continue to transform human civilization.# Important Physics Topics: Calculations and Real-World Applications

## Table of Contents
1. [Mechanics and Motion](#mechanics-and-motion)
2. [Energy and Work](#energy-and-work)
3. [Waves and Sound](#waves-and-sound)
4. [Electricity and Magnetism](#electricity-and-magnetism)
5. [Thermodynamics](#thermodynamics)
6. [Optics and Light](#optics-and-light)
7. [Modern Physics](#modern-physics)
8. [Fluid Mechanics](#fluid-mechanics)

---

## Mechanics and Motion

### Newton's Laws of Motion

**First Law (Law of Inertia):** An object at rest stays at rest, and an object in motion stays in motion at constant velocity, unless acted upon by an external force.

**Second Law:** F = ma (Force equals mass times acceleration)

**Third Law:** For every action, there is an equal and opposite reaction.

### Key Calculations

**Velocity and Acceleration:**
- v = u + at (final velocity = initial velocity + acceleration × time)
- s = ut + ½at² (displacement equation)
- v² = u² + 2as (velocity-displacement relationship)

**Force and Motion:**
- F = ma
- Weight: W = mg (where g = 9.8 m/s² on Earth)

### Real-World Applications

**Car Safety Systems:**
When a car traveling at 60 km/h (16.7 m/s) crashes into a wall, the deceleration can be enormous. If the car stops in 0.1 seconds:

```
a = (v - u)/t = (0 - 16.7)/0.1 = -167 m/s²
```

This is about 17 times the force of gravity! Airbags and crumple zones extend the stopping time to reduce this deadly acceleration.

**Rocket Propulsion:**
The Saturn V rocket that took astronauts to the Moon demonstrates Newton's third law. The rocket burns fuel to expel hot gases downward at high velocity, creating an upward thrust force.

**Satellite Orbits:**
The International Space Station orbits Earth at about 27,600 km/h. The gravitational force provides the centripetal force needed for circular motion:

```
F_gravitational = F_centripetal
GMm/r² = mv²/r
```

This balance keeps the ISS in stable orbit at approximately 408 km above Earth.

---

## Energy and Work

### Fundamental Concepts

**Work:** W = F × d × cos(θ)
- Work is done when a force causes displacement
- Measured in Joules (J)

**Kinetic Energy:** KE = ½mv²
**Potential Energy:** PE = mgh (gravitational)
**Conservation of Energy:** Total energy remains constant in isolated systems

### Key Calculations

**Power:** P = W/t = F × v
- Measured in Watts (W)

**Efficiency:** η = (Useful energy output)/(Total energy input) × 100%

### Real-World Applications

**Hydroelectric Power:**
The Hoover Dam generates electricity using gravitational potential energy. Water falling from height h converts PE to KE:

```
PE = mgh
For 1000 kg of water falling 221 m:
PE = 1000 × 9.8 × 221 = 2.17 × 10⁶ J
```

This energy is converted to electrical energy through turbines and generators.

**Roller Coasters:**
At the top of a hill, a roller coaster car has maximum potential energy. As it descends, PE converts to KE:

```
At top: PE = mgh, KE = 0
At bottom: PE = 0, KE = ½mv²
Therefore: mgh = ½mv²
Solving for velocity: v = √(2gh)
```

**Wind Energy:**
Wind turbines capture kinetic energy from moving air masses. The power available in wind is:

```
P = ½ρAv³
```
Where ρ is air density, A is swept area, and v is wind speed. This cubic relationship explains why wind speed is so crucial for wind power generation.

---

## Waves and Sound

### Wave Properties

**Wave Equation:** v = fλ
- v = velocity, f = frequency, λ = wavelength

**Sound Speed:** v = 343 m/s in air at 20°C

### Key Calculations

**Frequency and Period:** f = 1/T
**Doppler Effect:** f' = f(v ± v_observer)/(v ± v_source)

### Real-World Applications

**Medical Ultrasound:**
Ultrasound uses high-frequency sound waves (2-18 MHz) to image internal body structures. The waves reflect off tissue boundaries, and the time delay reveals depth:

```
Distance = (velocity × time)/2
For tissue (v ≈ 1540 m/s), if echo returns in 0.1 ms:
Distance = (1540 × 0.0001)/2 = 0.077 m = 7.7 cm
```

**Radar and GPS:**
Radio waves travel at the speed of light (3 × 10⁸ m/s). GPS satellites use precise timing to determine location:

```
Distance = c × t
If signal takes 0.067 seconds to reach satellite:
Distance = 3 × 10⁸ × 0.067 = 20,100 km
```

**Earthquake Detection:**
Seismographs detect P-waves (primary) and S-waves (secondary) that travel at different speeds through Earth. The time difference helps locate earthquake epicenters:

```
Distance = (t_S - t_P) × v_P × v_S/(v_P - v_S)
```

---

## Electricity and Magnetism

### Fundamental Laws

**Ohm's Law:** V = IR
**Power:** P = VI = I²R = V²/R
**Coulomb's Law:** F = kq₁q₂/r²

### Key Calculations

**Electrical Energy:** E = Pt = VIt
**Capacitance:** C = Q/V
**Magnetic Force:** F = BIL (on current-carrying conductor)

### Real-World Applications

**Household Electricity:**
A typical home uses about 30 kWh per day. For a 100W light bulb running 8 hours:

```
Energy = Power × Time = 100W × 8h = 800 Wh = 0.8 kWh
Cost = 0.8 kWh × $0.12/kWh = $0.096 per day
```

**Electric Motors:**
Electric vehicles use motors that convert electrical energy to mechanical energy. A Tesla Model S motor produces about 375 kW:

```
At 400V and 94% efficiency:
Current = P/(V × η) = 375,000/(400 × 0.94) = 996 A
```

**Electromagnetic Induction:**
Generators in power plants use Faraday's law to produce electricity. When a coil rotates in a magnetic field:

```
EMF = -N(dΦ/dt) = -N × B × A × ω × sin(ωt)
```

This principle powers everything from bicycle dynamos to massive power station generators.

---

## Thermodynamics

### Laws of Thermodynamics

**First Law:** ΔU = Q - W (Energy conservation)
**Second Law:** Entropy of isolated systems always increases
**Third Law:** Entropy approaches zero as temperature approaches absolute zero

### Key Calculations

**Heat Transfer:** Q = mcΔT
**Ideal Gas Law:** PV = nRT
**Efficiency:** η = 1 - T_cold/T_hot (Carnot engine)

### Real-World Applications

**Internal Combustion Engines:**
A car engine operates on the Otto cycle. For a typical engine with compression ratio 10:1:

```
Theoretical efficiency = 1 - (1/r)^(γ-1)
η = 1 - (1/10)^(1.4-1) = 1 - (0.1)^0.4 = 60%
```

Actual efficiency is lower due to friction, heat loss, and incomplete combustion.

**Refrigerators:**
Refrigerators move heat from cold interior to warm exterior. The coefficient of performance (COP):

```
COP = T_cold/(T_hot - T_cold)
For typical refrigerator: COP = 278K/(298K - 278K) = 13.9
```

**Heat Pumps:**
Heat pumps can be 3-4 times more efficient than electric heating because they move heat rather than generate it:

```
COP_heating = T_hot/(T_hot - T_cold)
For heat pump: COP = 298K/(298K - 273K) = 11.9
```

---

## Optics and Light

### Fundamental Principles

**Snell's Law:** n₁sin(θ₁) = n₂sin(θ₂)
**Lens Equation:** 1/f = 1/u + 1/v
**Mirror Equation:** Same as lens equation

### Key Calculations

**Magnification:** m = v/u = h'/h
**Critical Angle:** θc = sin⁻¹(n₂/n₁)

### Real-World Applications

**Optical Fibers:**
Internet data travels through optical fibers using total internal reflection. For silica fiber (n = 1.46) in air:

```
Critical angle = sin⁻¹(1/1.46) = 43.2°
```

Light rays entering at angles greater than this are trapped and can travel long distances with minimal loss.

**Camera Lenses:**
Camera focal length determines field of view. For a 35mm camera:

```
Field of view = 2 × tan⁻¹(d/2f)
For 50mm lens: FOV = 2 × tan⁻¹(36/100) = 39.6°
```

**Microscopes:**
Microscope resolution is limited by light wavelength:

```
Resolution = 1.22λ/(2NA)
For visible light (λ = 500 nm) and NA = 1.4:
Resolution = 1.22 × 500 × 10⁻⁹/(2 × 1.4) = 218 nm
```

This is why electron microscopes (shorter wavelength) can resolve much smaller details.

---

## Modern Physics

### Quantum Mechanics

**Planck's Equation:** E = hf
**de Broglie Wavelength:** λ = h/p
**Uncertainty Principle:** Δx × Δp ≥ ℏ/2

### Relativity

**Time Dilation:** t' = t/√(1 - v²/c²)
**Length Contraction:** L' = L√(1 - v²/c²)
**Mass-Energy:** E = mc²

### Real-World Applications

**GPS Satellites:**
GPS satellites experience both special and general relativistic effects. Without relativistic corrections:

```
Special relativity: Δt = -7.2 μs/day (time runs slower)
General relativity: Δt = +45.9 μs/day (time runs faster)
Net effect: +38.7 μs/day
```

Without these corrections, GPS accuracy would degrade by about 11 km per day!

**Nuclear Power:**
Nuclear fission releases energy according to E = mc². When uranium-235 fissions:

```
Mass defect ≈ 0.2 amu = 0.2 × 931.5 MeV = 186.3 MeV per fission
For 1 kg of U-235: Energy = 8.2 × 10¹³ J
```

This is millions of times more energy than chemical reactions.

**Photoelectric Effect:**
Solar panels use the photoelectric effect. For silicon (work function 1.12 eV):

```
Maximum kinetic energy = hf - φ
For 600 nm light: KE = (1240 eV⋅nm)/600 nm - 1.12 eV = 0.95 eV
```

---

## Fluid Mechanics

### Fundamental Principles

**Pressure:** P = F/A
**Buoyancy:** F_buoyant = ρ_fluid × V_displaced × g
**Continuity Equation:** A₁v₁ = A₂v₂
**Bernoulli's Equation:** P + ½ρv² + ρgh = constant

### Real-World Applications

**Airplane Flight:**
Airplane wings generate lift through pressure differences. Using Bernoulli's equation:

```
Lift = ½ρ(v₂² - v₁²) × A
For typical conditions: Lift ≈ 1000 N/m² wing area
```

**Blood Pressure:**
Blood pressure measurements use fluid mechanics. Normal blood pressure (120/80 mmHg):

```
Systolic: 120 mmHg = 120 × 133.3 Pa = 16,000 Pa
Diastolic: 80 mmHg = 80 × 133.3 Pa = 10,664 Pa
```

**Hydraulic Systems:**
Hydraulic brakes multiply force using Pascal's principle:

```
F₂/F₁ = A₂/A₁
If brake pedal area = 5 cm², brake pad area = 50 cm²:
Force multiplication = 50/5 = 10 times
```

---

## Conclusion

These physics principles and calculations form the foundation of our technological world. From the smartphone in your pocket to the GPS guiding your car, from the electricity powering your home to the medical devices saving lives, physics is everywhere. Understanding these concepts not only satisfies our curiosity about how the world works but also enables us to design better technologies, solve complex problems, and make informed decisions about the future.

The mathematical relationships described here are not just abstract formulas—they represent the fundamental rules that govern our universe. By mastering these concepts, we gain the tools to understand, predict, and manipulate the physical world around us, opening doors to innovation and discovery that continue to transform human civilization.# Important Physics Topics: Calculations and Real-World Applications

## Table of Contents
1. [Mechanics and Motion](#mechanics-and-motion)
2. [Energy and Work](#energy-and-work)
3. [Waves and Sound](#waves-and-sound)
4. [Electricity and Magnetism](#electricity-and-magnetism)
5. [Thermodynamics](#thermodynamics)
6. [Optics and Light](#optics-and-light)
7. [Modern Physics](#modern-physics)
8. [Fluid Mechanics](#fluid-mechanics)

---

## Mechanics and Motion

### Newton's Laws of Motion

**First Law (Law of Inertia):** An object at rest stays at rest, and an object in motion stays in motion at constant velocity, unless acted upon by an external force.

**Second Law:** F = ma (Force equals mass times acceleration)

**Third Law:** For every action, there is an equal and opposite reaction.

### Key Calculations

**Velocity and Acceleration:**
- v = u + at (final velocity = initial velocity + acceleration × time)
- s = ut + ½at² (displacement equation)
- v² = u² + 2as (velocity-displacement relationship)

**Force and Motion:**
- F = ma
- Weight: W = mg (where g = 9.8 m/s² on Earth)

### Real-World Applications

**Car Safety Systems:**
When a car traveling at 60 km/h (16.7 m/s) crashes into a wall, the deceleration can be enormous. If the car stops in 0.1 seconds:

```
a = (v - u)/t = (0 - 16.7)/0.1 = -167 m/s²
```

This is about 17 times the force of gravity! Airbags and crumple zones extend the stopping time to reduce this deadly acceleration.

**Rocket Propulsion:**
The Saturn V rocket that took astronauts to the Moon demonstrates Newton's third law. The rocket burns fuel to expel hot gases downward at high velocity, creating an upward thrust force.

**Satellite Orbits:**
The International Space Station orbits Earth at about 27,600 km/h. The gravitational force provides the centripetal force needed for circular motion:

```
F_gravitational = F_centripetal
GMm/r² = mv²/r
```

This balance keeps the ISS in stable orbit at approximately 408 km above Earth.

---

## Energy and Work

### Fundamental Concepts

**Work:** W = F × d × cos(θ)
- Work is done when a force causes displacement
- Measured in Joules (J)

**Kinetic Energy:** KE = ½mv²
**Potential Energy:** PE = mgh (gravitational)
**Conservation of Energy:** Total energy remains constant in isolated systems

### Key Calculations

**Power:** P = W/t = F × v
- Measured in Watts (W)

**Efficiency:** η = (Useful energy output)/(Total energy input) × 100%

### Real-World Applications

**Hydroelectric Power:**
The Hoover Dam generates electricity using gravitational potential energy. Water falling from height h converts PE to KE:

```
PE = mgh
For 1000 kg of water falling 221 m:
PE = 1000 × 9.8 × 221 = 2.17 × 10⁶ J
```

This energy is converted to electrical energy through turbines and generators.

**Roller Coasters:**
At the top of a hill, a roller coaster car has maximum potential energy. As it descends, PE converts to KE:

```
At top: PE = mgh, KE = 0
At bottom: PE = 0, KE = ½mv²
Therefore: mgh = ½mv²
Solving for velocity: v = √(2gh)
```

**Wind Energy:**
Wind turbines capture kinetic energy from moving air masses. The power available in wind is:

```
P = ½ρAv³
```
Where ρ is air density, A is swept area, and v is wind speed. This cubic relationship explains why wind speed is so crucial for wind power generation.

---

## Waves and Sound

### Wave Properties

**Wave Equation:** v = fλ
- v = velocity, f = frequency, λ = wavelength

**Sound Speed:** v = 343 m/s in air at 20°C

### Key Calculations

**Frequency and Period:** f = 1/T
**Doppler Effect:** f' = f(v ± v_observer)/(v ± v_source)

### Real-World Applications

**Medical Ultrasound:**
Ultrasound uses high-frequency sound waves (2-18 MHz) to image internal body structures. The waves reflect off tissue boundaries, and the time delay reveals depth:

```
Distance = (velocity × time)/2
For tissue (v ≈ 1540 m/s), if echo returns in 0.1 ms:
Distance = (1540 × 0.0001)/2 = 0.077 m = 7.7 cm
```

**Radar and GPS:**
Radio waves travel at the speed of light (3 × 10⁸ m/s). GPS satellites use precise timing to determine location:

```
Distance = c × t
If signal takes 0.067 seconds to reach satellite:
Distance = 3 × 10⁸ × 0.067 = 20,100 km
```

**Earthquake Detection:**
Seismographs detect P-waves (primary) and S-waves (secondary) that travel at different speeds through Earth. The time difference helps locate earthquake epicenters:

```
Distance = (t_S - t_P) × v_P × v_S/(v_P - v_S)
```

---

## Electricity and Magnetism

### Fundamental Laws

**Ohm's Law:** V = IR
**Power:** P = VI = I²R = V²/R
**Coulomb's Law:** F = kq₁q₂/r²

### Key Calculations

**Electrical Energy:** E = Pt = VIt
**Capacitance:** C = Q/V
**Magnetic Force:** F = BIL (on current-carrying conductor)

### Real-World Applications

**Household Electricity:**
A typical home uses about 30 kWh per day. For a 100W light bulb running 8 hours:

```
Energy = Power × Time = 100W × 8h = 800 Wh = 0.8 kWh
Cost = 0.8 kWh × $0.12/kWh = $0.096 per day
```

**Electric Motors:**
Electric vehicles use motors that convert electrical energy to mechanical energy. A Tesla Model S motor produces about 375 kW:

```
At 400V and 94% efficiency:
Current = P/(V × η) = 375,000/(400 × 0.94) = 996 A
```

**Electromagnetic Induction:**
Generators in power plants use Faraday's law to produce electricity. When a coil rotates in a magnetic field:

```
EMF = -N(dΦ/dt) = -N × B × A × ω × sin(ωt)
```

This principle powers everything from bicycle dynamos to massive power station generators.

---

## Thermodynamics

### Laws of Thermodynamics

**First Law:** ΔU = Q - W (Energy conservation)
**Second Law:** Entropy of isolated systems always increases
**Third Law:** Entropy approaches zero as temperature approaches absolute zero

### Key Calculations

**Heat Transfer:** Q = mcΔT
**Ideal Gas Law:** PV = nRT
**Efficiency:** η = 1 - T_cold/T_hot (Carnot engine)

### Real-World Applications

**Internal Combustion Engines:**
A car engine operates on the Otto cycle. For a typical engine with compression ratio 10:1:

```
Theoretical efficiency = 1 - (1/r)^(γ-1)
η = 1 - (1/10)^(1.4-1) = 1 - (0.1)^0.4 = 60%
```

Actual efficiency is lower due to friction, heat loss, and incomplete combustion.

**Refrigerators:**
Refrigerators move heat from cold interior to warm exterior. The coefficient of performance (COP):

```
COP = T_cold/(T_hot - T_cold)
For typical refrigerator: COP = 278K/(298K - 278K) = 13.9
```

**Heat Pumps:**
Heat pumps can be 3-4 times more efficient than electric heating because they move heat rather than generate it:

```
COP_heating = T_hot/(T_hot - T_cold)
For heat pump: COP = 298K/(298K - 273K) = 11.9
```

---

## Optics and Light

### Fundamental Principles

**Snell's Law:** n₁sin(θ₁) = n₂sin(θ₂)
**Lens Equation:** 1/f = 1/u + 1/v
**Mirror Equation:** Same as lens equation

### Key Calculations

**Magnification:** m = v/u = h'/h
**Critical Angle:** θc = sin⁻¹(n₂/n₁)

### Real-World Applications

**Optical Fibers:**
Internet data travels through optical fibers using total internal reflection. For silica fiber (n = 1.46) in air:

```
Critical angle = sin⁻¹(1/1.46) = 43.2°
```

Light rays entering at angles greater than this are trapped and can travel long distances with minimal loss.

**Camera Lenses:**
Camera focal length determines field of view. For a 35mm camera:

```
Field of view = 2 × tan⁻¹(d/2f)
For 50mm lens: FOV = 2 × tan⁻¹(36/100) = 39.6°
```

**Microscopes:**
Microscope resolution is limited by light wavelength:

```
Resolution = 1.22λ/(2NA)
For visible light (λ = 500 nm) and NA = 1.4:
Resolution = 1.22 × 500 × 10⁻⁹/(2 × 1.4) = 218 nm
```

This is why electron microscopes (shorter wavelength) can resolve much smaller details.

---

## Modern Physics

### Quantum Mechanics

**Planck's Equation:** E = hf
**de Broglie Wavelength:** λ = h/p
**Uncertainty Principle:** Δx × Δp ≥ ℏ/2

### Relativity

**Time Dilation:** t' = t/√(1 - v²/c²)
**Length Contraction:** L' = L√(1 - v²/c²)
**Mass-Energy:** E = mc²

### Real-World Applications

**GPS Satellites:**
GPS satellites experience both special and general relativistic effects. Without relativistic corrections:

```
Special relativity: Δt = -7.2 μs/day (time runs slower)
General relativity: Δt = +45.9 μs/day (time runs faster)
Net effect: +38.7 μs/day
```

Without these corrections, GPS accuracy would degrade by about 11 km per day!

**Nuclear Power:**
Nuclear fission releases energy according to E = mc². When uranium-235 fissions:

```
Mass defect ≈ 0.2 amu = 0.2 × 931.5 MeV = 186.3 MeV per fission
For 1 kg of U-235: Energy = 8.2 × 10¹³ J
```

This is millions of times more energy than chemical reactions.

**Photoelectric Effect:**
Solar panels use the photoelectric effect. For silicon (work function 1.12 eV):

```
Maximum kinetic energy = hf - φ
For 600 nm light: KE = (1240 eV⋅nm)/600 nm - 1.12 eV = 0.95 eV
```

---

## Fluid Mechanics

### Fundamental Principles

**Pressure:** P = F/A
**Buoyancy:** F_buoyant = ρ_fluid × V_displaced × g
**Continuity Equation:** A₁v₁ = A₂v₂
**Bernoulli's Equation:** P + ½ρv² + ρgh = constant

### Real-World Applications

**Airplane Flight:**
Airplane wings generate lift through pressure differences. Using Bernoulli's equation:

```
Lift = ½ρ(v₂² - v₁²) × A
For typical conditions: Lift ≈ 1000 N/m² wing area
```

**Blood Pressure:**
Blood pressure measurements use fluid mechanics. Normal blood pressure (120/80 mmHg):

```
Systolic: 120 mmHg = 120 × 133.3 Pa = 16,000 Pa
Diastolic: 80 mmHg = 80 × 133.3 Pa = 10,664 Pa
```

**Hydraulic Systems:**
Hydraulic brakes multiply force using Pascal's principle:

```
F₂/F₁ = A₂/A₁
If brake pedal area = 5 cm², brake pad area = 50 cm²:
Force multiplication = 50/5 = 10 times
```

---

## Conclusion

These physics principles and calculations form the foundation of our technological world. From the smartphone in your pocket to the GPS guiding your car, from the electricity powering your home to the medical devices saving lives, physics is everywhere. Understanding these concepts not only satisfies our curiosity about how the world works but also enables us to design better technologies, solve complex problems, and make informed decisions about the future.

The mathematical relationships described here are not just abstract formulas—they represent the fundamental rules that govern our universe. By mastering these concepts, we gain the tools to understand, predict, and manipulate the physical world around us, opening doors to innovation and discovery that continue to transform human civilization.

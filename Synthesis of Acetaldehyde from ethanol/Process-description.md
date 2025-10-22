# Process Description — Synthesis of Acetaldehyde from Ethanol

Acetaldehyde needs to be synthesized from 400 kmol/h ethanol at 60 °C and 5.5 atm pressure. An isothermal plug flow reactor of length 7 m and dia 11.5 cm will be used which will operate at 8 bar and 275 °C. The reactor will be governed by the following vapour phase equilibrium power law reaction kinetics:

                         C2H5OH <==> CH3CHO + H2  ----------------------- (1) 
r₁ = -k<sub>1</sub>|Cₑₜₕₐₙₒₗ| 
---
k<sub>1</sub>= 1.5 × 10⁹ exp(-8.5 × 10⁷ / RT)  

(activation energy is in J/kmol and Temp (T<sub>o</sub>) is in °C)  

                        C2H5OH + CH3CHO <==> CH3COOC2H5 + H2  ----------- (2)
r₂ = -k<sub>2</sub> |C<sub>acetaldehyde</sub>|¹·³⁷ / |C<sub>ethanol</sub>|¹·⁶⁷ |C<sub>hydrogen</sub>|⁰·²⁴
---
k<sub>2</sub>= 0.11 exp(-100902/R (1/T - 1/220))

PSRK property method will be used.

Feed is pumped (80% pump efficiency and 70% driver efficiency) at 8 bar and heated up to 275°C (zero pressure drop) before feeding to the reactor.

Reactor output is cooled down to 25°C with pressure drop of 0.3 bar before being flashed at zero duty and zero pressure drop. Liquid output of flash is separated through a membrane separator where H₂ is separated from others. Vapour outputs of "Flash" and "Sep" are added together and sent out as stack. Liquid output of the separator will be fractionated through a "Radfrac" column with 22 stages (feed stage 11th), reflux ratio 1.8, distillate to feed ratio 0.4, condenser pressure 6.5 bar and column pressure drop of 1.5 bar. 90% of the bottom product of the fractionator is recycled back to the reactor, while remaining 10% is purged.

Heater is replaced with a shell and tube heat exchanger. Design and sizing of exchanger needs to be done. 2000 kmol/h of steam at 9 bar is available for that purpose.

Composition profile of reactor and fractionator column may be examined.

Pressure profile of fractionator column may also be examined.

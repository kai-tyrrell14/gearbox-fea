# Gear Ratio Calculation

## Design Objective
The gearbox was designed to reduce rotational speed and increase output torque for robotic actuation applications. A two-stage spur gear arrangement was selected to achieve a high overall reduction ratio while maintaining compact packaging.

---

## Stage 1 Ratio
Stage 1 consists of a 12-tooth driver gear and a 60-tooth driven gear.

\[
\text{Stage 1 Ratio} = \frac{\text{Driven Gear Teeth}}{\text{Driver Gear Teeth}} = \frac{60}{12} = 5:1
\]

This means the intermediate shaft rotates at one-fifth of the input speed, while transmitted torque is increased by a factor of approximately five (neglecting losses).

---

## Stage 2 Ratio
Stage 2 consists of a 15-tooth driver gear and a 60-tooth driven gear.

\[
\text{Stage 2 Ratio} = \frac{\text{Driven Gear Teeth}}{\text{Driver Gear Teeth}} = \frac{60}{15} = 4:1
\]

This further reduces rotational speed and increases torque at the output shaft.

---

## Total Gearbox Ratio
The total gearbox reduction ratio is the product of the two stage ratios.

\[
\text{Total Ratio} = 5 \times 4 = 20:1
\]

This means the output shaft rotates twenty times slower than the input shaft.

For example, if the input shaft rotates at 3000 rpm:

\[
\text{Output Speed} = \frac{3000}{20} = 150 \text{ rpm}
\]

---

## Engineering Interpretation
A two-stage reduction was selected to achieve a large overall ratio without requiring impractically large gears in a single stage. This configuration provides increased torque and reduced output speed, making it suitable for robotic systems that require controlled motion and higher load capability.

The selected 20:1 reduction ratio is appropriate for compact mechatronic applications where motor speed must be converted into usable actuator torque.

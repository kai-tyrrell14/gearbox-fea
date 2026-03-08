# Two Stage Spur Gearbox
This project involves a SolidWorks designed two stage reduction gearbox intended for robotic actuation applications. The gearbox reduces high speed motor input and increases torque whilst maintaining a compact size. Finite Element Analysis was also performed to ensure the systems reliability under the expected loading conditions.

# 1. System Overview
![Motion Animation](media/motion_animation.gif)

This demonstrates the motion of the gearbox including gears, shafts and bearings.

# 2. Features
- Two stage spur gear reduction gearbox
- 20:1 overall reduction ratio  
- Compact and accurate gear train layout  
- Fully modelled mechanical assembly in SolidWorks  
- Motion study for kinematic verification  
- Finite Element Analysis for structural everification  
- Engineering drawings and exploded assembly documentation  

# 3. Hardware
| Component | Description |
|----------|-------------|
| Spur Gears | Power transmission between shafts |
| Input Shaft | Receives rotational input |
| Intermediate Shaft | Transfers motion between gear stages |
| Output Shaft | Provides reduced-speed high-torque output |
| Deep Groove Ball Bearings | Maintain shaft alignment and reduce friction |
| Gearbox Housing | Structural support and component alignment |

Bearings support each shaft within the housing to maintain accurate gear alignment while allowing free rotation.

# 4. System Design

The gearbox consists of three shafts arranged in a parallel configuration and two gear reduction stages.

## 4.1 Mechanical System

The drivetrain transmits motion through two spur gear stages:

Stage 1  
12-tooth driver gear → 60-tooth driven gear  
Reduction ratio = **5:1**

Stage 2  
15-tooth driver gear → 60-tooth driven gear  
Reduction ratio = **4:1**

Total gearbox reduction:

**20:1**

## 4.2 Structural System

The gearbox housing supports the bearings and maintains precise alignment between the gear meshes. Bearings constrain the shafts radially while allowing rotational motion.

## 4.3 Motion System

Gear mates were used in SolidWorks to define the relationship between meshing gears. A motion study was conducted to verify that rotational motion propagates correctly through the drivetrain.

---

# 5. Design Validation

## Motion Verification

A SolidWorks Motion Study was performed to confirm that the gearbox produces the intended **20:1 reduction ratio** and that rotational motion propagates smoothly through both gear stages.

![Motion Animation](media/gearbox_motion.gif)

## Structural Analysis

Finite Element Analysis (FEA) was conducted on the gear geometry to evaluate stress distribution under representative loading conditions. Maximum stress occurs at the **gear tooth root**, consistent with expected spur gear behaviour.

![FEA Stress Plot](media/fea_stress.png)

---

# 6. Repository Structure

An overview of the files included in this repository:

• `/CAD` – SolidWorks parts and assemblies  
• `/analysis` – Engineering calculations and validation files  
• `/drawings` – Engineering drawings and exploded assembly  
• `/docs` – Design documentation and project overview  
• `/media` – Renders, animations, and analysis images  

---

# 7. Engineering Challenges

A number of design challenges were encountered during the development of the gearbox:

• Determining an appropriate reduction ratio while maintaining compact gear sizes  
• Ensuring correct shaft alignment and gear meshing within the assembly  
• Designing shaft diameters to accommodate increasing transmitted torque  
• Maintaining accurate bearing placement within the gearbox housing  

More information can be found in `docs/engineering_challenges.md`.

---

# 8. Future Improvements

Potential improvements to the design may include:

• Gear contact analysis for improved load modelling  
• Fatigue life estimation for gear durability  
• Optimisation of the gearbox housing design  
• Development of a physical prototype for experimental validation  

More information can be found in `docs/future_improvements.md`.

---

# Author

Kai Tyrrell  
Mechatronics Engineering Student  
RMIT University

# Design Overview
## 1. System Details
This project consists of a small two-stage reduction gearbox, designed to convert a high speed motor input to a lower speed and higher torque output suitable for robotic actuation applications. The gearbox consists of 3 shafts; an input shaft, and intermediate shaft and an output shaft. These shafts are supported by deep grove ball bearings mounted in a housing. The rotational motion input is transmitted through two stages of spur gears achieving an overall gear resuction ratio of 20:1. The gearbox was designed and assembled in SolidWorks, which was also used to perform a motion study and Finite Element Analysis (FEA).

## 2. Mechanical Design
The objective of the mechanical design stage was to implement a two stage gear configuration to achieve the necessary 20:1 reduction ratio whilst maintaining a compact size. The two gear stages include:
- Stage 1: 12 tooth pinion driving a 60 tooth gear.
- Stage 2: 15 tooth pinion driving a 60 tooth gear.

This prodcues the following reduction ratios:
- Stage 1: 5:1
- Stage 2: 4:1`
- Overall gearbox: 20:1

These gears are attached to three separate shafts which increase in size as the transmitted torque increases. The three shaft diameter sizes are:
- Input shaft: 8mm
- Intermediate shaft: 10mm
- Output shaft: 12mm

These shafts are supported by deep groove ball bearings increasing in bore size to support each shaft size.

## 3. Structural Design
The bearings supporting the shafts are mounted in a gearbox housing which provides the structural support for the entire system. This support ensures the correct alignment between meshing gears with the housing and bearings preventing translational movement of the shafts, whilst maintaining free rotational motion.

A Finite Element Analysis (FEA) was performed to determine whether the gearbox could withstand the expected loading conditions. The analysis was focused on the critical region for spur gears, the tooth root, where the stress distribution under expected loading conditions is analysed. The results of the FEA verified that the design of the gearbox was acceptable under the necessary loading conditions and is suitable for the proposed applications.

## 4. Motion Verification
In order to verify the kinematics of the gearbox would behave as expected, a SolidWorks motion study was performed. Gear mates were applied to meshing gears to ensure the appropriate ratios and a motor input was applied to the input shaft. The motion study confirmed that the expected 20:1 ratio was achieved whilst smooth motion of all shafts and gears was also observed. This confirmed the suitability of the gear meshing, assembly constraints and overall gearbox layout.

## 5. Key Design Decisions
In order to ensure the gearbox performed reliably several key design decisions were implemented:
- To achieve the desired 20:1 gear reduction ratio whilst maintaining a compact size, two spur gear stages used.
- Spur gears were chosen as they are easily available and are the simplest method to transmit motion.
- Shaft diameters were increased as the torque transmitted increases to ensure reliability.
- Standard deep groove ball bearings were implemented to support shafts and maintain alignment.
- A motion study and FEA were performed to ensure the gearbox will perform reliably under the expected conditions.
  

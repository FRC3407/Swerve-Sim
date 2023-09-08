# Swerve-Sim
#### Work done during summer 2023 on an example swerve API featuring 3D visualization (AdvantageScope), control based on second-order kinematics, and an *unfinished* simulator (see below). The project is based on WPILib version 2023.4.3.

- ## Current Status (9/8/23)
  Most interface/utility classes are complete and could be used as a base for driving an actual swerve base, however, the general driver/container class is unfinished.
The simulator is theoretically functional but not fully tested. Due to time limitations of this project/repo, further development of the simulation can be found **[here](https://github.com/S1ink/Swerve-Simulation)**.
- ## Resources Used
  - [Swerve base CAD (onshape)](https://cad.onshape.com/documents/e5ac6c72dd56b8c17b755e80/w/53462e21ae53c65e73ff644e/e/8f86e6f27e761f0f1d59d196?renderMode=0&uiState=648e46aaf2f9a210eca5e3a9)
  - [SDS MK4i page (for CAD specs)](https://www.swervedrivespecialties.com/products/mk4i-swerve-module)
  - [AdvantageScope Docs](https://github.com/Mechanical-Advantage/AdvantageScope/blob/main/docs/INDEX.md)
  - [AdvantageScope 3d field docs](https://github.com/Mechanical-Advantage/AdvantageScope/blob/main/docs/tabs/3D-FIELD.md)
  - [AdvantageScope custom configurations (robot models)](https://github.com/Mechanical-Advantage/AdvantageScope/blob/main/docs/CUSTOM-CONFIG.md)
  - [AdvantageScope converting CAD to glTF](https://github.com/Mechanical-Advantage/AdvantageScope/blob/main/docs/GLTF-CONVERT.md)
  - [WPILib coordinate systems](https://docs.wpilib.org/en/stable/docs/software/advanced-controls/geometry/coordinate-systems.html)
  - [WPILib state-space control](https://docs.wpilib.org/en/stable/docs/software/advanced-controls/state-space/state-space-intro.html)
  - [WPILib physics simulation (state-space model)](https://docs.wpilib.org/en/stable/docs/software/wpilib-tools/robot-simulation/physics-sim.html)
  - [WPILib Swerve Kinematics](https://docs.wpilib.org/en/stable/docs/software/kinematics-and-odometry/swerve-drive-kinematics.html)
  - [WPILib Swerve Odometry](https://docs.wpilib.org/en/stable/docs/software/kinematics-and-odometry/swerve-drive-odometry.html)
  - [Advanced Kinematics Tuning](https://www.chiefdelphi.com/t/whitepaper-swerve-drive-skew-and-second-order-kinematics/416964) --> [Relevant Whitepaper](https://www.chiefdelphi.com/uploads/short-url/qzj4k2LyBs7rLxAem0YajNIlStH.pdf)
  - [Rigid Body Dynamics - Wikipedia](https://en.wikipedia.org/wiki/Rigid_body_dynamics)

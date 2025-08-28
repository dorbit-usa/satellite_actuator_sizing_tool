# Satellite Actuator Sizing Tool

This MatLab tool is used to determine actuator sizing.  It models the following sources of external disturbances
* Solar Radiation Pressure Torque
* Gravity Gradient Torque
* Aerodynamic Torque
* Thruster Torque
* Spacecraft Dipole Torque

It requires as input
* Spacecraft Geometry
* Mass Properties
* Reaction Wheel Alignments
* Magnetic Torque Bar Alignments
* Steering Laws

It then runs numerous long-running simulations at various flight conditions which include
* Orbit
* Environment Model (SRP, AP)
* Steering Law
* Torque Bar Max Torque

Then, the following metrics for each model are generated
* System Momentum Time History
* Wheel Speed Time History
* Wheel Speed Torque History


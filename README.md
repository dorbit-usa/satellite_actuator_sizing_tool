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
* Magnetic Torque Bar Duty Cycle
* Steering Laws

It then runs numerous year-long simulations at various flight conditions which include
* Orbit
* Environment Model (SRP, AP)
* Steering Law
* Torque Bar Max Dipole

Then, the following metrics for each scenario are generated
* Force and Torque Time History
* System Momentum Time History
* Spacecraft Orbit State Time History
* Wheel Speed Time History



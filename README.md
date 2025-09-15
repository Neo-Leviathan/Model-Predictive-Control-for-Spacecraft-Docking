# Model-Predictive-Control-for-Spacecraft-Docking
Overview

This project investigates the use of Model Predictive Control (MPC) for autonomous spacecraft rendezvous and docking (RVD), a maneuver requiring precise six-degree-of-freedom (6-DOF) control of both translation and rotation. Traditional controllers such as PD or LQR perform well in simplified cases but degrade in coupled dynamics or when explicit constraints must be enforced.

A nonlinear 6-DOF plant model was developed, and both MPC and a baseline LQR controller were implemented and compared. Results show that MPC achieves stable convergence in coupled and uncoupled cases, with positional errors under 0.05 m and attitude errors within 0.024 rad RMS, highlighting its advantages for high-precision spacecraft control.

Documentation

A detailed technical report describing the problem formulation, methodology, results, and discussion is included in this repository.

Results (Highlights)

Stable convergence achieved with MPC under 6-DOF nonlinear dynamics.

MPC outperforms LQR in coupled scenarios.

Positional error: < 0.05 m

Attitude error: ~0.024 rad RMS

(Figures available in the report.)

Future Work

Planned extensions include incorporating delay-tolerant strategies and running Monte Carlo simulations to evaluate robustness under uncertainties.

License

This work is licensed under the Creative Commons License. Please cite this repository if using material from it

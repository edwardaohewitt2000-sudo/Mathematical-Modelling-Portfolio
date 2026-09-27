# Edward Hewitt
 
 Applied Mathematician | Numerical Analyst | Thermal-Fluids Modeller| North West, UK

I develop mathematical and computational models of complex physical systems with a focus on thermal-fluid dynamics, phase-change processes, moving-boundary problems and nonlinear partial differential equations.

This repository showcases selected modelling projects demonstrating mathematical formulation, numerical implementation, verification, validation, and scientific computing techniques. 


# Technical Expertise & Physical Domains

Phase Change & Moving Boundaries: Modified Stefan Problem, Enthalpy Formulations, Moving Mesh Methods, Density Anomalies.

Multiphase & Interfacial Phenomena: Micro/Meso/Macro Critical Heat Flux (CHF) multi-scale models, Thin-Film Dynamics, Vapor-Liquid Hydrodynamics.

Numerical Methods & PDEs: Finite Difference (FDM), Finite Volume (FVM), Non-Linear PDE Solvers, Multiscale Coupling.

## Modelling Philosophy

My approach to mathematical modelling follows four stages:
1. Physical understanding: Develop a qualitative and literature supported understanding of the governing physics before model construction.
2. Mathematical Formulation
3. Numerical Implementation
4. Verification, Validation and Sensitivity Analysis.

Particular emphasis is placed on understanding model assumptions, operating regimes and limitations. 

## Technical Skills

### Programming
- Python
- MATLAB
- Simulink

### Numerical Methods
- Finite Difference Methods
- Finite Volume Methods
- Nonlinear PDE Solvers

### Analysis
- Verification & Validation
- Sensitivity Analysis
- Uncertainty Quantification
- Stability Analysis

# Selected Engineering Models

## 1. Multi-Scale Critical Heat Flux (CHF) & Boiling Dynamics Model

### Objective
Developed a multi-scale computational model to investigate the onset of Critical Heat Flux (CHF) during pool and flow boiling, with a focus on the physical mechanisms governing boiling crisis and dryout.
 
### Physical Phenomena
- Thin-film evaporation
- Bubble nucleation and growth
- Bubble coalescence and departure
- Vapour layer formation
- Liquid-vapour interfacial dynamics
- Bulk fluid hydrodynamics
 
### Multi-Scale Architecture
 
#### Micro Scale
Modelled thin-film evaporation dynamics at the heated surface, capturing local heat transfer mechanisms and microlayer depletion.
 
#### Meso Scale
Simulated bubble nucleation, growth, interaction and coalescence to investigate vapour accumulation and surface coverage.
 
#### Macro Scale
Modelled bulk fluid circulation, vapour removal mechanisms and large-scale hydrodynamic behaviour governing CHF development.
 
### Mathematical Framework
- Coupled nonlinear partial differential equations
- Conservation of mass, momentum and energy
- Interfacial transport modelling
- Multi-scale coupling between local and global boiling phenomena
 
### Numerical Methods
- Finite Difference based discretisation
- Explicit and semi-implicit numerical schemes
- Numerical stability and convergence assessment
- Grid sensitivity analysis
 
### Verification
- Limiting-case comparisons against established boiling theory
- Numerical convergence testing
- Parameter consistency checks
 
### Key Findings
- Demonstrated the importance of coupling micro-scale evaporation with macro-scale hydrodynamic behaviour.
- Identified parameter sensitivities influencing CHF prediction.
- Investigated the transition from efficient nucleate boiling to boiling crisis conditions.
 
### Limitations
- Simplified treatment of turbulence effects.
- Assumed continuum-scale behaviour.
- Requires further validation against experimental boiling data.
 
### Tech Stack
Python | NumPy | SciPy | PDE Solvers | Scientific Computing

## 2. Modified Stefan Problem: Ice Accretion with Density Anomaly

## Objective
Develop an asymptotic and numerical model describing ice accretion on general cold manifolds incorporating the nonlinear density anomaly of water. 

## Key Findings
- Demonstrated the influence of manifold geometry on thermal gradients.
- Investigated geometry dependent interface propagation.
- Extended the model from planar geometries to cylindrical, elliptical, corrugated and star shaped manifolds.

## Physical Phenomena 
- Phase change
- Heat and Mass Transfer
- Moving boundary behaviour
- Density Variation

  ## Mathematical Formulation
  - Modified Stefan Condition
  - Nonlinear Heat Equation
  - Moving Boundary Problems
 
  ## Asssumptions
  - Continuum Approximation
  - Negligeable Air Flow Effects
  - Prescribed Boundary Temperature
 
  ## Numerical Method
  - Finite Difference Method
  - Explicit Time Integration
  - Interface Tracking Algorithm
 
  ## Verification
  - Comparison against analytical Stefan solutions in limiting cases
  - Grid Convergence

  ## Validation
  - Comparison with published literature results
 
  ## Limitations

  - Not suitable for turbulent airflow conditions
  - Does not account for ice fracture or shedding
 
  ## Future Development

  - Adaptive Meshing
  - Coupled fluid flow effects

### Generalised Geometry Investigation
 
The phase-change framework was extended from simple planar domains to arbitrary cold manifolds including:
 
- Cylindrical surfaces
- Elliptical surfaces
- Corrugated surfaces
- Star-shaped surfaces
 
This enabled comparative investigation of the influence of geometric curvature on thermal gradients and interface evolution.

# Technical Skills Demonstrated

- Partial Differential Equations
- Numerical Methods
- Finite Difference Methods
- Multiscale Modelling
- Sensitivity Analysis
- Verification & Validation
- Uncertainty Quantification
- Python
- MATLAB
- Simulink

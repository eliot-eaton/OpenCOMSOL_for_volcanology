# Example Model Idea: Magma-Hydrothermal Interaction

**This is an example file to demonstrate the format. Feel free to delete it or use it as inspiration.**

## Research Question
How do rising magma intrusions interact with established hydrothermal systems, and what are the time scales for thermal and pressure changes in the hydrothermal system?

## Motivation
Understanding magma-hydrothermal interactions is crucial for:
- Predicting phreatic and phreatomagmatic eruptions
- Interpreting geophysical monitoring signals
- Understanding mineral alteration patterns
- Assessing volcanic hazards in hydrothermal systems

Current models often treat these systems separately, but coupling is essential for realistic predictions.

## Proposed Approach

### Physics Modules
- [x] Heat Transfer (conduction and convection)
- [x] Porous Media Flow (Darcy flow in rock)
- [x] Structural Mechanics (stress changes, rock failure)
- [ ] Multiphase Flow (potential boiling)
- [ ] Chemical Reactions (alteration, optional)

### Key Processes to Model
1. Heat transfer from magma intrusion to surrounding rock
2. Convective circulation in hydrothermal system
3. Pressure evolution due to heating and phase changes
4. Potential rock deformation and permeability changes
5. Boiling and two-phase flow near intrusion

### Geometry and Domain
- 2D axisymmetric or 3D
- Domain: ~2-5 km × ~2-5 km
- Includes magma intrusion body (500-1000 m scale)
- Surrounding fractured/porous rock
- Pre-existing hydrothermal circulation

### Coupling Requirements
- Thermal-hydraulic coupling (temperature affects fluid properties)
- Thermo-mechanical coupling (thermal stress)
- Hydraulic-mechanical coupling (pressure-dependent permeability)
- Potential phase-change effects

## Key Challenges
- Handling large temperature gradients (20°C to 1000°C)
- Multi-scale permeability structure
- Transient simulation over appropriate time scales (days to years)
- Phase transitions and potential boiling
- Nonlinear material properties
- Computational expense of fully coupled system

## Expected Outputs
- Temperature evolution over time
- Fluid pressure and flow patterns
- Deformation and stress fields
- Time to reach critical pressure/temperature thresholds
- Identifying zones prone to failure or eruption

## Relevant Literature
- Hurwitz, S., & Lowenstern, J. B. (2014). Dynamics of the Yellowstone hydrothermal system. Reviews of Geophysics, 52(3), 375-411. DOI: 10.1002/2014RG000452
- Ingebritsen, S. E., & Appold, M. S. (2012). The physical hydrogeology of ore deposits. Economic Geology, 107(4), 559-584.
- Fournier, R. O. (1999). Hydrothermal processes related to movement of fluid from plastic into brittle rock in the magmatic-epithermal environment. Economic Geology, 94(8), 1193-1211.

## Potential Applications
- Hazard assessment at active volcanoes with hydrothermal systems
- Understanding precursory signals to hydrothermal eruptions
- Interpreting seismic and deformation monitoring data
- Exploring ore deposit formation mechanisms
- Planning geothermal energy projects near active systems

## Collaboration
- [x] Seeking collaborators
- [x] COMSOL expertise needed (especially multiphase flow)
- [x] Volcanic process expertise needed (hydrothermal systems, eruption triggers)
- Experience with field observations from hydrothermal systems would be valuable

## Contact
**Example Author**
- Email: example@institution.edu
- Institution: Example University

## Status
- [x] Just an idea
- [ ] Literature review in progress
- [ ] Proof-of-concept started
- [ ] Seeking funding

## Notes
This model would complement existing work on:
- Pure hydrothermal convection models
- Magma chamber deformation models
- Volcanic degassing models

Could potentially be developed in stages:
1. Simple thermal model (heat conduction only)
2. Add hydrothermal convection
3. Add mechanical coupling
4. Add phase changes if warranted

Initial 2D axisymmetric model could provide proof-of-concept before expanding to full 3D.

# Simulation-input-files
Simulation input files: Room-temperature DNA unwinding via terahertz modulation of biological water
+--------------------------------------------------------------------+
|                                                                    |
|               Simulation File Description                          |
|                                                                    |
+--------------------------------------------------------------------+

Completion of this example requires:
Gromacs software (https://www.gromacs.org/)

1. This example include the following files:

	conf.gro (This file contains initial coordinate of atoms).
    grompp.mdp(This file describes control parameters for simulations).
    topol.top and top_DNA_chain_A/B.itp(This file contains System topology information, detailing the structure and interactions within the entire simulation system).
    charmmm27.ff(force field parameters)
    index.ndx(This file is index file, which contains the definitions of collections of atoms or atom groups)

2. Trajectory and data analysis:

	Using the built-in tools provided by GROMACS

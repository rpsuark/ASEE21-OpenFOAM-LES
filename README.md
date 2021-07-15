# ASEE21-OpenFOAM-LES
Implementation of LES, law of the wall and log law inflow in OpenFOAM

The input case file buildingLES can simulate flow around a cube using LES turbulence model with logarithmic inflow profile and law of the wall boundary condition. The ASEE-LES.pdf has the detail of how to run the case file using OpenFOAM.

Executing the case file:

To run the simulation, the following commands should be executed under the buildingLES directory:

• Generate hexahedral multi-block mesh

$ blockMesh

• Run the simulation

$ pisoFoam

These are part of the ASEE-2021 paper,'Teaching Modeling Turbulent Flow Around Building Using LES Turbulence Method and Open-source Software OpenFOAM' by Z. Mansouri, S. Verma,  and R.P. Selvam from the Univeristy of Arkansas. Please cite this web page when you use it.

This work is supported by NSF under award number CMMI-1762999 for R.P. Selvam and S. Verma. Ms. Z. Mansouri is supported by Womble Professorship.

If you have any input or comments, please feel free to send it to rps@uark.edu .

#  Molecular Simulation Design Framework (MoSDeF) tutorial 

This notebook contains all the code presented in the tutorial video on how to use MosDEF to generate data files containing interaction parameters (force field) of a molecule of interest using only it's SMILES string. The data files are generate for LAMMPS simulation the documentations includes intructions on how to generate the data file for GROMACS, HOOMD-Blue, and GPU-Optimized MOnte Carlo (GOMC). 

Video link:


## Additional Information and links

- Mosdef link:  https://mosdef.org/
- mBuild Tutorials: https://github.com/mosdef-hub/mbuild_tutorials
- Foyer tutorials:  https://github.com/mosdef-hub/foyer_tutorials


# Preparing conda enviroment

Conda-forge does not come as a default package in conda, so we need to add it first just in case.

`conda config --add channels conda-forge` <br>
`conda config –-set channel_priority strict`


Now, create a conda enviroment from the env.yaml. You can change the name of the enviroment changing the first line of the yaml file.

`conda env create -f env.yaml`


# Tutorial 
 
Open the MosDEF_Tutorial Notebook to learn how to generate data file for molecular simulations using the OPLS-AA force field in LAMMPS, GROMACS, etc. This code can be used to generate force field parameters and configurations files for systems of interts at specified densities. Run the LAMMPS simulations to compleate the tutorial.


# Challenges and prizes

Generate a Lammps data file for liquid systems of the molecules presented in the notebook and equilibrate their volume for 20 ns. Calcualte the average density and error of your simulations and post your resulst on the comments of the video. Be among the first 20 comments to get a 50% discount on your subscription for our course on "Advanced Molecular Dynamics Simulations and Enhanced Sampling". 

To qualify, ensure you're subscribed to our channel, following us on X, and have notifications turned on for both accounts.


## Lammps Installation

In case you dont have LAMMPS install, follow the instructions in the video and repo below to install the software and run the simulations. 

Youtube video: https://www.youtube.com/watch?v=-cYhA2wFGWs&t=10s

Repository: https://github.com/MolecularMindset/Lammps_VMD_Intro


<br>
<br>

# Follow us

Youtube: https://www.youtube.com/channel/UCS4G1tjaTmjvAICKsSLPBlw
X: https://twitter.com/MolecMindset


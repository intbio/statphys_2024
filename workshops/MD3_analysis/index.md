# Workshop: Analyzing MD simulations in Gromacs

## Description
- We will outline basic approaches to analyze MD simulations trajectories.
- Duration: 90 minutes
- Objectives: be able to 
    - **6.1 seminar**
    - Open and analyze trajectories using MDAnalysis
    - Properly analyze equillibration, autocorellation and uncertainty.
    - Analyze protein RMSD
    - Analyze distances, angles, contacts, hydrogen bonds, etc.
    - Analyze radial distribution functions.
    - Analyze kintetic parameters (diffusion, etc.)
    - **6.1 seminar**
    - Analyze thermodynamic fluctuations
    - RMSD matrix calculation and cluster analysis using Gromacs
    - Principal component analysis using gromacs. 
    


## Jupyter notebook
- [MD_analysis.ipynb](MD_analysis.ipynb)

## Required software and resources
- Access to a Jupyter notebook evironment with Python 3, MDanalysis, nglview libraries
- Access to Newton cluster with Gromacs installed or install Gromacs at your local workstation. See [http://www.gromacs.org](http://www.gromacs.org)

## Learning resources
- [MD Analysis tutorials](https://www.mdanalysis.org/MDAnalysisTutorial/) 



## Assignments

From previous assignments you should have a simulation for a protein of your choice set up in Gromacs. You may need to adjust the simulation parameters if needed (trajectory write parameters, duration, temperature etc).
Following analyses of this system will be needed as an assignment:

**Seminar 6.1**
1. Calculate system density, perform proper etimate of statistical uncertainty.
2. Calcuate RMSD of the protein with time. Make conclusions if the system has reached local equilibrium state.
3. Calcuate distance between N- and C-ends of protein. Make conclusions if the system has reached local equilibrium state. 
4. Calcualte the nunmber of hydrogen bonds within your protein and with water. Estimate average number (with uncertainty). Plot variation with time.
5. Calculate radial distribution function between water molecules.
6. Estimate water diffusion coefficients from mean square displacement.
**Seminar 6.2**
1. Calculate the isochoric heat capacity of the system from energy fluctuations (Note: you will need to simulate in NVT ensemble, but find the optimal volume at 1 bar first) or from simulations at different temperatures.
2. Plot RMSD matrix for MD frames; perform cluster analysis for mainchain+H atoms; visualize clusters and dynamics of systems transitions between them 
3. Perform PCA: plot atom covariance matrix, eigenvalues plot, calculate fraction of explained variability by first 6 vectors, make vector implementations and make representing first eigenvectors snapshots.  


### Troubleshooting
- Consult with the seminar protocol/recording
- Ask questions in Slack

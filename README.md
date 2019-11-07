# DFT And Some Basics
Onboarding repository for new students.

This repo contains some starting information that is hopefully useful for new students. 
We are going to build it as we go! 

## Week 1 : Running jobs on our local cluster mirage. 
A very basic introduction to parallel computing clusters and how to interact with them. 

We Will: get accounts on mirage, learn about how a compute cluster works (head node, compute node, etc.), 
learn about the queuing system and how to submit jobs to it. 

Task: Use VASP on mirage to run a convergence test. We want to converge the total 
energy of silicon unit cell as a function of (1) INCAR parameterss ENCUT and (2) the KPOINT sampling. 

Write a script or two to automate the process. You want to cycles reasonable values of ENCUT and KPOINTS, 
runs VASP on mirage, and extract the total energy for each run.  

You should generate a csv file in the following format: 

encut,kpoint,energy
\# 
\#

This format follows the philosophy of Tidy Data. 

## Week 2: Introduction to Shrodinger Equation, DFT, and DFT SCF loop, &  Analysis of Convergence Results Using Jupyter Notebooks. 

Task: Get python and jupyter running on your computer. 
Then use the notebook converge_energies.ipynb to analyze your results. 
Get familiar with pandas, matplotlib, seaborn, and altair. 

What are reasonable parameters of ENCUT and KPOINTS to get converged total energies in silicon? 

## Week 3: DFT & Prediction of silicon lattice constant, bulk modulus. 

## Week 4: DFT & Prediction of silicon band gap 

## Week 5: Supercells and scaling tests.  

Tasks: Get pymatgen working, and use it to generate a 2x2x2, 3x3x3, and 4x4x4 silicon supercell. 

## 5) Week 5: Hybrid functionals - get ready for some pain! 
Scaling tests, lattice constant, and band gap. 

(Other tasks: geometry optimization, phonons, barrier heights and NEB, ...) 

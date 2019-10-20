# DFT And Some Basics
Onboarding repository for new students.

This repo contains some starting information that is hopefully useful for new students. 
We are going to build it as we go! 

## 1) Week 1 : Running jobs on our local cluster mirage. 
A very basic introduction to parallel computing clusters and how to interact with them. 

We Will: get accounts on mirage, learn about how a compute cluster works (head node, compute node, etc.), 
learn about the queuing system and how to submit jobs to it. 

Task: Use VASP on mirage to run a convergence test. We want to converge the total 
energy of silicon unit cell as a function of (1) INCAR parameterss ENCUT and (2) the KPOINT sampling. 
You should generate a csv file in the following format: 

encut,kpoint,energy

This format follows the philosophy of Tidy Data. 

## 2) Week 2: Analysis of Convergence Results Using Jupyter Notebooks. 

Task: Get python and jupyter running on your computer. 
Then use the notebook converge_energies.ipynb to analyze your results. 
What are reasonable parameters of ENCUT and KPOINTS to get converged total energies in silicon? 

## 3) Week 3: Introduction to Shrodinger Equation, DFT & Prediction of silicon lattice constant, bulk modulus, and band gap. 

## 4) Week 4: 


# LSTM-for-RANS-modified
This project implements and evaluates a Long Short-Term Memory (LSTM) neural 
network pipeline for predicting Reynolds shear stress profiles — a critical closure term in 
Reynolds-Averaged Navier-Stokes (RANS) turbulence simulations. Motivated by the 
pioneering research of Pasinato (2024), which demonstrated that LSTM networks can 
effectively replace traditional RANS turbulence models such as the κ−ε model, this 
project reproduces and extends those concepts in a structured machine learning pipeline. 
A physics-inspired synthetic dataset is constructed, three model families (Linear, MLP, 
and LSTM) are systematically compared through an ablation study, and the best
performing model is thoroughly evaluated. Results confirm that LSTM architectures 
significantly outperform non-sequential baselines in capturing the wall-normal structure 
of turbulent shear stress profiles, validating the sequence modeling hypothesis for this 
class of physical prediction problems.

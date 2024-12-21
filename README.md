# HEP_MLC
Multilabel classification of HEP constraints with ML/DL

## How to Use?
1- Download ScannerS and all of its required libraries,and interfacing packages (e.g. micrOMEGAs and EVADE).
2- If you want to enable Latin Hypercube Sampling, then add the lhc.hpp file to ScannerS/include/Tools directory, and replace src/Setup.cpp and inlcude/Setup.cpp with the corresponding files in this repository (avoid this if you are familiar with ScannerS)
3- Open scans, and select the model. Specify the ranges (or leave the default), and the constraints. Conduct scans.
4- Chech imbalance, and conduct more targeted scans if required.
5- Open baseline and train a ML classifier.
6- Open training_validating_testing and train a MLC. Or conduct optuna trials to fine-tune hyperparameters (be careful this could become very heavy on the PC). 


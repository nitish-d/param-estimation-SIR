# param-estimation-SIR
Some quick example code for parameter estimation with an SIR model, as well as for examining identifiability and uncertainty using the Fisher information matrix and profile likelihoods. This code was originally developed for an assignment for the NIMBioS/MBI/CAMBAM Graduate Summer School, 2017. Equivalent code is provided in both R and Matlab, which goes through the following steps:
- Simulate the model at some starting parameter values
- Estimate the model parameters from (simulated) outbreak data using maximum likelihood (ML) (assuming Poisson with mean given by the model, but can be changed to whatever you prefer, e.g. least squares, etc.)
- Calculate a simplified form of the Fisher information matrix (FIM) and test its rank to evaluate the number of identifiable parameters/combinations
- Generate profile likelihoods for each parameter and determine 95% confidence intervals

Questions? Contact Marisa Eisenberg (marisae@umich.edu). This material is licensed under the MIT License---feel free to use/modify with acknowledgement.

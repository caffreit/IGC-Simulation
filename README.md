# IGC-Simulation
This code simulates the profile data from an Inverse Gas Chromatograph.
It first defines a surface energy distribution according to given parameters.
Starting at low surface coverage.
It simulates the surface free energy for each alkane (Hex to Decane).
It converts the surface free energy to the free energy of adsorption.
The straight line fit of these free energies is used to calculate the true surface energy for that particular low coverage.
Then updates the surface energy distribution.
It then repeats the above procedure for a slightly higher surface coverage until 100% coverage is reached.
Finally when the entire data set is simulated the data is fit to a stretched exponential and the parameters and data are written to excel files.

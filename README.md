# MolecularModeling-MidtermProject

Midterm project of Molecular Modeling and Drug Design course - MSc in Data Science and Information Technologies, Departement of Informatics and Telecommunications, National & Kapodistrian Uneversity of Athens.

# Goal

The key aim of this project is the processing, the preparation and the observation of G12C mutant of Kirsten rat sarcoma, K-RAS-4B protein, which is responsible for approximately 25% of all human cancers. 

# Implementation

On Report.pdf you can find the complete report of the project and all of the steps followed for the simulation.

A quick introduction:

- 4LDJ.pdb file downloaded from Protein Data Bank
- Visualization of mutant using VMD and creation of the required .psf file
- NAMD simulation (the files used for the simulation are not uploaded) - minimization, heating and equilibration phases
- Production run for 1.000.000 steps - 2ns
- Trajectory analysis - time series of a specific salt bridge depiction (using VMD), creation of a movie of the simulation (using VMD), calculation of RMSD time series (using RMSD.ipynb) and calculation of the first cluster representative (using cluster_representative.ipynb)

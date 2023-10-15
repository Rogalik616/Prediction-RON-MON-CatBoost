# Prediction of RON and MON octane numbers for individual substances

**RON** (Research Octane Number) and **MON** (Motor Octane Number) are two important parameters used to characterise the quality and octane number of petrol. They are of great importance in the petroleum and automotive industries. The determination of RON and MON is important for the following reasons:

* Engine efficiency and power

* Detonation prevention

* Environmental protection

* Compatibility and miscibility

* Economic aspects

These characteristics are often measured experimentally and there are standards by which octane numbers are determined. However, for various reasons (economic efficiency or evaluation of new compounds), the prediction of octane numbers is an urgent task.

## File description

* data.csv.csv: Contains raw data on RON and MON values of various molecules collected from different sources
* data_fixed.csv: Contains cleaned data on RON and MON values. Removed inaccuracies, typos, and obvious errors
* data_final.csv: Contains three columns {Smiles, RON, MON}. The RON and MON values were taken as the average of all values for each molecule
* description.txt: Contains a detailed description of the procedure for clearing the dataset
* requirements.txt: Contains information about the packages needed to work in the attached notebook
* prediction-RON-MON.ipynb: A notebook with a solution to the problem

## Starting up the notebook
Save all files to the current directory where the laptop is running (or change the data_root variable to the path where my csv files are saved).

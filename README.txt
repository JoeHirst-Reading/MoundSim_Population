# MoundSim Population

MoundSim Population is an agent-based model designed to explore the population growth of the pre-Columbian Casarabe Culture across a range of parameter assumptions. 

## Installation

MoundSim Population is designed to be run using NetLogo vers. 6.3.0. Please make sure this program is installed before attempting to run MoundSim Population. To run the program, 
please ensure that the data files associated with the model are located within the same directory as the model file. 

## Folder Structure

Inside the 'Model' subfolder, you will find: 

MoundSim_Population.nlogo - The primary model file. A text version can also be found in MoundSim_Population.txt.
config.txt - configuration parameters used to initialise the model. The order of values in this file follow the order of parameters found in the 'to configure' procedure of 
		the model file. 
MMR_Death.json - Data for household agent mortality.
MMR_Elevation.asc - Data for patch elevation.
MMR_LandUse.asc - Initial patch land cover classification data.
MMR_Sediment.dbf + MMR_Sediment.shp - Data for patch productivity. 

Inside the 'Documentation' subfolder, you will find:
LHS_Parameters.csv - a csv file containing the Latin Hypercube Sample parameters used during experiments. 
ODD - an Overview, Design + Details (ODD) description of MoundSim Population. 


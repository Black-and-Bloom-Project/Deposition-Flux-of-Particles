# Calculation of the Dry Deposition Flux of particles 

Version of this script: v26 (last update: 25/11/2020)
Author: Nuno Canha

# Goal of the script
This python script aims to calculate the deposition flux of particles, based on the particles deposition velocity and their concentration (obtained from monitored OPC data).
For this calculation, two previously obtained datasets are needed: 
- dry deposition database (output of "DDV script" script, namely "DDV_final.csv")
- concentration database obtained from OPC data (output of "OPC data analysis" script, namely "Hourly Conc particles.csv")

The output of this script gathers:
- Figures with temporal series of deposition flux of particles for specific diameter of particles (e.g. 2.55 micrometers) or for integrated bins
- Figure with statistical outputs (mean and SD) for each integrated bin
- Animated plots (in mp4 and gif) regarding the temporal variability of particles flux (for integrated bins)
- Dataset with final results of deposition fluxes of particles (for individual bins and for integrated bins)

# Updates
- the latest update focus on creating different outputs and also to replace NaN by zero values, along with the creation of integrated fluxes (test B&B).

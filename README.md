# Kolkata_Data_PMC_paper_TrafficCountEstimationUsingCrowdSourcedTrajectory
This release contains the raw data that are used in the paper titled [Traffic count estimation using crowd-sourced trajectory data in the absence of dedicated infrastructure](https://doi.org/10.1016/j.pmcj.2024.101935). 

The raw trajectory data interpreted camera data with signal timing information, traffic counts and queue lengths data were collected at a single-lane signalised road intersection at the Webel-More in Kolkata. Validation datasets are manually collected using a video camera installed at the observer's location. A ground-truth dataset of vehicle counts, departure headways, and signal timing is manually constructed using time-stamped video camera footage and visual inspection. A smartphone-equipped vehicle with the GPSlogger Android application is used to collect the set of vehicle trajectory data.

 P.S. -  All the .txt files contain raw GNSS data with timestamps recorded in GMT. Hence all the timestamps in .txt files are needed to be adjusted by adding 5 hours 30 miutes (GMT +5:30), which is Kolkata, India time zone. 
 
 The timestamps in the .csv files (files thos contain link count and leader follower headway) are local time as they are recorded in Kolkata. 
 
 "ds1 L..." stands for leader trajectory of dataset 1 and "ds1 F..." stands for follower trajectory of dataset 1. Similarly we have recorded multiple such leader follower trajectories.    

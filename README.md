# Demand Driven Scheduling for Automated Metro-Lines - Instances

This repository contains the data of the instances used for the computational experiments of the paper *Demand Driven Scheduling for Automated Metro-Lines*.

The first set of instances is located in the *mono* folder.
All files in the folder are named according to the convention mono_S_T_2.demand, where S and T denote the number of stations and time-steps respectively.

The second set of instances, related to the Milan metro line, are reported in the *milan* folder.
The files in the folder are named according to the convention milan-2_T.demand

Each file contains the passenger arrival data of the instance.
The passenger data is 3-dimensional a[i,j,t] denotes the total number of passngers (i,j,t) in the instance.
In the file, the arrival matrix is reported concatenated along the time axis.

An additional set of files (*.inst* files) is provided to describe the data associated to the optimized line.
The field of the file describe the number of stations, the number of trains operating the line, the time necessary to perform a short-turn, and the travel time from station 1 to each of the stations (provided as a vector in the line *station data*)
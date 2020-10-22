# Demand Driven Scheduling for Automated Metro-Lines - Instances

This repository contains the data of the instances used for the computational experiments of the paper *Demand Driven Scheduling for Automated Metro-Lines*.

The first set of instances is located in the *mono* folder.
All files in the folder are named according to the convention mono_S_T_2.demand, where S and T denote the number of stations and time-steps respectively.

The second set of instances, related to the Milan metro line, are reported in the *milan* folder.
The files in the folder are named according to the convention milan-2_T.demand

Each file contains the passenger arrival data of the instance.
The passenger data is 3-dimensional a[i,j,t] denotes the total number of passngers (i,j,t) in the instance.
In the file, the arrival matrix is reported concatenated along the time axis.

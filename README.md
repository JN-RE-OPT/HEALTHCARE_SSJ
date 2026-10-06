# Healthcare case of SSJ

This repository contains data and instances for the healthcare vaccine project.

## Structure of files

- BD_SSJ.xlsx – Master database
- data_SSJ_R* – Original region instances (`.dat` files)
- data_SSJ_NR* – New region instances (`.dat` files)

## Structure of data (`.dat` files)

param N:= Number of health centers
param K:= Number of vehicles
param T:= Horizon time
param Q:= Capacity per vehicle
param w:= Partial demand per health center
param W:= Total demand per health center
param serv:= Service time per health center
param early:= Initial time window per health center
param late:= Time window finish per health center
param duedate:= Due date per health center
param c:= Origin-destination time matrix 

##
*Kilometers per min conversion factor: 284.19 (km/min) for the Euclidean distance conversion.

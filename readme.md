This repository contains network traces that represent substation communication under different scenarios (Normal, Disturbance and Attacks). The reference substation one-diagram is shown in Figure 1. 

![alt text](https://www.overleaf.com/project/5c89e48e54c39a58ab59ad93/file/5cbe86157fc67069ab12de21?format=png)

Each folder represents one scenario, it contains： 
	1. One pcap file: captures GOOSE packets from 18 IEDs during 10 mins. 
	2. 18 csv files: list transmitted data from 18 IEDs at every second during 10 mins.

But the attacking scenario is based on normal scenario's trasmission traffic, so there is no specific CSV in Attack folder.

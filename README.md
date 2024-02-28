## A Python File Reader for OVITO
A custom file reader for OVITO.  
File extension: .lkmc  
Each .latt_traj file consists of two parts: header and main body.  

In the header region, the initial state of the simulation cell is written in the following format:  
&nbsp;&nbsp;&nbsp;&nbsp; Line 1: Comment  
&nbsp;&nbsp;&nbsp;&nbsp; Line 2: Scaling factor  
&nbsp;&nbsp;&nbsp;&nbsp; Line 3: a  
&nbsp;&nbsp;&nbsp;&nbsp; Line 4: b  
&nbsp;&nbsp;&nbsp;&nbsp; Line 5: c  
&nbsp;&nbsp;&nbsp;&nbsp; Line 6: number of sites N  
&nbsp;&nbsp;&nbsp;&nbsp; Line 7: Coordinate type  
&nbsp;&nbsp;&nbsp;&nbsp; Line 8 ... Line N + 7: Atomic number x y z occupation state 


&nbsp;&nbsp;&nbsp;&nbsp; Line N + 8: number of sites that participated in the reaction  
In the
main body, the 
Format of .latt_traj files  

***********************************************************************
 Simulation code from Durstewitz & Gabriel (2006), "Dynamical basis of 
 irregular spiking in NMDA-driven prefrontal cortex neurons", Cerebral
 Cortex
***********************************************************************

This archive should contain all files needed to run the network and 
single neuron simulations from the paper above. For single neurons, 
both NEURON and MatLab-based code is provided (for both runSglPCwcNMDA.m
is the ML-wrapper).

Please note that many network parameters are initialized according to 
random distributions (with given mean & stdv). Precise parameter 
configurations could therefore depend on the way the random number 
generator is implemented and initialized (and on processor type).
The paramter configuration on which the simulations in the paper were 
based is provided here in the file 'NetPar0.par'.

The simulation files expect a directory called 'out' in the current path.

For questions or comments please contact:
Dr Daniel Durstewitz
Centre for Theoretical and Computational Neuroscience
University of Plymouth
Portland Square, A 220
Plymouth, PL4 8AA, UK
daniel.durstewitz@plymouth.ac.uk

Copyright (C) 2006 for all software in this package by the Authors of
the above cited paper. This software may be used under the terms of the 
General Public License (www.gnu.org/copyleft/gpl.txt).

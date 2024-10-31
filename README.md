# Verification of shuttling protocols in crossbar spin qubit architectures
This repository contains a verification algorithm for adiabatic qubit shuttling-based routing in the shared-control crossbar architecture, which is used in the manuscript 'Compiling the surface code to crossbar spin qubit architectures'. 

As inputs, one needs to specify (i) the desired movements of the electrons (qubits) in the array, and (ii) the abstract pulse sequence specifying the gate-voltage changes. Then, the algorithm verifies whether the abstract pulse sequence generates the desired movements.

For an L×L crossbar array, assuming periodic boundary conditions, abstract plunger gate voltage values are expected as a list of integer values with length L.

This version of the code can handle up to L=13 different plunger gate voltages (implying a unit cell size L×L=13×13), since we use lowercase characters to enumerate the (vertical and horizontal) barrier gates.

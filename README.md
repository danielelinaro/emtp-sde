# Stochastic Differential Equations in the Electromagnetic Transients Program

This repository contains example simulation files for the implementation of SDEs in EMTP. The general procedure is described in the manuscript:

*Simulation of Stochastic Electromagnetic Transients in EMTP: a Bug Turned Into a Feature* <br/>
by F. Bizzarri, D. Linaro and A. Brambilla.

The following files are contained in this repository:

1. **Test_delay_RNG.ecf** shows how to implement a discrete map in EMTP, and is discussed in Section 4 of the paper.
1. **Kloeden4.19.ecf** contains a basic example of implementation of an SDE whose solution is explicitly known. It is described in Section 5.A of the paper.
1. **Wind.ecf** allows simulating the stochastic behavior of wind speed. It is described in Section 5.B of the paper.
1. **Machine.ecf** implements a stochastic simulation of a power system and is described in Section 5.C of the paper.

The manuscript is currently under review in the IEEE Transactions on Power Delivery.

For any question or comment about the simulation files, you can contact either [Federico Bizzarri](mailto:federico.bizzarri@polimi.it) or [Daniele Linaro](daniele.linaro@polimi.it).

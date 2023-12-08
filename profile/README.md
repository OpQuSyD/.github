# Open Quantum System Dynamics

Research conducted by the group of Prof. Walter Strunz (Institute of Theoretical Physics, 
TU Dresden University of Technology, 01062 Dresden, Germany)

# Repositories

### HOPS

The Hierarchy of Pure States (HOPS) is a stochastic numerical method to rigorously solve 
the full Schrödinger Equation for the system **and** its environment in a Monte-Carlo sense [1,2].
It is based on the stochastic pure state formalism governed by the Non-Markovian 
Quantum State Diffusion (NMQSD) equation [3], now reformulated in a hierarchical scheme
(similar to HEOM [4], a density matrix based approach to the same problem). 
In contrast to many "reduced" approaches (e.g. master equation techniques), no approximations on the 
level of the global Hamiltonian are required.
The method is exact in the sense that numerical errors can be made arbitrarily small, 
in a controlled way.
Details of HOPS have been discussed in Ref. [2,5,6] 
 
### [StocProc](https://github.com/OpQuSyD/stocproc)

A utility to accurately sample complex-valued stationary Gaussian stochastic 
processes continuously in time for a given auto-correlation-functions.     



# References

1. [Suess, D., Eisfeld, A. & Strunz, W. T. 
   Hierarchy of Stochastic Pure States for Open Quantum System Dynamics. 
   Phys. Rev. Lett. 113, 150403 (2014).](http://link.aps.org/doi/10.1103/PhysRevLett.113.150403)

2. [Hartmann, R. & Strunz, W. T. 
   Exact Open Quantum System Dynamics Using the Hierarchy of Pure States (HOPS). 
   J. Chem. Theory Comput. 13, 5834–5845 (2017).](http://pubs.acs.org/doi/10.1021/acs.jctc.7b00751)

3. [Strunz, W. T., Diósi, L. & Gisin, N. 
   Open System Dynamics with Non-Markovian Quantum Trajectories. 
   Phys. Rev. Lett. 82, 1801–1805 (1999).](https://link.aps.org/doi/10.1103/PhysRevLett.82.1801)

4. [Tanimura, Y. 
   Numerically “exact” approach to open quantum dynamics: The hierarchical equations of motion (HEOM). 
   J. Chem. Phys. 153, 020901 (2020).](https://aip.scitation.org/doi/full/10.1063/5.0011599)

5. [Hartmann, R., Werther, M., Grossmann, F. & Strunz, W. T. 
   Exact open quantum system dynamics: Optimal frequency vs time representation of bath correlations. 
   J. Chem. Phys. 150, 234105 (2019).](https://aip.scitation.org/doi/abs/10.1063/1.5097158)

6. [Hartmann, R. & Strunz, W. T. 
   Open Quantum System Response from the Hierarchy of Pure States. 
   J. Phys. Chem. A 125, 7066–7079 (2021).](https://pubs.acs.org/doi/10.1021/acs.jpca.1c03339)

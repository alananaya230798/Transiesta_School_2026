Tutorials for Transiesta School 20226 by Niels Gabriel and Alan Anaya:

1. Orbital Prunning with sisl: a beginner's tutorial
This tutorial introduces the basic ingredients for prunning orbitals in sisl. The tutorial is divided into two parts:
Nanoporous graphene (NPG): from DFT to a reduced 
 Hamiltonian. We read a precomputed SIESTA Hamiltonian, inspect its band structure, keep only the carbon and nitrogen 
 orbitals, compare the reduced model with the original DFT bands, visualize selected wave functions, and calculate the transmission along the conducting direction.
STO: Systems such as SrTiO
 (STO) exhibit complex band structures, in which the electronic states generally arise from linear combinations of several atomic orbitals. Unlike in graphene or nanoporous graphene (NPG), where a simplified description can be obtained by retaining only the 
 orbitals, the electronic structure of STO cannot be accurately captured using a single orbital type. Instead, the choice of orbitals must be adapted to the bands of interest, whether they belong to the valence band, the conduction band, or another selected subset of bands. 
 Note that, since we are now considering bulk STO, it is essential to preserve the symmetries of the bulk crystal when selecting the orbital basis. This requires retaining complete sets of symmetry-related orbitals, such as the t2g 
 orbitals or the e1g orbitals 

2.Reals Space Self Energies with sisl: a beginner's tutoria

This tutorial introduces the basic ingredients of quantum transport calculations with sisl using real space (surrounding) self energies RSSE. The tutorial is divided into four parts:

2.1 Real-space self-energies (RSSE) for graphene. We build a simple graphene tight-binding model and use a real-space self-energy to embed a finite graphene region in an otherwise infinite graphene sheet. We then calculate the DOS and LDOS from the retarded Green function.

2.2 Carbon vacancy in graphene. We employ the real space self energy to study the localize state arising from a carbon vacancy in graphene.

2.3 STM wire injecting into graphene. We attach an explicit Au chain to the graphene device and calculate transmission and injected bond currents.

2.4 Vertical graphene–CNT–graphene transport. We construct a carbon nanotube (CNT) connected between two graphene sheets, reuse the graphene RSSEs as electrodes, and calculate transmission, DOS, and spatially resolved LDOS.


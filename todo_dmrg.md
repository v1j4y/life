DMRG
====

Priority 1:
-----------

1. Verify if correct states are taken while truncating the density matrix.
2. Are you sure of having the correct S+, S- and Sz operators ?

Priority 2:
-----------

1. Check if Mathematica would be able to handle the proper dimensions and other requirements.
2. Project out unnecessary states.
3. Implement the Hubbard matrix.
    a. Implement the Hamiltonian
    b. Implement the Projector for the half filling case
    c. Implement the projection operators which project the hole at given positions

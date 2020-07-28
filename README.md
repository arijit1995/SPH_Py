# SPH_Py
Numba codes for Smoothed Particle Hydrodynamics
Basic numba codes for smoothed particle hydrodynamics.
The particles can be created using the get particle array.
All the terms in the equations are used as string keys in numba dictionaries.

Basic workflow can be understood as:
1.  Create Particle Array
2.  Iterate over all required equations in a python for loop
3.  Keep the required time evolve function in the loop
4.  Store the necessary values required from the Particle Array( They are stored in the form of numpy arrays)

Feel free to test for bugs and suggest modifications

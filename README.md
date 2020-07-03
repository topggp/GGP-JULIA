# GGP-JULIA

Written by Robin GRAPIN with the help of Joseph Morlier, this is the Julia version of the Generalized Geometry Projection Framework [1]. It includes as well a Julia version of the Method of Moving Asymptotes (MMA) optimization solver [2]. So far only the test case of the MBB beam is usable, but you can inspirate yourself of its implementation for the other loadcases.

Import the following packages : 
 + Plots
 + SparseArrays
 + LinearAlgebra
 + SuiteSparse
 + VectorizedRoutines
 
Modify the problem through the parameterrs of the main function calles "topggp" after having executed the previous functions. Chose the design space through the inputs nelx and nely, select the problem through the input problem, or define a new one writing from the line 114 of the main function, change the end conditions through the input maxoutit or the parameters kkttol and changetol lines 223 and 224.


References

[1] Coniglio, Simone et al. "Generalized Geometry Projection: A unified approach for geometric feature based topology optimization." Archives of Computational Methods in Engineering, DOI: 10.1007/s11831-019-09362-8 (2019) 

[2] Svanberg, Krister. "MMA and GCMMA, versions September 2007." Optimization and Systems Theory 104 (2007).

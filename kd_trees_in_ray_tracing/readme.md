# KD trees in ray tracing
A term paper written for the "Computational Geometry" elective.\
The paper gives motivation for space partitioning algorithms in the context of ray tracing. It specifically covers binary space partitioning algorithms, then further focuses on kd trees. The (time) complexity involved is analyzed, along with an analysis of the commonly used Surface Area Heuristic.\
Three different approaches to building kd trees are analyzed:
1) Exact SAH in $O(N log{N})$
    + An algorithmic solution which gives optimal building results with the best possible time complexity
2) An Adaptive Error-Bounded Heuristic
    + A solution which sacrifices the optimality of the solution for building speed, using piecewise quadratic approximations of the SAH function
3) Parallel KD trees for dynamic scenes
    + A solution which allows for parallelization during building, as well as incorporating a heuristic binning strategy
\
[View in Github](https://github.com/hiddenMedic/papers/blob/main/kd_trees_in_ray_tracing/KDtrees.pdf)
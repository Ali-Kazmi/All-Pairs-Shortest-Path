Here, I focus on performance against common libraries, on the All Pairs shortest path graph algorithm. This algorithm calculates the distance of the shortest path between every pair of vertices on the graph. I compare networkX (a slower python library) to SciPy (a high performance python library) to my own APSP implementation (that uses Numba to essentially compile it down to C, and can achieve similar performance to scipy) 

I use real (subsets of) california road network data for this project! 

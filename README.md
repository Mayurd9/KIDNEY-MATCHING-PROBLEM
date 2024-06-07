# KIDNEY-MATCHING-PROBLEM
This code is the implementation of the research paper:
New insights on integer programming models for the kidney exchange problem. Miguel Constantino, Xenia Klimentova, Ana Viana, and Abdur Rais (Constantino et al). European Journal of Operational Research, 231(1):57–68, 2013.

Kidney exchange problem is a graph problem whose each vertex or node represents a donor-recipient pair who are incompatible with each other. Presence of edge between two vertices indicates that those two vertices are part of the same cycle/chain.

The research paper contains various integer programming formulations to solve kidney matching problem in kidney exchange programs. I have solved those formulations using glpk solver since all of the formulations are linear. I have solved the problem for 10 vertices/nodes representing 10 incompatible donor-recipient pairs. First graph displayed by the code shows all the possible edges, intention is to show the complexity of the problem. The weight matrix in the code is assumed by me and all of the formulations are solved for the same weight matrix displayed at the starting of the code. The code can be run for any valid weight matrix. Solution of each formulation is displayed using graph. We can see cycles formed in these graphs. I have recorded execution time required to solve each formulation and then done comparison of execution times of all the formulations at the end of the code


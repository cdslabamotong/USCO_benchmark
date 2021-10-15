
# SCO_benchmark

SCO: stochastic combinatorial optimization (SCO) problem

What is SCO problem?

Consider the shorest path problem where the graph is stochastic, but we do not know the graph distribution. Given a pair of nodes (u,v), how to find the path between them that is the shortest in terms of the graph distribution? 

The common approach would first learn the graph distribution from some data, and then solve the expected shortest path problem. We consider another approach: we want to find the shorest path from u to v, by using the input-solution data: (u_i,v_i,p_i) where p_i shows the shortest path from u_i to v_i.

For formal definition, see https://github.com/cdslabamotong/usco_benchmark/blob/main/Stochastic%20Combinatorial%20Optimization%20Problem.pdf



We provide three benckmarks for stochastic combinatorial optimization problem.

Stochastic shortest path

Stochastic bipartite matching

Stochastic set cover

Presentation: https://recorder-v3.slideslive.com/?share=48762&s=18001758-e2b6-476a-b6fc-49b320d17bd1

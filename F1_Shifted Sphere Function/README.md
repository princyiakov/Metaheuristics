## [*Sphere* function](http://benchmarkfcns.xyz/benchmarkfcns/spherefcn.html)

### Mathematical statement

<image src = "https://github.com/princys-lab/Metaheuristics/blob/master/F1_Shifted%20Sphere%20Function/F1_MathematicalExp.PNG" width = "500">

### Graphical representation

<image src = "https://github.com/princys-lab/Metaheuristics/blob/master/F1_Shifted%20Sphere%20Function/F1_GraphicalExp.PNG" width = "500">

### Solution

Since the function is convex and quadratic (hence with a unique minimum),
intensification was privileged over diversification.
In dimension 50, PSO works well with more weight on the social factor than on the cognitive one.
In dimension 500, PSO becomes too slow and SADE works better, with a mutation variant
which puts emphasis on the global best solution.

#### Dimension d = 50

| Method  | | Results  |   |
| --- | --- | --- | --- |
| algorithm | PSO | best fitness | -450.000 |
| population size | 50 | difference with global minimum | 5.11e-5 |
| number of generations | 300 | distance of solution to optimal point | 7.15e-3 |
| inertia weight | 0.50 | computation time | 0.8s |
| social weight | 4.00 | number of function evaluations | 15050 |
| cognitive weight | 2.00 |
| swarm topology| local best |
| neighbors to consider | 10 |
| stopping criterion | number of generations |

![convergence graph](sphere_50_convergence_graph.png)

#### Dimension d = 500

| Method  | | Results  |   |
| --- | --- | --- | --- |
| algorithm | SADE | best fitness | -499.999 |
| population size | 100 | difference with global minimum | 6.75e-4 |
| max. number of generations | 15000 | distance of solution to optimal point | 2.60e-2 |
| mutation variant | best/2/exp | computation time | 36.5s |
| stopping criterion | fitness tolerance (1e-3) | number of function evaluations | 1072200 |

![convergence graph](sphere_500_convergence_graph.png)

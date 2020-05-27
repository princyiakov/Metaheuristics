## [*Sphere* function](http://benchmarkfcns.xyz/benchmarkfcns/spherefcn.html)

### Mathematical statement

<image src = "https://github.com/princys-lab/Metaheuristics/blob/master/F1_Shifted%20Sphere%20Function/F1_MathematicalExp.PNG" width = "500">

### Graphical representation

<image src = "https://github.com/princys-lab/Metaheuristics/blob/master/F1_Shifted%20Sphere%20Function/F1_GraphicalExp.PNG" width = "500">

### Algorithm

The function is 1. Convex 2. Quadratic 3. Unique Minimum
I chose BFGS Method from the Scipy Package for this function . 

#### Dimension d = 50

| Parameters  | | 
| --- | --- |
| Algorithm | BFGS |
| Lower Limit | -100 |
| Upper Limit | 100 |
| f_bias | -450 |
| Stopping Criteria  | 1e-5|
| Number of Evaluations | 520 |
| Computational Time| 0.46 seconds |


![convergence graph](https://github.com/princys-lab/Metaheuristics/blob/master/F1_Shifted%20Sphere%20Function/F1_GraphicalExp.PNG)

#### Dimension d = 500

| Method  | | Results  |   |
| --- | --- | --- | --- |
| algorithm | SADE | best fitness | -499.999 |
| population size | 100 | difference with global minimum | 6.75e-4 |
| max. number of generations | 15000 | distance of solution to optimal point | 2.60e-2 |
| mutation variant | best/2/exp | computation time | 36.5s |
| stopping criterion | fitness tolerance (1e-3) | number of function evaluations | 1072200 |

![convergence graph](sphere_500_convergence_graph.png)

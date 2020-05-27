## [*Sphere* function](http://benchmarkfcns.xyz/benchmarkfcns/spherefcn.html)

### Mathematical statement

<image src = "https://github.com/princys-lab/Metaheuristics/blob/master/F1_Shifted%20Sphere%20Function/F1_MathematicalExp.PNG" width = "500">

### Graphical representation

<image src = "https://github.com/princys-lab/Metaheuristics/blob/master/F1_Shifted%20Sphere%20Function/F1_GraphicalExp.PNG" width = "500">

### Algorithm

The function is 1. Convex 2. Quadratic 3. Unique Minimum
I chose BFGS Method from the Scipy Package for this function . 

### Dimension d = 50

| Parameters  | | 
| --- | --- |
| Algorithm | BFGS |
| Lower Limit | -100 |
| Upper Limit | 100 |
| f_bias | -450 |
| Stopping Criteria  | 1e-5|


#### Convergence Graph 
<image src = "https://github.com/princys-lab/Metaheuristics/blob/master/F1_Shifted%20Sphere%20Function/ConvergenceCurve.PNG" width = "500">
  
| Result   | | 
| --- | --- |
| Best Fitness  | -450 |
| Best Solution|  [ 97.24993638  77.06098421 -19.03114778  25.42869932 -22.90880332
  69.57217711   5.36971211  61.48072979 -21.30069768  92.34681328
 -93.97587886  90.74598743  42.876982    29.30964994 -10.66954731
 -65.07461569  67.04941681  94.01877076 -73.00501935 -49.80219668
  82.00142644  35.29318546  24.63215076   2.44313705 -99.3034501
 -54.62233721  95.69145956  72.25047991 -97.12295382  -2.84462876
 -16.71940553  54.58048415  -2.37049099   4.5129143   56.40988633
  18.24587122 -74.72144313 -78.0561454   32.58107693  99.41862385
 -30.76381098 -64.78909547 -86.42220578 -38.12082286 -33.04803889
 -24.76648744  90.44136674  43.86410377  55.86848806  85.62835219] |
| Number of Evaluations | 520 |
| Computational Time| 0.46 seconds |

#### Dimension d = 500

| Method  | | Results  |   |
| --- | --- | --- | --- |
| algorithm | SADE | best fitness | -499.999 |
| population size | 100 | difference with global minimum | 6.75e-4 |
| max. number of generations | 15000 | distance of solution to optimal point | 2.60e-2 |
| mutation variant | best/2/exp | computation time | 36.5s |
| stopping criterion | fitness tolerance (1e-3) | number of function evaluations | 1072200 |

![convergence graph](sphere_500_convergence_graph.png)

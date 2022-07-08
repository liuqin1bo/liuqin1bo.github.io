<head>
     <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
     <script type="text/x-mathjax-config">
         MathJax.Hub.Config({
             tex2jax: {
             skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
             inlineMath: [['$','$']]
             }
         });
     </script>
 </head>

# Part 1. A matrix on the matrix theory(editing)

| |  |M1|M2|M3|M4|M5|M6|M7|M8|M9|M10|M11|M12|M13|M14|M15|M16|M17|M18|M19|M20|M21|M22|
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|       
| |Property\Type|General Matrix|Square Matrix|Diagonal Matrix|Upper Trangular Matrix|Lower Trangular Matrix|Diagonal Dominant Matrix|Strictly Diagonal Dominant Matrix|Symmetric Matrix|Hermitian Matrix|Normal Matrix|Unitary Matrix|Householder Matrix|Positive Semidefinite Matrix|Hankel Matrix|Toplitz Matrix|Permutation Matrix|Companion Matrix|[Z-Matrix](https://en.wikipedia.org/wiki/Z-matrix_(mathematics))|[M-Matrix](https://en.wikipedia.org/wiki/M-matrix)|H-Matrix|[Hilbert Matrix](https://en.wikipedia.org/wiki/Hilbert_matrix)|[Adjacency Matrix](https://en.wikipedia.org/wiki/Adjacency_matrix)|
|1|Definition|d1 | d2| d3|d4 |d5 |d6 | d7|d8|d9 | d10|d11 |d12 |d13 |d14 |d15 |d16 |d17 |A matrix with all off-diagonal entries less than zero.|A Z-matrix with eigenvalues whose real parts are nonnegative. |A is an H-Matrix if its Comparision matrix \<A\> is an M-Matrix|d21| d22|
|2|Rank|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|3|Diagonizability|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|4|Determinant|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|5|Blocks|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|6|Determinant|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|7|Singularity|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|8|Characteristic Polynomial|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|9|Minimal Polynomial|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|10|Eigenvalues|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|11|Schur Complements|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|12|Upper bandwidth|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|13|Lower bandwidth|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|14|Sparsity|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|15|Jordan Cononical Form|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|16|Schur Unitary Decomposition|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|17|SVD|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|18|Polar Decomposition|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|19|Spectral Decomposition|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|20|QR Decomposition|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|21|Cholesky Factorization(M13)|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|22|Spectral norm|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|23|Frobenius norm|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|24|Submulticative norm|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|25|Numerical Range|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|26|Numerical Radius|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|27|Transpose|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|28|Conjugate|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|29|Transpose Conjugate|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|31|Adjoint|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|32|Comparision|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19|$Comparision=$\<A\>=<br>$(m_{i,j})=\vert a_{i,i}\vert,$ if $j=i$; <br>$(m_{i,j})=-\vert a_{i,j}\vert$, if $i\neq j$ |21|22|
|33|Generalized Inverse|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|34|Tensor Products|1 |2 |3 |4 |5 |6 |7 |8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| 20 |21|22|
|35|Cross Result 1|1 |2 |3 |4 |5 |6 |The Schur Complement of an SDD matrix is again SDD. <br><font color=blue>1979, Carlson and Markham.[1]</font>|8 |9 |10 |11 |12 |13 |14 |15 |16 |17 |18 |19| If $A$ is an H-Matrix, then \<A\> is a M-Matrix.|21|22|


## References
[1] D. Carlson and T. Markham, Schur complements of diagonally dominant matrices, Czech. Math. J. 29(104), pp. 246–251, 1979.

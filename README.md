NetworkX -- Numerical Error Associated with Computing Eigenvalues for the Laplacian Matrix of a Graph
========

Example
--------------

![Download](download.png)

   



Explanation
--------------
Here, we have unweighted graph H with 3 visible connected components generated using the NetworkX software library.  

```python
eig=nx.laplacian_spectrum(H)
print(eig)
connected_components = nx.number_connected_components(H)
print(connected_components)
```
The above code is used to compute the number of connected components in H and the eignvalues of the the Laplacian matrix of graph H.


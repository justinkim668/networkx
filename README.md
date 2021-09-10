NetworkX -- Numerical Error Associated with Computing Eigenvalues for the Laplacian Matrix of a Graph
========

Example
--------------

![Download](download.png)

   



Explanation
--------------
Here, we have graph H with 3 visible connected components generated using the NetworkX software library.  

```python
eig=nx.laplacian_spectrum(H)
print(eig)
connected_components = nx.number_connected_components(L)
print(connected_components)
```



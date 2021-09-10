NetworkX -- Numerical Error Associated with Computing Eigenvalues for the Laplacian Matrix of a Graph
========

Example
--------------

![Alt text](download.png)

   



Simple example
--------------

Find the shortest path between two nodes in an undirected graph:

.. code:: python

    >>> import networkx as nx
    >>> G = nx.Graph()
    >>> G.add_edge('A', 'B', weight=4)
    >>> G.add_edge('B', 'D', weight=2)
    >>> G.add_edge('A', 'C', weight=3)
    >>> G.add_edge('C', 'D', weight=4)
    >>> nx.shortest_path(G, 'A', 'D', weight='weight')
    ['A', 'B', 'D']


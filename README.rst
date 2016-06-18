graphpca
===========

Produces a low-dimensional representation of the input graph.

Calculates the ETCD of the graph and reduces its dimension using PCA. The
result is an embedding of the graph nodes as vectors in a low-dimensional
space.


Usage
-----

::

    >>> import networkx as nx
    >>> import graphpca
    >>> g = nx.erdos_renyi_graph(10000, 0.2)
    >>> g_2 = graphpca.reduce_graph(g, 2)
    >>> graphca.plot_2d(g_2)


Contributing
------------

Feel free to fork me and create a pull request at
https://github.com/brandones/graphpca



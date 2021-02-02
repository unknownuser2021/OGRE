# StaticGraphEmbeddings
OGRE - Online two-stages embedding method for large graphs

## Overview
OGRE and its variants are fast online two-stages graph embedding algorithms for large graphs. The accuracy of existing embedding, as defined by auxiliary tests, is maximal for a core of high degree vertices. We propose to embed only this core using existing methods, and then update online the remaining vertices, based on the position of their already embedded neighbors. The position of each new vertex is a combination of its first and second neighbors’ positions. We present three versions of this heuristic:

a) a weighted combination (OGRE), b)a directed regression (DOGRE), and c) a directedweighted  regression  (WOGRE).  We  show  thatOGRE is not only much faster than existing meth-ods, and applicable to very large graphs but alsoreaches a higher accuracy in vertex classificationand link prediction tasks, compared with the threeleading graph embedding algorithms: Node2Vec,HOPE, and Graph Factorization. Finally, OGREcan be combined with a Graph Neural Network(GNN) seed to obtain even higher accuracy vertexclassification in very large graphs.

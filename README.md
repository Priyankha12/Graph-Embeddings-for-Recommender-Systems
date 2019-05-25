# Graph-Embeddings-for-Recommender-Systems
This project involves predicting a user’s preference for some item they have not yet rated. 
I used a collaborative filtering model to explore this problem. 
In this model, the goal is to find the sentiment of a user about a particular item. 
This task is performed using a graph-based technique called DeepWalk.

Steps:
1. Created a heterogeneous information network with nodes consisting of users, item- ratings, items, and other entities related to those items
2. Used DeepWalk to generate random walks over this graph
3. Based on these random walks, embedded the graph in a low dimensional space using word2vec.

Finally I evaluate and compare preference propagation algorithms in heterogeneous information networks generated from user-item relationships.

Running the program:
python -m rec2vec --walk-length 2 --number-walks 2 --workers 4



# karate-club
Graph-based analysis of Zachary's Karate Club, as described in the paper "An Information Flow Model for Conflict and Fission in Small Groups", Wayne W. Zachary et al. (1972).
## Data Description
Two files contain the graph data: karate-edges.txt and karate-labels.txt. Each member of the karate club is one node, numbered 1 to 34, while the 77 edges represent two members who interacted outside of the club, i.e. were friends.
### *karate.edgelist*
A list of all 77 edges in the graph.
### *karate.labels*
A {1, 2}-labelling of each node, representing which faction that member joined after the club schism (Mr Hi vs John A.).
### *colour.labels*
A set of colour labellings of the 4 'friend communities' within the dataset. Only one node for each colour is provided, so this can be used for semi-supervised learning tasks.
- \[1, 0, 0, 0\] = 'red'
- \[0, 1, 0, 0\] = 'green'
- \[0, 0, 1, 0\] = 'blue'
- \[0, 0, 0, 1\] = 'purple'

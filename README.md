# Dijkstras-Algorithm

Sample input:
//Line one is a list of Nodes in network
A B C D Z

// Successive lines are the costs of each edge
A B 10
A Z 18
B C 3
B Z 17
B D 1
C D 1
D Z 4
.

Samle output:
A:0 B:+Inf C:+Inf D:+Inf Z:+Inf
A:0 B:10 C:+Inf D:+Inf Z:18
A:0 B:10 C:13 D:11 Z:18
A:0 B:10 C:12 D:11 Z:15
A:0 B:10 C:12 D:11 Z:15
A:0 B:10 C:12 D:11 Z:15
Z < D < B < A

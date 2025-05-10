# CSCI-3104-Problem-Set-8-solution

Download Here: [CSCI 3104 Problem Set 8 solution](https://jarviscodinghub.com/assignment/csci-3104-problem-set-8-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

1. (10 pts) Ginerva Weasley is playing with the network given below. Help her calculate the number of paths from node 1 to node 14. Hint: assume a “path” must have at least one edge in it to be well deﬁned, and use dynamic programming to ﬁll in a table that counts number of paths from each node j to 14, starting from 14 down to 1.
1 //

2 //

3 //

4 //

5 //
!!
6

7 // 8 // 9 //

10 //
!!
11
!! 12 // 13 // 14
2. (10 pts) Ginny Weasley needs your help with her wizardly homework. She’s trying to come up with an example of a directed graph G = (V,E), a start vertex v ∈ V and a set of tree edges ET ⊆ E such that for each vertex v ∈ V , the unique path in the graph (V,ET) from s to v is a shortest path in G, yet the set of edges ET cannot be produced by running a depth-ﬁrst search on G, no matter how the vertices are ordered in each adjacency list. Include an explanation of why your example satisﬁes the requirements.
3. (15 pts) Prof. Dumbledore needs your help to compute the in- and out-degrees of all vertices in a directed multigraph G. However, he is not sure how to represent the graph so that the calculation is most eﬃcient. For each of the three possible representations, express your answers in asymptotic notation (the only notation Dumbledore understands), in terms of V and E, and justify your claim.
(a) An adjacency matrix representation. Assume the size of the matrix is known. (b) An edge list representation. Assume vertices have arbitrary labels. (c) An adjacency list representation. Assume the vector’s length is known.
4. (30 pts) Deep in the heart of the Hogwarts School of Witchcraft and Wizardry, there lies a magical grey parrot that demands that any challenger eﬃciently convert directed multigraphs into directed simple graphs. If the wizard can correctly solve a series of arbitrary instances of this problem, the parrot will unlock a secret passageway. Let G = (E,V ) denote a directed multigraph. A directed simple graph is a G0 = (V,E0), such that E0 is derived from the edges in E so that (i) every directed multiedge, e.g.,{(u,v),(u,v)}or even simply{(u,v)}, has been replaced by a single directed
1
CSCI 3104 Problem Set 8
1 2 3
54
1 2 3
54
1 3 2 2 1 3 3 3 3 4 4 4 5 2 5 1 5 3 1
input output
1 2 3 2 1 3 3 4 4 1 2 5 5 1 3
G = (V,E) G′ = (V,E′)
An example of transforming G → G0
edge {(u,v)} and (ii) all self-loops (u,u) have been removed.
Describe and analyze an algorithm (explain how it works, give pseudocode if necessary, derive its running time and space usage, and prove its correctness) that takes O(V + E) time and space to convert G into G0, and thereby will solve any of the Sphinx’s questions. Assume both G and G0 are stored as adjacency lists. Hermione’s hints: Don’t assume adjacencies Adj[u] are ordered in any particular way, and remember that you can add edges to the list and then remove ones you don’t need.
5. (15 pts extra credit) Professor McGonagall has provided the young wizard Ron with three magical batteries whose sizes are 42, 27, and 16 morts, respectively. (A mort is a unit of wizard energy.) The 27-mort and 16-mort batteries are fully charged (containing 27 and 16 morts of energy, respectively), while the 42-mort battery is empty, with 0 morts. McGonagall says that Ron is only allowed to use, repeatedly, if necessary, the mort transfer spell when working with these batteries. This spell transfers all the morts in one battery to another battery, and it halts the transfer either when the source battery has no morts remaining or when the destination battery is fully charged (whichever comes ﬁrst).
2
CSCI 3104 Problem Set 8
McGonagall challenges Ron to determine whether there exists a sequence of morttransfer spells that leaves exactly 12 morts either in the 27-mort or in the 16-mort battery.
(a) Ron knows this is actually a graph problem. Give a precise deﬁnition of how to model this problem as a graph, and state the speciﬁc question about this graph that must be answered. (b) What algorithm should Ron apply to solve the graph problem? (c) Apply that algorithm to McGonagall’s question. Report and justify your answer.



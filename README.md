# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## Answer 

We have two graphs $A$ and $B$ with different numbers of nodes.

For these graphs to be isomorphic, we need to pair up each node from graph $A$ with exactly one node from graph $B$, no nodes should be left without a pair.

If graph $A$ has more nodes than graph $B$, we would run out of nodes in graph $B$ to pair with. Some nodes from $A$ would be left without a partner in $B$.

Similarly, if graph $B$ has more nodes than graph $A$, some nodes in $B$ would be left without a matching node from $A$.

In either case, we can't create a proper one-to-one pairing between the nodes of the two graphs. This means the graphs cannot be isomorphic.

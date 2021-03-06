# Causal Graphs

Causal graphs also referred to as **DAG - Directed Acyclic Graphs**!!!

* **There are 2 types of graphs:**
* **Directed Graphs**: When the arrow points to the direction of **the cause** of a variable. There has a particular direction of the path between the variables. **Directed graphs** have edges with direction.
* **UnDirected Graphs**: When there is a line between the variables showing that there is an association between them. **Undirected graphs** have edges that do not have a direction. 

![](../.gitbook/assets/image%20%2821%29.png)

* **A Directed Graph can be of 2 types:**
* **Cyclic Graphs**: A cyclic graph is a graph in which the only repeated vertices are the first and last vertices.
* **Acyclic Graphs**: An acyclic graph is a graph without cycles. When following the graph from node to node, you will never visit the same node twice.

**Causal graphs or DAG's** are the graphs with :

1. Directed paths \(No undirected paths\) between variables. 
2. Acyclic graphs 

**Note**: **Why Acyclic?**

* A causal arrow represents the time associated with the node, which increases as we follow the paths in the graph so that there is no path in order to return to the same node. Causality represents that a particular event or treatment affects the future and cant affect the past, hence there are no causal Loops.
* We require the graph to be acyclic to prevent "causal loops". A DAG must not contain a feedback loop where a variable causes itself.

**Causal graphs** provide a way to visualize the causal relationships between the treatment, the outcome, and all the biases \(confounder bias, selection bias, and others\) altogether. **Causal Graphs** represent association and causation both, simultaneously. **They help us think better.** They allow us to think in a new way about solving a problem.

**Note**: Causal Graphs are essential because they explicitly define the underlying assumptions.

**Causal DAGs consist of three elements:**

1. Variables \(nodes, vertices\) 
2. Arrows \(directed edges, arcs\): possible direct causal effects. The arrows order the variables in time.
3. Missing arrows; sharp assumptions about absent direct causal effects.

**Helpful in:**

1. Identifying variables to control for
2. Explicit the assumptions about origin of data 

**Applications:**

1. Model testing
2. Structure learning
3. Reduce "what if" questions to symbolic calculus\(Testable implications\)
4. Reducing scientific questions to symbolic calculus\(Testable implications\)


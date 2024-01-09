# Cascade-Failure-Protection

Definition 1 (Independent Cascade (IC) Model). Consider a graph G = (V, E) with puv defined on each edge (u, v) ∈ E.
The diffusion process proceeds in rounds. In round 0, all nodes u ∈ V are activated with probability ru. Then in each round t > 0, every node u activated in round t − 1 will have one chance to activate their inactivated neighbors v ∈ N(u) with probability puv, where N(u) denotes the neighborhood of u. Once a node is activated, it will never be deactivated. The process stops when no more nodes can be activated.

Definition 2 (Diffusion Minimization with Edge Protection
(DMEP)). Given a graph G′ = (V′, E′), edge weights puv and protection costs cuv, (u, v) ∈ E′, and a positive integer B, find a set of edges S ⊆ E′p to protect such that the expected number of activated nodes after the diffusion process starting from D, defined by the IC model, I(S) = E[I(S)], is minimized and the protection cost C(S) = Í e∈S Ce, is at most B.

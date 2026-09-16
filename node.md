---
alias: nodes, vertex, vertices
tags: cyber
crystal-type: entity
crystal-domain: cyber
---
a point in a [[graph]] that can be connected to other points by [[links]]

the irreducible pair: a [[graph]] is [[nodes]] and [[links]]. everything else — [[degree]], path, adjacency, centrality — is derived from these two

in the [[cybergraph]], a node is a [[particle]]. a [[neuron]] is the authoring subject referenced by [[cyberlinks]]; its identity and data representation follow the supported protocol profile

| generic | [[cybergraph]] |
|---|---|
| node | [[particle]] |
| authoring node | [[neuron]] |

see [[link]] for the other half of the pair. see [[graph]] for the structure they compose

## software node

in deployment terminology a node is a process participating in the network. its
GraphSession can host data from many neurons without its own signing identity.
full, partial and light modes describe storage/verification duties independently
of how many subject bindings or progs it serves. [[shard]] is a governed graph
partition. these deployment roles are distinct from the mathematical vertex.

see [node modes](../cyber/specs/node-modes.md).

discover all [[concepts]]

---
alias: installed program, program installation
tags: cyber, core
crystal-type: entity
crystal-domain: cyber
---
# prog

installed program code and state executed by a [[neuron]]. a prog has an
addressable data ID, pinned source/revision, state, lifecycle and finite execution
policy. it can receive input, retain a continuation and request authorized host
acts. the neuron supplies subject identity; a prog has no additional signing key.

two installations of the same code have independent state. multiple tasks can
wait or execute under their quotas while the neuron's authoritative state
publications serialize. cancellation, program removal and worker replacement
preserve the subject and other work. history and pending outcomes remain in
[[cybergraph]]/[[BBG]] under their retention contract.

[[soma]] composes tasks, models and tools using this execution mechanism. a skill
can be versioned instructional data or reference executable prog code. [[soul]]
configures behavior and policy, ward checks current grants, and vault performs
permitted secret operations. installing code or reading a manifest grants no
world access by itself.

## foreign contract profiles

[[cosmwasm]] in [[bostrom]], [[evm]] in [[ethereum]] and [[bitcoin script]] retain
their respective execution, address and consensus contracts. a foreign contract
account may itself be an addressable protocol subject where that network says so;
its address/rights are not reinterpreted as a local prog ID. invocation through an
attached neuron requires an explicit supported foreign action adapter.

see [execution](../neuron/specs/execution.md),
[lifecycle](../neuron/specs/lifecycle.md) and [[cyb/parts/prog]].

discover all [[concepts]]

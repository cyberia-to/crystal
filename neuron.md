---
icon: 🤪
alias: neurons, protocol subject
tags: cyber, core
crystal-type: entity
crystal-domain: cyber
crystal-size: bridge
---
# neuron

the protocol subject that authors [[signals]] and [[cyberlinks]], carries rights,
and participates in the graph's resource accounting. human, AI, sensor and other
programmed behavior can act through a neuron under the supported identity profile.

in the native profile, NeuronId is the 32-byte [[hash]] of the compressed public
key. an address is its network/profile-specific representation. foreign subjects
retain their own domain, address and verification rules. identical address text
or reused key material across incompatible domains does not merge their identity.
[[spell]] performs the supported signing operation.

## robot, subject and work

a named [[robot]] attaches any number of neurons for different keys, networks and
devices. [[soul]] is configuration; [[soma]] owns cognition; ward checks current
authority and vault manages secret custody. no root neuron is required to own the
other attachments.

a neuron may link directly, be observed without control, or execute durable
[[progs]]. a prog holds installed code/state; tasks and invocations represent work.
their addressable data IDs and independent lifecycles require no additional keys.
two installations of the same code can progress independently under one neuron.

changing a program, pausing a task or replacing a device preserves the subject.
a different native public key creates a different subject unless a supported
protocol defines verified continuity. selection changes never retarget already
admitted work; each action retains its original subject, network and context.

## active agency

linking spends protocol-accounted resources and influences [[focus]] and [[karma]]
under the selected network's rules. the [[intelligence]] loop is [[observation]] →
decision → [[cyberlink]] → graph recomputation → observation. observation alone
requires no program or running VM, while an act needs current authority.

[[cybergraph]] stores history and [[BBG]] provides durability. local runtime
commits, network signal steps and consensus finality carry distinct evidence.
see [the foundational model](../cyb/specs/architecture.md) and
[identity contract](../neuron/specs/identity.md) for exact semantics.

discover all [[concepts]]

---
alias: files
tags: cyber
crystal-type: entity
crystal-domain: cyber
---
a file is a [[particle]] with [[data]], [[name]], and [[meta]]

```
file = (particle, data, name, meta)
```

| component | role |
|-----------|------|
| [[particle]] | the [[Hemera]] hash of data — the file's identity in the [[cybergraph]] |
| data | the content bytes themselves |
| name | human-readable label for the file |
| meta | structured attributes — author [[neuron]], creation [[height]], [[cyberlinks]] to related particles, mime hints, anything else the [[dialect]] declares |

two files with the same data share the same particle. they remain different files when their name or meta differ — the particle is the content's intrinsic identity, the file is the [[neuron]]-facing wrapper around it

a file is what flows through [[tape]] frames when an [[agent]] sends "a thing" rather than a raw [[atom]] or [[molecule]]. the name lets humans address it, the meta lets the [[graph]] reason about it, the particle anchors it in [[content-addressed]] space, the data is the substance

every [[image]], [[sound]], [[video]], document, dataset, source file, and program in the [[cybergraph]] is a file in this sense — particles wrapped with the labels and attributes that make them legible to neurons

discover all [[concepts]]

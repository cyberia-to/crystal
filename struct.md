---
tags: cyb, cyber, core
alias: struct particle, structured data, json, toml
crystal-type: entity
crystal-domain: cyb
---
trees, configurations, records, and schemas as [[file]]. the native format for machine-readable knowledge in the [[cybergraph]]

source format: JSON, TOML — any hierarchical key-value structure

---

## rendering

```
json/toml source → parse → tree layout → collapsible glyph tree → GPU render
```

nodes expand and collapse. keys and values have distinct styling. depth encoded visually. the robot renders any struct file as an interactive tree regardless of nesting depth or key count

## in the cybergraph

struct is how machines describe their own state — and how the graph describes complex objects with named parts

types of struct files: smart contract ABIs, network configurations, protocol parameters, API schemas, scientific metadata, genomic annotations, experimental conditions, machine learning model configs, governance proposals, identity documents

a struct file is often the metadata companion to another file: the pixels file of a satellite image may have a struct file linked that contains coordinates, timestamp, sensor calibration, and resolution

## properties

- machine-readable natively — parseable by any conformant JSON or TOML parser without transformation
- schema-flexible — struct does not require a fixed schema. the [[cybergraph]] discovers schema by topology: files that share struct shapes cluster via [[motifs]]
- queryable by [[datalog]] — any key path in a struct file is accessible as a datalog term
- composable — struct files embed in [[component]] files as data sources for tables and forms

## relation to other languages

struct is the configuration language of the cybergraph. [[text]] carries argument; struct carries specification. a [[component]] reads a struct and renders it as interactive form fields. [[datalog]] queries struct fields directly

see [[json]] for the primary source format. see [[table]] for 2D structured data. see [[component]] for interactive composition

discover all [[concepts]]

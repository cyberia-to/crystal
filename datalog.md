---
tags: cyber, computer science
crystal-type: entity
crystal-domain: cyber
alias: Datalog, datalog programs
---
declarative logic programming language for querying graph structures. the theoretical basis of [[inf]] — cyber's [[cybergraph]] query language.

a datalog program consists of facts (corresponding to [[cyberlinks]]) and rules (derived relations through logical inference). recursion is native; programs always terminate by construction, which makes datalog suitable for on-chain query evaluation. the language operates over the same [[particle]] namespace as the rest of [[cyber]], treating content-addressed identifiers as constants in the logic.

full spec lives in the [[inf]] repo — see [[inf/README]] for cyber's CozoDB-based datalog dialect and [[inf/queries]] for the syntax.

see [[computation]], [[languages]], [[cyberlink]], [[cybergraph]], [[particle]], [[neural language]]

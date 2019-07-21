# Interoperability Discussion

July 19, 2019

What if we could create interoperability for peer-to-peer databases, something
like REST?

- Versions
- Operations / events
- Data types

Things to think about using
- CRDT — converge to one state
- Inmutable chain of diffs

Single ontology doesn’t work (some people thought it would, decided not to pursue that angle)
Must be able to be federated
Structure is local to the dataset / application
GraphQL migth be useful — specifies presentation to enable querying independent from storage schema

Need some kind of Authority : could be DNS, public key

### Version discussion
Timestamp or version number
We're really talking about causality not about time

How would this be solved across space?  (e.g. not reliant on terrestrial clock)

Lamport clock to create local ordering

Application independent of database

Data-types and subscription



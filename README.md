# Arthur Keen

I build agentic AI systems on knowledge graphs, and I build them with coding
agents as my development team. This account holds the results: 71 repositories
of demos, solution accelerators and customer proofs of concept since December
2024, and about 9,800 contributions in the last year.

I'm a solutions architect at [ArangoDB](https://arango.ai), where I also lead a
team of four developers. Earlier I was CTO at two companies, chief scientist at a
third, and head of machine learning at ArangoDB. In the 1990s I co-developed the
IDEF4 object-oriented design method.

## Agents that use graphs

- [agentic-graph-analytics](https://github.com/ArthurKeen/agentic-graph-analytics):
  graph analytics for people who don't know graph algorithms. Name a use case
  such as fraud detection or risk management. Agents choose the algorithms, run
  them and combine the results into an answer.
- [arango-shared-memory](https://github.com/ArthurKeen/arango-shared-memory):
  cross-project memory for Claude Code and Cursor, stored in ArangoDB. Coding
  agents on 7 projects use it to share requirements and code patterns, and to
  catch drift between a PRD and the code in both directions.
- [arango-entity-resolution](https://github.com/ArthurKeen/arango-entity-resolution):
  entity resolution that combines record blocking and similarity matching with
  graph embeddings, vector search and GraphRAG.

## Ontologies from the data you already have

- [relational-schema-analyzer](https://github.com/ArthurKeen/relational-schema-analyzer):
  turns a relational schema into a conceptual model, OWL-capable, mapped back to
  the source tables.
- [arango-schema-analyzer](https://github.com/ArthurKeen/arango-schema-analyzer):
  the same for an ArangoDB database. It infers entities and relationships from
  the physical collections and emits the mapping the query transpilers use.
- [r2g-arango](https://github.com/ArthurKeen/r2g-arango): projects PostgreSQL
  and Snowflake data as a graph in ArangoDB, by batch ETL, CDC over Kafka, or
  live queries through a mapping studio.
- [ontology-driven-arango-graph-generator](https://github.com/ArthurKeen/ontology-driven-arango-graph-generator):
  builds an ArangoDB graph from any OWL/RDF ontology plus sample data, as RDF,
  property graph or labeled property graph.
- [aws-ontology](https://github.com/ArthurKeen/aws-ontology): an OWL 2 ontology
  of AWS resources and their relationships.

## Natural language and query languages

- [arango-cypher-py](https://github.com/ArthurKeen/arango-cypher-py): an LLM
  writes Cypher against the conceptual model, and a transpiler turns it into AQL
  for the physical one. The LLM never sees the physical schema.
- [arango-sparql-py](https://github.com/arango-solutions/arango-sparql-py):
  SPARQL 1.1 to AQL transpiler and microservice.
- [arango-query-core](https://github.com/ArthurKeen/arango-query-core): the
  shared conceptual model under both transpilers and the federated query engine
  described below.

## Tooling

- [arangodb-data-tools-rs](https://github.com/ArthurKeen/arangodb-data-tools-rs):
  Rust library and CLI for bulk import, export, dump and restore, with pluggable
  storage backends.
- [arango-byoc-deploy](https://github.com/ArthurKeen/arango-byoc-deploy): the
  shared deployer for Arango Container Manager services.

## In progress, not public yet

- A contextual data fabric that queries several databases as one virtual graph.
  For each query it decides how to mix federation, virtualization and
  materialization.
- Ontology extraction from unstructured documents.
- Controlled natural language generated from an ontology, giving LLMs a
  deterministic path from plain English to SPARQL, AQL, Cypher/GQL, SQL,
  Gremlin and GSQL.
- idef0-rs: IDEF0 (FIPS 183) modeling in Rust that produces verifiable function
  contracts for people and coding agents.

## Background

- 7 US patents, on federated query generation and schema rewriting across public
  and private datasets, and on network intrusion and coordinated attack
  detection.
- Writing: [Transforming RDF-star to Property Graphs](https://arxiv.org/abs/2210.05781)
  (QuWeDa at ISWC 2022),
  [Tracing Hidden Risk](https://medium.com/arango-solutions/tracing-hidden-risk-cfe576e4b980),
  [Designing at Speed](https://medium.com/arango-solutions/designing-at-speed-4ec6b0729df2).
- Former W3C Advisory Committee member, Linked Data Benchmark Council director,
  FIBO Finalization Task Force member.
- Ph.D., Texas A&M. Engineering degrees from Stellenbosch.

[LinkedIn](https://www.linkedin.com/in/arthurkeen/)

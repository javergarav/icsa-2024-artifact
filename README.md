# ICSA 2024 - Artifact

Artifact for the [21st IEEE International Conference on Software Architecture (ICSA 2024)](https://conf.researchr.org/home/icsa-2024)

## Accepted Paper

- **Track:** Research Papers.
- **Type:** Short Paper.
- **Name**: Sarch-Checks: A Method for Checking Software Architecture Security Properties using a Knowledge Graph.
- **Authors**: Jeisson Vergara-Vargas, Salah Sadou, Chouki Tibermacine, Felipe Restrepo-Calle.

## Artifact Details

### Name

Sarch-Knows: Knowledge Graph for Supporting Sarch-Checks Method.

### Abstract

Sarch-knows is a knowledge graph presented in the paper, required for the checking process of the proposed install/. The artifact presented to ICSA corresponds to a compact version of this knowledge graph.

### Overview

In order to interact with Sarch-Knows, it is necessary to recognize the way as the Neo4j client works. Thus, general aspects are described below:

**1.** Finish the [INSTALL](INSTALL.md) guide.

**2.** Recognize the Neo4j client dashboard:

![alt text](./figures/readme/fig1.png)

**Notation:**

1. Neo4j client URL.
2. Current user of the database.
3. Node labels of the database. A **node label** is a way to categorize or group nodes based on their common characteristics or properties.
4. Relationship types of the database. A **relationship** is a directed connection between two nodes.
5. Property keys of the database. **Property keys** are used to define the attributes or properties of nodes and relationships.
6. Field to perform Cypher queries. [Cypher](https://neo4j.com/developer/cypher/) is a declarative graph query language developed by Neo4j for querying, updating, and managing graph data stored in a Neo4j graph database.
7. Button to run Cypher queries.
8. Space where the results of Cypher queries appear.
9. Information about the connection made to the database.

### Examples

Some examples that can be executed, using the Cypher language in the Neo4j client, are described in [Test Cases](TEST_CASES.md).
# Neo4j Training Materials

This repository contains the slide decks used in our Neo4j foundations workshop. The sessions walk through the core ideas behind property graphs, what Neo4j is as a product, Cypher, data modeling, importing data, and the Graph Data Science library, in the order they are typically delivered.

The material is designed for engineers, data professionals, and architects who are new to graph databases or who want a structured refresh before applying Neo4j on a real project.

## Who this is for

- Engineers evaluating Neo4j for a new workload
- Data and analytics teams moving from relational or document stores into graphs
- Architects scoping a graph-based system and looking for shared vocabulary across the team
- Anyone preparing for a hands-on Neo4j workshop

No prior graph experience is assumed. Comfort with SQL or any general-purpose query language is helpful but not required.

## Workshop outline

The sessions are numbered in the order they are presented. Each deck is self-contained, so they can also be used as standalone references.

| Session | Topic | File |
| ------- | ----- | ---- |
| S01 | Labeled Property Graph model and an introduction to Cypher | [S01 LPG and Cypher.pdf](S01%20LPG%20and%20Cypher.pdf) |
| S02 | What is a graph, and where graphs fit in the data landscape | [S02 What is a graph.pdf](S02%20What%20is%20a%20graph.pdf) |
| S03 | What is Neo4j: the product, architecture, and ecosystem | [S03 What is Neo4j.pdf](S03%20What%20is%20Neo4j.pdf) |
| S04 | Common graph use cases across industries | [S04 Common Graph Use Cases.pdf](S04%20Common%20Graph%20Use%20Cases.pdf) |
| S05 | Graph data modeling, part 1: nodes, relationships, and properties | [S05 Modeling Part 1.pdf](S05%20Modeling%20Part%201.pdf) |
| S06 | Graph data modeling, part 2: refactoring and modeling for queries | [S06 Modeling Part 2.pdf](S06%20Modeling%20Part%202.pdf) |
| S07 | Importing CSV data into Neo4j | [S07 Importing CSV into Neo4j.pdf](S07%20Importing%20CSV%20into%20Neo4j.pdf) |
| S08 | Indexes and constraints in Cypher | [S08 Cypher Indexes and Constraints.pdf](S08%20Cypher%20Indexes%20and%20Constraints.pdf) |
| S09 | Graph Data Science, part 1: projections and core algorithms | [S09 GDS Part 1.pdf](S09%20GDS%20Part%201.pdf) |
| S10 | Graph Data Science, part 2: applied workflows | [S10 GDS Part 2.pdf](S10%20GDS%20Part%202.pdf) |

## How to use this material

1. Clone or download the repository.
2. Work through the decks in numerical order. The modeling sessions (S05, S06) assume the vocabulary introduced in S01 and S02.
3. Pair the GDS sessions (S09, S10) with a running Neo4j instance that has the Graph Data Science plugin installed, so you can try the examples as they are introduced.

If you are running a workshop from these materials, the decks are intended to be used alongside a hands-on environment such as Neo4j Aura, Neo4j Desktop, or a Docker-based instance. A typical day-one delivery covers S01 through S06, with imports, indexes, and GDS on day two.

## Suggested prerequisites

- A Neo4j environment you can write to. [Neo4j Aura](https://neo4j.com/cloud/aura/) offers a free tier that is sufficient for most of the exercises.
- Neo4j Browser or Neo4j Workspace for running Cypher queries.
- For S09 and S10, the Graph Data Science library installed on the target instance.

## Contributing

This repository is maintained by the Neo4j field team. If you are delivering this workshop and find errors, outdated screenshots, or content that no longer reflects the current product, please open an issue or a pull request.

## License

Internal training material. Please contact the Neo4j field team before redistributing externally.

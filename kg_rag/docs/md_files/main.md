# KNOWLEDGE GRAPH 
- [1. Limitations of traditional RAG](#Limitations-of-traditional-RAG)
- [2. Overview of Knowledge Graph](#Overview-of-Knowledge-Graph)
- [3. Knowledge graph solutions](#Knowledge-graph-solutions)
- [4. GraphRAG](#GraphRAG)
    - [Architecture](#Architecture)

# Limitations of traditional RAG
The main limitation of traditional RAG system is, it will not be able to take the questions which are spanning the complete document. But most of the  times user will have the questions realted to complete document to get the questions understood and answered intentionally rather than the direct question.

# Overview of Knowledge Graph
Knowledge graph on the other hand will summarize the information and create the multi layered structure. It will extract the entities and create the nodes. 

# Knowledge graph solutions 
Currently knowledge graph solution is provided by 3 approaches 
1. [Graphrag from Microsoft](https://www.microsoft.com/en-us/research/project/graphrag/)
2. [LlamaIndex Graph rag](https://docs.llamaindex.ai/en/stable/examples/query_engine/knowledge_graph_rag_query_engine/)
3. [Neo4j graph rag](https://neo4j.com/developer-blog/graphrag-llm-knowledge-graph-builder/)

# GraphRAG
Overview and details of the Graph Rag are explained in below section are explained in below link 
[Graphrag](https://github.com/viswanath27/rag/blob/main/kg_rag/docs/md_files/graphrag.md)

## Architecture
Graph Rag architecure is shown below 

![GraphRagArchitecture](https://github.com/viswanath27/rag/blob/main/kg_rag/docs/images/kg_arch.png)

### Source documents

### Text Chunking 

### Entity Extraction

### Relationship Extraction

### Knowledge Graph Generation

### Community Detection

### Heirarchial Community Structure 

### Community Levels
* Root Level C0
* High Level C1 
* Low Level C3 

### Generate Community Services 
<p align="right">
  <a href="https://github.com/viswanath27/rag/blob/main/kg_rag/docs/md_files/main.md">
    <img src="https://github.com/viswanath27/rag/blob/main/kg_rag/docs/images/cho_icon.png" alt="home" style="width:5%;">
  </a>
</p>

# Quering in GraphRAG
- [1. Overview](#Overview)
- [2. Architecture](#Architecture)
- [3. Indexing Phase](#Indexing-Phase)
    - [1. Source documents](#Source-documents)
    - [2. Text Chunking](#Text-Chunking)
    - [3. Entity Extraction](#Entity-Extraction)
    - [4. Relationship Extraction](#Relationship-Extraction)
    - [5. Knowledge Graph Generation](#Knowledge-Graph-Generation)
    - [6. Community Detection](#Community-Detection)
    - [7. Heirarchial Community Structure](#Heirarchial-Community-Structure)
    - [8. Community Levels](#Community-Levels)
    - [9. Generate Community Services](#Generate-Community-Services)

## Overview
Overview and details of the Graph Rag are explained in below section. There are 2 main phases for this operation.
* Indexing Phase
* Quering Phase 

## Architecture
Graph Rag architecure is shown below 

![GraphRagArchitecture](https://github.com/viswanath27/rag/blob/main/kg_rag/docs/images/query_arch.png)

## User Query
---
This is the user Query which user wants to know the response about. 

## Select Community Level
---
The first action before we do any thing is choose the community level against which Answer has to be extracted today this is done manually while we are giving the command. But this should be done automatically so that there is a seemless response. 

## Retrieve Relevant Community Service
---
This is where the retrieve the relevant community services based on the question. If there are multiple communities against which this question is matching, that should also be fetched.

## General Partial Responses
---
Based on this communities there will be responses, there can be multiple responses as there are multiple communities. 

## Combine Responses 
---
Once the partial responses are generated these will be combined and augumented to form the answer. 

## Final Answer 
---
Final Answer is generated based on the responses from the above partial answers. 
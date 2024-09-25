# Math-solver

Goal:

Develop a RAG based tool which helps student in 15-151 with their homeworks

Updates

1. Use GraphRAG
    1. output data source, entity, and meta-data
        each entity comes with description
        do reference footnote
    


2. Use Traditional RAG Model
    1. Use elastic search + embedding model and vector search
        problem: model have problem with latex, for example, a change with variable name fails the search
        potential solution: train a embedding model

        problem: cannot retrieve pages by keywords very well
        solution: 



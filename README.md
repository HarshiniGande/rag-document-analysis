# RAG Pipeline for Large-Scale Document Analysis

Production NLP system using retrieval-augmented generation (RAG) to extract structured insights from 50,000+ unstructured documents.

## Stack
Python · PyTorch · LLMs · Hugging Face Transformers · Vector Embeddings

## What it does
- Ingests and preprocesses large volumes of unstructured real-world documents
- Uses transformer-based embeddings to index documents into a vector store
- Retrieves semantically relevant chunks and passes them to an LLM for structured answer generation
- Evaluated using ROUGE and retrieval benchmarks; iterated on architecture based on empirical results

## Key result
Achieved measurable retrieval precision improvements over baseline keyword search across 50,000+ documents.

## Design decisions
- Chose dense retrieval over BM25 for semantic coverage on domain-specific language
- Modular pipeline design allows swapping embedding models and LLM backends independently
- Full methodology documented for reproducibility

## Report
Full project report available: [rag-project-report.pdf](./rag%20project%20report.pdf)

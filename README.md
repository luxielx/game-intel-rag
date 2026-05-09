# Game Intel RAG

AI-powered game intelligence assistant that helps players query patch notes, guides, and game knowledge with source citations.

## Problem

Game knowledge is scattered across patch notes, wikis, guides, and community discussions. Players often need quick, reliable answers with sources.

## Solution

Game Intel RAG uses retrieval-augmented generation to search trusted game documents and generate answers with citations.

## Planned Features

- Import patch notes and game documents
- Chunk and index documents
- Generate embeddings
- Ask questions over game knowledge
- Return answers with source citations
- Track retrieval quality
- Provide a simple web UI

## Tech Stack

- Python
- FastAPI
- PostgreSQL / pgvector or Qdrant
- Docker
- LLM APIs / local models
- TypeScript / React later

## Roadmap

- [ ] FastAPI backend skeleton
- [ ] Document import
- [ ] Text chunking
- [ ] Vector search
- [ ] Question answering
- [ ] Citations
- [ ] Evaluation dashboard
- [ ] Frontend demo

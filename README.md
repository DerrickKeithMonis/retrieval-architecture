# Retrieval Architecture

Grounded retrieval pipelines with provenance tracking for agentic systems.

## Purpose

This repository explores how to build retrieval layers that agents can actually trust: every answer must be traceable to a source, and every source must be versioned and scored.

## What's inside

- **Chunking and embedding strategies** — experiments for technical and unstructured documents.
- **Provenance tracking** — source IDs, version anchors, and confidence scores attached to retrieved context.
- **Hybrid search** — combining vector, keyword, and metadata filters.
- **Re-ranking and filtering** — keeping only the context that improves answer quality.

## Design principles

1. Retrieval is not search — it is grounded context selection.
2. Every retrieved passage carries a citation.
3. Updates to source documents invalidate stale context explicitly.
4. Latency and quality are measured together.

## Status

Reference architecture and experiments — being hardened against real document corpora.

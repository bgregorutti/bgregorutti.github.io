---
layout: single
permalink: /open-source/
author_profile: true
---

A selection of personal open source projects spanning AI tooling, NLP, music information retrieval, and data science. All code is available on [GitHub](https://github.com/bgregorutti).

---

## AI & LLM Tools

### [mcp-local-agent](https://github.com/bgregorutti/mcp-local-agent)
**MCP server to connect Claude Code to local LLMs**

An MCP server that delegates code generation tasks from Claude Code to local models (via LM Studio or Ollama), with an iterative feedback loop to maintain quality. Saves 60–90% on API costs by routing simple and medium tasks to a free local model while Claude handles architecture and complex decisions (to be challenged).

`Python` · `MCP` · `Ollama` · `LM Studio` · `Claude Code`

---

### [graphrag-neo4j](https://github.com/bgregorutti/graphrag-neo4j)
**Graph RAG with Neo4j storage**

Lightweight Graph Retrieval-Augmented Generation (RAG) demo using Neo4j for structured context storage, SentenceTransformers for embeddings, and HuggingFace for text generation. Stores document graphs with vector embeddings, retrieves relevant nodes by similarity and graph expansion, and generates answers from the retrieved context.

`Python` · `Neo4j` · `SentenceTransformers` · `HuggingFace` · `RAG`

---

### [visualize-embeddings](https://github.com/bgregorutti/visualize-embeddings)
**Interactive word embedding visualiser**

A full-stack web application for computing and visualising word and sentence embeddings using transformer models (`all-MiniLM-L6-v2`). Displays raw 384-dim vectors and projects them to 2D via UMAP for interactive exploration of semantic relationships. Deployed with Docker Compose (FastAPI backend + nginx frontend).

`Python` · `FastAPI` · `sentence-transformers` · `UMAP` · `Docker`

---

### [biases-llm](https://github.com/bgregorutti/biases-llm)
**LLM bias testing tool**

A web application for testing and comparing biases across different language models (OpenAI, Anthropic, local LLMs via LM Studio/Ollama). Supports side-by-side multi-model comparison, pre-built bias test prompts (gender, professional, cultural), visual highlighting of bias indicators, and CSV/JSON export for further analysis. Built for educational use in the "Biases in AI" course.

`Python` · `FastAPI` · `JavaScript` · `OpenAI` · `Anthropic` · `Ollama`

---

### [chatbot-dash](https://github.com/bgregorutti/chatbot-dash)
**Minimal chatbot template with Plotly Dash**

A clean, reusable template for building a chatbot interface with Plotly Dash. Useful as a starting point for deploying LLM-backed chat applications in Python without a JavaScript frontend.

`Python` · `Dash` · `LLM`

---

## Machine Learning & Data Science

### [rfgroove-py](https://github.com/bgregorutti/rfgroove-py)
**Grouped variable importance and selection with random forests**

Python implementation of grouped feature importance measures and Recursive Feature Elimination (RFE) for random forests, based on two peer-reviewed articles. Allows computing importance scores for groups of features — particularly useful for functional and multivariate data where variables are naturally grouped. Compatible with scikit-learn.

`Python` · `scikit-learn` · `random forests` · `feature selection`

*Based on: Gregorutti et al. (2017), Gregorutti et al. (2015) — see [Publications](/publications/).*

---

## Music Technology

### [reharmonizer](https://github.com/bgregorutti/reharmonizer)
**Chord substitution and reharmonisation tool**

A full-stack web application implementing music theory algorithms for chord substitution and reharmonisation. Supports diatonic, tritone, circle-of-fifths, chromatic approach, and modal interchange substitution techniques, with a database of 15,000+ chord substitution pairs. Renders music notation via VexFlow and provides improvisation note recommendations.

`Python` · `FastAPI` · `React` · `TypeScript` · `PostgreSQL` · `VexFlow` · `Docker`

---

### [music-genre-classification](https://github.com/bgregorutti/music-genre-classification)
**Music genre classification using deep CNNs**

End-to-end music genre classifier trained on the GTZAN dataset using a 2D convolutional network over spectrograms derived via Short-Time Fourier Transform. Achieves 94.6% mean accuracy across 10 genres. Served via a Flask/Dash web app with real-time prediction during audio playback, containerised with Docker.

`Python` · `TensorFlow` · `Flask` · `Dash` · `Docker` · `GTZAN`

---

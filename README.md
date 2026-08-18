# Minhao Zhang

I build enterprise data agents: natural-language interfaces over real databases, the retrieval
and semantic layers that ground them, and the evaluation that decides whether they work.
M.S. Applied Data Science at the University of Chicago, graduating December 2026.

`Python` `SQL` `PostgreSQL` `LangGraph` `PyTorch` `TypeScript` `Docker` `GCP` `AWS Bedrock` `Neo4j`

---

### [governed-bi](https://github.com/Minhao-Zhang/governed-bi) · agentic BI over a live Postgres data lake

![license](https://img.shields.io/badge/license-MIT-blue?style=flat-square) ![python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![postgres](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![langgraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)

Natural-language SQL that stays governed. The model never holds a database handle: every generated
statement passes a deterministic SQL check that fails closed. The semantic layer is a separate
version-controlled corpus the serving agent reads but cannot write, and every evaluation run is
pinned to a content hash of the corpus it served.

### [BIRD-Obfuscation](https://github.com/Minhao-Zhang/BIRD-Obfuscation) · contamination-resistant text-to-SQL benchmark

[![dataset](https://img.shields.io/badge/%F0%9F%A4%97%20dataset-minhaozhang%2FBIRD__Obfuscation-yellow?style=flat-square)](https://huggingface.co/datasets/minhaozhang/BIRD_Obfuscation) ![license](https://img.shields.io/badge/license-CC%20BY--SA%204.0-lightgrey?style=flat-square)

A public benchmark can score a text-to-SQL model well for the wrong reason, because memorized
schemas and questions contaminate the signal. This one renames identifiers, plants decoy columns,
withholds foreign keys, and paraphrases questions in ways that leave the gold SQL unchanged. Each
dimension targets a single failure mode instead of an aggregate score.

### [obsidian-mcp-server](https://github.com/Minhao-Zhang/obsidian-mcp-server) · MCP server for a personal knowledge vault

[![stars](https://img.shields.io/github/stars/Minhao-Zhang/obsidian-mcp-server?style=flat-square&label=stars)](https://github.com/Minhao-Zhang/obsidian-mcp-server/stargazers) [![forks](https://img.shields.io/github/forks/Minhao-Zhang/obsidian-mcp-server?style=flat-square&label=forks)](https://github.com/Minhao-Zhang/obsidian-mcp-server/network/members) ![license](https://img.shields.io/badge/license-AGPL--3.0-lightgrey?style=flat-square) ![typescript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

An Obsidian plugin that runs a local MCP server, so AI assistants can search and edit a knowledge
vault over a standard interface. Semantic search runs against a local vector index with
configurable OpenAI-compatible embeddings. Installed by strangers, and carrying merged patches
from outside contributors.

### [slay_the_spire_agent](https://github.com/Minhao-Zhang/slay_the_spire_agent) · agent operations, learned on a hard game

![license](https://img.shields.io/badge/license-Apache--2.0-lightgrey?style=flat-square) ![langgraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square) ![fastapi](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

An LLM agent wired into a running game through a mod interface, built to practise the operational
half of agent work: traces, replay, legal-action validation, and human-in-the-loop control.

---

At the University of Chicago I build internal AI tooling, including a nine-service Cloud Run
workflow across Microsoft Graph, Airtable, Box, and Zoom, and I led Claude Code adoption for
technical and non-technical staff. Accuracy figures live in each repo rather than here, so they
stay current.

Chicago, IL · [LinkedIn](https://www.linkedin.com/in/minhao--zhang/)

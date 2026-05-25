# ⚙️ RUL-MultiAgent-LLM

A Multi-Agent Collaborative System for Remaining Useful Life (RUL) Prediction based on Domain Generalization.

## 📌 Project Overview
This project leverages the reasoning capabilities of Large Language Models (LLMs) to address the distribution shift problem in mechanical health monitoring. By integrating open-source time-series foundation models (e.g., Chronos, Moirai) with LLM-driven expert agents, the system automates domain-invariant feature extraction and cross-domain RUL prediction.

## 🚀 Architecture
- **Time-Series Agent:** Handles raw sensor data (C-MAPSS) and performs zero-shot feature extraction.
- **Literature Agent:** RAG-based retrieval focusing on top-tier reliability journals (RESS, MSSP) to provide physical failure context.
- **Expert Reasoning Agent:** Utilizes Chain-of-Thought (CoT) to bridge the semantic gap between numeric degradation patterns and physical mechanisms, guiding the domain adaptation process.

## 📊 Current Progress
- [x] Baseline setup for C-MAPSS FD002/FD004
- [x] Integration of Time-Series Foundation Models API
- [ ] Multi-Agent Debate Loop refinement (Current Token consumption is high, waiting for API plan upgrade)

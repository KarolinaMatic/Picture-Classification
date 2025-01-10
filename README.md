# SIA-Normen Chatbot mit RAG

## Beschreibung
Dieses Projekt implementiert einen Chatbot, der spezifische Fragen zu den SIA-Normen beantworten kann. Der Chatbot kombiniert ein vortrainiertes Sprachmodell (z. B. GPT) mit einer Retrieval-Augmented-Generation (RAG)-Pipeline. Dabei werden relevante Informationen aus PDF-Dokumenten zu den SIA-Normen extrahiert, segmentiert und in einer Vektor-Datenbank (FAISS) indexiert.

## Features
- Beantwortet spezifische Fragen zu den SIA-Normen.
- Nutzt RAG (Retrieval-Augmented-Generation), um präzise Antworten zu geben.
- Implementiert eine Vektor-Datenbank mit FAISS für schnelle und relevante Abfragen.
- Unterstützt längere Konversationen mit kontextbewussten Antworten.

## Installation
1. **Voraussetzungen**:
   - Python 3.8 oder höher.
   - Folgende Python-Bibliotheken: `faiss-cpu`, `openai`, `numpy`, `pandas`, `textwrap`.

2. **Bibliotheken installieren**:
   ```bash
   pip install
   faiss-cpu
   openai
   numpy
   pandas
   textwrap

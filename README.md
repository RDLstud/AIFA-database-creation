# AIFA-database-creation


A complete pipeline for enriching and exploring pharmaceutical data from the Italian Medicines Agency (AIFA), combining **web scraping**, **SQL analysis**, and **LLM-based information extraction**.

---

## 📚 Overview

Starting from a raw dataset provided by AIFA, this project:

1. 🕸 **Performs web scraping** to enrich each drug entry with:
   - AIC Code
   - Equivalence Group Code
   - Active Ingredients
   - Contraindications and other metadata

2. 🗄 **Stores and queries** the enriched dataset using **Microsoft SQL Server** to extract meaningful relationships and insights about drugs.

3. 🤖 **Applies a Large Language Model (LLM)** (via [Ollama](https://ollama.com/)) to analyze **unstructured columns**, aiming to automatically detect patterns or relevant medical information from textual data.

---

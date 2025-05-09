# 🔎 LLM Data Toolkit — Retrieval & Generation Workflows in Python

A curated set of **Jupyter notebooks (00 – 90)** that show, step by step, how to
turn unstructured text into structured, analysis‑ready data with the
**OpenAI Python SDK**.

<div align="center">
  
| 🚀 Quick wins | 📚 Re‑usable patterns | 🧪 Validation baked in |
|---------------|----------------------|------------------------|
| Extract causal “A → B” graphs from PDFs | Two‑stage retrieval flows that cut costs 3× | Modal‑vote agreement, cosine sanity checks |
| Generate supply‑chain nets & innovation profiles | Async batch jobs (10 k calls ⇢ 1 ¢/req) | Bias‑check extensions for demographic tasks |

</div>

---

## 📂 Notebook catalogue

| ID | Notebook name | What you learn (one‑liner) |
|----|---------------|----------------------------|
| `00_api_smoke_test.ipynb` | **Hello API** | Key handling, quick connectivity check |
| `10_single_stage_retrieval.ipynb` | **Retrieval v1** | Extract causal edges from abstracts via JSON schema |
| `20_two_stage_retrieval.ipynb` | **Retrieval v2** | Summarise 30 pp → then pull edges (cheaper & cleaner) |
| `30_supply_chain_generation.ipynb` | **Generation** | Bill‑of‑materials for an EV (inputs + scores) |
| `40_embeddings_mapping.ipynb` | **Node → Code** | Map free‑text parts to HS6 / JEL codes with embeddings |
| `50_dictionary_gen_prune.ipynb` | **Keyword builder** | Context‑aware n‑gram lists & LLM pruning loop |
| `60_tweet_stance.ipynb` | **Stance classifier** | Pro / anti / neutral / unrelated with modal voting |
| `70_name_gender.ipynb` & `71_name_race.ipynb` | **Demographic tagging** | Same helper, different schema; bias tests included |
| `80_company_innovation.ipynb` | **Innovation profiler** | 17‑field profile from just *name + country* |
| `90_batch_translation_demo.ipynb` | **Async batching** | Split → upload → poll → parse 50 k requests end‑to‑end |



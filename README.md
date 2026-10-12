## Yasser Mourabih

Final-year engineering student at IMT Nord Europe, currently on an exchange semester at
Hohai University in Nanjing, China. I build data and machine-learning systems end to end
— from the ingestion pipeline to the served model — and I care about the part most
projects skip: checking that the thing still works outside the conditions it was built
in.

> **Looking for a 6-month end-of-studies internship, starting late January 2027** —
> data science, data/ML engineering, NLP and LLM applications. Based in France from
> January; available for video interviews now (UTC+8).

---

### Projects

**[garde-fou](https://github.com/YasserMourabih/garde-fou)** — prompt-injection
screening for LLM applications.

Five detectors, from a bilingual rule engine to a fine-tuned multilingual transformer,
assembled into a three-stage cascade and served over a FastAPI endpoint — it detects
more than any single model it contains, at a tenth of their median latency. Built on six
public corpora, plus an evaluation set I wrote and published. The finding that made it
worth building: a detector that blocks **98.9%** of attacks on its own test split blocks
**15.9%** of the same attacks written in French.

`Python` · `PyTorch` · `transformers` · `scikit-learn` · `FastAPI` · 140 tests · CI on 3.10–3.12

**[anime-data-platform](https://github.com/YasserMourabih/anime-data-platform)** — a
complete data platform, from API to interface.

25,000+ titles pulled from the AniList GraphQL API into PostgreSQL, a TF-IDF recommender
weighted over genres, tags and synopses, and a Dagster pipeline that refreshes the whole
thing on a weekly schedule. Served through Streamlit, containerised with Docker.

`Python` · `PostgreSQL` · `Dagster` · `Streamlit` · `Docker`

---

### Working with

| | |
|---|---|
| **Languages** | Python · Java · SQL |
| **Data** | pandas · numpy · PostgreSQL · Dagster · Airflow · GraphQL and REST APIs |
| **ML & NLP** | scikit-learn · PyTorch · LangChain · transformers · sentence-transformers |
| **Shipping** | FastAPI · Streamlit · Docker · Kubernetes · Git · GitHub Actions · pytest |

---

### Reach me

[LinkedIn](https://www.linkedin.com/in/yasser-mourabih)

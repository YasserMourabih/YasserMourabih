## Yasser Mourabih

Final-year engineering student at IMT Nord Europe. I work on LLM evaluation and on the
unglamorous half of machine learning: finding out whether a model still does anything
useful once it leaves the benchmark it was trained on.

> **Looking for a 6-month end-of-studies internship, starting late January 2027** —
> LLM evaluation, AI safety, RAG, or data/ML engineering. Based in France.

---

### Projects

**[garde-fou](https://github.com/YasserMourabih/garde-fou)** — a multilingual
prompt-injection filter, and the audit that motivates it.

A detector trained on the largest public corpus blocks **98.9%** of attacks on its own
test split, and **15.9%** of the same attacks written in French. The repository is that
measurement, a French evaluation set I wrote and published, and the three-stage cascade
that survives the audit — detecting more than any single model it contains, at a tenth
of their median latency. Along the way: fine-tuning turned out to trade away
out-of-distribution calibration, and a third of the French collapse turned out to be
threshold drift rather than model failure.

`Python` · `PyTorch` · `transformers` · `scikit-learn` · `FastAPI` · 140 tests · CI on 3.10–3.12

**[anime-data-platform](https://github.com/YasserMourabih/anime-data-platform)** — an
end-to-end data platform, from API to interface.

25,000+ titles pulled from the AniList GraphQL API into PostgreSQL, a TF-IDF
recommender weighted over genres, tags and synopses, and a Dagster pipeline that
refreshes the whole thing on a weekly schedule. Served through Streamlit, containerised
with Docker.

`Python` · `PostgreSQL` · `Dagster` · `Streamlit` · `Docker`

---

### Reach me

[LinkedIn](https://www.linkedin.com/in/VOTRE-PROFIL) · yasser.mourabih@etu.imt-nord-europe.fr

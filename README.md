# AI Data Factory – Recommender Systems

Interactive study material for the Recommender Systems module of the
[AI Data Factory bootcamp](https://ai-factory.aueb.gr/) at AUEB.

Each lecture comes with a self-contained HTML study app: concept summaries,
a mastery quiz, and small interactive tools for experimenting with the
maths and code covered in class.

**Instructor:** Dimitrios Panagopoulos, PhD
**Format:** [online, live, 6 lectures]
**Prerequisites:** [e.g. Python, pandas, basic linear algebra]

## Open the study apps

Live version (GitHub Pages): **<PAGES_URL>**

Or clone the repo / download a file and open it in any modern browser.
No installation is needed, but an internet connection is required because
the pages load Tailwind CSS, MathJax and Font Awesome from CDNs.

## Contents

| # | Lecture | Topics | Interactive tools |
|---|---------|--------|-------------------|
| 1 | [Introduction to Recommender Systems](lecture_1_study_app.html) | What a recommender system is, the Netflix Prize, MovieLens 10M benchmark and data schema, cold start problem | MovieLens file schema inspector, pandas loading snippet, matrix sparsity calculator |
| 2 | [Matrix Factorization & Collaborative Filtering](lecture_2_study_app.html) | Evaluation and train/test splitting, SVD formulation, limits of standard SVD on sparse data, regularized SGD, latent factor interpretability | 2-factor dot product simulator, Python implementations, tuning latent factors (k) |
| 3 | [Collaborative Filtering & Item-Based Recommendation](lecture_3_study_app.html) | Item-based CF, cosine similarity, items as vectors (embeddings), similarity matrix, computing recommendations | Live cosine similarity calculator, Python recommendation snippet, formula reference |
| 4 | [Not included in this repo] | | |
| 5 | [Scalable Recommenders with PySpark ALS & Neo4j](lecture_5_study_guide.html) | Distributed processing with PySpark, Alternating Least Squares and its parameters, Neo4j property graph model, Neo4j with Python GraphDataScience, Cypher path traversal | ALS factorization and rating prediction, Cypher co-rating recommendation tester |
| 6 | [Not included in this repo] | | |

### Supporting material

- [Streamlit fundamentals](streamlit_fundamentals_presentation.html):
  slide presentation covering Streamlit's execution model, display and input
  widgets, layouts, session state, caching, and common pitfalls.

## License

[e.g. CC BY-NC 4.0.] Please credit the author if you reuse this material.

## Contact

* Site: [dpanagopoulos.com](https://dpanagopoulos.com/)
* [LinkedIn](https://www.linkedin.com/in/dpanagopoulos/)
* [Medium](https://dpanagop-53386.medium.com/)
* Substack: [Eureka Codex](https://eurekacodex.substack.com/)

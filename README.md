# IA con evidencia 🔬

Notebooks que acompañan mi serie de publicaciones en LinkedIn: abriendo las "cajas negras"
de machine learning, deep learning e IA en general, con código reproducible y papers citados. Cada post tiene su notebook, si aplica:
la corrés y comprobás las afirmaciones con tus propios ojos.

## Índice

| # | Post | Notebook | Papers |
|---|------|----------|--------|
| 01 | ¿Qué es realmente un embedding? (y por qué hereda nuestros sesgos) | [`notebooks/01_embeddings_y_sesgos.ipynb`](notebooks/01_embeddings_y_sesgos.ipynb) | [Mikolov 2013](https://arxiv.org/abs/1301.3781) · [Bolukbasi 2016](https://arxiv.org/abs/1607.06520) |

| 03 | Auditá tu palabra de control antes de usarla | [`notebooks/03_auditar_controles.ipynb`](notebooks/03_auditar_controles.ipynb) | [Caliskan 2017](https://arxiv.org/abs/1608.07187) · [Gonen & Goldberg 2019](https://arxiv.org/abs/1903.03862) |

| 04 | RAG mínimo: las tres funciones, sin frameworks | [`notebooks/04_rag_minimo.ipynb`](notebooks/04_rag_minimo.ipynb) | [Lewis 2020](https://arxiv.org/abs/2005.11401) · [Liu 2023](https://arxiv.org/abs/2307.03172) |

| 05 | Evaluación mínima: golden set, métricas y LLM-como-juez | [`notebooks/05_eval_minima.ipynb`](notebooks/05_eval_minima.ipynb) | [Zheng 2023](https://arxiv.org/abs/2306.05685) |



## Cómo usar

```bash
git clone <este-repo>
cd ia-con-evidencia
pip install -r requirements.txt
jupyter lab
```

Cada notebook es autocontenida: instala sus dependencias en la primera celda y
declara sus descargas pesadas (ej: el modelo word2vec original pesa 1.6 GB).

## Filosofía

- **Con evidencia:** toda afirmación tiene un paper citado, un documento técnico o un experimento que la reproduce.
- **Notebooks chicas:** una idea por notebook, corrible en minutos.
- **Español rioplatense**, tecnicismos en inglés porque así se leen en los papers.

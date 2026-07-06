# IA con evidencia 🔬

Notebooks que acompañan mi serie de publicaciones en LinkedIn: abriendo las "cajas negras"
de machine learning, deep learning e IA en general, con código reproducible y papers citados. Cada post tiene su notebook, si aplica:
la corrés y comprobás las afirmaciones con tus propios ojos.

## Índice

| # | Post | Notebook | Papers |
|---|------|----------|--------|
| 01 | La T de ChatGPT y dónde vive "banco" | [`notebooks/02_banco_contextual.ipynb`](notebooks/02_banco_contextual.ipynb) | [Mikolov 2013](https://arxiv.org/abs/1301.3781) · [Vaswani 2017](https://arxiv.org/abs/1706.03762) · [Devlin 2018](https://arxiv.org/abs/1810.04805) |
| 04 | RAG mínimo: las tres funciones, sin frameworks | [`notebooks/04_rag_minimo.ipynb`](notebooks/04_rag_minimo.ipynb) | [Lewis 2020](https://arxiv.org/abs/2005.11401) · [Liu 2023](https://arxiv.org/abs/2307.03172) |



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

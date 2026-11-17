# Market-basket analysis of actor co-occurrence in the IMDB Top 1000

Project 2 — a.y. 2025/26, Università degli Studi di Milano.

Baskets = movies, items = credited actors (`Star1`–`Star4`). Frequent actor sets are found with
**A-Priori** (single-machine baseline) and **SON on Apache Spark** (scalable version), and the two are checked against
each other and against brute force.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Parsa-Hajian/amd-market-basket-imdb/blob/main/market_basket_imdb.ipynb)

## Contents
- `market_basket_imdb.ipynb` — the notebook (runs top to bottom on Google Colab; set `SUBSAMPLE` in the settings cell)
- `report/report.tex` — the project report (LaTeX)

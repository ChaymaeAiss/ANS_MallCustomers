# 🛍️ Mall Customer Segmentation — Unsupervised Machine Learning

> Segmentation non supervisée de clients d'un centre commercial à l'aide de plusieurs algorithmes de clustering, avec comparaison des métriques, réduction de dimension et analyse critique.

---

## 📌 Objectif

Ce projet applique des techniques d'apprentissage non supervisé sur le dataset **Mall Customers** afin d'identifier des profils clients distincts basés sur leur âge, leur revenu annuel et leur score de dépense. L'objectif final est de produire des segments actionnables pour des applications de marketing ciblé.

---


## 🛠️ Stack technique

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.x-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.x-150458?style=flat&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-0.13-4C72B0?style=flat)
![UMAP](https://img.shields.io/badge/UMAP--learn-0.5-blueviolet?style=flat)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-F9AB00?style=flat&logo=googlecolab&logoColor=white)

```
pandas · numpy · matplotlib · seaborn
scikit-learn · umap-learn
```

> Le notebook peut également être exécuté directement sur **Google Colab** — adapter simplement le chemin du dataset dans la cellule de chargement.


<table>
  <tr>
    <td align="center"><b>Elbow Method</b></td>
    <td align="center"><b>Silhouette Analysis</b></td>
  </tr>
  <tr>
    <td><img src="figures/Elbow.png" width="350"/></td>
    <td><img src="figures/Silhouette.png" width="350"/></td>
  </tr>
  <tr>
    <td align="center"><b>K-Means (k=5)</b></td>
    <td align="center"><b>DBSCAN</b></td>
  </tr>
  <tr>
    <td><img src="figures/Km.png" width="350"/></td>
    <td><img src="figures/DBSCAN.png" width="350"/></td>
  </tr>
  <tr>
    <td align="center"><b>t-SNE</b></td>
    <td align="center"><b>UMAP</b></td>
  </tr>
  <tr>
    <td><img src="figures/TSNE.png" width="350"/></td>
    <td><img src="figures/Umap.png" width="350"/></td>
  </tr>
</table>

---


## 📄 Dataset

**Mall Customers Dataset** — disponible sur [Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

| Variable | Type | Description |
|----------|------|-------------|
| CustomerID | int | Identifiant unique |
| Genre | str | Genre (Male/Female) |
| Age | int | Âge du client |
| Annual Income (k$) | int | Revenu annuel en milliers de dollars |
| Spending Score (1-100) | int | Score de comportement d'achat |

---

## 👤 Auteur

Projet réalisé dans le cadre d'un cours d'**Analyse Non Supervisée et Prétraitement** (ANSP) par Chaymae Al-aissaoui.


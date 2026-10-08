# TP 1 - Apprentissage Statistique (2025)

M2 EI2D & MATD - Université Paris 13 - Institut Galilée

**Noms :** ELIE / Kouldjim

**Date :** 6 octobre 2026

---

## 1. Objectif du TP

On génère nous-mêmes un jeu de données qui décrit trois variables :

| Variable | Valeurs possibles |
|---|---|
| Cheveux | B = blond, D = dark |
| Hauteur | T = tall, S = short |
| Pays | G = Greenland, P = Poland |

La question à laquelle on répond est la suivante :

> Si on observe un nouvel individu **grand (T)** et **blond (B)**, quel est son pays d'origine le plus probable ?

On y répond de quatre façons :

- MAP (maximum a posteriori) avec l'hypothèse de Bayes naïf ;
- MAP sans l'hypothèse de Bayes naïf ;
- MLE (maximum de vraisemblance) avec l'hypothèse de Bayes naïf ;
- MLE sans l'hypothèse de Bayes naïf.

Dans une dernière partie, on refait la même chose quand la couleur des cheveux est une **variable continue** (une intensité entre 0 et 1).

---

## 2. Contenu du dossier

| Fichier | Description |
|---|---|
| `TP1_Apprentissage_Statistique.ipynb` | Le notebook Jupyter avec tout le code, les résultats et les explications |
| `TP1_Apprentissage_Statistique.pdf` | Le rapport, c'est-à-dire le notebook exporté en PDF (code + résultats) |
| `README.md` | Ce fichier |

---

## 3. Prérequis

- Python 3 (testé avec Python 3.10 et plus)
- Jupyter Notebook ou JupyterLab (ou VS Code avec l'extension Jupyter, ou Google Colab)
- Les bibliothèques suivantes :
  - `numpy`
  - `matplotlib`
  - `random` (déjà inclus dans Python)

Installation des bibliothèques si besoin :

```bash
pip install numpy matplotlib notebook
```

---

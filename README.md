# Les fondamentaux de l'IA — Rendus de TPs

Depot des travaux pratiques du cours **Les fondamentaux de l'IA**.

## Structure du depot

| TP | Theme | Notebook principal | Sujet | Outputs |
|---|---|---|---|---|
| TP1 | Analyse d'un algorithme (Iris) | `TP1/notebook/TP1_Iris_Pipeline_SHAP.ipynb` | `TP1/docs/TP1.pdf` | `TP1/outputs/` |
| TP2 | Mini-projet IA (Cas A : Churn) | `TP2/notebook/TP2_CasA_Churn.ipynb` | `TP2/docs/TP2.pdf` | `TP2/assets/` |
| TP3 | Deep Learning (Fashion-MNIST Zalando) | `TP3/notebook/TP3_Deep_Learning_Classification_Produits_Zalando.ipynb` | `TP3/docs/TP3.pdf` | `TP3/assets/` |

Notes:
- `TP1/docs/answers.txt`, `TP2/docs/answers.txt` et `TP3/docs/answers.txt` contiennent les reponses textuelles complementaires.
- Les figures sont generees automatiquement via **Run All** des notebooks.

## Execution locale (mode recommande)

Depuis la racine du depot:

```bash
cd TPX
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```

Puis ouvrir le notebook du TP concerne et lancer **Run All**.
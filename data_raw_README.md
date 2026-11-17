# Données brutes — S&P 500

Les données ne sont pas incluses dans ce dépôt (redistribution limitée par la licence). Elles sont téléchargées automatiquement par le notebook.

| Élément | Valeur |
|---|---|
| **Série** | `SP500` — niveau de clôture quotidien du S&P 500 |
| **Organisme** | Federal Reserve Bank of St. Louis (FRED), données de S&P Dow Jones Indices LLC |
| **Page de la série** | https://fred.stlouisfed.org/series/SP500 |
| **URL de téléchargement (CSV)** | https://fred.stlouisfed.org/graph/fredgraph.csv?id=SP500 |
| **Licence** | Consultation libre ; redistribution limitée par S&P Dow Jones Indices |
| **Date d'extraction** | À COMPLÉTER (voir `data/raw/EXTRACTION.txt`, créé à l'exécution du notebook) |

## Comment obtenir les données

1. Ouvrir `notebooks/projet_F08.ipynb`.
2. Exécuter la cellule de chargement : elle télécharge le CSV et l'enregistre dans `data/raw/SP500.csv`, puis écrit la date d'extraction dans `data/raw/EXTRACTION.txt`.

Ou manuellement : ouvrir l'URL de téléchargement ci-dessus et enregistrer le fichier sous `data/raw/SP500.csv`.

Remarque : FRED ne publie qu'environ dix ans glissants pour cette série, donc la période exacte dépend de la date d'extraction.

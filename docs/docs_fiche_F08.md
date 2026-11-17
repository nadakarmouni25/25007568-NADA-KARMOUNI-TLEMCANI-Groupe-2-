# Fiche du sujet F8 — Battre la marche aléatoire

**Étudiante :** Nada Karmouni Tlemçani
**Code Apogée :** 25007568
**Groupe :** G2 FIN
**Cours :** BD & DS — Contrôle continu Partie B, ENCG Settat, S7 FIN et CI (2026–2027)

## Sujet attribué

| Élément | Valeur |
|---|---|
| Sujet | F8 — Battre la marche aléatoire |
| Tâche | Classification binaire |
| Algorithmes du support autorisés | 8 à 16 |
| Algorithme principal retenu | Régression logistique |
| Alternative comparée | Forêt aléatoire |
| Référence naïve | Classe majoritaire |

À COMPLÉTER : coller ici le texte de la fiche officielle reçue de l'enseignant (consigne détaillée du sujet F8), si elle contient des éléments absents du tableau ci-dessus.

## Question étudiée

Un modèle utilisant uniquement l'historique des rendements du S&P 500 prédit-il le sens du rendement du jour suivant mieux que la classe majoritaire, et la stratégie qui en découle reste-t-elle rentable après coûts de transaction ?

## Sources de données

- Série `SP500` (niveau de clôture quotidien), Federal Reserve Bank of St. Louis (FRED), données de S&P Dow Jones Indices LLC : https://fred.stlouisfed.org/series/SP500
- Licence : consultation libre, redistribution limitée. Les données ne sont pas incluses dans le dépôt ; voir `data/raw/README.md`.
- Date d'extraction : À COMPLÉTER (voir `data/raw/EXTRACTION.txt`).

## Références

- Fama, E. F. (1970). « Efficient Capital Markets: A Review of Theory and Empirical Work ». *The Journal of Finance*, 25(2), 383–417. (Hypothèse d'efficience des marchés.)
- Pedregosa, F. et al. (2011). « Scikit-learn: Machine Learning in Python ». *Journal of Machine Learning Research*, 12, 2825–2830. (Bibliothèque utilisée pour la régression logistique, la forêt aléatoire, `Pipeline`, `TimeSeriesSplit` et `GridSearchCV`.)
- Support de cours du module BD & DS, ENCG Settat (algorithmes 8 à 16). À COMPLÉTER avec l'intitulé exact du support.

## Outils utilisés

- Python, NumPy, pandas, matplotlib, scikit-learn, SciPy (versions dans `requirements.txt`).
- Usage des outils d'IA : voir `DECLARATION_IA.md`.

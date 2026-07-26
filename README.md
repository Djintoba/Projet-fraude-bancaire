# Projet-fraude-bancaire
Analyse exploratoire du risque de crédit bancaire
## Sources
[Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
## Contexte
Ce projet réalise une **analyse exploratoire (EDA)** d'un jeu de données bancaires sur le risque de crédit. L'objectif est de comprendre les facteurs qui influencent le défaut de paiement des emprunteurs et d'identifier les profils à risque.
Dans le secteur bancaire, évaluer le risque de crédit est fondamental pour décider si un prêt doit être accodé. Ce projet d'explorer les données et de formuler les hypothèses avant de construire des modèles prédictifs.

### Variables

| Colonne | Description | Type |
| :--- | :--- | :--- |
| `person_age` | Âge de l'emprunteur (années) | Numérique |
| `person_income` | Revenu annuel (USD) | Numérique |
| `person_home_ownership` | Situation de logement (`RENT`, `OWN`, `MORTGAGE`, `OTHER`) | Catégorielle |
| `person_emp_length` | Ancienneté dans l'emploi (années) | Numérique |
| `loan_intent` | Raison du prêt (`PERSONAL`, `EDUCATION`, `MEDICAL`, `VENTURE`, `HOMEIMPROVEMENT`, `DEBTCONSOLIDATION`) | Catégorielle |
| `loan_grade` | Note de risque (`A` à `G`, `A` = meilleur) | Catégorielle |
| `loan_amnt` | Montant du prêt demandé (USD) | Numérique |
| `loan_int_rate` | Taux d'intérêt du prêt (%) | Numérique |
| **`loan_status`** | **🔴 CIBLE :** `0` = Remboursé, `1` = Défaut de paiement | Numérique |
| `loan_percent_income` | Ratio prêt / revenu (montant du prêt / revenu annuel) | Numérique |
| `cb_person_default_on_file` | Antécédent de défaut (`Y` = Oui, `N` = Non) | Catégorielle |
| `cb_person_cred_hist_length` | Ancienneté du crédit (années) | Numérique |

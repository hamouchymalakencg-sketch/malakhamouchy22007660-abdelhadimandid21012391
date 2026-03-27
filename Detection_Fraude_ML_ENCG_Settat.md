# ENCG Settat – Détection de Fraude par Machine Learning (2024–2025)

## ÉCOLE NATIONALE DE COMMERCE ET DE GESTION  
### ENCG – SETTAT  

---

# RAPPORT DE PROJET  

## Détection de Fraude par Machine Learning  

**Modélisation prédictive, analyse exploratoire et classification supervisée appliquées aux transactions financières suspectes**

---

### Auteurs

- **Malak Hamouchy** – 22007660  
- **Abdelhadi Mandid** – 21012391  

**Filière :** Gestion Finance  
**Groupe :** 3  
**Année universitaire :** 2024 – 2025  

---

# 1. Introduction Générale

La fraude financière représente l'une des menaces les plus coûteuses pour l'économie mondiale.  
Le Machine Learning permet d’identifier automatiquement les transactions frauduleuses dans de grands volumes de données.

---

## 1.1 Objectifs du Projet

- Analyse exploratoire des données (EDA)  
- Prétraitement des données  
- Application de SMOTE  
- Entraînement d’un modèle Random Forest  

---

# 2. Revue de Littérature

## 2.1 Types de fraude

- Fraude carte bancaire  
- Usurpation d’identité  
- Fraude interne  
- Blanchiment d’argent  

---

## 2.2 Déséquilibre de classes

- Fraude = 1% à 3%  
- Importance de Precision, Recall, F1-score, AUC  

---

# 3. Dataset

## Variables principales

- Transaction_Amount  
- Transaction_Type  
- Account_Balance  
- Merchant_Category  
- Hour_of_Day  
- Customer_Age  
- Card_Type  
- Is_Fraud  

---

# 4. Méthodologie

## Pipeline

1. Chargement des données  
2. EDA  
3. Prétraitement  
4. SMOTE  
5. Modélisation  

---

# 5. Modélisation

```python
model = RandomForestClassifier(
    n_estimators=100,
    max_depth=10,
    random_state=42
)

model.fit(X_train, y_train)
y_pred = model.predict(X_test)
```

---

# 6. Évaluation

- Precision  
- Recall  
- F1-score  
- AUC-ROC  

---

# 7. Conclusion

Le projet montre l’efficacité du Machine Learning pour la détection de fraude, avec un modèle robuste et performant.

---

# Fin du rapport

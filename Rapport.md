# 📊 Estimation de la Taille du Secteur Informel par Région  
## Modèle de Prédiction par Régression

**Auteur :** Wiam FAHIM /Meryem FAKLANI 

**Établissement :** ENCG Settat  
**Module :** Machine Learning en Finance  

---

## 📌 1. Introduction

Le secteur informel constitue une composante importante de l’économie marocaine. Il influence la croissance économique, l’emploi et les recettes fiscales. Cependant, sa mesure reste complexe en raison de son caractère non déclaré.

**Objectif du projet :**  
Estimer et prédire la taille du secteur informel (% du PIB régional) à l’aide de modèles de Machine Learning basés sur la régression.

---

## 📊 2. Description des données

### 🔹 Structure du dataset

- 12 régions marocaines  
- Période : 2014 – 2023  
- 120 observations  

### 🔹 Variables utilisées

| Variable | Description |
|----------|------------|
| pib_regional | PIB régional (en milliards MAD) |
| taux_chomage | Taux de chômage (%) |
| taux_pauvrete | Taux de pauvreté (%) |
| alphabetisation | Taux d’alphabétisation (%) |
| densite_pop | Densité de population |
| part_agri | Part de l’agriculture (%) |
| acces_finance | Accès aux services financiers (%) |
| taux_urbanisation | Taux d’urbanisation (%) |
| annee | Année |
| taille_informel | Taille du secteur informel (% PIB) |

---

## 🔍 3. Analyse exploratoire (EDA)

### 📈 Distribution

- La taille du secteur informel varie entre 10% et 70%  
- Forte dispersion entre régions  

### 📍 Analyse régionale

- Certaines régions présentent un niveau élevé d’informalité  
- D’autres sont plus structurées et formalisées  

### 🔗 Corrélations

| Variable | Impact |
|----------|--------|
| Taux de chômage | Positif |
| Taux de pauvreté | Positif |
| Part agricole | Positif |
| Alphabétisation | Négatif |
| Accès à la finance | Négatif |
| Urbanisation | Négatif |

**Interprétation :**  
- Les régions pauvres et rurales ont plus d’informel  
- Les régions développées ont moins d’informel  

---

## ⚙️ 4. Préparation des données

### Étapes :

- Encodage des régions (One-Hot Encoding)  
- Normalisation des variables  
- Split des données :
  - 80% train  
  - 20% test  

### Validation :

- K-Fold Cross Validation (k=5)  

---

## 🤖 5. Modèles utilisés

- Régression Linéaire  
- Ridge  
- Lasso  
- Random Forest  
- Gradient Boosting  

---

## 📊 6. Résultats

| Modèle | RMSE | MAE | R² | CV R² |
|--------|------|-----|----|-------|
| Régression Linéaire | ~ | ~ | ~ | ~ |
| Ridge | ~ | ~ | ~ | ~ |
| Lasso | ~ | ~ | ~ | ~ |
| Random Forest | ~ | ~ | ~ | ~ |
| Gradient Boosting | ~ | ~ | ~ | ~ |

**Meilleur modèle :** celui avec le R² le plus élevé  

### Interprétation :

- RMSE faible = bonne précision  
- MAE faible = erreurs faibles  
- R² élevé = modèle performant  

---

## 📉 7. Analyse du modèle

### Réel vs Prédit

- Les points proches de la diagonale indiquent une bonne performance  

### Résidus

- Distribution aléatoire → modèle fiable  

---

## 📊 8. Importance des variables

Top variables :

1. Taux de chômage  
2. Taux de pauvreté  
3. Part agricole  

**Conclusion :**  
Les facteurs socio-économiques influencent fortement l’informel.

---

## 🔮 9. Prédictions (2024–2028)

### Hypothèses :

- Croissance du PIB : +3.5%  
- Baisse du chômage  
- Amélioration de l’accès à la finance  

### Résultats :

- Diminution progressive du secteur informel  
- Variation selon les régions  

---

## 📍 10. Analyse régionale

### Région la plus informelle :
- Région avec forte pauvreté et ruralité  

### Région la moins informelle :
- Région urbanisée avec accès à la finance  

---

## 🧠 11. Interprétation économique

### Facteurs qui augmentent l’informel :

- Chômage  
- Pauvreté  
- Agriculture  

### Facteurs qui réduisent l’informel :

- Éducation  
- Urbanisation  
- Inclusion financière  

---

## ⚠️ 12. Limites

- Données synthétiques  
- Simplification de la réalité  
- Variables manquantes  

---

## 🚀 13. Recommandations

- Améliorer l’éducation  
- Développer l’inclusion financière  
- Encourager l’urbanisation  
- Créer des emplois formels  

---

## 🏁 14. Conclusion

Le Machine Learning permet :

- D’estimer efficacement le secteur informel  
- D’identifier les facteurs clés  
- D’aider à la prise de décision économique  

---

## 📁 15. Livrables

- Code Python  
- Visualisations :
  - Distribution  
  - Corrélation  
  - Comparaison des modèles  
  - Prédictions  

---

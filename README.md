# 📩 Spam & Ham Message Classifier

## 📌 À propos
Ce projet de Machine Learning a pour objectif de classifier automatiquement des messages textuels en deux catégories : **Spam** (indésirable) ou **Ham** (légitime)   Développé dans le cadre d'un cursus de Master, il met en œuvre un pipeline complet de Data Science, allant du nettoyage des données brutes à l'évaluation de modèles prédictifs[cite: 1, 11].

---

## 📖 Description du Projet
  Le système utilise des techniques de Traitement du Langage Naturel (NLP) pour transformer du texte non structuré en vecteurs numériques exploitables par des algorithmes de classification[cite: 6]. [cite_start]Une attention particulière est portée à la **gestion du déséquilibre des classes**, un défi courant dans la détection de spam où les messages illégitimes sont souvent minoritaires[cite: 8].

---

## 🎯 Objectifs & Fonctionnalités
-  **Analyse Exploratoire (EDA)** : Visualisation de la distribution des données et identification des mots-clés via des Nuages de Mots (WordClouds)[cite: 3, 4].
- **Prétraitement de données** : Nettoyage des valeurs manquantes et suppression des doublons pour garantir la qualité du modèle[cite: 5].
- **Ingénierie des caractéristiques** : Vectorisation par **TF-IDF** pour normaliser l'importance des mots[cite: 6].
- **Équilibrage des données** : Application de la méthode **Oversampling** sur la classe Spam pour éviter les biais de prédiction[cite: 8, 9].
- **Comparaison de Modèles** : Entraînement et évaluation comparative de **Naive Bayes** et de la **Régression Logistique**[cite: 11, 12].

---

## 🛠️ Technologies Utilisées
- **Langage** : Python[cite: 1, 2].
- **Analyse & Data Viz** : Pandas, NumPy, Matplotlib, Seaborn, WordCloud[cite: 1, 2, 4].
- **Machine Learning** : Scikit-learn (TfidfVectorizer, MultinomialNB, LogisticRegression)[cite: 1, 6, 11].

---

## 📂 Structure du Projet
- `spam_Emails_data.csv` : Dataset contenant les messages et leurs labels[cite: 2].
- `ml-spam&ham.ipynb` : Notebook Jupyter contenant l'intégralité du code et des analyses[cite: 1].
- `README.md` : Documentation du projet.

---

## 📊 Évaluation & Résultats
Le projet utilise plusieurs métriques pour valider la performance des modèles[cite: 12]:
* **Précision** : Pour minimiser les faux positifs (ne pas classer un mail important comme spam)[cite: 14].
* **Rappel (Recall)** : Pour maximiser la détection des messages frauduleux[cite: 14].
* **F1-Score** : Pour trouver le meilleur équilibre entre précision et rappel[cite: 15].

---

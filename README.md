# mastercard_challenge

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

[Datasets]https://www.kaggle.com/competitions/sgh-x-mastercard-hackathon-may-2025

A short description of the project.

# Fraud Detection Model — Mastercard Case Study

Projekt edukacyjny polegający na budowie modelu wykrywającego **fraud (oszustwa transakcyjne)** na podstawie danych transakcyjnych.

Celem projektu było przejście pełnego procesu analitycznego:
od eksploracji danych (EDA), przez feature engineering, aż do budowy i ewaluacji modelu klasyfikacyjnego.

---

## 🎯 Cel projektu

- Analiza danych transakcyjnych
- Identyfikacja wzorców fraudów
- Budowa modelu klasyfikacyjnego 
- Ocena skuteczności modelu
- Interpretacja wyników

Projekt realizowany jako ćwiczenie praktyczne z zakresu **Data Science / Machine Learning**.

---

## 📊 Problem biznesowy

Fraudy stanowią istotne zagrożenie dla instytucji finansowych.  
Celem było stworzenie modelu, który:

- klasyfikuje transakcje jako:
  - `0` – normalna transakcja
  - `1` – potencjalny fraud
- minimalizuje liczbę fałszywych negatywów (niezauważonych fraudów)

---

## 🛠 Technologie

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib / seaborn
- Jupyter Notebook

---

## 📁 Struktura repozytorium

```
mastercards/
│
├── notebooks/        # Pełny proces analizy w Jupyter Notebook
├── models/           # Zapisane modele (jeśli występują)
├── reports/          # Wizualizacje i raporty
├── references/       # Opis danych
├── tests/            # Testy (jeśli występują)
├── pyproject.toml
└── README.md
```

---

## 🔎 Etapy analizy

### 1️⃣ Data Exploration (EDA)

- analiza rozkładu klas (imbalanced dataset)
- wizualizacja cech
- korelacje między zmiennymi

### 2️⃣ Przygotowanie danych

- czyszczenie danych
- skalowanie zmiennych
- podział na zbiór treningowy i testowy

### 3️⃣ Modelowanie

W projekcie wykorzystano model klasyfikacyjny (np. Logistic Regression / Random Forest / inny).

Model trenowany był do wykrywania fraudów w danych transakcyjnych.

### 4️⃣ Ewaluacja modelu

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC

Szczególny nacisk położono na **Recall dla klasy fraud**, ponieważ pominięcie oszustwa jest kosztowne biznesowo.

---

## ▶️ Jak uruchomić projekt

```bash
git clone https://github.com/MateuszPietkiewicz/mastercards.git
cd mastercards

python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

pip install -r requirements.txt
jupyter notebook
```

Następnie otwórz notebook w folderze `notebooks/`.

---

## 📈 Wyniki

Model osiągnął zdolność wykrywania fraudów z określoną skutecznością (szczegóły w notebooku).

W notebookach znajduje się:
- analiza błędów
- interpretacja wyników
- wizualizacje

---

## 🧠 Czego nauczyłem się w tym projekcie

- pracy z niezbalansowanymi danymi
- budowy pipeline ML
- interpretacji metryk klasyfikacyjnych
- znaczenia Precision vs Recall w kontekście biznesowym
- organizacji projektu data science

---

## 🚀 Możliwe rozszerzenia

- zastosowanie SMOTE do balansowania klas
- tuning hiperparametrów (GridSearch)
- model ensemble
- deployment modelu jako API

---



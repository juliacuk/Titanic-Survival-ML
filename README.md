# 🚢 Titanic Survival Prediction - Machine Learning Analysis

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)

##  O projekcie
Celem projektu było zbudowanie i porównanie modeli uczenia maszynowego, które przewidują szanse na przeżycie pasażerów Titanica. Analiza obejmuje pełen proces **Data Science** — od czyszczenia danych (EDA) po zaawansowaną wizualizację wyników za pomocą technik redukcji wymiarowości.

##  Wykorzystane Technologie & Algorytmy
* **Stack:** Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn)
* **Modele:** * `SVM` (Support Vector Machine) – najlepsza wydajność
  * `KNN` (K-Nearest Neighbors)
  * `Decision Trees`

##  Kluczowe Etapy Prac
1. **Preprocessing:** Mapowanie płci, uzupełnianie braków w wieku (Mean Imputation).
2. **Feature Engineering:** Skalowanie danych (`StandardScaler`), kluczowe dla KNN i SVM.
3. **Analiza (EDA):** Potwierdzenie, że płeć (`Sex`) i klasa biletu (`Pclass`) to najważniejsze zmienne.
4. **Wizualizacja:** Zastosowanie **PCA** oraz **t-SNE** do analizy skupisk pasażerów.

##  Wyniki i Wnioski
| Model | Accuracy | AUC |
| :--- | :--- | :--- |
| **SVM** | **~80%** | **0.85** |
| KNN | ~78% | 0.82 |
| Decision Tree | ~78% | 0.81 |

> **Wniosek:** Najlepszy balans między precyzją a czułością wykazał model **SVM**. Dane są mocno przemieszane, co pokazała wizualizacja t-SNE, czyniąc problem ciekawym wyzwaniem klasyfikacyjnym.

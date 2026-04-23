# Titanic Survival Prediction - Machine Learning Analysis

##  O projekcie
Celem projektu było zbudowanie i porównanie modeli uczenia maszynowego, które przewidują szanse na przeżycie pasażerów Titanica. Analiza opiera się na danych z serwisu Kaggle i obejmuje pełen proces - od czyszczenia danych (EDA) po zaawansowaną wizualizację wyników.

##  Wykorzystane Modele
W projekcie porównałem trzy algorytmy klasyfikacji:
* **SVM (Support Vector Machine)** - najwyższa stabilność wyników.
* **KNN (K-Nearest Neighbors)**.
* **Decision Trees (Drzewa Decyzyjne)**.

##  Kluczowe etapy
1. **Preprocessing**: Mapowanie płci na wartości liczbowe, uzupełnianie braków w wieku (Age) średnią.
2. **Eksploracja danych**: Analiza korelacji cech `Sex` i `Pclass` jako głównych czynników przeżycia.
3. **Inżynieria cech**: Skalowanie danych (StandardScaler), co było kluczowe dla modeli odległościowych (KNN, SVM).
4. **Wizualizacja**: Wykorzystanie technik **PCA** oraz **t-SNE** do zrozumienia struktury danych.

##  Wyniki
Wszystkie modele osiągnęły dokładność (Accuracy) na poziomie **78-80%** oraz AUC w granicach **0.82-0.85**. 
Najlepszy balans między precyzją a czułością wykazał model **SVM**.

##  Jak uruchomić projekt
1. Sklonuj repozytorium: `git clone https://github.com/TWOJA_NAZWA/Titanic-ML.git`
2. Zainstaluj biblioteki: `pip install pandas scikit-learn seaborn matplotlib`
3. Otwórz notatnik w folderze `notebooks/`.
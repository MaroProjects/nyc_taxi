# Analiza taksówek w Nowym Yorku 

## Ogólny zarys
Projekt zawiera analizę danych dotyczących przejazdów taksówek w Nowym Jorku.
W pliku `NYCtaxi.ipynb` znajduje się szczegółowy proces przygotowania, eksploracji i wizualizacji danych, a następnie rozwiązania 3 kluczowych problemów:

**> Znalezienie optymalnego kierunku ruchu "wolnego" taksówkarza, tak aby maksymalizować szansę zdobycia pasażera**

**> Optymalna alokacja taksówkarzy, tak aby minimalizować czas oczekiwania pasażerów na przewóz**

**> Predykcja napiwku w zależności od parametrów przejazdu**

## Funkcje użyte w kodzie
- **Czyszczenie i wstępne przetwarzanie danych:**  
  - Usuwanie lub uzupełnianie wartości brakujących  
  - Konwersja typów danych (daty, liczby)  
  - Przygotowanie danych do dalszej analizy

- **Analiza eksploracyjna (EDA):**  
  - Statystyki opisowe
  - Wizualizacje rozkładów i zależności między zmiennymi  
  - Identyfikacja wartości odstających

- **Analiza czasowa:**  
  - Badanie zmian liczby przejazdów w ciągu dnia, tygodnia i miesiąca  
  - Identyfikacja godzin i dni o największym natężeniu ruchu

- **Analiza przestrzenna:**  
  - Wizualizacja na mapach lokalizacji rozpoczęcia i zakończenia kursów  
  - Identyfikacja tzw. „hotspotów” (obszarów o dużym natężeniu przejazdów)

- **Budowanie modeli:**  
  - Model Machinelearning, DeepLearning
    ![modelDeepL](https://github.com/user-attachments/assets/6c65908e-6224-4918-9386-eecf02fc484f)
  - Model optymalizacji gradientowej
    ![optymalny_kierunek_ruchu](https://github.com/user-attachments/assets/c94dae02-af28-4e33-bf08-dc60ef6e2ab1)
  - Model algorytmu zachłannego
    ![mapa_rozlozenia_taxi](https://github.com/user-attachments/assets/0f41924b-76c4-4fed-a768-fa4b2d2186bf)



- **Budowanie modeli:**  
  - Model Machinelearning, DeepLearning

    <img src="https://github.com/user-attachments/assets/6c65908e-6224-4918-9386-eecf02fc484f" alt="modelDeepL" width="50%" />

  - Model optymalizacji gradientowej

    <img src="https://github.com/user-attachments/assets/c94dae02-af28-4e33-bf08-dc60ef6e2ab1" alt="optymalny_kierunek_ruchu" width="400" />

  - Model algorytmu zachłannego

    <img src="https://github.com/user-attachments/assets/0f41924b-76c4-4fed-a768-fa4b2d2186bf" alt="mapa_rozlozenia_taxi" width="400" />


## Wymagania
Aby uruchomić analizę w środowisku lokalnym potrzebne są następujące pliki:

> https://github.com/codeforgermany/click_that_hood/blob/main/public/data/new-york-city-boroughs.geojson

> https://d37ci6vzurychx.cloudfront.net/trip-data/yellow_tripdata_2009-01.parquet









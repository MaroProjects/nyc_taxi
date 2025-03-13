# NYC Taxi Data Analysis

## Overview
Projekt zawiera analizę danych dotyczących przejazdów taksówek w Nowym Jorku.
W pliku `NYCtaxi.ipynb` znajduje się szczegółowy proces przygotowania, eksploracji i wizualizacji danych, a następnie rozwiązania 3 kluczowych problemów:
**Znalezienie optymalnego kierunku ruchu "wolnego" taksówkarza, tak aby maksymalizować szansę zdobycia pasażera**
**Optymalna alokacja taksówkarzy, tak aby minimalizować czas oczekiwania pasażerów na przewóz**
**Predykcja napiwku w zależności od parametrów przejazdu**

## Features
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

- **Wnioski statystyczne:**  
  - Korelacje między zmiennymi (np. długość trasy a cena)  
  - Porównanie różnych segmentów rynku (np. poszczególne dzielnice, pory roku)

## Requirements
Aby uruchomić analizę w środowisku lokalnym potrzebne są następujące pliki:
> https://github.com/codeforgermany/click_that_hood/blob/main/public/data/new-york-city-boroughs.geojson

> https://d37ci6vzurychx.cloudfront.net/trip-data/yellow_tripdata_2009-01.parquet

![Opis alternatywny](.C:/Users/marco/OneDrive/Documents/Praca/optymalny_kierunek_ruchu.png "Optymalny kierunek ruchu taksówek")






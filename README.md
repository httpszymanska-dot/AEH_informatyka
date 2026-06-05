 Klasyfikacja stadiów snu (Sleep Staging) z danych EEG

## Opis projektu
Projekt realizuje automatyczny potok (pipeline) przetwarzania danych neurobiologicznych w celu 
klasyfikacji stadiów snu na podstawie sygnałów EEG. Celem jest przejście od surowych plików .edf 
do wytrenowanego modelu Random Forest, który rozpoznaje fazy snu.

## Źródło danych
Dane pochodzą z bazy **Sleep-EDF Database** dostępnej w serwisie **PhysioNet**.
- Pobieranie odbywa się automatycznie za pomocą skryptu `data/download.py`.

## Struktura projektu

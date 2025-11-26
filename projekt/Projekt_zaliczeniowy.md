# Projekt zaliczeniowy

## Analiza bliskości (wyszukiwanie najbliższego sąsiada)

<img src="../wyklady/_images/2_polaczenia.png" width="500">

Projekt obejmuje samodzielne napisanie funkcji w środowisku PyQGIS. Głównym celem jest
wyszukanie najbliższego sąsiada pomiędzy dwiema warstwami punktowymi:

1. `dostawcy.gpkg` (punkty główne).
2. `odbiorcy.gpkg` (punkty podrzędne).

W zależności od zakresu wykonanych prac, można uzyskać maksymalnie następujące oceny:

### Ocena dostateczna

- Wyznaczenie dla każdego odbiorcy najbliższego dostawcy. W tym
  celu należy zastosować zagnieżdżoną pętlę.
- Stworzenie linii pomiędzy najbliższym odbiorcą a dostawcą.
  Do warstwy należy dodać atrybut z obliczoną odległością.
- Wynikiem operacji będzie zapisana warstwa wektorowa na dysku.
 
### Ocena dobra

- Kod należy przygotować jako skrypt przetwarzania QGIS, w którym
  użytkownik wskazuje warstwy wejściowe oraz ścieżkę zapisu wyniku.

### Ocena bardzo dobra

- Skopiowanie atrybutów tabeli z warstwy dostawcy do odbiorcy.
- Wynikiem operacji będzie zaktualizowana warstwa `odbiorcy.gpkg`.
- Kod należy przygotować w postaci skryptu przetwarzania QGIS.

## Termin

Projekt zaliczeniowy proszę wysłać do 6 lutego (piątek) na GitHub Classroom.

Zadanie 1

W bazie danych firmy X zawarte są informacje o instalacjach pewnej aplikacji,
o urządzeniach, na których ta aplikacja została zainstalowana, oraz o krajach, w których
przeprowadzono instalację.
Dane zgromadzono w plikach tekstowych: <i>kraje.txt</i>, <i>instalacje.txt</i> oraz
<i>urzadzenia.txt</i>. Pierwszy wiersz każdego z plików jest wierszem nagłówkowym,
a dane w wierszach rozdzielone są znakami tabulacji. 
Plik o nazwie kraje.txt zawiera informacje o krajach, w których instalowano aplikację.
W każdym wierszu pliku znajdują się następujące dane: 

<b>kod_k</b> – kod kraju (napis dwuznakowy)

<b>nazwa_k</b> – nazwa kraju (napis do 50 znaków)

<b>ludnosc_k</b> – ludność kraju (liczba całkowita do 10 cyfr określająca liczbę ludności).


Przykład:
| kod_k | nazwa_k | ludnosc_k |
|-------|---------|-----------|
| AN    | NETHERLANDS ANTILES | 227049 |
| CR | COSTA RICA | 5003393 |
| DZ | ALGERIA | 42545964 |


Plik o nazwie urzadzenia.txt zawiera informacje o urządzeniach, na których może być
instalowana aplikacja. W każdym wierszu pliku znajdują się następujące informacje:

<b>kod_u</b> – unikatowy kod (liczba całkowita co najwyżej 5-cyfrowa)

<b>nazwa_u</b> – nazwa urządzenia (napis do 80 znaków)

<b>producent_u</b> – producent urządzenia (napis do 35 znaków)

<b>typ_u</b> – typ urządzenia (napis: Tablet, Phone lub PC).

Uwaga: nazwa urządzenia nie jest unikatowa – w tabeli mogą występować dwa lub więcej
urządzenia o tej samej nazwie.

Przykład:
| kod_u | nazwa_u     | producent_u | typ_u |
|-------|-------------|-------------|-------|
| 12410 | PLATINUM_E5 | Sky devices | Phone |
| 6549  | Ilium L1120 | Lanix       | Phone |



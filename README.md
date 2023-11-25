Zadanie 1

W bazie danych firmy X zawarte są informacje o instalacjach pewnej aplikacji,
o urządzeniach, na których ta aplikacja została zainstalowana, oraz o krajach, w których
przeprowadzono instalację.
Dane zgromadzono w plikach tekstowych: <i>kraje.txt</i>, <i>instalacje.txt</i> oraz
<i>urzadzenia.txt</i>. Pierwszy wiersz każdego z plików jest wierszem nagłówkowym,
a dane w wierszach rozdzielone są znakami tabulacji. 
Plik o nazwie <i>kraje.txt</i> zawiera informacje o krajach, w których instalowano aplikację.
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


Plik o nazwie <i>urzadzenia.txt</i> zawiera informacje o urządzeniach, na których może być
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

Plik o nazwie <i>instalacje.txt</i> zawiera informacje o instalacjach aplikacji. W każdym
wierszu pliku znajdują się następujące informacje:

<b>data_i</b> – data instalacji (w formacie dd.mm.rrrrr)

<b>kod_u</b> – kod urządzenia, na którym była wykonana instalacja (liczba całkowita co
najwyżej 5-cyfrowa)

<b>kod_k</b> – kod kraju, w którym znajdowało się to urządzenie (napis dwuznakowy).

Uwaga: kod_u nie oznacza pojedynczego egzemplarza urządzenia, a tylko jego rodzaj

Przykład:
| data_i | kod_k | kod_u |
|------|-------|------|
| 01.03.2019 | AM | 145 |
| 01.03.2019 | AR | 804 |
| 01.03.2019 | AT | 12632 |


Z wykorzystaniem danych zawartych w podanych plikach oraz dostępnych narzędzi
informatycznych, podaj odpowiedzi do zadań 7.1.–7.4. Odpowiedzi zapisz w pliku
<i>wyniki7.txt</i>, a każdą z nich poprzedź numerem odpowiedniego zadania.

Zadanie 7.1. (0–2)
Dla każdego typu urządzenia podaj liczbę instalacji aplikacji na tym typie urządzenia.

Zadanie 7.2. (0–2)
Podaj nazwę producenta urządzeń, dla którego w lutym 2019 wykonano najwięcej instalacji.
Podaj liczbę tych instalacji.

Zadanie 7.3. (0–3)
Podaj nazwy pięciu krajów, w których przeprowadzono najwięcej instalacji w przeliczeniu na
1 000 000 mieszkańców, oraz podaj liczby tych instalacji.
Dla każdego z tych pięciu krajów podaj liczbę instalacji na 1 000 000 mieszkańców
z dokładnością do dwóch miejsc po przecinku.
Uwaga: pomiń kraje, w których jest mniej niż milion mieszkańców.

Zadanie 7.4. (0–2)
Podaj kod oraz nazwę urządzenia typu tablet („Tablet”), na którym zainstalowano aplikację
w największej liczbie krajów. Podaj także liczbę krajów, w których instalowano aplikację na
tym urządzeniu.








<h1>Zadanie 1</h1>
W pewnej lidze siatkówki w sezonie 2019/2020 rozgrywki rozpoczęły się w październiku
2019 roku i zakończyły się pod koniec maja 2020 roku. Rozegrano ponad 300 spotkań.
Mecze rozgrywano w różne dni tygodnia. Liczby meczów rozgrywanych w rożne dni mogą
być różne. Liczby meczów rozegranych przez poszczególne drużyny mogą być także różne.
Dane o wynikach drużyn zostały zgromadzone w plikach: <i>kluby.txt</i>, <i>sedziowie.txt</i>
i <i>mecze.txt</i>. Pierwszy wiersz każdego z plików jest wierszem nagłówkowym, a dane
w wierszach rozdzielono średnikami.<br><br>
Plik o nazwie <i>kluby.txt</i> zawiera informacje o klubach, które uczestniczyły
w rozgrywkach. W każdym wierszu pliku znajdują się następujące dane: identyfikator klubu,
nazwa klubu oraz miasto, w którym klub się znajduje i rozgrywa mecze. <br> <b>Przykład:</b> <br><br>


| Id_klubu | Nazwa | Miasto |
|--------|------|-------|
| 101 | Sfinks | Szymbark |
| 102 | Zenit | Licowo |
| 103 | Victoria | Radelko |

Plik o nazwie <i>sedziowie.txt</i> zawiera informacje o sędziach, którzy prowadzili spotkania.
W każdym wierszu pliku znajdują się następujące dane: identyfikator, imię i nazwisko
sędziego.<br>
<b>Przykład:</b>

| Id_sedziego | Imie | Nazwisko |
|--------|------|-------|
| 301 | Jan | Malinowski |
| 302 |Szymon |Rutkowski |
| 303 | Anna | Nowak |

Plik o nazwie <i>mecze.txt</i> zawiera informacje o rozegranych spotkaniach (meczach) przez
poszczególne drużyny – gospodarzy spotkań. W każdym wierszu pliku znajdują się
następujące dane: identyfikator meczu, data rozegrania meczu, identyfikator klubu (drużyny)
gospodarza, liczba wygranych setów, liczba przegranych setów, identyfikator sędziego, który
prowadził mecz.
Uwaga: w pliku <i>mecze.txt</i> nie zapisano informacji o drużynach gości.

<h2>Zadanie 1.1. (0–1)</h2>
Ile meczów zakończyło się tzw. tie-breakiem, czyli rozegrano w nich dokładnie pięć setów?
<h2>Zadanie 1.2. (0–2)</h2>
Utwórz zestawienie miast z liczbą rozegranych w nich meczów. Wyniki posortuj
od największej liczby meczów do najmniejszej.
<h2>Zadanie 1.3. (0–3)</h2>
Podaj imiona i nazwiska sędziów, którzy poprowadzili więcej spotkań (meczów) niż średnia
liczba spotkań przeprowadzonych przez jednego sędziego.
<h2>Zadanie 1.4. (0–3)</h2>
Podaj imiona i nazwiska sędziów, którzy nie prowadzili żadnego spotkania (meczu) ani
w Licowie („Licowo”), ani w Szymbarku (”Szymbark”) w okresie od 15 października 2019 roku
do 15 grudnia 2019 roku.
<h2>Zadanie 1.5. (0–3)</h2>
Spotkanie (mecz) jest wygrane, jeśli liczba wygranych setów w tym spotkaniu jest większa
niż liczba setów przegranych. Utwórz zestawienie klubów, w przypadku których liczba
wygranych spotkań jest <b>większa lub równa</b> liczbie spotkań przegranych. Dla każdego takiego
klubu podaj jego nazwę, miasto oraz liczby spotkań wygranych i przegranych.
















<br><br><br>
<h1>Zadanie 2</h1>

<p>W bazie danych firmy X zawarte są informacje o instalacjach pewnej aplikacji,
o urządzeniach, na których ta aplikacja została zainstalowana, oraz o krajach, w których
przeprowadzono instalację.
Dane zgromadzono w plikach tekstowych: <i>kraje.txt</i>, <i>instalacje.txt</i> oraz
<i>urzadzenia.txt</i>. Pierwszy wiersz każdego z plików jest wierszem nagłówkowym,
a dane w wierszach rozdzielone są znakami tabulacji. 
Plik o nazwie <i>kraje.txt</i> zawiera informacje o krajach, w których instalowano aplikację.
W każdym wierszu pliku znajdują się następujące dane:</p>

<b>kod_k</b> – kod kraju (napis dwuznakowy)<br>
<b>nazwa_k</b> – nazwa kraju (napis do 50 znaków)<br>
<b>ludnosc_k</b> – ludność kraju (liczba całkowita do 10 cyfr określająca liczbę ludności).


Przykład:
| kod_k | nazwa_k | ludnosc_k |
|-------|---------|-----------|
| AN    | NETHERLANDS ANTILES | 227049 |
| CR | COSTA RICA | 5003393 |
| DZ | ALGERIA | 42545964 |


Plik o nazwie <i>urzadzenia.txt</i> zawiera informacje o urządzeniach, na których może być
instalowana aplikacja. W każdym wierszu pliku znajdują się następujące informacje:

<b>kod_u</b> – unikatowy kod (liczba całkowita co najwyżej 5-cyfrowa)<br>
<b>nazwa_u</b> – nazwa urządzenia (napis do 80 znaków)<br>
<b>producent_u</b> – producent urządzenia (napis do 35 znaków)<br>
<b>typ_u</b> – typ urządzenia (napis: Tablet, Phone lub PC).<br>
Uwaga: nazwa urządzenia nie jest unikatowa – w tabeli mogą występować dwa lub więcej
urządzenia o tej samej nazwie.

Przykład:
| kod_u | nazwa_u     | producent_u | typ_u |
|-------|-------------|-------------|-------|
| 12410 | PLATINUM_E5 | Sky devices | Phone |
| 6549  | Ilium L1120 | Lanix       | Phone |

Plik o nazwie <i>instalacje.txt</i> zawiera informacje o instalacjach aplikacji. W każdym
wierszu pliku znajdują się następujące informacje:

<b>data_i</b> – data instalacji (w formacie dd.mm.rrrrr)<br>
<b>kod_u</b> – kod urządzenia, na którym była wykonana instalacja (liczba całkowita co
najwyżej 5-cyfrowa)<br>
<b>kod_k</b> – kod kraju, w którym znajdowało się to urządzenie (napis dwuznakowy).<br>
Uwaga: kod_u nie oznacza pojedynczego egzemplarza urządzenia, a tylko jego rodzaj

Przykład:
| data_i | kod_k | kod_u |
|------|-------|------|
| 01.03.2019 | AM | 145 |
| 01.03.2019 | AR | 804 |
| 01.03.2019 | AT | 12632 |



<h2>Zadanie 2.1. (0–2)</h2>
Dla każdego typu urządzenia podaj liczbę instalacji aplikacji na tym typie urządzenia.

<h2>Zadanie 2.2. (0–2)</h2>
Podaj nazwę producenta urządzeń, dla którego w lutym 2019 wykonano najwięcej instalacji.
Podaj liczbę tych instalacji.

<h2>Zadanie 2.3. (0–3)</h2>
Podaj nazwy pięciu krajów, w których przeprowadzono najwięcej instalacji w przeliczeniu na
1 000 000 mieszkańców, oraz podaj liczby tych instalacji.
Dla każdego z tych pięciu krajów podaj liczbę instalacji na 1 000 000 mieszkańców
z dokładnością do dwóch miejsc po przecinku.
Uwaga: pomiń kraje, w których jest mniej niż milion mieszkańców.

<h2>Zadanie 2.4. (0–2)</h2>
Podaj kod oraz nazwę urządzenia typu tablet („Tablet”), na którym zainstalowano aplikację
w największej liczbie krajów. Podaj także liczbę krajów, w których instalowano aplikację na
tym urządzeniu.








W pewnej lidze siatkówki w sezonie 2019/2020 rozgrywki rozpoczęły się w październiku
2019 roku i zakończyły się pod koniec maja 2020 roku. Rozegrano ponad 300 spotkań.
Mecze rozgrywano w różne dni tygodnia. Liczby meczów rozgrywanych w rożne dni mogą
być różne. Liczby meczów rozegranych przez poszczególne drużyny mogą być także różne.
Dane o wynikach drużyn zostały zgromadzone w plikach: kluby.txt, sedziowie.txt
i mecze.txt. Pierwszy wiersz każdego z plików jest wierszem nagłówkowym, a dane
w wierszach rozdzielono średnikami.
Plik o nazwie kluby.txt zawiera informacje o klubach, które uczestniczyły
w rozgrywkach. W każdym wierszu pliku znajdują się następujące dane: identyfikator klubu,
nazwa klubu oraz miasto, w którym klub się znajduje i rozgrywa mecze.
Przykład:
Id_klubu;Nazwa;Miasto
101;Sfinks;Szymbark
102;Zenit;Licowo
103;Victoria;Radelko
Plik o nazwie sedziowie.txt zawiera informacje o sędziach, którzy prowadzili spotkania.
W każdym wierszu pliku znajdują się następujące dane: identyfikator, imię i nazwisko
sędziego.
Przykład:
Id_sedziego;Imie;Nazwisko
301;Jan;Malinowski
302;Szymon;Rutkowski
303;Anna;Nowak
Plik o nazwie mecze.txt zawiera informacje o rozegranych spotkaniach (meczach) przez
poszczególne drużyny – gospodarzy spotkań. W każdym wierszu pliku znajdują się
następujące dane: identyfikator meczu, data rozegrania meczu, identyfikator klubu (drużyny)
gospodarza, liczba wygranych setów, liczba przegranych setów, identyfikator sędziego, który
prowadził mecz.
Uwaga: w pliku mecze.txt nie zapisano informacji o drużynach gości.
Przykład:
Id_meczu;Data;Id_klubu;Sety_wygrane;Sety_przegrane;Id_sedziego
1;2019-10-16;102;1;3;319
2;2019-10-19;106;3;2;306
3;2019-10-19;109;0;3;317
Wykorzystaj dostępne narzędzia informatyczne i podaj odpowiedzi do zadań 6.1.–6.5.
Odpowiedzi zapisz w pliku wyniki6.txt. Każdą odpowiedź poprzedź numerem
oznaczającym zadanie.
Więcej arkuszy znajdziesz na stronie: arkusze.pl
Strona 7 z 8
EINP-R2_100
Zadanie 6.1. (0–1)
Ile meczów zakończyło się tzw. tie-breakiem, czyli rozegrano w nich dokładnie pięć setów?
Zadanie 6.2. (0–2)
Utwórz zestawienie miast z liczbą rozegranych w nich meczów. Wyniki posortuj
od największej liczby meczów do najmniejszej.
Zadanie 6.3. (0–3)
Podaj imiona i nazwiska sędziów, którzy poprowadzili więcej spotkań (meczów) niż średnia
liczba spotkań przeprowadzonych przez jednego sędziego.
Zadanie 6.4. (0–3)
Podaj imiona i nazwiska sędziów, którzy nie prowadzili żadnego spotkania (meczu) ani
w Licowie („Licowo”), ani w Szymbarku (”Szymbark”) w okresie od 15 października 2019 roku
do 15 grudnia 2019 roku.
Zadanie 6.5. (0–3)
Spotkanie (mecz) jest wygrane, jeśli liczba wygranych setów w tym spotkaniu jest większa
niż liczba setów przegranych. Utwórz zestawienie klubów, w przypadku których liczba
wygranych spotkań jest większa lub równa liczbie spotkań przegranych. Dla każdego takiego
klubu podaj jego nazwę, miasto oraz liczby spotkań wygranych i przegranych.

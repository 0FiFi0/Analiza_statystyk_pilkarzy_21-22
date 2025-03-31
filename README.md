# Analiza_statystyk_pilkarzy_21-22
Projekt z czerwca 2024
**Dokumentacja projektu**

**Cele projektu**

- Analiza statystyk piłkarzy z sezonu 2021-2022.

- Wyodrębnienie kluczowych statystyk i ich prezentacja

- Porównanie graczy na podstawie najważniejszych statystyk

- Porównanie statystyk zespołów do innych drużyn z różnych lig

**Opis bazy**

- Dane piłkarskie dotyczące zawodników z 5 najlepszych lig z sezonu 2021-2022.

- Kolumny zawierają informacje takie jak narodowość, wiek, liczba rozegranych meczów, minuty na boisku, gole, asysty, strzały, celność podań, driblingi, kartki oraz faule.

**Użyte rozwiązania**

1. **Wczytanie i przygotowanie danych**:

   - Wczytanie danych z pliku CSV.

   - Uzupełnienie brakujących wartości.

   - Poprawienie błędnych wartości

2. **Filtracja najważniejszych danych**:

   - Wyodrębnienie kluczowych kolumn.

   - Przeliczenie statystyk na 90 minut gry.

3. **Analiza danych**:

   - Obliczenia średnich wartości kluczowych statystyk

   - Graficzna prezentacja wyników na wykresach (Za pomocą biblioteki Plotly).

**Wyniki**

- Stworzono bazę danych zawierającą tylko kluczowe statystyki piłkarzy

- Stworzono wykresy i tabele prezentujące porównania graczy pod kątem danych statystyk gry.

- Stworzono wykresy prezentujące dane o zespołach na podstawie średnich ligowych.

- Analiza zawodników pod kątem wieku oraz porównanie ich na tle zespołu oraz danej ligi

**Wnioski**

- Najlepsi zawodnicy nie wyróżniają się jedynie pod kątem najwyższych bramek zdobytych ale również są ważne inne aspekty gry.

- W kluczowych ligach nie liczy się tylko wiek zawodnika ale głównie jego umiejętności.

- Kartki nie są w 100% zależne tylko od liczby fauli ale od rodzaju faulu, agresji na boisku oraz stosowanego języka.

- Duża zależność występuje w strzałach do zdobytych bramek. Można zaobserwować że czym więcej dany zawodnik oddaje strzałów tym więcej ma bramek.

- Najlepszy strzelec niekoniecznie musi być w drużynie która zdobyła najwięcej bramek w lidze.

- Istnieje prawie zerowa zależność miedzy podaniami a zdobytymi asystami.

- W danych ligach przeważają narodowości zawodników z krajów z których wywodzi się dana liga.

- Najwięcej zawodników z polski gra w Serie A ,a żaden nie gra w La liga

**Pomysły na rozwinięcie**

- Dodanie większej ilości lig.

- Dodanie danych z innych sezonów oraz uwzględnienie dodatkowych zmiennych, takich jak warunki pogodowe, rodzaj boiska itp.

- Przewidywanie formy danych zawodników na przyszłe sezony uwzględniając poprzednie lata

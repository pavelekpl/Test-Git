# JavaScript Algorytmy i Stgruktury Danych

[![Build Status](https://travis-ci.org/trekhleb/javascript-algorithms.svg?branch=master)](https://travis-ci.org/trekhleb/javascript-algorithms)
[![codecov](https://codecov.io/gh/trekhleb/javascript-algorithms/branch/master/graph/badge.svg)](https://codecov.io/gh/trekhleb/javascript-algorithms)

To repozytorium zawiera wiele przyk?adów JavaScript opartych na 
znanych algorytmach i strukturach danych.

Ka?dy algorytm i struktura danych zawiera osobny plik README
wraz z powi?zanymi wyja?nieniami i odno?nikami do dalszego czytania (w??cznie z tymi do YouTube videos).

_Read this in other languages:_
[_English_](https://github.com/trekhleb/javascript-algorithms/)
[ç®€ä½“ä¸­æ–‡](README.zh-CN.md),
[ç¹é«”ä¸­æ–‡](README.zh-TW.md),
[í•œêµ­ì–´](README.ko-KR.md)

> Jeste?my w trakcie pisania ksi??ki, która w jasny i specyficzny sposób, wyja?ni g?ówne algorytmy. Je?eli chcesz dosta? powiadomienie o tym kiedy ksi??ka â€œJavaScript Algorithmsâ€ zostanie wydana,[kliknij tutaj](https://upscri.be/402324/).


## Struktury Danych

Struktura danych to sposób uporz?dkowania i przechowywania informacji w komputerze ?eby mog?aby by? sprawnie dost?pna i efektywnie zmodyfikowana. Dok?adniej, struktura danych jest zbiorem warto?ci danych, relacjami pomi?dzy nimi, zadaniami lub dzia?aniami, które mog? dotyczy? danych. 

`B` - Pocz?tkuj?cy, `A` - Zaawansowany

* `B` [Lista](src/data-structures/linked-list)
* `B` [Lista Dwukierunkowa](src/data-structures/doubly-linked-list)
* `B` [Kolejka](src/data-structures/queue)
* `B` [Stos](src/data-structures/stack)
* `B` [Tabela Skrótu](src/data-structures/hash-table)
* `B` [Sterta](src/data-structures/heap)
* `B` [Kolejka Priorytetowa](src/data-structures/priority-queue)
* `A` [Trie](src/data-structures/trie)
* `A` [Drzewo](src/data-structures/tree)
    * `A` [Wyszukiwanie Binarne](src/data-structures/tree/binary-search-tree)
    * `A` [AVL Drzewo](src/data-structures/tree/avl-tree)
    * `A` [Drzewa czerwono-czarne](src/data-structures/tree/red-black-tree)
    * `A` [Drzewo Segmentu](src/data-structures/tree/segment-tree) - z przyk?adami zapyta? o min / max / sumie sum
    * `A` [Drzewo Fenwicka](src/data-structures/tree/fenwick-tree) (Drzewo Indeksowane Binarnie)
* `A` [Graf](src/data-structures/graph) (zarówno skierowane i nieukierunkowane)
* `A` [Roz??czny Zestaw](src/data-structures/disjoint-set)
* `A` [Filtr Blooma](src/data-structures/bloom-filter)

## Algorytmy

Algorytm jest to sko?czony ci?g jasno zdefiniowanych czynno?ci, koniecznych do wykonania pewnego rodzaju zada?. Sposób post?powania prowadz?cy do rozwi?zania problemu.

`B` - Pocz?tkuj?cy, `A` - Zaawansowany

### Algorytmy wed?ug tematu

* **Matematyka**
  * `B` [Manipulacja Bitami](src/algorithms/math/bits) - ustaw / uzyskaj / aktualizuj / usuwaj bity, mno?enie / dzielenie przez dwa, tworzenie negatywów itp.
  * `B` [Silna](src/algorithms/math/factorial) 
  * `B` [Ci?g Fibonacciego](src/algorithms/math/fibonacci)
  * `B` [Test Pierwszorz?dno?ci]
(src/algorithms/math/primality-test) (trial division method)
  * `B` [Algorytm Euclideana](src/algorithms/math/euclidean-algorithm) - calculate the Greatest Common Divisor (GCD)
  * `B` [Najmniejsza Wspólna Wielokrotno??](src/algorithms/math/least-common-multiple) (LCM)
  * `B` [Sito Eratosthenes-a](src/algorithms/math/sieve-of-eratosthenes) - znajdowanie wszystkich liczb pierwszych do okre?lonego limitu
  * `B` [Jest Pot?g? Dwójki](src/algorithms/math/is-power-of-two) - sprawd?, czy liczba jest pot?g? dwóch (algorytmy naiwne i bitowe)
  * `B` [Trójk?t Pascala](src/algorithms/math/pascal-triangle)
  * `A` [Partycja Ca?kowita](src/algorithms/math/integer-partition)
  * `A` [Algorytm Liu Huia](src/algorithms/math/liu-hui) - przybli?one obliczenia na podstawie N-gonów
* **Zestawy**
  * `B` [Produkt Kartezyjny](src/algorithms/sets/cartesian-product) - wynik wielu zestawów
  * `B` [Przetasowanie Fisher Yates-a](src/algorithms/sets/fisher-yates) - losowa permutacja ko?cz?cej si? serii
  * `A` [Zestaw Zasilaj?cy](src/algorithms/sets/power-set) - podzbiór wszystkich serii
  * `A` [Permutacje](src/algorithms/sets/permutations) (z albo bez powtórze?)
  * `A` [Kombinacje](src/algorithms/sets/combinations) (z albo bez powtórze?)
  * `A` [Najd?u?sza Wspólna Podsekwencja](src/algorithms/sets/longest-common-subsequence) (LCS)
  * `A` [Najd?u?sza Wzrostaj?ca Podsekwencja](src/algorithms/sets/longest-increasing-subsequence)
  * `A` [Najkrótsza Wspólna Supersekwencja](src/algorithms/sets/shortest-common-supersequence) (SCS)
  * `A` [Problem Knapsacka](src/algorithms/sets/knapsack-problem) - "0/1" i "Rozwi?zany" 
  * `A` [Maksymalna Podtablica](src/algorithms/sets/maximum-subarray) - "Metoda Si?owa" i "Dynamiczne Programowanie" (Kadane-a) wersje
  * `A` [Suma Kombinacji](src/algorithms/sets/combination-sum) - 
znajd? wszystkie kombinacje, które tworz? okre?lon? sum?
* **?a?cuchy**
  * `B` [Odleg?o?? Hamminga](src/algorithms/string/hamming-distance) - liczba pozycji, w których symbole s? ró?ne
  * `A` [Odleg?o?? Levenshteina](src/algorithms/string/levenshtein-distance) - minimalna odleg?o?? edycji mi?dzy dwiema sekwencjami
  * `A` [Algorytm Knuth–Morris–Pratta](src/algorithms/string/knuth-morris-pratt) (Algorytm KMP) - dopasowywanie wzorców (dopasowywanie wzorców)
  * `A` [Algorytm Z](src/algorithms/string/z-algorithm) - szukanie pod?a?cucha(dopasowywanie wzorców)
  * `A` [Algorytm Rabin Karpa](src/algorithms/string/rabin-karp) - szukanie pod?a?cucha
  * `A` [Najd?u?sza Wspólna Pod?a?cucha](src/algorithms/string/longest-common-substring)
  * `A` [Dopasowanie Wyra?e? Regularnych](src/algorithms/string/regular-expression-matching)
* **Szukanie**
  * `B` [Wyszukiwanie Liniowe](src/algorithms/search/linear-search)
  * `B` [Jump Search](src/algorithms/search/jump-search) (lub Przeszukiwanie Bloku) - szukaj w posortowanej tablicy
  * `B` [Wyszukiwanie Binarne](src/algorithms/search/binary-search) - szukaj w posortowanej tablicy
  * `B` [Wyszukiwanie Interpolacyjne](src/algorithms/search/interpolation-search) - szukaj w równomiernie roz?o?onej, posortowanej tablicy
* **Sortowanie**
  * `B` [Sortowanie b?belkowe](src/algorithms/sorting/bubble-sort)
  * `B` [Sortowanie przez wymiane](src/algorithms/sorting/selection-sort)
  * `B` [Sortowanie przez wstawianie](src/algorithms/sorting/insertion-sort)
  * `B` [Sortowanie stogowe](src/algorithms/sorting/heap-sort)
  * `B` [Sortowanie przez scalanie](src/algorithms/sorting/merge-sort)
  * `B` [Sortowanie szybkie](src/algorithms/sorting/quick-sort) - wdro?enia w miejscu i nie na miejscu
  * `B` [Sortowanie Shella](src/algorithms/sorting/shell-sort)
  * `B` [Sortowanie przez zliczanie](src/algorithms/sorting/counting-sort)
  * `B` [Sortowanie pozycyjne](src/algorithms/sorting/radix-sort)
* **Drzewa**
  * `B` [Przeszukiwanie w g??b](src/algorithms/tree/depth-first-search) (DFS)
  * `B` [Przeszukiwanie wszerz](src/algorithms/tree/breadth-first-search) (BFS)
* **Grafy**
  * `B` [Przeszukiwanie w g??b](src/algorithms/graph/depth-first-search) (DFS)
  * `B` [Przeszukiwanie wszerz](src/algorithms/graph/breadth-first-search) (BFS)
  * `B` [Algorytm Kruskala](src/algorithms/graph/kruskal) - znalezienie Minimalnego Drzewa Opinaj?cego (MST) dla wa?onego nieukierunkowanego wykresu
  * `A` [Algorytm Dijkstry](src/algorithms/graph/dijkstra) - znajdowanie  najkrótszej ?cie?ki z pojedynczego ?ród?a w grafie
  * `A` [Algorytm Bellmana-Forda](src/algorithms/graph/bellman-ford) - znajdowanie najkrótszych ?cie?ek do wszystkich wierzcho?ków wykresu z jednego wierzcho?ka
  * `A` [Algorytm Floyd-Warshalla](src/algorithms/graph/floyd-warshall) - znajd? najkrótsze ?cie?ki mi?dzy wszystkimi parami wierzcho?ków
  * `A` [Detect Cycle](src/algorithms/graph/detect-cycle) - zarówno dla wykresów skierowanych, jak i nieukierunkowanych(wersje oparte na DFS i Roz??czny Zestaw)
  * `A` [Algorytm Prima](src/algorithms/graph/prim) - znalezienie Minimalnego Drzewa Opinaj?cego (MST) dla wa?onego nieukierunkowanego wykresu
  * `A` [Sortowanie Topologiczne](src/algorithms/graph/topological-sorting) - metoda DFS 
  * `A` [Punkty Artykulacji](src/algorithms/graph/articulation-points) - Algorytm Tarjana (oparty o DFS)
  * `A` [Mosty](src/algorithms/graph/bridges) - Oparty na algorytmie DFS 
  * `A` [?cie?ka Euleriana i Obwód Euleriana](src/algorithms/graph/eulerian-path) - Algorytm Fleurya - Odwied? ka?d? kraw?d? dok?adnie raz
  * `A` [Cykl Hamiltoniana](src/algorithms/graph/hamiltonian-cycle) - Odwied? ka?dy wierzcho?ek dok?adnie raz
  * `A` [Silnie Po??czone Komponenty](src/algorithms/graph/strongly-connected-components) - Algorytm Kosaraja 
  * `A` [Travelling Salesman Problem](src/algorithms/graph/travelling-salesman) - najkrótsza ?cie?ka która odwiedza ka?de miasto i wraca miasta pocz?tkuj?cego
* **Niezkategorizowane**
  * `B` [Wie?a Hanoi](src/algorithms/uncategorized/hanoi-tower)
  * `B` [Kwadratowa Matryca Obrotu](src/algorithms/uncategorized/square-matrix-rotation) - in-place algorithm
  * `B` [Jump Game](src/algorithms/uncategorized/jump-game) - cofanie, dynamiczne programowanie (od góry do do?u + od do?u do góry) i przyk?ady chciwego  
  * `B` [Unikatowe ?cie?ki](src/algorithms/uncategorized/unique-paths) - cofanie, dynamiczne programowanie i przyk?ady oparte na Trójk?cie Pascala
  * `A` [Problem N-Queens](src/algorithms/uncategorized/n-queens)
  * `A` [Knight's Tour](src/algorithms/uncategorized/knight-tour)

### Algorytmy wed?ug paradygmatu

Paradygmat algorytmiczny jest ogóln? metod? lub podej?ciem, które jest podstaw? projektowania klasy algorytmów. Jest abstrakcj? wy?sz? ni? poj?cie algorytmu, podobnie jak algorytm jest abstrakcj? wy?sz? ni? program komputerowy.

* **Metoda Si?owa** - Sprawdza wszystkie mo?liwosci i wybiera  najlepsze rozwi?zanie.
  * `B` [Wyszukiwanie Liniowe](src/algorithms/search/linear-search)
  * `A` [Maksymalna Podtablica](src/algorithms/sets/maximum-subarray)
  * `A` [Problem z Podró?uj?cym Sprzedawc?](src/algorithms/graph/travelling-salesman) - najkrótsza mo?liwa trasa, która odwiedza ka?de miasto i wraca do miasta pocz?tkowego
* **Chciwy** - wybierz najlepsz? opcj? w obecnym czasie, bez wzgl?du na przysz?o??
  * `B` [Jump Game](src/algorithms/uncategorized/jump-game)
  * `A` [Niezwi?zany Problem Knapsacka ](src/algorithms/sets/knapsack-problem)
  * `A` [Algorytm Dijkstry](src/algorithms/graph/dijkstra) - 
znalezienie najkrótszej ?cie?ki do wszystkich wierzcho?ków grafu
  * `A` [Algorytm Prima](src/algorithms/graph/prim) - znalezienie Minimalnego Drzewa Opinaj?cego (MST) dla wa?onego nieukierunkowanego wykresu
  * `A` [Algorytm Kruskala](src/algorithms/graph/kruskal) - znalezienie Minimalnego Drzewa Opinaj?cego (MST) dla wa?onego nieukierunkowanego wykresu
* **Dziel i Zwyci??aj** - podziel problem na mniejsze cz??ci, a nast?pnie rozwi?? te cz??ci
  * `B` [Wyszukiwanie Binarne](src/algorithms/search/binary-search)
  * `B` [Wie?a Hanoi](src/algorithms/uncategorized/hanoi-tower)
  * `B` [Trójk?t Pascala](src/algorithms/math/pascal-triangle)
  * `B` [Algorytm Euclideana](src/algorithms/math/euclidean-algorithm) - obliczy? Najwi?kszy Wspólny Dzielnik(GCD)
  * `B` [Sortowanie przez scalanie](src/algorithms/sorting/merge-sort)
  * `B` [Szybkie Sortowanie](src/algorithms/sorting/quick-sort)
  * `B` [Drzewo Przeszukiwania W G??b](src/algorithms/tree/depth-first-search) (DFS)
  * `B` [Graf Przeszukiwania W G??b](src/algorithms/graph/depth-first-search) (DFS)
  * `B` [Jump Game](src/algorithms/uncategorized/jump-game)
  * `A` [Permutacje](src/algorithms/sets/permutations) (z albo bez powtórze?)
  * `A` [Kombinacje](src/algorithms/sets/combinations) (z albo bez powtórze?)
* **Programowanie Dynamiczne** - zbuduj rozwi?zanie, korzystaj?c z wcze?niej znalezionych podrz?dnych rozwi?za?
  * `B` [Ci?g Fibonacciego](src/algorithms/math/fibonacci)
  * `B` [Jump Game](src/algorithms/uncategorized/jump-game)
  * `B` [Unikatowe Scie?ki](src/algorithms/uncategorized/unique-paths)
  * `A` [Dystans Levenshteina](src/algorithms/string/levenshtein-distance) - minimalna odleg?o?? edycji mi?dzy dwiema sekwencjami
  * `A` [Najd?u?sza Wspólna Podsekwencja](src/algorithms/sets/longest-common-subsequence) (LCS)
  * `A` [Najd?u?sza Wspólna Pod?a?cucha](src/algorithms/string/longest-common-substring)
  * `A` [Najd?u?sza Wzrostaj?ca Podsekwencja](src/algorithms/sets/longest-increasing-subsequence)
  * `A` [Najkrótsza Wspólna Supersekwencja](src/algorithms/sets/shortest-common-supersequence)
  * `A` [0/1 Problem Knapsacka](src/algorithms/sets/knapsack-problem)
  * `A` [Partycja Ca?kowita](src/algorithms/math/integer-partition)
  * `A` [Maksymalne Podtablice](src/algorithms/sets/maximum-subarray)
  * `A` [Algorytm Bellman-Forda](src/algorithms/graph/bellman-ford) - znalezienie najkrótszej ?cie?ki wszystkich wierzcho?ków wykresu
  * `A` [Algorytm Floyd-Warshalla](src/algorithms/graph/floyd-warshall) - 
znajd? najkrótsze ?cie?ki mi?dzy wszystkimi parami wierzcho?ków
  * `A` [Dopasowanie Wyra?e? Regularnych](src/algorithms/string/regular-expression-matching)
* **Algorytm z nawrotami** - podobny do metody si?owej, próbuje wygenerowa? wszystkie mo?liwe rozwi?zania, jednak za ka?dym razem generujesz nast?pne rozwi?zanie które testujesz
je?eli zaspokaja wszystkie warunki, tylko wtedy generuje kolejne rozwi?zania. W innym wypadku, cofa sie, i pod??a inna ?cie?ka znale?enia rozwi?zania. Zazwyczaj, u?ywane jest przej?cie przez Przeszukiwania W G??b(DFS) przestrzeni stanów.
  * `B` [Jump Game](src/algorithms/uncategorized/jump-game)
  * `B` [Unikatowe Scie?ki](src/algorithms/uncategorized/unique-paths)
  * `A` [Cykl Hamiltoniana](src/algorithms/graph/hamiltonian-cycle) - Visit every vertex exactly once
  * `A` [Problem N-Queens](src/algorithms/uncategorized/n-queens)
  * `A` [Knight's Tour](src/algorithms/uncategorized/knight-tour)
  * `A` [Zestaw Sumy](src/algorithms/sets/combination-sum) - znajduje wszystkie zestawy które tworz? okre?lon? sum?
* **Metoda Podzia?u i Ogranicze?** - Pami?ta o niskonak?adowym rozwi?zaniu znalezionym na ka?dym etapie szukania nawrotu,
u?ywa kosztu niskonak?adowego kosztu, które dotychczas zosta?o znalezione jako niska granica najmniejszego kosztu
do rozwi?zanie problemu, aby odrzuci? cz?stkowe rozwi?zania o kosztach wi?kszych ni? niskonak?adowe
rozwi?zanie znalezione do tej pory. 
Zazwyczan trajektoria BFS, w po??czeniu z trajektori? Przeszukiwania W G??b (DFS) drzewa przestrzeni stanów jest u?yte.

## Jak u?ywa? repozytorium

**Zainstaluj wszystkie zale?nosci**
```
npm install
```

**Uruchom ESLint**

Mo?esz to uruchomi? aby sprawdzi? jako?? kodu.

```
npm run lint
```

**Uruchom wszystkie testy**
```
npm test
```

**Uruchom testy u?ywaj?c okre?lonej nazwy**
```
npm test -- 'LinkedList'
```

**Playground**

Mo?esz pociwiczy? ze struktur? danych i algorytmami w `./src/playground/playground.js` zakartotekuj i napisz
testy do tego w `./src/playground/__test__/playground.test.js`.

Nast?pnie uruchom nast?puj?c? komend? w celu przetestowania czy twoje kod dzia?a wed?ug oczekiwa?: 

```
npm test -- 'playground'
```

## Pomocne informacje

### ?ród?a

[â–¶ Struktury Danych i Algorytmy na YouTube](https://www.youtube.com/playlist?list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)

### Big O Notacja

Kolejno?? wzrastania algorytmów wed?ug Big O notacji. 

![Big O grafy](./assets/big-o-graph.png)

?ród?o: [Big O Cheat Sheet](http://bigocheatsheet.com/).

Poni?ej umieszczamy list? najbardziej u?ywanych Big O notacji i ich porównania wydajno?ci do róznych rozmiarów z wprowadzonych danych.

| Big O notacja | Obliczenia na 10 elementów | Obliczenia na 100 elementów | Obliczenia na 1000 elementów |
| -------------- | ---------------------------- | ----------------------------- | ------------------------------- |
| **O(1)**       | 1                            | 1                             | 1                               |
| **O(log N)**   | 3                            | 6                             | 9                               |
| **O(N)**       | 10                           | 100                           | 1000                            |
| **O(N log N)** | 30                           | 600                           | 9000                            |
| **O(N^2)**     | 100                          | 10000                         | 1000000                         |
| **O(2^N)**     | 1024                         | 1.26e+29                      | 1.07e+301                       |
| **O(N!)**      | 3628800                      | 9.3e+157                      | 4.02e+2567                      |

### Z?o?ono?? operacji struktury danych

| Struktura Danych         | Dost?p    | Szukaj    | Umieszczanie | Usuwanie  | Komentarze  |
| ----------------------- | :-------: | :-------: | :-------: | :-------: | :-------- |
| **Szereg**               | 1         | n         | n         | n         |           |
| **Sterta**               | n         | n         | 1         | 1         |           |
| **Kolejka**               | n         | n         | 1         | 1         |           |
| **Lista Powi?zana**         | n         | n         | 1         | 1         |           |
| **Tablica funkcji mieszanej**          | -         | n         | n         | n         | W wypadku idealnej funkcji skrótu koszt móg?by sie równa? O(1) |
| **Binarne Drzewo Poszukiwa?**  | n         | n         | n         | n         | In case of balanced tree costs would be O(log(n)) |
| **B-Drzewo**              | log(n)    | log(n)    | log(n)    | log(n)    |           |
| **Drzewa czerwono-czarne**      | log(n)    | log(n)    | log(n)    | log(n)    |           |
| **AVL Drzewo**            | log(n)    | log(n)    | log(n)    | log(n)    |           |
| **Filtr Blooma **        | -         | 1         | 1         | -         | Fa?szywe dotatnie s? mo?liwe podczas wyszukiwania |

### Sortowanie Tablic Z?o?ono?ci Algorytmów

| Nazwa                  | Najlepszy            | ?redni             | Najgorszy              | Pami??    | Stabilno??  | Komentarze  |
| --------------------- | :-------------: | :-----------------: | :-----------------: | :-------: | :-------: | :-------- |
| **Sortowanie b?belkowe**       | n               | n<sup>2</sup>       | n<sup>2</sup>       | 1         | Yes       |           |
| **Sortowanie przez wstawianie**    | n               | n<sup>2</sup>       | n<sup>2</sup>       | 1         | Yes       |           |
| **Sortowanie przez wybieranie**    | n<sup>2</sup>   | n<sup>2</sup>       | n<sup>2</sup>       | 1         | No        |           |
| **Sortowanie przez kopcowanie**         | n&nbsp;log(n)   | n&nbsp;log(n)       | n&nbsp;log(n)       | 1         | No        |           |
| **Sortowanie przez scalanie**        | n&nbsp;log(n)   | n&nbsp;log(n)       | n&nbsp;log(n)       | n         | Yes       |           |
| **Szybkie sortowanie**        | n&nbsp;log(n)   | n&nbsp;log(n)       | n<sup>2</sup>       | log(n)    | No        | Szybkie sortowanie jest zazwyczaj robione w miejsce O(log(n)) stosu przestrzeni |
| **Sortowanie Shella**        | n&nbsp;log(n)   | zale?y od luki w uk?adzie   | n&nbsp;(log(n))<sup>2</sup>  | 1         | No         |           |
| **Sortowanie przez zliczanie**     | n + r           | n + r               | n + r               | n + r     | Yes       | r - najwi?kszy numer w tablicy|
| **Sortowanie Radix**        | n * k           | n * k               | n * k               | n + k     | Yes       | k -d?ugo?? najd?u?szego klucza |

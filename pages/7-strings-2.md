---
layout: page
title: Distanțe de editare
permalink: /7-strings-2/
tags: [strings, data structures]
---

# Descriere

Distanța Levenshtein reprezintă numărul minim de operatii de editare (inserări, ștergeri, substituții) 
necesare pentru a transforma un string în alt string.

Cerința este să descoperiți, pentru un cuvânt A, toate cuvintele din dicționar aflate la o distanță Levenshtein mai
mică decât K.

# Precizări

- Pentru această problemă veți compara calcularea directă a distanței Levenshtein între două cuvinte folosind programare dinamică,
respectiv optimizarea posibilă folosind structura de date Trie.

- (Bonus) Soluția cu programare dinamică poate fi implementată atăt iterativ, cât și recursiv cu memoizare. Care sunt avantajele fiecărei implementări?
- (Bonus) Puteți aborda și alte metrici folosite pentru măsurarea distanței de editare (Damerau–Levenshtein, Hamming, Smith–Waterman, etc.).

# Structură teste

#### Format date intrare

- Pe prima linie se va afla numărul N, reprezentând numărul de cuvinte din dicționar, respectiv K.
- Pe a doua linie se va afla cuvântul A.
- Pe următoarele N linii se vor afla cuvintele ce compun dicționarul.

#### Format date ieșire

- Pe prima linie se va afla M, numărul de cuvinte din dicționar aflate la o distanta Levenshtein mai mică
decât K față de cuvântul A.
- Pe următoarele M linii se vor afla cuvintele care respectă condiția, ordonate în funcție de distantă, respectiv lexicografic.

#### Restricții

- $$1 \leq N \leq 10^5$$
- $$1 \leq |cuvânt|, K \leq 10^3$$ 

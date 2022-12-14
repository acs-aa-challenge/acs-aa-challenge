---
layout: page
title: Rezolvarea sistemelor de ecuații
permalink: /9-eq/
tags: [math]
---

# Descriere

Se cere să se rezolve un sistem de ecuații de tip $$Ax = B$$, unde $$A$$ și $$B$$ sunt matrice.

# Precizări

- Trebuie să comparați cel puțin **doi algoritmi** cunoscuți (e.g. Gauss, Householder) sau variante ale acestora.
- Pentru a evalua performanța algoritmilor trebuie să analizați cel puțin:
    - Dimensiunea matricilor și timpul de execuție
    - Analiza cazurilor în funcție de tipul de sistem: sistem supradimensionat, subdimensionat, compatibil, compatibil nedeterminat, incompatibil.

# Structură recomandată teste

#### Format date intrare

- Pe prima linie se citesc $$N$$ și $$M$$, numărul de linii și numarul de coloane ale sistemului.
- Pe următoarele $$N$$ linii se citesc valorile $$A[i][j]$$ ale sistemului.
- Pe ultima linie se vor citi cele $$N$$ valori pentru vectorul $$B$$.

#### Format date ieșire

- Se afișează pe o singura linie valorile pentru $$x[i]$$ sau, dacă nu se pot determina, se afișează mesajul "Sistem incompatibil", respectiv "Sistem compatibil nedeterminat".

#### Restricții

- $$1 \leq N, M \leq 100$$
    

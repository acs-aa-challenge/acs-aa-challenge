---
layout: page
title: Cel mai scurt drum (2)
permalink: /12-allsp/
tags: [graphs, all-to-all]
---

# Descriere

Fie un graf $$G$$ cu $$N$$ noduri și $$M$$ muchii. Calculați distanța minimă între oricare două noduri. 

# Precizări

- Comparați cel puțin trei algoritmi din lista de mai jos:
    - **Dijkstra** (aplicat între oricare două noduri)
      - Specificați complexitatea cu/fără heap-uri.
    - **Bellman-Ford** (aplicat între oricare două noduri)
      - Comparați varianta cu, respectiv fără coadă.
    - **Floyd-Warshall**
      - Analizați pe ce tipuri de grafuri este mai eficient decât algoritmii precedenți. 
    - **Johnson**
      - Explicați de ce poate fi folosit pe grafuri cu muchii de cost negativ.

- Particularitățile grafului schimbă rezolvarea (ex: acesta poate fi orientat/neorientat, cu costuri pozitive/negative pe
  muchii, aciclic, dens/rar, etc.).

# Structură teste

#### Format date intrare

- Pe prima linie se află două numere, $$N$$ și $$M$$, reprezentând numărul de noduri, respectiv de muchii, separate printr-un spațiu.
- Pe următoarele $$M$$ linii se află câte 3 numere naturale $$X$$, $$Y$$, $$C$$, cu semnificația că există o muchie între nodul $$X$$ și $$Y$$
  de lungime $$C$$.

#### Format date ieșire

- Afișați matricea de adicentă cu distanțele minime între noduri ($$A[i][j]$$ - distanța minimă de la nodul $$i$$ la nodul $$j$$).
- Dacă nu există drum între nodul $$i$$ și nodul $$j$$ veți afișa "NaN" (not a number).

#### Restricții

- $$ 1 \leq N \leq 10^4$$
- $$ 1 \leq M \leq min(N^2, 10^6)$$
- $$ 0 \leq X, Y < N$$
- $$ -10^6 \leq C \leq 10^6$$
- Nodurile sunt numerotate de la 0 la $$N-1$$.

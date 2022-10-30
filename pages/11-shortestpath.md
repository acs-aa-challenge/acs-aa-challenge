---
layout: page
title: Shortest Path (1)
permalink: /11-sp/
tags: [graphs]
---

# Descriere

Fie un graf $$G$$ cu $$N$$ noduri și $$M$$ muchii. Calculați distanța minimă de la un nod S și toate celelalte
noduri din graf.

# Precizări

- Comparați cel puțin trei algoritmi din lista de mai jos:
  - **Dijkstra** 
    - Specificați complexitatea cu/fără heap-uri
  - **Bellman-Ford**
    - Comparați varianta cu, respectiv fără coadă.
  - **Dijkstra - adaptat pentru costuri foarte mici ale muchiilor**
  - O soluție cu complexitate liniară pentru grafuri orientate aciclice
    - Explicați de ce nu poate fi aplicată soluția pentru grafuri care nu sunt ciclice.

- Particularitățile grafului schimbă rezolvarea (ex: acesta poate fi orientat/neorientat, cu costuri pozitive/negative pe
muchii, aciclic, dens/rar, etc.).

# Structură teste

#### Format date intrare

- Pe prima linie se află două numere, $$N$$ și $$M$$, reprezentând numărul de noduri, respectiv de muchii, separate printr-un spațiu.
- Pe a doua linie se află nodul sursă $$S$$.
- Pe următoarele $$M$$ linii se află câte 3 numere naturale $$X$$, $$Y$$, $$C$$, cu semnificația că există o muchie între nodul $$X$$ și $$Y$$
  de lungime $$C$$.

#### Format date ieșire

- Pe prima linie se vor afla $$N$$ valori reprezentând distanța de la nodul sursă $$S$$ la fiecare nod din graf.
- Dacă nu există drum între $$S$$ și nodul $$i$$ veți afișa "NaN" (not a number).

#### Restricții

- $$ 1 \leq N \leq 10^5$$
- $$ 1 \leq M \leq 5 * 10^5$$
- $$ 1 \leq X, Y \leq N$$
- $$ -10^6 \leq C \leq 10^6$$
- Nodurile sunt numerotate de la 0 la $$N-1$$.

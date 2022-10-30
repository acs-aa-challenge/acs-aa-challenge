---
layout: page
title: Cozi de prioritate
permalink: /5-pq/
---

# Descriere

Pentru acest subiect veți compara structuri de date care pot fi folosite pentru a reprezenta API-ul
specific unei cozi de prioritate:

- Adâugarea unui element.
- Ștergerea elementului minim (/maxim).
- Afișarea elementului minim (/maxim).

# Precizări

# Structură teste
- **Format date intrare**
    - Pe prima linie se află numărul $$N$$ de query-uri
    - Pe următoarele $$N$$ linii se află câte un query de forma:
        - 0 a - Se adaugă elementul 'a' în coada de priorități.
        - 1 - Se elimină elementul minim din coada de priorități.
        - 2 - Se afișează elementul minim din coada de priorități.

- **Format date ieșire**
    - Fișierul de ieșire va conține output-ul, **pe câte o linie**, corespunzător interogărilor de tipul 2 (daca acestea există în fișierul de intrare).

- **Restricții**
    - $$ 1 \leq N \leq 10^5$$
    - $$ 1 \leq a \leq 10^6$$ 

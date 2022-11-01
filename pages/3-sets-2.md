---
layout: page
title: Mulțimi (2)
permalink: /3-sets-2/
tags: [data structures, skiplists, self-balancing bst]
---

# Descriere

Pentru acest subiect veți compara structuri de date care pot fi folosite pentru a reprezenta API-ul
specific unei mulțimi:

- Adâugarea unui element.
- Ștergerea unui element.
- Verificarea dacă un element aparține mulțimii.
- Modificarea unui element din mulțime.
- Afișarea elementelor mulțimii.

# Precizări

- Veți compara **Skip Lists** cu un arbore binar de căutare echilibrat (AVL, Treap-uri, Arbori roșu-negru, etc. - la alegere)
- Menționați ce avantaje oferă o structură de date față de cealaltă (ex: complexitate, ce operații suplimentare pot fi implementare eficient, etc.).
- Pentru arbori binari de căutare echilibrați trebuie prezentată doar pe scurt complexitatea temporală pentru cazul cel mai defavorabil.
- Pentru Skip Lists trebuie explicată și complexitatea pe cazul mediu.

# Structură teste

#### Format date intrare
- Pe prima linie se află numărul $$N$$ de interogari.
- Pe următoarele $$N$$ linii se află câte o interogare de forma:
    - 0 a - Se adaugă elementul 'a' în mulțime
    - 1 a - Se elimină elementul 'a' din mulțime
    - 2 a - Verifică dacă elementul 'a' aparține mulțimii
    - 3 a b - Elementul 'a' din mulțime (dacă există) este înlocuit cu elementul 'b'
    - 4 - Afișarea tuturor elementelor mulțimii

#### Format date ieșire
- Fișierul de ieșire va conține output-ul, **pe câte o linie**, corespunzător interogărilor de tipul 2, respectiv 4 (daca există în fișierul de intrare).
- Pentru interogări de tipul 2, răspunsul va fi 1 (dacă elementul există) sau 0 (altfel).
- Pentru interogări de tipul 4, răspunsul va consta în secvența de elemente, în orice ordine.

#### Restricții
- $$ 1 \leq N \leq 10^5$$
- $$ 1 \leq a, b \leq 10^6$$ 

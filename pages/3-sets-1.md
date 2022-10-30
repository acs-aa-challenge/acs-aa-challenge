---
layout: page
title: Mulțimi (1)
permalink: /3-sets-1/
---

# Descriere

Pentru acest subiect veți compara structuri de date care pot fi folosite pentru a reprezenta API-ul 
specific unei mulțimi:

- Adâugarea unui element.
- Ștergerea elementului minim (/maxim).
- Afișarea elementului minim (/maxim).
- Modificarea unui element din mulțime.
- Afișarea elementelor mulțimii.

# Precizări

- Veți compara tabelele de dispersie cu un arbore binar de căutare echilibrat (AVL, Treap-uri, Arbori roșu-negru, etc.)
- Menționați ce avantaje oferă o structură de date față de cealaltă (ex: complexitate, ce operații suplimentare pot fi implementare eficient, etc.).
- Pentru tabele de dispersie trebuie să faceți o analiză a metodelor de evitare a coliziunilor. Este suficient să explicați în ce situații sunt mai potrivite unele decât altele (înlănțuire vs. adresare deschisă). Explicați cum puteți trata cazul când nu știți dinainte toate operațiile care vor fi aplicate structurii (nici măcar un număr aproximativ al lor - varianta online). Explicați de ce nu există această problemă și în cazul arborilor. Explicați ce proprietăți ar trebui să aibă o funcție hash ca să fie considerată bună. Precizați doar complexitatea cazului mediu și a celui defavorabil, cu o scurtă argumentare pentru fiecare (referitor doar la complexitatea temporală).
- Pentru arbori binari de căutare echilibrați trebuie prezentată doar pe scurt complexitatea temporală pentru cazul cel mai defavorabil.

# Structură teste
- **Format date intrare**
  - Pe prima linie se află numărul $$N$$ de query-uri 
  - Pe următoarele $$N$$ linii se află câte un query de forma:
    - 0 a - Se adaugă elementul 'a' în mulțime
    - 1 a - Se elimină elementul 'a' din mulțime
    - 2 a - Verifică dacă elementul 'a' aparține mulțimii
    - 3 a b - Elementul 'a' din mulțime (dacă există) este înlocuit cu elementul 'b'
    - 4 - Afișarea tuturor elementelor mulțimii

- **Format date ieșire**
  - Fișierul de ieșire va conține output-ul, **pe câte o linie**, corespunzător interogărilor de tipul 2, respectiv 4 (daca acestea există în fișierul de intrare). 
  - Pentru interogări de tipul 2, răspunsul va fi 1 (dacă elementul există) sau 0 (altfel).
  - Pentru interogări de tipul 4, răspunsul va consta în secvența de elemente, în orice ordine.

- **Restricții**
  - $$ 1 \leq N \leq 10^5$$
  - $$ 1 \leq a, b \leq 10^6$$ 

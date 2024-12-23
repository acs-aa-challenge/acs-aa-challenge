---
layout: page
title: Problema comis-voiajorului (TSP)
permalink: /17-np-1-tsp/
tags: [np-complete, graphs]
---

# Descriere

Fie un graf neorientat G cu N noduri și M muchii. Care este cel mai scurt traseu care începe și se termină cu același nod și 
conține fiecare nod din graf o singură dată?

# Precizări

- Veți compara cel puțin două soluții:
  1. O soluție care obține întotdeauna rezultatul corect (e.g. Held-Karp).
  2. Un algoritm care obține un răspuns **apropiat** de cel corect și consumă o cantitate **rezonabilă** de resurse (spațiu/timp) pentru orice instanță a problemei. (e.g. o euristică nebanală a cărei complexitate și funcționalitate să puteți să o prezentați).

- Discutați care sunt compromisurile ce trebuie făcute pentru implementare și totodată explicați euristicile aplicate.
- **Este important să măsurați cât de apropiat este rezultatul obținut de soluția voastră de rezultatul corect.**
- Alegeți testele suficient de mici astfel încât să puteți rula un algoritm care garantează un rezultat corect într-un timp rezonabil. 
Puteți porni de la un set de teste existent.

- Discuție despre ce strategie/combinație de algoritmi ați aplica pentru a rezolva problema în practică. S-ar putea obține rezultate mai bune folosind algoritmul ales dacă am investi mai multe resurse?
- Există soluții particulare care au o performanță bună garantată pe anumite tipuri de intrări?

# Structură teste

#### Format date intrare

- Pe prima linie se află două numere, $$N$$ și $$M$$, reprezentând numărul de noduri, respectiv de muchii, separate printr-un spațiu.
- Pe următoarele $$M$$ linii se află câte 3 numere naturale $$X$$, $$Y$$, $$C$$, cu semnificația că există o muchie între nodul X și Y
  de lungime C.

#### Format date ieșire

- Pe prima linie se va afla $$S$$, lungimea celui mai scurt traseu, dacă acesta există. 
- Pe a doua linie se vor afla $$N$$ numere, reprezentând ordinea în care vor fi vizitate nodurile de pe traseul ales.
- Altfel, dacă un traseu care să respecte condițiile problemei nu există, veți afișa doar mesajul "Nu există soluție.".

#### Restricții

- $$ 1 \leq N \leq 20$$
- $$ 1 \leq M \leq N*(N-1)$$
- $$ 0 \leq X, Y < N$$
- $$ 1 \leq C \leq 10^6$$
- Nodurile sunt numerotate de la 0 la N-1.

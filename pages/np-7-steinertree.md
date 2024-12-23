---
layout: page
title: Steiner Tree
permalink: /np-7-steinertree/
tags: [np-complete, graphs]
---

# Descriere

Fie un graf neorientat $$G$$ cu $$N$$ noduri și $$M$$ muchii având asociate costuri pozitive. De asemenea, fie o submulțime $$T$$ de noduri.
Determinați un subgraf aciclic conex al lui $$G$$, de cost **minim**, care conține toate nodurile din $$T$$.

# Precizări

- Costul unui subgraf este determinat de suma costurilor muchiilor sale.

- Veți compara cel puțin trei soluții:
    1. O soluție care obține întotdeauna rezultatul corect (e.g. backtracking).
    2. Doi algoritmi care obțin un răspuns apropiat de cel corect și consumă o cantitate rezonabilă de resurse (spațiu/timp) pentru orice instanță a problemei. (e.g. o euristică nebanală a cărei complexitate și funcționalitate să puteți să o prezentați).

- Discutați care sunt compromisurile ce trebuie făcute pentru implementare și totodată explicați euristicile aplicate.
- **Este important să măsurați cât de apropiat este rezultatul obținut de soluția voastră de rezultatul corect.**
- Alegeți testele suficient de mici astfel încât să puteți rula un algoritm care garantează un rezultat corect într-un timp rezonabil.
  Puteți porni de la un set de teste existent.

- Discuție despre ce strategie/combinație de algoritmi ați aplica pentru a rezolva problema în practică.
  S-ar putea obține rezultate mai bune folosind algoritmul ales dacă am investi mai multe resurse?

- Există soluții particulare care au o performanță bună garantată pe anumite tipuri de intrări?

# Structură teste

#### Format date intrare

- Pe prima linie se află două numere, $$N$$, $$M$$ și numărul $$T$$.
- Pe a doua linie se află $$T$$ numere, reprezentănd indexul nodurilor care trebuie conectate.
- Pe următoarele $$M$$ linii se află câte 3 numere naturale $$X$$, $$Y$$, $$C$$, cu semnificația că există o muchie între nodul $$X$$ și $$Y$$
  de lungime $$C$$.

#### Format date ieșire

- Pe prima linie afișați $$S$$ (costul subarborelui identificat).

#### Restricții

- $$ 1 \leq T \leq N \leq 20$$
- $$ 1 \leq M \leq N*(N-1)$$
- $$ 0 \leq X, Y < N$$
- Nodurile sunt numerotate de la 0 la N-1.

---
layout: page
title: Knapsack
permalink: /19-np-3-knapsack/
tags: [np-complete]
---

# Descriere

Fie o mulțime formată din $$N$$ obiecte. Fiecare obiect $$i$$ are asociată o greutate $$g_i$$ și o valoare $$v_i$$.
Identificați o submulțime de obiecte, astfel încât suma greutăților acestora să nu depășească o valoare maximă $$G$$
iar suma valorilor lor să fie maximă.

# Precizări

- Aceasta este o problemă NP-Completă.
- Veți compara cel puțin trei soluții:
  1. Două soluții care garantează întotdeauna un rezultat corect (ex: folosind backtracking/programare dinamică).
  2. Un algoritm care obține un răspuns apropiat de cel corect și consumă o cantitate rezonabilă de resurse (spațiu/timp) pentru orice instanță a problemei. (e.g. o euristică nebanală a cărei complexitate și funcționalitate să puteți să o prezentați).

- Discutați care sunt compromisurile ce trebuie făcute pentru implementare și totodată explicați euristicile aplicate.
- **Este important să măsurați cât de apropiat este rezultatul obținut de soluția voastră de rezultatul corect.**
- Alegeți testele suficient de mici astfel încât să puteți rula un algoritm care garantează un rezultat corect într-un timp rezonabil.
  Puteți porni de la un set de teste existent.

- Există soluții particulare care au o performanță bună garantată pe anumite tipuri de intrări?

- (Bonus): Discuție despre ce strategie/combinație de algoritmi ați aplica pentru a rezolva problema în practică.
  S-ar putea obține rezultate mai bune folosind algoritmul ales dacă am investi mai multe resurse?

# Structură teste

#### Format date intrare

- Pe prima linie se află două numere, $$N$$ și $$G$$.
- Pe următoarele $$N$$ linii se va afla câte o pereche de numere, $$g_i, v_i$$, semnificând greutatea, respectiv valoarea
asociată fiecărui obiect.

#### Format date ieșire

- Pe prima linie se află valoarea maximă care poate fi obținută.
- Pe a doua linie se vor afla indicii elementelor selectate.

#### Restricții

- $$ 1 \leq N \leq 10^4$$
- $$ 1 \leq G \leq 10^6$$
- $$ 0 \leq g_i, v_i \leq 10^6$$

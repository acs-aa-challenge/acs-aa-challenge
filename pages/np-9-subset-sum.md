---
layout: page
title: Subset Sum
permalink: /np-9-subset-sum/
tags: [np-hard]
---

# Descriere

Fie o mulțime formată din $$N$$ obiecte. Fiecare obiect $$i$$ are asociată o valoare întreagă $$v_i$$.
Identificați o submulțime de obiecte, astfel încât suma valorilor acestora să fie exact $$T$$.

# Precizări

- Veți compara cel puțin trei soluții:
  1. Două soluții care garantează întotdeauna un rezultat corect (ex: folosind backtracking/programare dinamică).
  2. Un alt algoritm care obține un răspuns apropiat de cel corect și consumă o cantitate rezonabilă de resurse (spațiu/timp) pentru orice instanță a problemei. (e.g. o euristică nebanală a cărei complexitate și funcționalitate să puteți să o prezentați).

- Discutați care sunt compromisurile ce trebuie făcute pentru implementare și totodată explicați euristicile aplicate.
- **Este important să măsurați cât de apropiat este rezultatul obținut de soluția voastră de rezultatul corect.**
- Alegeți testele suficient de mici astfel încât să puteți rula un algoritm care garantează un rezultat corect într-un timp rezonabil.
  Puteți porni de la un set de teste existent.

- Există soluții particulare care au o performanță bună garantată pe anumite tipuri de intrări?

- S-ar putea obține rezultate mai bune folosind algoritmul ales dacă am investi mai multe resurse?

# Structură teste

#### Format date intrare

- Pe prima linie se află două numere, $$N$$ și $$T$$.
- Pe următoarele $$N$$ linii se va afla câte un număr întreg $$v_i$$, semnificând valoarea fiecărui obiect. 

#### Format date ieșire

- Pe prima linie se află numărul de obiecte alese din mulțime.
- Pe a doua linie se vor afla indicii obiectelor selectate.

#### Restricții

- $$ 1 \leq N \leq 10^4$$
- $$ 1 \leq T \leq 10^6$$
- $$ -10^6 \leq v_i \leq 10^6$$

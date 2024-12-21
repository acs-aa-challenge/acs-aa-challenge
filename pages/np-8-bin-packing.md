---
layout: page
title: Bin Packing
permalink: /np-8-bin-packing/
tags: [np-complete, packing, hard]
---

# Descriere

Fie o colecție de $$N$$ obiecte și o capacitate maximă reprezentată de numărul natural $$C$$. Cum putem partiționa colecția inițială într-un număr minim de submulțimi ($$K$$) astfel încât suma mărimilor din fiecare submulțime să fie mai mică sau egală cu $$C$$?

# Precizări

- Veți compara cel puțin trei soluții:
    1. O soluție care obține întotdeauna rezultatul corect (e.g. backtracking).
    2. Doi algoritmi care obțin un răspuns apropiat de cel corect și consumă o cantitate rezonabilă de resurse (spațiu/timp) pentru orice instanță a problemei. (e.g. o euristică nebanală a cărei complexitate și funcționalitate să puteți să o prezentați).

- Discutați care sunt compromisurile ce trebuie făcute pentru implementare și totodată explicați euristicile aplicate.
- **Este important să măsurați cât de apropiat este rezultatul obținut de soluția voastră de rezultatul corect.**
- Alegeți testele suficient de mici astfel încât să puteți rula un algoritm care garantează un rezultat corect într-un timp rezonabil.
  Puteți porni de la un set de teste existent.

- Există soluții particulare care au o performanță bună garantată pe anumite tipuri de intrări?

- (Bonus): Discuție despre ce strategie/combinație de algoritmi ați aplica pentru a rezolva problema în practică.
  S-ar putea obține rezultate mai bune folosind algoritmul ales dacă am investi mai multe resurse?

# Structură teste

#### Format date intrare

- Pe prima linie se află două numere, $$N$$ și $$C$$.
- Pe următoarele $$N$$ linii se va afla câte o pereche de numere, $$g_i$$, semnificând greutatea asociată fiecărui obiect.

#### Format date ieșire

- Pe prima linie se va afla numărul minim de submulțimi ($$K$$).
- Pe fiecare din următoarele linii se vor afla indicii unei din submulțimi, în ordine crescătoare.
- Dacă sunt mai multe soluții posibile, afișați oricare dintre ele.

#### Restricții

- $$ 1 \leq N \leq 10^3$$
- $$ 1 \leq C \leq 10^6$$
- $$ 0 \leq g_i \leq 10^6$$

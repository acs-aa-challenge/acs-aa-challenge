---
layout: page
title: K-Clique
permalink: /20-np-4-clique/
tags: [np-complete, graphs, hard]
---

# Descriere

Fie un graf neorientat $$G$$ cu $$N$$ noduri și $$M$$ muchii. Există un subgraf cu $$K$$ noduri, 
în care fiecare nod este conectat direct cu toate celelalte noduri (nodurile formează o clică)?

# Precizări

- Aceasta este o problemă NP-Completă.
- Veți compara cel puțin două soluții:
    1. O soluție care obține întotdeauna rezultatul corect (e.g. backtracking).
    2. Un algoritm care obține un răspuns apropiat de cel corect și consumă o cantitate rezonabilă de resurse (spațiu/timp) pentru orice instanță a problemei. (e.g. o euristică nebanală a cărei complexitate și funcționalitate să puteți să o prezentați).

- Discutați care sunt compromisurile ce trebuie făcute pentru implementare și totodată explicați euristicile aplicate.
- **Este important să măsurați cât de apropiat este rezultatul obținut de soluția voastră de rezultatul corect.**
- Alegeți testele suficient de mici astfel încât să puteți rula un algoritm care garantează un rezultat corect într-un timp rezonabil.
  Puteți porni de la un set de teste existent.

- (Bonus): Discuție despre ce strategie/combinație de algoritmi ați aplica pentru a rezolva problema în practică.
  S-ar putea obține rezultate mai bune folosind algoritmul ales dacă am investi mai multe resurse?

- Există soluții particulare care au o performanță bună garantată pe anumite tipuri de intrări?

# Structură teste

#### Format date intrare

- Pe prima linie se află trei numere, $$N$$, $$M$$ și $$K$$.
- Pe următoarele $$M$$ linii se află câte 2 numere naturale $$X$$, $$Y$$, cu semnificația că există o muchie între nodul X și Y.

#### Format date ieșire

- Dacă în graf există cel puțin o K-clică, afișați cele K noduri care o compun pe o singură linie.
- Altfel, afișați mesajul: "Nu există soluție."

#### Restricții

- $$ 1 \leq N, K \leq 20$$
- $$ 1 \leq M \leq N*(N-1)$$
- $$ 0 \leq X, Y < N$$
- Nodurile sunt numerotate de la 0 la N-1.

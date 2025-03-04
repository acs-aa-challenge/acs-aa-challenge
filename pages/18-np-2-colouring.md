---
layout: page
title: Colorarea grafurilor
permalink: /18-np-2-colouring/
tags: [np-complete, graphs]
---

# Descriere

Fie un graf neorientat $$G$$ cu $$N$$ noduri și $$M$$ muchii. Problema cere să asociem o culoare fiecărui nod, astfel încât oricare două noduri adiacente 
(conectate printr-o muchie directă) să aibă culori diferite. Care este numărul **minim** de culori 
necesare pentru a colora toate nodurile conform restricției menționate anterior?

# Precizări

- Veți compara cel puțin două soluții:
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

- Pe prima linie se află două numere naturale, $$N$$ și $$M$$.
- Pe următoarele $$M$$ linii se află câte 2 numere naturale $$X$$, $$Y$$, cu semnificația că există o muchie între nodul X și Y.

#### Format date ieșire

- Pe prima linie, afișați $$K$$, numărul minim de culori necesare.
- Pe a doua linie afișați $$N$$ valori, separate prin spațiu, reprezentând culorile asociate fiecărui nod.
- Dacă există mai multe soluții, se poate afișa oricare.

#### Restricții

- $$ 1 \leq K \leq N \leq 20$$
- $$ 1 \leq M \leq N*(N-1)$$
- $$ 0 \leq X, Y < N$$
- Nodurile și culorile sunt numerotate de la 0.

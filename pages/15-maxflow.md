---
layout: page
title: Flux maxim
permalink: /15-maxflow/
tags: [graphs, hard]
---

# Descriere

Fie un graf orientat cu $$N$$ noduri și $$M$$ muchii. Fiecare muchie are o anumită capacitate - prin fiecare muchie putem 
transporta o anumită cantitate de informaţie. Mai mult, există un nod special numit sursă, $$S$$, de unde poate pleca oricâtă 
informaţie, şi un nod special numit destinaţie, $$D$$, care poate primi oricâtă informaţie. Singura limitare este dată de 
capacităţile muchiilor. Astfel, antitatea de informație care intră într-un nod trebuie să fie egală cu cea care iese din nod
(cu excepția nodurilor $$S$$ si $$D$$). Se cere să se determine capacitatea maximă care poate fi transmisă de la $$S$$ la $$D$$.

# Precizări

- Comparați trei algoritmi (ex: Ford-Fulkerson, Edmonds-Karp, Dinic, Push-relabel, etc.)
  - Puteți opta pentru un algoritm naiv (Ford-Fulkerson) și doi mai eficienți.
- Testați folosind grafuri cu dimensiuni variabile, respectiv dimensiuni variabile relative între N şi M, 
de exemplu $$M << N, M = N, M = N log N, M = N * \sqrt N, M\sim\ {N^2}$$.
- Analizați și cum influențează structura internă a grafului performanța algoritmiilor.

# Structură teste

#### Format date intrare

- Pe prima linie se află două numere, $$N$$ și $$M$$, reprezentând numărul de noduri, respectiv de muchii, separate printr-un spațiu.
- Pe a doua linie se află id-ul nodului sursă $$S$$ și nodului destinație $$D$$.
- Pe următoarele $$M$$ linii se află câte 3 numere naturale $$X$$, $$Y$$, $$C$$, cu semnificația că există un arc între nodul $$X$$ și $$Y$$
  de capacitate $$C$$.

#### Format date ieșire

- Pe prima linie se va afla un singur număr reprezentând fluxul maxim ce poate fi trimis prin rețea de la $$S$$ la $$D$$.

#### Restricții

- $$ 1 \leq N \leq 10^3$$
- $$ 1 \leq M \leq min(N^2, 10^4)$$
- $$ 1 \leq X, Y \leq N$$
- $$ 1 \leq C \leq 10^6$$
- Nodurile sunt numerotate de la 0 la $$N-1$$.

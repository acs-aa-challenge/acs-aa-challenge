---
layout: page
title: Cuplaj maxim în graf bipartit
permalink: /16-matching/
tags: [graphs, hard]
---

# Descriere

Fie un graf neorientat bipartit $$G$$ cu $$N$$ noduri și $$M$$ muchii. Un graf este bipartit dacă poate fi descompus în 
două mulțimi de noduri, $$L$$ și $$R$$, astfel încât fiecare nod nu este adiacent cu alte noduri din aceeași mulțime.

Un **cuplaj** este o submulțime $$E$$ de **muchii**, astfel încât oricare două muchii din $$E$$ au cel mult un nod comun. 
Un cuplaj maxim este un cuplaj de cardinalitate maximă. Determinați cuplajul maxim pentru graful $$G$$.

# Precizări

- Comparați algoritmii Ford-Fulkerson și Hopcroft Karp.
- Analizați cum este afectată performanța algoritmilor în funcție de particularitățile grafului (ex: numărul de noduri/muchii,
structura internă a acestuia).

# Structură teste

#### Format date intrare

- Pe prima linie se află două numere, $$N$$ și $$M$$, reprezentând numărul de noduri, respectiv de muchii, separate printr-un spațiu.
- Pe următoarele $$M$$ linii se află câte două numere naturale $$X$$, $$Y$$, cu semnificația că există o muchie între nodul $$X$$ și $$Y$$
  ($$X$$ din mulțimea $$L$$ și $$Y$$ din mulțimea $$R$$).

#### Format date ieșire

- Pe prima linie se va afișa $$S$$, numărul de muchii din cuplajul maxim.
- Pe următoarele $$S$$ linii se află câte două numere naturale $$X$$, $$Y$$, separate prin spațiu, cu semnificația
că nodul $$X$$ a fost cuplat cu nodul $$Y$$.
- Dacă există mai multe soluții se poate afișa oricare.

#### Restricții

- $$ 1 \leq N \leq 2 * 10^4$$
- $$ 1 \leq S \leq M \leq min(N^2, 10^5)$$
- $$ 0 \leq X, Y < N$$
- $$ -10^6 \leq C \leq 10^6$$
- Nodurile sunt numerotate de la 0 la $$N-1$$.

---
layout: page
title: Arbore parțial de cost minim
permalink: /13-mst/
tags: ["graphs"]
---

# Descriere

Fie un graf conex neorientat $$G$$ cu $$N$$ noduri și $$M$$ muchii. Selectați un subset de muchii astfel încât subgraful 
format de acestea să fie aciclic, să cuprindă toate nodurile din graful original și suma costurilor muchiilor să fie minimă. 

# Precizări

- Pentru acest subiect veți compara cel puțin doi algoritmi, Kruskal și Prim.
- Analizați cum este afectată performanța algoritmilor în funcție de particularitățile grafului (ex: numărul de noduri/muchii,
  structura internă a acestuia).

# Structură teste

#### Format date intrare

- Pe prima linie se află două numere, $$N$$ și $$M$$, reprezentând numărul de noduri, respectiv de muchii, separate printr-un spațiu.
- Pe următoarele $$M$$ linii se află câte două numere naturale $$X$$, $$Y$$, cu semnificația că există o muchie între nodul $$X$$ și $$Y$$.

#### Format date ieșire

- Pe prima linie se va afișa $$S$$, reprezentând suma costurilor muchiilor selectate.
- Pe următoarele $$N-1$$ linii se află câte două numere naturale $$X$$, $$Y$$, separate prin spațiu, cu semnificația
  că muchia care leaga nodurile $$X$$ și $$Y$$ face parte din arborele parțial de cost minim.

#### Restricții

- $$ 1 \leq N \leq 2 * 10^5$$
- $$ 1 \leq M \leq 5 * min(N^2, 10^5)$$
- $$ 1 \leq X, Y \leq N$$
- $$ -10^6 \leq C \leq 10^6$$
- Nodurile sunt numerotate de la 0 la $$N-1$$.

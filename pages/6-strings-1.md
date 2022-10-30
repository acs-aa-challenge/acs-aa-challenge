---
layout: page
title: String Matching
permalink: /6-strings-1/
---

# Descriere

Fie doua secvențe de caractere, A și B. Identificați toate aparițiile șirului A ca subsecvență a lui B.

# Precizări

- Pentru această problemă puteți analiza, la alegere, **doi** dintre următorii algoritmi: Knuth-Morris-Pratt (KMP),
Rabin-Karp și Boyer-Moore.
- Analizați avantajele și dezavantajele oferite de fiecare algoritm.

- Rabin-Karp:
  - Precizați probabilitatea unei false potriviri în funcție de dimensiunea spațiului cheilor. Argumentați cum 
  putem micșora această probabilitate. 
  - Discutați ce tipuri de funcții hash putem folosi în implementare.
- Boyer-Moore:
  - Pentru ce fel de date se comporta mai bine decât KMP?

# Structură teste

#### Format date intrare
  - Pe prima linie se află șirul A.
  - Pe a doua linie se află șirul B.
  
#### Format date ieșire
  - Pe prima linie se va afla numărul de apariții a șirului A în șirul B.
  - Pe a doua linie se vor afla pozițiile de început corespunzătoare fiecărei apariții.

#### Restricții
  - $$1 \leq |A|, |B| \leq 10^6$$
  - Șirurile sunt indexate de la 0.

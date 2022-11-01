---
layout: page
title: Identificare numerelor prime
permalink: /8-primes/
tags: ["math"]
---

# Descriere

Fiind dat un set de date de intrare se dorește identificarea numerelor prime din acel set.

# Precizări
- Comparați **doi algoritmi**.

# Opțiuni posibile

- **Fermat**: Argumentați de ce algoritmul poate întoarce true pentru numere compuse (care nu sunt prime) și cum influențează numărul de iterații acest lucru. Funcționează întotdeauna folosirea unui număr mare de iterații? Justificați.
- **Miller-Rabin**: Comparați algoritmul cu Fermat și evidențiați cazurile în care se preferă utilizarea Miller-Rabin.
- **Solovay-Strassen**: Argumentați de ce algoritmul poate întoarce true pentru numere compuse (care nu sunt prime).
- **Frobenius**: Evidențiați caracteristicile acestui algoritm prin comparație cu celălalt algoritm ales.

# Structură teste

#### Format date intrare
- Pe prima linie, $$N$$ (int - numărul de elemente din secvență)
- Pe următoarea linie $$N$$ numere întregi (reprezentabile pe 32 biți)

#### Format date ieșire
- Pe prima linie, $$M$$ - numărul de elemente prime
- Pe a doua linie se va afla secvența propriu-zisă de numerele prime extrase din secvența originală.

#### Restricții:
- $$1 \leq N \leq 10^6$$
    

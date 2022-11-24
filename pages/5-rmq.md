---
layout: page
title: Elementul minim dintr-un interval (RMQ)
permalink: /5-rmq/
tags: [data structures]
---

# Descriere
Dat fiind un vector $$A$$ cu $$N$$ elemente de tip întreg, răspundeți eficient la întrebări de tipul: "Care este elementul minim din intervalul care începe la poziția $$x$$ și se termină la poziția $$y$$?". Se consideră că se dă vectorul și apoi se fac $$M$$ interogări.

<!-- , fără a se modifica între timp vectorul. -->

# Precizări

- Comparați **trei variante** de rezolvare.
- Discutați cazurile când $$M \ll N$$ ($$M$$ mult mai mic decât $$N$$), M proporțional cu $$N$$ și $$M \gg N$$ ($$M$$ mult mai mare decât $$N$$).
- Calculați complexitatea în funcție de aceste două variabile ($$N$$ și $$M$$). 
- Discutați cum se modifică problema dacă utilizatorul poate să solicite schimbarea valorii unui element de la o anumită poziție în timpul interogărilor pentru fiecare metodă aleasă. (varianta online)

## Opțiuni posibile

- Nu se acceptă soluția banală sau variante echivalent de slabe cu $$O(n)$$ per interogare.
- Una dintre variante trebuie să fie o variantă care se comportă bine pentru cazul când se pot și modifica elemente. 
- Una dintre variante trebuie să fie o metodă care răspunde în $$O(1)$$ la interogare pentru scenariul în care elementele vectorului nu se modifică.

# Structură teste

#### Format date intrare    
  - Pe prima linie, $$N$$ (int - numărul de elemente din secvență), $$M$$ numărul de interogări
  - Pe a doua linie, $$N$$ elemente (numere întregi - reprezentabile pe 32 biti)
  - Pe următoarele $$M$$ linii, câte o pereche de numere întregi $$(x, y)$$ reprezentând poziții din secvență.

#### Format date ieșire    
  - $$M$$ linii care vor conține un singur număr reprezentând răspunsul la fiecare interogare.

#### Restricții
  - $$1 \leq N, M \leq 1000000$$
  - $$1 \leq x, y \leq N$$

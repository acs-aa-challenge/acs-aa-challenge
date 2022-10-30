---
layout: page
title: Lowest Common Ancestor
permalink: /14-lca/
tags: ["graphs"]
---

# Descriere
Se dă un arbore $$T$$ cu $$N$$ noduri și apoi se fac $$M$$ interogări. Pentru fiecare interogare se dau două noduri $$u$$ și $$v$$. Trebuie să returnați nodul $$w$$ cu cea mai mare adâncime din $$T$$ care este strămoș atât pentru $$u$$, cât și pentru $$v$$.

# Precizări

- Comparați **două variante** de rezolvare.
- Discutați cazurile când $$M \ll N$$ ($$M$$ mult mai mic decât $$N$$), $$M$$ proporțional cu $$N$$ și $$M \gg N$$ ($$M$$ mult mai mare decât $$N$$).
- Discutați cum afectează structura grafului performanța algoritmului ales.
- Calculați complexitatea în funcție de aceste două variabile ($$N$$ și $$M$$). 

# Opțiuni posibile
- Nu se acceptă soluția banală sau variante mai slabe ca $$O(h)$$ per interogare, unde $$h$$ este înălțimea arborelui.

# Structură recomandată teste

#### Format date intrare
    - Pe prima linie: $$N$$ (int - numărul de noduri din arbore), $$M$$ (int - numărul de interogări).
    - Pe următoarele $$N-1$$ linii: câte o pereche de numere întregi, reprezentănd muchiile arborelui.
    - Pe fiecare dintre următoarele $$M$$ linii se vor afla id-urile a câte două noduri, $$u$$ și $$v$$, reprezentând o interogare.

#### Format date ieșire
    - $$M$$ linii care vor conține un singur număr reprezentând răspunsul la fiecare interogare.

#### Restricții
    - $$2 \leq N, M \leq 1000000$$
    - Nodurile sunt numerotate de la 0 la $$N-1$$.


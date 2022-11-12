---
layout: page
title: Recomandări
permalink: /recomandari/
---

## Implementare ##

- Trebuie să ținem cont de particularitatea datelor pe care ne așteptăm să le întâlnim în practică. 
Datele generate pur sintetic (e.g. folosind random) pot să ne ghideze într-o direcție greșită. 
De exemplu, fie o problemă unde trebuie să realizăm diferite interogări pe secvențe de caractere. 
Putem să generăm relativ ușor secvențe aleatoare de caractere pentru testare dar este 
posibil să nu evaluăm corect algoritmi care merg foarte bine pe text natural (e.g.: dacă algoritmul exploatează distribuția cuvintelor întâlnite în limba engleză).

- Este important să generăm teste suficient de mari. Procesoarele moderne sunt foarte rapide, 
teste cu 10 elemente sunt total insuficiente pentru a putea măsura eficiența unui algoritm.

- De asemenea, este important, atunci când comparăm mai mulți algoritmi, să îi rulăm _pe aceleași teste_, pentru a putea face o evaluare corecta.

- Pentru a analiza o structură de date care suportă mai multe tipuri de interogări trebuie să putem măsura precis timpul 
petrecut pentru fiecare interogare. De asemenea, dacă structura de date are anumiți parametrii fixați 
(e.g. factorul de încărcare de la hashtable), ar trebui să investigăm și impactul modificării acestor valori.

- Ne așteptăm **să aveți cel puțin 20 de teste generate**. Nu este necesar să exagerați, să generați 100 de teste, dar o temă cu puține teste va fi punctată corespunzător.

- Ca să fiți siguri că performanțelor obținute nu sunt întâmplătoare, este util să rulați de mai multe ori pe același set de teste și să calculați o medie a valorilor obținute.
  Vă recomandăm (dar nu este obligatoriu) să folosiți tool-uri de benchmarking (ex: hyperfine, <a href="https://openjdk.org/projects/code-tools/jmh/">jmh</a> (Java),  <a href="https://github.com/google/benchmark">Google Benchmark</a> (C++)) care să vă ajute să automatizați parțial acest aspect.

- De asemeni, vă recomandăm să folosiți tool-uri de profiling (ex: <a href="http://www.brendangregg.com/perf.html">perf</a>, <a href="http://valgrind.org/docs/manual/cl-manual.html">valgrind</a>, etc.). pentru a descoperi cu precizie unde este bottleneck-ul codului nostru.

- Tot pentru o testare riguroasă, este important să măsurați separat rezolvarea problemei de partea de IO a datelor.

## Redactare ##

Referitor la redactare, sunt câteva aspecte importante care trebuie urmărite:

- Textul trebuie să fie **ușor de inteles** și **concis**.
  - Nu scrieti cu gandul la numarul de pagini. Aveti ce sa scrieti, iar noi oricum evaluăm conținutul, nu numărul de pagini. :-)
  - Evitati fraze prea lungi. Dacă o frază este prea lungă (>3 randuri), spărgeți-o în două sau mai multe fraze.
  - Daca o sintagmă nu aduce nici o informație suplimentară mai bine nu o folosiți. (ex: “Se observă trivial ca …”).
  - Evitați folosirea unor expresii repetitive ("Așadar.., așadar..", "Deci.., deci..") în aceeași frază/paragraf.
  - Ajută să căutați sinonime pentru a evita repetiții.

- **Evitați afirmațiile vagi**, neargumentate (ex: "după cum se spune", "cel mai folosit algoritm", "cel mai bun algoritm").
- Pentru prezentarea unui algoritm evitați să puneți prea mult cod direct in lucrare. 
  - Ar fi preferabil să prezintați (succint) în cuvinte comportamentul algoritmului (eventual folosind pseuducod) pentru 
  ca cineva care nu știe algoritmul să poată înțelege ușor despre ce este vorba fără să fie nevoit să urmărească secvențe lungi de cod.

- Folosiți consecvent diateza activă, timpul trecut, pentru a evidenția propriile rezultate.
  - “**Am facut** X.” (vs.: “S-a facut X.”)

- **Explicați notațiile folosite**.
  - (ex: "Complexitate $$O(n + r)$$" - trebuie să specificați cine este '$$n$$' și '$$r$$')

- Graficele trebuie să fie **ușor de înteles**.
  - Să aibă o legendă clară (“higher is better”).
  - Să fie menționate **unitățile de măsură** folosite.
  - Să aibă valori normalizate (daca este cazul) pentru a se putea distinge între elementele afișate.
  - Să aibă o rezoluție bună (ex: să poate fi ușor de citit în format print).

- Într-un tabel în care comparați performanța unor algoritmi marcați cu bold cel mai bun rezultat.
  - Specificați **unitățile de măsura**.

- Dacă preluați o informație/tabel/poza/grafic, etc. este **obligatoriu** să specificați explicit sursa în locul unde
  ați folosit informația, respectiv să folosiți ghilimele atunci când preluați un paragraf nemodificat.
  - Pentru editarea referințelor, puteți folosi funcția "cite" din Google Scholar. Un exemplu este disponibil <a href="https://libguides.com.edu/c.php?g=649172&p=4554037">aici</a>.
  - Nu folosiți Wikipedia ca referință directă.
  - În general, nu citați generic un portal (ex: www.geeksforgeeks.org); Citați explicit pagina care a fost relevantă pentru voi și menționați data accesării.

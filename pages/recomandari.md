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

- De asemeni, vă recomandăm să folosiți tool-uri de profiling (ex: <a href="http://www.brendangregg.com/perf.html">perf</a>, <a href="http://valgrind.org/docs/manual/cl-manual.html">valgrind</a>, etc.). pentru a descoperi cu precizie unde este bottleneck-ul codului nostru

- Tot pentru o testare riguroasă, este important să măsurați separat rezolvarea problemei de partea de IO a datelor.

## Redactare ##

- **Evitați afirmațiile vagi**, neargumentate (ex: "după cum se spune", "cel mai folosit algoritm", "cel mai bun algoritm").
- Dacă preluați o informație, tabel, poza, grafic, etc. este **obligatoriu** să specificați sursa, respectiv să folosiți ghilimele atunci când preluați un paragraf nemodificat.
- Puteți fi penalizați pentru folosirea unor termeni fară explicarea semnificației lor.
(ex: "Complexitate $$O(n + r)$$" - fără a specifica cine este '$$r$$')
- Evitați folosirea unor expresii repetitive ("Așadar.., așadar..", "Deci.., deci..") în aceeași frază/paragraf.
- La prezentarea algoritmului evitați să puneți prea mult cod direct in lucrare. Ar fi preferabil să prezintați (succint) în cuvinte comportamentul algoritmului (eventual folosind pseuducod) pentru ca cineva care nu știe algoritmul să poată înțelege ușor despre ce este vorba fără să fie nevoit să urmărească secvențe lungi de cod.
- Pentru a fi ușor de înteles, graficele trebuie să aibă o legendă, respectiv să aibă valorile normalizate.
- **Specificați unitățile de măsură** folosite in tabele/grafice.
- Într-un tabel în care comparați performanța unor algoritmi marcați cu bold cel mai bun rezultat.
- Pentru editarea referințelor, puteți folosi funcția "cite" din Google Scholar. Mai multe detalii <a href="https://libguides.com.edu/c.php?g=649172&p=4554037">aici</a>.
- Dacă doriți să adăugați o referință la un website, menționați data ultimei accesări.
- Nu folosiți Wikipedia ca referință directă.

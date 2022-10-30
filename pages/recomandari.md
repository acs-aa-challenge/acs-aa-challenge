---
layout: page
title: Recomandări
permalink: /recomandari/
---

## Implementare ##
- Ca să fiți siguri că performanțelor obținute nu sunt întâmplătoare, este util să rulați de mai multe ori pe același set de teste și să calculați o medie a valorilor obținute. 
Vă recomandăm (dar nu este obligatoriu) să folosiți tool-uri de benchmarking (ex: <a href="https://openjdk.org/projects/code-tools/jmh/">jmh</a> (Java),  <a href="https://github.com/google/benchmark">Google Benchmark</a> (C++)) care să vă ajute să automatizați parțial acest aspect.
- De asemeni, vă recomandăm să folosiți tool-uri de profiling (ex: <a href="http://www.brendangregg.com/perf.html">perf</a>, <a href="http://valgrind.org/docs/manual/cl-manual.html">valgrind</a>, etc.).
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

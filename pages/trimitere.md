---
layout: page
title: Trimiterea Temei
permalink: /trimitere/
---

## Etapa 0

[//]: # (Pe 08.11.2022, la ora 20:00, vom publica un formular unde veți putea să vă înscrieți opțiunile de probleme, respectiv algoritmii preferați.)
Tema va fi alocată folosind un script automat, în funcție de ordinea completării formularului și opțiunile alese,
astfel încât, la nivelul unei semigrupe, un subiect va fi alocată unui singur student. Studenții restanțieri pot alege orice subiect.

Înscrieți-vă opțiunile de probleme preferate în acest <a href="https://forms.gle/i7t8nDFVB392YDUj9">acest</a> formular.

[//]: # (  **Formularul va fi accesibil începând cu data de 1.11, la ora 20.** )
[//]: # (Vineri, 4.11, vom publica alocarea subiectelor pentru fiecare student.)

## Etapa 1

Veți încărca pe Moodle o arhivă care va conține documentul în format .pdf.
Documentul se va numi **NumărSubiect.pdf** unde în loc de NumărSubiect veți trece numărul problemei alese - (ex: "1.pdf" pentru primul subiect)

Deoarece soluțiile vor fi repartizate pentru corectare automat, arhiva va fi denumită, **obligatoriu**, folosind ID-ul vostru de Moodle.
De exemplu, daca ID-ul vostru este "ion.popescu", arhiva **trebuie** să se numească "ion.popescu.zip"

## Etapa 2

Vom reveni cu mai multe detalii legate de submisie în curând (vom folosi vmchecker pentru a valida structura arhivei).

În principiu arhiva va conține:

- **Documentul final** în format .pdf. Documentul se va numi "**EtapaFinala.pdf**".

- **Sursele pentru algoritmii utilizați**, respectând structura sugerată la fiecare problemă.

- **Setul de date de test**:
        - Testele de intrare se vor afla într-un folder numit **"in"**.                
        Fiecare test se va numi "testX.in", unde X reprezintă ID-ul testului. (ex: "test1.in")
        - Rezultatele corecte pentru fiecare test se vor afla într-un folder numit **"out"**.                
        Fiecare rezultat se va numi "testX.out", unde X reprezintă ID-ul testului. (ex: "test1.out")                

- Programul folosit pentru generarea testelor.

- Fișierul **Makefile**.

    - Pentru fiecare algoritm implementat, trebuie să existe o regulă corespunzatoare de run. 
    - Vom folosi următoarea convenție de denumire/evaluare: "make run-p1" - pentru testarea algoritmului 1, "make run-p2" - pentru testarea celui de-al doilea algoritm, etc.
    - Vă recomandăm să includeți o regulă separată de run pentru cel mai bun algoritm evaluat, "run-best".
    - Pentru compilare este suficientă o singură regulă de build ("make build"). Dacă lucrați într-un limbaj interpretat (e.g. Python) sunt suficiente doar regulile de run.
    - Regulă de **clean**.

- Fișierul **README**, în care veți menționa:

    - Numele și grupa.
    - Ce reprezintă fiecare fișier din arhivă.
    - Alte detalii speciale legate de evaluare.
    - **Sursele exacte dacă ați preluat conținut din surse externe (e.g. teste, secvență de cod)**.
        - Mentionați referința directă (de exemplu, pagina web/pagina dintr-o carte/lucrare de cercetare)

Deoarece soluțiile vor fi repartizate pentru corectare automat, arhiva va fi denumită, **obligatoriu**, folosind ID-ul vostru de Moodle.
De exemplu, daca ID-ul vostru este "ion.popescu", arhiva **trebuie** să se numească "ion.popescu.zip"

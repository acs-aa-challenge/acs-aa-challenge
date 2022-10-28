---
layout: page
title: Trimiterea Temei
permalink: /trimitere/
---

    \item \textbf{Etapa 0}
    
    Înscrieți-vă opțiunea în sheetul corespunzător semigrupei voastre. \textbf{\color{burntorange}Sheet-ul va fi publicat in data de 14.10 la ora 20 pe moodle.} În cadrul unei semigrupe nu este permis ca doi studenți să aleagă aceiași algoritmi.
    
    \item \textbf{Etapa 1}
    
    Veți încărca pe Moodle o arhivă care va conține documentul în format .pdf.
    Documentul se va numi \textbf{NumărSubiect.pdf} unde în loc de NumărSubiect veți trece numărul subiectului ales - 1 pentru Flux, 2 pentru RMQ, etc.
    
    Deoarece soluțiile vor fi repartizate pentru corectare automat, arhiva va fi denumită, 
    \textbf{obligatoriu}, folosind ID-ul vostru de Moodle.
    De exemplu, daca ID-ul vostru este "ion.popescu", arhiva \textbf{trebuie} să se numească "ion.popescu.zip"

    \item \textbf{Etapa 2}
    
    Veți încărca pe Moodle o arhivă care va conține:
    
    \begin{itemize}
        \item \textbf{Sursele pentru algoritmii utilizați}, respectând structura sugerată la fiecare problemă.
        \item \textbf{Setul de date de test}:
            \begin{enumerate}
                \item Testele de intrare se vor afla într-un folder numit \textbf{"in"}.
                
                Fiecare test se va numi "testX.in", unde X reprezintă ID-ul testului. (ex: "test1.in")
                \item Rezultatele corecte pentru fiecare test se vor afla într-un folder numit \textbf{"out"}. 
                
                Fiecare rezultat se va numi "testX.out", unde X reprezintă ID-ul testului. \newline (ex: "test1.out")
                
            \end{enumerate}
        \item Programul folosit pentru generarea testelor (dacă a fost necesar).
        \item Fișierul \textbf{Makefile}.
        \begin{itemize}
            \item Pentru fiecare algoritm implementat, trebuie să existe o regulă corespunzatoare de run. 
            \item Vom folosi următoarea convenție de denumire/evaluare: "make run-p1" - pentru testarea algoritmului 1, "make run-p2" - pentru testarea celui de-al doilea algoritm, etc.
            \item Vă recomandăm să includeți o regulă separată de run pentru cel mai bun algoritm evaluat, "run-best".
            \item Pentru compilare este suficientă o singură regulă de build ("make build"). Dacă lucrați într-un limbaj interpretat (e.g. Python) sunt suficiente doar regulile de run.
            \item Regulă de \textbf{clean}.
    \end{itemize}
        
        \item Fișierul \textbf{README}, în care veți menționa:
        \begin{itemize}
            \item Numele și grupa.
            \item Ce reprezintă fiecare fișier din arhivă.
            \item Alte detalii speciale legate de evaluare.
            \item \textbf{Sursele exact dacă ați preluat conținut din surse externe (e.g. teste, secvență de cod)}.
        \end{itemize}
         
    \end{itemize}
    
    Deoarece soluțiile vor fi repartizate pentru corectare automat, arhiva va fi denumită, 
    \textbf{obligatoriu}, folosind ID-ul vostru de Moodle.
    De exemplu, daca ID-ul vostru este "ion.popescu", arhiva \textbf{trebuie} să se numească "ion.popescu.zip"

%  Puteți sa verificați \textbf{un exemplu} de arhivă pentru etapa 2 \%href{https://github.com/AAResources/HomeworkAssignment/tree/master/Example}{{\color{blue}aici}}.

    \item \textbf{Etapa 3}
    
    Veți încărca pe Moodle o arhivă care va conține documentul final în format .pdf. Documentul se va numi "\textbf{EtapaFinala.pdf}".

    Deoarece soluțiile vor fi repartizate pentru corectare automat, arhiva va fi denumită, 
    \textbf{obligatoriu}, folosind ID-ul vostru de Moodle. De exemplu, daca ID-ul vostru este "ion.popescu", arhiva \textbf{trebuie} să se numească "ion.popescu.zip"

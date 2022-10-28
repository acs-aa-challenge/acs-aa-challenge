---
layout: page
title: Compresia datelor
permalink: /9-compression/
---

# Descriere

Cerința este să comprimați, respectiv să decomprimați, **fără pierdere de informații**, un fișier.

# Precizări

- Trebuie să comparați **doi algoritmi** cunoscuți (e.g. Huffman coding, Lempel-Ziv-Welch (LSW), Arithmetic Coding, etc.) sau variante ale acestora.
- Pentru a evalua performanța algoritmilor trebuie să analizați cel puțin:
    - Resursele consumate în timpul procesului de comprimare/decomprimare.
    - Dimensiunea inițială a fișierului vs. dimensiunea fișierului comprimat.
    
# Structură recomandată teste

- **Format date intrare**

    - Fișierele pot fi de orice tip (text, audio, video, etc.), cu extensia originală.
    - Este foarte important să documentați caracteristicile acestora în Readme.
    - Puteți defini propriile reguli pentru prelucrarea acestora în fișierul Makefile.

- **Format date ieșire**

    - Fișierele comprimate echivalente testelor de intrare.
    - Atenție: trebuie să implementați și operația de decomprimare, care trebuie să se realizeze fără pierdere de informații. 
    - Practic, o execuție completă a programului de testare va consta în comprimarea fișierului inițial, decomprimarea într-un fișier temporar ("aux.in") și apoi compararea fișierului temporar cu cel inițial.

- **Restricții**

    - (Orientativ) Un fișier de intrare să nu depăsească 10 MB.
    

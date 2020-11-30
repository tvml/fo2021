---
layout: page
title: "Programmi Python"
#subheadline: "Informazioni"
teaser: ""
permalink: /codici/
header: no
---

* Una versione _in progress_ (largamente incompleta e da testare) del codice è accessibile su Github, [qui](https://github.com/tvml/python_fo)

* Un testo introduttivo a Python, liberamente disponibile su web, è il [seguente](https://greenteapress.com/wp/think-python/)

**Temi proposti per sviluppo di algoritmi** (si fa riferimento al codice messo a disposizione)

1. ~~Classe RegEx: funzione nfa(), derivazione ASFND da espressione regolare, con relativa implementazione delle funzioni kleene(), concat() e unite in NFA (per 2 persone)~~
2. Classe DFA: funzione regex(), derivazione espressione regolare da dfa,  mediante calcolo delle r_{ij}^k
3. Classe DFA: funzione regex(), derivazione espressione regolare da dfa,  mediante eliminazione degli stati
4. Classe DFA: funzione finite(), verifica che il linguaggio accettato è finito
5. Classe NPDA: funzioni empty_stack() e final_state(), derivazione NPDA equivalente che accetta per pila vuota
   e NPDA equivalente che accetta per stato finale
6. Classe CFG: funzioni to_gnf() derivazione grammatica in Greibach Normal Form e npda(), derivazione npda equivalente (per 2 persone)
7. Classe NPDA: funzione cfg() derivazione cfg equivalente
8. Classe RG: funzione lrg, derivazione grammatica regolare sinistra equivalente e 
   Classe LRG: funzione rg, derivazione grammatica regolare (destra) equivalente
9. Classe DFA: funzione reverse(), derivazione dfa che accetta il linguaggio delle stringhe rovesciate
   Classe CFG: funzione reverse(), derivazione cfg che genera il linguaggio delle stringhe rovesciate (2 persone)
10. Classe Reductions, funzione pcp_to_ambiguos_cfg(), implementazione della riduzione da PCP a verifica ambiguità di cfg
11. Classe LL1_parser, funzione derive_parse_table(), derivazione tabella parsing predittivo LL(1) mediante calcolo funzioni FIRST e FOLLOW (2 persone)


FrGramm - a lexical-functional grammar fragment of French https://github.com/lfg-french-grammar/frgramm

Author: Leonel F. de Alencar leonel.de.alencar@ufc.br

Copyright (C) 2016-2017 Leonel F. de Alencar

License: Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0). For more information, visit https://creativecommons.org/licenses/by-nc-sa/4.0/

FrGramm is a computational grammar fragment of French in the LFG formalism. It is implemented in the Xerox Linguistic Environment - XLE. To compile a parser from the grammar and parse sentences in French, you first need XLE:

http://www2.parc.com/isl/groups/nltt/xle/

You also need XFST to compile the source files of the basic tokenizer and the basic morphological analizer into finite-state transducers:

http://web.stanford.edu/~laurik/fsmbook/home.html

You can download the source files of both transducers from here:

https://github.com/lfg-french-grammar/lesson6

https://github.com/lfg-french-grammar/lesson7

The finite-state transducers must be compiled with XFST in the operating system where you are running XLE. Edit the respective path in the morphology.lfg file to point to the location of each transducer file in your system.

FrGramm is a significantly improved version of the grammar fragment from chapter 8 of the following book:

Schwarze, Christoph & Alencar, Leonel F. de. Lexikalisch-funktionale Grammatik: Eine Einführung am Beispiel des Französischen mit computerlinguistischer Implementierung [Lexical-Functional Grammar: A French-based Introduction with Computational Implementation]. Tübingen: Stauffenburg, 2016. X, 271 pp. Stauffenburg Einführungen, 30. ISBN 978-3-95809-411-6.

For more information on this book, visit

http://lfg-book.blogspot.com.br/2016/01/new-lfg-books-abstract.html 
http://linguistlist.org/issues/27/27-761.html

If you publish work that uses FrGramm, please cite the following paper, which was published bilingually in both English and Portuguese:

ENGLISH VERSION OF THE PAPER

APA style

Alencar, Leonel Figueiredo de (2017). A computational implementation of periphrastic verb constructions in French. Alfa, 61 (2), 437-466.

ABNT style

Alencar, Leonel Figueiredo de. A computational implementation of periphrastic verb constructions in French. Alfa, São Paulo, v. 61, n. 2, p. 437-466, 2017.

PORTUGUESE VERSION OF THE PAPER

APA style

Alencar, Leonel Figueiredo de (2017). Uma implementação computacional de construções verbais perifrásticas em francês. Alfa, 61 (2), 351-380.

ABNT style

Alencar, Leonel Figueiredo de. Uma implementação computacional de construções verbais perifrásticas em francês. Alfa, São Paulo, v. 61, n. 2, p. 351-380, 2017.


For bug reports, comments, and suggestions, please write to: leonel.de.alencar@ufc.br

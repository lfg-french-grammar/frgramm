# frgramm
FrGramm - a lexical-functional grammar fragment of French https://github.com/lfg-french-grammar/frgramm

Author: Leonel F. de Alencar leonel.de.alencar@ufc.br

Copyright (C) 2016-2017 Leonel F. de Alencar

License: Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0). For more information, visit https://creativecommons.org/licenses/by-nc-sa/4.0/

FrGramm is a computational grammar fragment of French in the LFG formalism. It is implemented in the Xerox Linguistic Environment - XLE. To compile a parser from the grammar and parse sentences in French, you first need XLE: 

http://www2.parc.com/isl/groups/nltt/xle/

You also need XFST to compile the source files of the basic tokenizer and the basic morphological analizer into finite-state transducers:

http://web.stanford.edu/~laurik/fsmbook/home.html

You can download the source files of both transducers from here:

https://github.com/lfg-french-grammar/book/chapter6
https://github.com/lfg-french-grammar/book/chapter7

The finite-state transducers must be compiled with XFST in the operating system where you are running XLE. Edit the respective path in the morphology.lfg file to point to the location of each transducer file in your system.

FrGramm is a significantly improved version of the grammar fragment from chapter 8 of the following book:

Schwarze, Christoph & Alencar, Leonel F. de. Lexikalisch-funktionale Grammatik: Eine Einführung am Beispiel des Französischen mit computerlinguistischer Implementierung [Lexical-Functional Grammar: A French-based Introduction with Computational Implementation]. Tübingen: Stauffenburg, 2016. X, 271 pp. Stauffenburg Einführungen, 30. ISBN 978-3-95809-411-6.

For more information on this book, visit

http://lfg-book.blogspot.com.br/2016/01/new-lfg-books-abstract.html 
http://linguistlist.org/issues/27/27-761.html

If you publish work that uses FrGramm, please cite the following paper:

Alencar, Leonel Figueiredo de (2017). A computational implementation of periphrastic verb constructions in French. Alfa, Rev. Linguíst. (São José Rio Preto), 61. To appear. http://www.scielo.br/scielo.php?script=sci_serial&pid=1981-5794&lng=en&nrm=iso

For bug reports, comments, and suggestions, please write to: leonel.de.alencar@ufc.br

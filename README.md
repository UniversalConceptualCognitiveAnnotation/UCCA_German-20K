UCCA-Annotated German Corpus
============================
Version 1.1 (May 21, 2020)
----------------------------------

This bundle contains 248 passages annotated according to the foundational layer of UCCA.
The total number of tokens in this corpus is 88716.


Corpus:
-------
The German corpus used here is the book
[Zwanzigtausend Meilen unter'm Meer](http://www.gasl.org/refbib/Verne__20000_Meilen.pdf)
(Vingt Mille Lieues Sous les Mers / Twenty Thousand Leagues Under the Sea),
a classic science fiction novel written in French by Jules Verne (1828--1905),
and first published in 1870.


Format and Source Code:
----------------------

Information about the format of the xml files and source code for reading and manipulating them are
available at https://universalconceptualcognitiveannotation.github.io

Known Issues:
-------------
Sentence 25515002 is [dropped](.travis.yml) when splitting to sentences. It is
the third sentence in passage [25515](xml/25515.xml) ("Darauf begann er seine
Erklärung folgendermaßen: ..."), and it has 386 tokens. It comprises several
sentences, but since they are all inside a quote which is a Participant in a
top scene, they are not split by the [sentence-splitting
script](https://github.com/danielhers/ucca/blob/master/scripts/standard_to_sentences.py)
(since it only splits on top scenes).


Licensing:
----------

The UCCA annotation is distributed under the 
"Attribution-ShareAlike 3.0 Unported" license (http://creativecommons.org/licenses/by-sa/3.0/).
Please follow the link for exact details.

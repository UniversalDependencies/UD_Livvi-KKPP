# Summary

UD Livvi-KKPP is a manually annotated new corpus of Livvi-Karelian made directly
in the Universal dependencies annotation scheme. The data is collected from
[VepKar corpora](http://dictorpus.krc.karelia.ru/en/corpus/text) and consists of
mostly modern news texts but also some stories and educational texts.


# Introduction

UD Karelian-KKPP is a manually annotated new corpus of Livvi-Karelian made in
Universal dependencies annotation scheme. The data is collected from
[VepKar corpora](http://dictorpus.krc.karelia.ru/en/corpus/text) and consists of
mostly modern news texts but also some stories and educational texts. We have
based many decisions in the dependency annotations on pre-existing
Finnish treebanks. The morphological annotations and grammar are based on the
refered books (Markianova, Ahtia) and the [Karelian
dictionary](http://kaino.kotus.fi/cgi-bin/kks/karjala.cgi), with necessary
orthographical modernisations.


# Acknowledgments

The Livvi (Olonets-Karelian) transducer used in the automated annotation was
originally built with funding from Kone Foundation «Language Programme» in
Creation of Morphological Parsers for Minority Finno-Ugrian Languages. Rueter,
J., Salo, M., Rantakaulio, T., Kuprina, J., Blumberga, R. & Soosaar, S.
(01/01/2013–31/12/2014), Where Timo Rantakaulio and Jelena Ruppijeva both worked
with description and evaluation.  Jelena Ruppijeva translated 19 sentences from
the Finnish text in
[http://ilazki.thinkgeek.co.uk/brat/#/uralic/fin](http://ilazki.thinkgeek.co.uk/brat/#/uralic/fin),
these can be found in the training set.

# References

* Markianova, Ludmila. [Karjalan
  kielioppi](https://opastajat.net/opastus/opastus.html), Periodika, (2002).
* Ahtia, Edvard Vilhelm. *Karjalan kielioppi.* Karjalan Kansalaisseura, (1938).
* [Karjalan kielen
   verkkosanakirja](http://kaino.kotus.fi/cgi-bin/kks/kks_etusivu.cgi)
* (citation)
The construction of the Finite-state description is mentioned but not documented in:

```
@article{2a8a012a1cc640db9ec0e4466f9d3e65,
title = "The Livonian-Estonian-Latvian Dictionary as a threshold to the era of
language technological applications",
abstract = "This article outlines the multiple use of electronic source
materials from the Livonian-Estonian-Latvian Dictionary of 2012 in a “Kone
Foundation” funded project for developing finite-state morphological parsers. It
provides an introduction to the project, the language-independent Giellatekno
infrastructure at Troms{\o}, Norway, and the materials utilized in the
electronic manuscript of the dictionary. The introduction is followed by an
extensive description of what has been developed on the Giellatekno
infrastructure with explicit indications of where parallel projects might be
initiated.",
keywords = "6121 Languages, Livonian, Uralic Languages, Kone Language Programme,
open-source, language-independent infrastructure, HFST, Giellatekno,
morphological parser, spellcheckers, morphology-savvy web dictionary,
intelligent computer-assisted language learning",
author = "Jack Rueter",
note = "ESUKA – JEFUL 2013, 5–1: 253–261 Volume: Proceeding volume:",
year = "2014",
doi = "10.12697/jeful.2014.5.1.14",
language = "English",
volume = "5",
pages = "251–259",
journal = "Journal of Estonian and Finno-Ugric Linguistics",
issn = "1736-8987",
publisher = "University of Tartu",
number = "1",

}
```

# Cite as

If you use the treebank, please cite the UDW 2019 paper:

```
@inproceedings{pirinen2019building,
  title={Building minority dependency treebanks, dictionaries and computational grammars at the same time—an experiment in Karelian treebanking},
  author={Pirinen, Tommi A},
  booktitle={Proceedings of the Third Workshop on Universal Dependencies (UDW, SyntaxFest 2019)},
  pages={132--136},
  year={2019}
}
```


# Changelog

* 2019-11-15 v2.5
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.5
License: CC BY-SA 4.0
Includes text: yes
Genre: nonfiction news web
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Pirinen, Tommi A
Contributing: elsewhere
Contact: tommi.antero.pirinen@uni-hamburg.de
===============================================================================
</pre>

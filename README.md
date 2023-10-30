# Gagauz-Turkish Morphological Analyzer: A Proof of Concept

Welcome to our repository dedicated to the morphological analysis of the Gagauz Turkish language. This project serves as an initial demonstration of the capabilities and structure of the analyzer.  Inspired by the design from an existing [GitHub repository](https://fomafst.github.io/morphtut.html) that offers a straightforward morphological analyzer for English, we've crafted this project to provide insights into the linguistic intricacies of Gagauz Turkish.

For extracting rules and lexicon we used the [_Finite-state morphological analysis for Gagauz_ paper](http://openaccess.altinbas.edu.tr/xmlui/handle/20.500.12939/1170) and a grammar book. 

[_Özkan, N. (1996). Gagavuz Türkçesi grameri: giriş, ses bilgisi, şekil bilgisi, cümle, sözlük, metin örnekleri. (No Title)._]

The analyzer is structured into two main components:

* **gagauz.lexc**: This file encompasses the lexicon and morphotactics.
* **gagauz.foma**: This file is dedicated to the phonological, morphophonological, and orthographic aspects.

To enhance the usability and exploration of our project for fellow researchers, we've included an extras section. Here's what you'll find inside:
This folder includes four files 
* **verbs.lexc**: A comprehensive lexicon of verbs.
* **nouns.lexc**: A lexicon detailing nouns.
* **rules.txt**: This file captures our various attempts at alternation rules, both successful and experimental.
* **Numerals.lexc**: A lexicon focused on numerals.

## About the Lexicon
* Includes the modeled facts for Verbs, Nouns, Numerals
* Since it is proof of concept, this lexicon is not fully comprehended, and not all possible facts are included.

## About the foma script
* Includes the modeled facts for the alternation rules component and the full grammar.
* Like the Lexicon part, this script is not fully comprehended, and not all possible facts are included.
* Full stack is saved in the **gagauz.bin** file.


We invite researchers and enthusiasts to delve into our work, provide feedback, and collaborate for further refinements.

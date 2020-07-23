# webscrapper_folha
Simple and personal python web scraper built as an evaluation method for "ILC - Introdução à Linduagem Computacional" (Introduction to Computational Linguistics) class at UFABC - Universidade Federal do ABC.

The scraper was built to make a robust corpus for further textual analysis. It is built and tested to be used under a very specific set of conditions, and only works at folha.com.br, as the needs for the project.

The corpora consists of texts about Soccer World Cup from two distinct years, into a 1 month range around the '94 and '14 World Cup opening dates, containing the words "Copa do Mundo" and also, with the '94 text search options including "printed version".

# Script usage is not meant to bypass the subscription system.

Code is still open to otimizations and shortenings.


Usage:
1st block: imports;

2nd block: first search page (must be in "Edição Impressa") and search result count (reference to calculate amount of pages to be swept);

3rd block: saves all page content and all page titles in lists;

4th block: create files for every text in the input directory (both single files and a stacked version);

#TO DO:
Refactor
Add NLP files

# RUAN FERNANDES, Matheus Costa, Vitor Miguel. Aug/19.

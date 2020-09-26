# webscraper-folha
* Python web scraper, part of a Natural Language Processing (NLP) project, consisting of a linguistic study between two corporas. Both corporas were built with articles scraped from "Folha de São Paulo", ranging 1 month around the opening and with 20 years of difference between each corpora. 
* The project was developed as part of the evaluation method for "ILC - Introdução à Linguagem Computacional" (Introduction to Computational Linguistics), at UFABC - Universidade Federal do ABC.

* The scraper was built to make a robust corpus for further textual analysis. It is built and tested to be used under a very specific set of conditions, and only works at folha.com.br, as the needs for the project.

* The corpora consists of texts about Soccer World Cup from two distinct years, into a 1 month range around the '94 and '14 World Cup opening dates, containing the words "Copa do Mundo" and also, with the '94 text search options including "printed version".


# IMPORTANT NOTE:
      
Script is not meant to be used in order to bypass the subscription system. 

During the development process, the group had an account with a recurring payment in order to have full access to the website.




# Content (to be updated):
    
- 1st cell: imports;

- 2nd cell: first search page (must be in "Edição Impressa") and search result count (reference to calculate amount of pages to be swept);

- 3rd cell: save all page content and all page titles in separated lists;

- 4th cell: create files for every saved text in the input directory (both single files and a stacked version);


# TO DO:
- [ ] Better README.md
- [ ] Refactor;
- [ ] Add NLP processing files and bring results;

__________

<h2> RUAN FERNANDES, Matheus Costa, Vitor Miguel. UFABC, Aug/19. </h2>

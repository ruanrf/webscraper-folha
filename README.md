# webscrapper-folha
* Simple and personal python web scraper built as an evaluation method for "ILC - Introdução à Linduagem Computacional" (Introduction to Computational Linguistics) class at UFABC - Universidade Federal do ABC.

* The scraper was built to make a robust corpus for further textual analysis. It is built and tested to be used under a very specific set of conditions, and only works at folha.com.br, as the needs for the project.

* The corpora consists of texts about Soccer World Cup from two distinct years, into a 1 month range around the '94 and '14 World Cup opening dates, containing the words "Copa do Mundo" and also, with the '94 text search options including "printed version".


# IMPORTANT NOTE:
      
Script usage is not meant to bypass the subscription system. 

During the development process, we had an account with a recurring payment in order to have full access to the website.




# Content:
    
- 1st cell: imports;

- 2nd cell: first search page (must be in "Edição Impressa") and search result count (reference to calculate amount of pages to be swept);

- 3rd cell: save all page content and all page titles in separated lists;

- 4th cell: create files for every saved text in the input directory (both single files and a stacked version);


# TO DO:
    
- [ ] Refactor;
- [ ] Add NLP processing;

__________

> RUAN FERNANDES, Matheus Costa, Vitor Miguel. Aug/19.

# webscrapper_folha
Simple personal python web scraper, which was used to build a text corpus for part of a university project in Introduction to Computational Linguistics (ILC). 
Only works in its current stage at folha.com.br.

The script use is not intended for bypassing the subscription system (only logged subscribers may read news).

Code is still open to otimizations and shortenings.

Usage:
1st block: imports
2nd block: first search page (must be in "Edição Impressa") and search result count (reference to calculate amount of pages to be swept).
3rd block: saves all page content and all page titles in lists.
4th block: create files for every text in the input directory (both single files and a stacked version).

# RUAN FERNANDES, Matheus Costa, Vitor Miguel. Aug/19.

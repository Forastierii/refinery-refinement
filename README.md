# PETR Refining Business Review on Tableau
The PETR Refining Business is evaluating its resources and wants a new strategy given that COVID stroke hard its businesses. We will use Python, Postgre and Tableau in order to import, treat, store and use the data to visualize trends and propose ideas for the refinery company we have.

## Source

For this work we had to extract information from different sources:

- ¹Refineries around the world: Wikipedia was webscrapped in order to get data on name of refinery, country, status of refinery, production (nominal).

- Refineries in Brazil and its state: Wikipedia was used as well, through webscrapping.

- COVID data: the API elaborated by Oxford team on the Policy Tracker. The API can be accessed through the links below and information/documentation is provided on GitHub:
https://github.com/OxCGRT/covid-policy-tracker
https://www.bsg.ox.ac.uk/research/research-projects/coronavirus-government-response-tracker

- ISO Country Codes: in order to our databases use the same coding system for countries, the table was uploaded through a CSV provided by an user from GitHub. It can be downloaded below:
https://gist.github.com/cpl/3dc2d19137588d9ae202d67233715478#file-countries_codes_and_coordinates-csv

- ²Refinery Output for brazilian refineries and fuel sales throughout Brazil are part of the program "Dados Abertos" from the brazilian government and can be obtained in the form of CSVs provided by ANP (Agência Nacional do Petróleo):
https://www.gov.br/anp/pt-br/centrais-de-conteudo/dados-abertos/anuario-estatistico-2020-dados-abertos#secao4

- Information on Worlds reserves of oil, energy matrix and related information can be retrieved from the comprehensive study done by BP:
https://www.bp.com/en/global/corporate/energy-economics/statistical-review-of-world-energy/downloads.html

1. List of world refineries form Wikipedia is not complete but it didn't have an effect on the overall analysis of the brazilian market.
2. The Diesel data are missing, ANP hasn't updated it completely for 2020.

## What are we aiming at

- What is our business?
- How is our supply going?
- What are our operations and where they are?
- What is the impact of COVID to our business?
- Where should we go now that we know the data?

## Aknowledgements

- Thanks to my Ironhack bootcamp colleagues who helped me get through the nasty bits of this project.

#  São Paulo State Hospital Registry of Cancer Database

The **Hospital Registry of Cancer** ([RHC](http://www.fosp.saude.sp.gov.br/publicacoes/acessobancodados)) is formed from data generated by hospital institutions in the State of São Paulo (Brazil) being coordinated by the [Fundação Oncocentro de São Paulo](http://www.fosp.saude.sp.gov.br/) (FOSP). The dataset is well documented, but this is only available in Portuguese.

The RHC:
* started its activities on 01/01/2000;
* has quarterly update;
* had their records anonymized;
* is formed by **analytical cases** (those who arrived at the institution without treatment, diagnosed or not);

RHC objectives: 
* know and improve the care provided to cancer patients during all stages of treatment;
* expand access to the state base and offer the possibility of performing specific tabulations and analyzes.

Pediatric tumors differ in location and morphology to tumors in adults and can be analyzed according to the International Classification of Cancer in Childhood (CICI), which defines the largest diagnostic groups.

The above information was adapted from the FOSP.

This notebook presents an exploratory data analysis (EDA) of the mentioned dataset and will include soon a data cleaning section intended to make the dataset more machine learnable.

I started this joint project at [Information Technology Center Renato Archer](https://www.cti.gov.br/). 

Team members:
* [Dr. Mariângela Dametto](https://www.linkedin.com/in/mariangela-dametto-16368644/)
* [Dr. Rodrigo Bonacin](https://www.linkedin.com/in/rodrigobonacin/)
* [Dr. Sergio M. Vechi](www.linkedin.com/in/sergiovechi)

Libraries used in this project:
* `numpy`
* `pandas`
* `matplotlib`
* `missingno`
* `simpledbf`
* `datetime`

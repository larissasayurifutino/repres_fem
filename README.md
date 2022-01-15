# repres_fem

## Main aim

This project aims to:

1. recognize person entities in journalists texts from [Folha](https://www1.folha.uol.com.br) website, 
2. to classify these entitites by gender and 
3. to quantify the percentage of quotes that were given by women by journalist and editorial branch (next steps).


## How to use it

### To get and process data

If you want to scrap news texts run: 01_webscrap_newspage.ipynb.

In case you have a JSON file with thse data run: 02_clean_data.ipynb

### To recognize Person entities and to assign each of them to a gender

Run: 03_entity_recog.ipynb

## Data

* The entity recognition step uses a trained model in Portuguese available at *spacy* library.


* The gender recognition step uses data from brazilian names available at: [https://brasil.io/dataset/genero-nomes/nomes/](https://brasil.io/dataset/genero-nomes/nomes/).


## Python Libraries

* requests

* lxml.html

* re

* json

* pandas

* spacy

* itertools

* numpy

## Remarks

This project was developed in Google colab and hence the code asks for Google Drive access.

## Last update

January 14, 2022


## Author

Larissa Sayuri Futino Castro dos Santos

## Acknowledment

Many thanks to [@cuducos](https://github.com/cuducos) for the assistance.

Also, many thanks to [@rhhernandes](https://github.com/rhhernandes) who shares his knowledge, dream and data for this project.

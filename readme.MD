# Weapons in Brazil

Data cleaning and analysis from the National Weapons System in Brazil (SINARM).

# Source
| Folder         | Request ID                                                                                                            | Year's range | Format | Publication date |
|----------------|-----------------------------------------------------------------------------------------------------------------------|--------------|--------|------------------|
| timeseries_csv | [08198006680202150](http://www.consultaesic.cgu.gov.br/busca/dados/Lists/Pedido/Item/displayifs.aspx?ID=1530523)      | 2009-2020    | CSV    | 03/2021          |
| timeseries_pdf | [08198032105202021](www.consultaesic.cgu.gov.br/busca/dados/Lists/Pedido/Item/displayifs.aspx?ID=1415871)             | 2009-2019    | PDF    | 10/2020          |
| y2021          | [0881_08198021419202180](http://www.consultaesic.cgu.gov.br/busca/dados/Lists/Pedido/Item/displayifs.aspx?ID=1562289) | 2021         | CSV    | 07/2021          |

# Notebooks

## cleaning.ipynb

Notebook to clean our time series and produce `time_series.csv`.

## br_queries.ipynb

National queries. It creates `total.csv`.

# Datasets

## time_series.csv

Dataset from 2009 to 2021 created with `cleaning.ipynb`

## total.csv

New licenses by category and year created by `queries.ipynb`.

## 2021_2020_agg.csv 

Data from 2021 and 2002. **Edited manually**.

# References

http://soudapaz.org/noticias/o-globo-exercito-ignora-norma-e-nao-integra-sistema-de-armas-ao-da-policia-federal/

https://www.gov.br/mj/pt-br/acesso-a-informacao/atuacao-internacional/legislacao-traduzida/lei_n_10-826_de_22_de_dezembro_de_2003_eng-docx.pdf#page=3

# Resources

https://www.tablesgenerator.com/markdown_tables

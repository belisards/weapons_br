# 💥 🇧🇷 Weapons licenses in Brazil

Data cleaning and analysis from the National Weapons System in Brazil (SINARM). All files were provided by Federal Police via LAI (like FOIA) requests. 

# 📁 Directories

| Directory         | Comment             | Request ID                                                                                                            | Year's range | Format | Publication date |
|----------------|---------------------|-----------------------------------------------------------------------------------------------------------------------|--------------|--------|------------------|
| timeseries_csv | Main source         | [08198006680202150](http://www.consultaesic.cgu.gov.br/busca/dados/Lists/Pedido/Item/displayifs.aspx?ID=1530523)      | 2009-2020    | CSV    | 03/2021          |
| timeseries_pdf | TO DO: fact-checking | [08198032105202021](www.consultaesic.cgu.gov.br/busca/dados/Lists/Pedido/Item/displayifs.aspx?ID=1415871)             | 2009-2019    | PDF    | 10/2020          |
| y2021          | Most recent data    | [08198021419202180](http://www.consultaesic.cgu.gov.br/busca/dados/Lists/Pedido/Item/displayifs.aspx?ID=1562289) | 2021         | CSV    | 07/2021          |    |

# 📚 Notebooks

Jupyter notebooks using Python.

## cleaning.ipynb

Notebook to clean our time series and produce `time_series.csv`.

## br_queries.ipynb

National queries. It creates `total.csv`.

# 📝 Datasets

CSV files from this repository.

## time_series.csv

Dataset from 2009 to 2021 created by `cleaning.ipynb`. Each row is the total of new records per state, year and category.

## total.csv

New licenses by category and year intially produced by `queries.ipynb`. Other means "Loja de Arma" and "Outros Tipos". Governmental means "Loja de Arma"  and "Outros Tipos". **Edited manually**.

## 2021_2020_agg.csv 

Data from 2021 and 2002. **Edited manually**.

# ➕ References

[Military records not included](http://soudapaz.org/noticias/o-globo-exercito-ignora-norma-e-nao-integra-sistema-de-armas-ao-da-policia-federal/)

[SINARM legislation in english](https://www.gov.br/mj/pt-br/acesso-a-informacao/atuacao-internacional/legislacao-traduzida/lei_n_10-826_de_22_de_dezembro_de_2003_eng-docx.pdf#page=3)

[Policy changes in 2019](https://g1.globo.com/politica/noticia/2019/05/22/veja-o-que-muda-no-novo-decreto-para-a-posse-e-porte-de-armas-no-pais.ghtml)

[Policy changes in 2021](https://www.metropoles.com/brasil/governo-altera-decretos-e-amplia-facilidades-para-acessar-arma-de-fogo)

# 🛠️ Resources

- Python + Pandas
- [Markdown table generator](https://www.tablesgenerator.com/markdown_tables)

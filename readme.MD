# 💥 🇧🇷 Licenças de armas de no Brasil

Limpeza de dados e análise do Sistema Nacional de Armas (SINARM). Todo os dados foram fornecidos pela Polícia Federal via Lei de Acesso à Informação.

# 📁 Directories

| Diretório         | Comentário             | ID do pedido de LAI                                                                                                            | Período coberto | Formato | Data de publicação |
|----------------|---------------------|-----------------------------------------------------------------------------------------------------------------------|--------------|--------|------------------|
| timeseries_csv | Fonte principal         | [08198006680202150](http://www.consultaesic.cgu.gov.br/busca/dados/Lists/Pedido/Item/displayifs.aspx?ID=1530523)      | 1997-2020    | CSV    | 03/2021          |
| timeseries_pdf | Para fact-checking | [08198032105202021](www.consultaesic.cgu.gov.br/busca/dados/Lists/Pedido/Item/displayifs.aspx?ID=1415871)             | 2009-2019    | PDF    | 10/2020          |
| y2021          | Dados mais recentes    | 08198026615202141 | 2021         | CSV    | 08/2021          |    |

# 📚 Notebooks

Jupyter notebooks (Python).

## cleaning.ipynb

Jupyter notebook para limpar a série histórica e criar o `time_series.csv`. A equivalência entre as novas e antigas categorias precisa ser checada.

## br_queries.ipynb

Faz consultas nacionais. Cria o arquivo `total.csv`.

# 📝 Dados

Arquivos CSV criados pelos scripts.

## time_series.csv

Dataset de 2009 a 2021 criado pelo `cleaning.ipynb`. Cada linha é o total de novos registros por estado, ano e categoria.

## total.csv

Novas licenças por categoria e ano, produzido pelo `queries.ipynb`.

# ➕ References

[Armas militares não inclusas](http://soudapaz.org/noticias/o-globo-exercito-ignora-norma-e-nao-integra-sistema-de-armas-ao-da-policia-federal/)

[Legislação do SINARM](https://www.gov.br/mj/pt-br/acesso-a-informacao/atuacao-internacional/legislacao-traduzida/lei_n_10-826_de_22_de_dezembro_de_2003_eng-docx.pdf#page=3)

[Mudanças regulatórias em 2019](https://g1.globo.com/politica/noticia/2019/05/22/veja-o-que-muda-no-novo-decreto-para-a-posse-e-porte-de-armas-no-pais.ghtml)

[Mudanças regulatórios em 2021](https://www.metropoles.com/brasil/governo-altera-decretos-e-amplia-facilidades-para-acessar-arma-de-fogo)

# 🛠️ Recursos

- Python
- Pandas 
- [Markdown table generator](https://www.tablesgenerator.com/markdown_tables)

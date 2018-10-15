# moradas_agueda_2018


O projecto do evento [dados abertos, em Águeda](http://sig.cm-agueda.pt/drupal/node/291)

## Ideia & Objetivos

+ Melhorar base de dados dos topónimos;
+ Implementar rotinas para visualização de erros;
+ Implementar rotinas para correção de erros;
+ Permitir a edição dos dados de forma simplificada (QGIS);
+ Normalização dos dados

## Equipa
+ Ana Rita Melo
+ Aurélio Pires
+ Hugo Santos
+ Pedro Pereira
+ Rui Cavaco

## [Apresentação](https://goo.gl/aHdza5)

## Resultados

O resultado do trabalho descrito na [apresentação](https://goo.gl/aHdza5) está disponível na forma de [ficheiro *backup*](enderecos_data.backup) de PostgreSQL. 

### Conteúdo do schema *data*

As tabelas incluidas neste backup:

+ 'estagio_sheets_moradas' - união das sheets de ficheiro de ODS de trabalho contendo moradas
+ 'insert_npol' - conversão de shapefile de número de edifício ("número de polícia")
+ 'rv_agueda2018' - conversão de shapefile de rede viária
+ 'toponimo' - ageregação de topónimos únicos
+ 'lugar' - agregação de lugares

A construção da tabela 'estagio_sheets_moradas' foi produzida usando este [Notebook Jupyter]("Importação sheets moradas.ipynb")

A construção das tabelas de agregação encontra-se descrita na [apresentação](https://goo.gl/aHdza5)

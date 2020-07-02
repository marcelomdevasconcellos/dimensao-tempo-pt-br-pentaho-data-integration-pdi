# README - Dimensão Tempo (PT-BR) Pentaho Data Integration #

Utilize este repositório para criar a dimensão tempo do seu projeto de ETL no Pentaho Data Integration (PDI) em Português-Brasil.

### Exemplo de execução no Mac OS X: ###

__Observação: Altere a pasta caso necessário.__

`/Applications/pentaho/data-integration/kitchen.sh -param:DW_SERVER=localhost -param:DW_DATABASE=pentaho -param:DW_PORT=5432 -param:DW_USER=postgres -param:DW_PASS=postgres -file dim_tempo.kjb > dim_tempo.log`

### Exemplo de execução no Linux: ###

__Observação: Altere a pasta caso necessário.__

`/opt/pentaho/data-integration/kitchen.sh -param:DW_SERVER=localhost -param:DW_DATABASE=pentaho -param:DW_PORT=5432 -param:DW_USER=postgres -param:DW_PASS=postgres -file dim_tempo.kjb > dim_tempo.log`

### Testado em: ###

* PDI 8.3
* PDI 9.0

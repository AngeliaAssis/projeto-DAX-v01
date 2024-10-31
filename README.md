
# 📊 Modelagem de Dados com Fórmula DAX - Power BI

Projeto do desafio de modelagem dimensional utilizando fórmula DAX no Power BI - [DIO](https://www.dio.me/).


## Objetivo do projeto
1. Utilizar a tabela 'Financial Sample' do Power BI para realizar a modelagem de dados.

2. Criação do Star Schema com a geração da tabela 'fato' e tabelas 'dimensão' a partir de uma única tabela.

3. Utilizar fórmula DAX 'calendar' para criação da tabela dimensão 'data'.


## Etapas do projeto
1. Replicar o diagrama relacional no [SqlDBM](https://sqldbm.com/Home/).
2. Geração de SQL no SqlDBM para gerar o script de criação do banco de dados.
3. Criação do novo banco de dados MySQL na instância do Azure.
4. Criação das tabelas.
5. Conexão do banco de dados MySQL com o Power BI.
6. Fazer a modelagem dos dados no Power BI com o Power Query.
7. Criar o diagrama dimensional - star schema.


## Aplicações utilizadas
Power BI<br>
Power Query<br>
Fórmulas DAX<br>


## Fases da modelagem de dados
1. Verificar como o Power BI reconhece a modelagem e relacionamentos.

2. Fazer transformações no Power Query:

a. duplicação da tabela 'financial sample'.

b. renomeação as tabelas para fato e dimensão.

c. eliminação das colunas desnecessárias para cada tabela dimensão.

d. verificar se 'tipo de dado' está de acordo.

e. realização de agrupamentos.

f. criação das colunas 'índice'.

g. criação das colunas condicionais para gerar 'ID_Produto'.

h. remoção das linhas duplicadas.


3. Criação das tabela dimensão 'd_Nova_Data' utilizando a fórmula DAX função 'calendar'.


3. Criação das relações através do Power BI em 'gerenciar relações'. Modelagem dimensional em star schema concluída.

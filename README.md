
# 📊 Modelagem de Dados com Fórmula DAX - Power BI

Projeto do desafio de modelagem dimensional utilizando fórmula DAX no Power BI - [DIO](https://www.dio.me/).


## Objetivo do projeto
1. Utilizar a tabela 'Financial Sample' do Power BI para realizar a modelagem de dados.

2. Criação do Star Schema com a geração da tabela 'fato' e tabelas 'dimensão' a partir de uma única tabela.

3. Utilizar fórmula DAX 'calendar' para criação da tabela dimensão 'data'.


## Aplicações utilizadas
Power BI<br>
Power Query<br>
Fórmulas DAX<br>


## Fases da modelagem de dados
1. Verificar como o Power BI reconhece a modelagem e relacionamentos.

2. Fazer transformações no Power Query:

      a. duplicação da tabela 'financial sample'.<br>
      b. renomeação as tabelas para fato e dimensão.<br>
      c. eliminação das colunas desnecessárias para cada tabela dimensão.<br>
      d. verificar se 'tipo de dado' está de acordo.<br>
      e. realização de agrupamentos.<br>
      f. criação das colunas 'índice'.<br>
      g. criação das colunas condicionais para gerar 'ID_Produto'.<br>
      h. remoção das linhas duplicadas.<br>


3. Criação da tabela dimensão 'd_Nova_Data' utilizando a fórmula DAX função 'calendar'.


4. Criação das relações através do Power BI em 'gerenciar relações'. Modelagem dimensional em star schema concluída.

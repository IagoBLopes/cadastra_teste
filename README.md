# Teste de engenharia de dados, Cadastra

## Descricao sobre o teste:
Este desafio destaca a capacidade de criar uma solução completa, desde a coleta de dados por meio de uma API até o armazenamento eficiente desses dados em um banco de dados relacional.

## Tecnologias Utilizadas
- Python: Coleta e transformação de dados.
- BigQuery: Armazenamento de dados.
- Power BI: Visualização e análise de dados.

## Todos o processo necessário para criação: 

- Obter os dados da API de criptomoedas.
- Processar e transformar os dados.
- Armazenar os dados em um banco de dados.
- Criar visualizações no Power BI.

2. Coleta de Dados
Ferramenta usada: Python.
Acesse a API CoinCap (ou outra especificada) para obter os dados de criptomoedas.
Tecnologias e bibliotecas utilizadas:
requests para consumir a API.
pandas para manipulação de dados.
Tratamento de exceções para lidar com erros de conexão ou dados inconsistentes.

3. Aplicação da Metodologia Medalhão
Estruturei os dados em camadas:
Bronze: Dados brutos extraídos da API.
Silver: Dados tratados e normalizados.
Gold: Dados prontos para visualização e análise.

## Bronze:
![model](C:\Users\Iago_\Desktop\projetos_pessoais\cadastra_teste\src\bronze_assets.png)

## Silver:
![model](C:\Users\Iago_\Desktop\projetos_pessoais\cadastra_teste\src\silver_assets.png)

## Gold:
![model](C:\Users\Iago_\Desktop\projetos_pessoais\cadastra_teste\src\gold_assets.png)

4. Armazenamento dos Dados
Banco de Dados: BigQuery.
Configurei a conexão com o BigQuery para armazenar os dados.
Transformei os dados em tabelas otimizadas para consultas.
Ferramentas usadas:
Biblioteca google-cloud-bigquery para integração com Python.
SQL para consultas e validação dos dados armazenados.

5. Visualizações no Power BI
Importei os dados do BigQuery para o Power BI, e realizei a construção da visão com os principais KPIs pedidos no teste: 

## Préview dashboard:
![model][def]
[def]: C:\Users\Iago_\Desktop\projetos_pessoais\cadastra_teste\src\dashboard_vfinal.png
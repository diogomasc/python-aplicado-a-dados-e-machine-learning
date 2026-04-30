# Análise Exploratória da Flora Brasileira (2020)

Este diretório contém uma análise exploratória de dados (EDA) focada na biodiversidade botânica do Brasil, utilizando a base de espécies da Flora do Brasil. O objetivo prático é aplicar conhecimentos de manipulação de dados com Pandas e visualização com Matplotlib estudados no repositório.

## O que é analisado neste projeto?

- **Auditoria de Dados:** Verificação de formatação e valores nulos.
- **Limpeza e Agrupamentos:** Foco apenas em espécies com status taxonômico classificado como "NOME_ACEITO". Adicionalmente, verificamos quais são as 10 famílias botânicas mais diversas encontradas no Brasil.
- **Linha do Tempo (Visão Histórica):** Um gráfico interativo detalhando a frequência em que novas espécies de plantas foram descobertas e listadas a partir do ano de 1500.

## Como obter a Base de Dados

O arquivo original de dados (`taxon.txt`) não foi adicionado a este repositório via Git por conta de seu grande tamanho (aproximadamente 90 MB).

Para que o notebook `BrazilianFlora.ipynb` funcione adequadamente em sua máquina local, você deve baixar a base de dados manualmente:

1. Acesse o portal oficial de downloads do Jardim Botânico do Rio de Janeiro através deste link:
   [https://ipt.jbrj.gov.br/jbrj/resource?r=lista_especies_flora_brasil&v=393.408](https://ipt.jbrj.gov.br/jbrj/resource?r=lista_especies_flora_brasil&v=393.408)
2. Faça o download do arquivo Darwin Core Archive (DwC-A) ou do arquivo texto principal.
3. Extraia o conteúdo e mova o arquivo `taxon.txt` diretamente para o interior desta pasta (`BrazilianFlora2020/`).
4. Pronto! O Jupyter Notebook agora será capaz de ler o conjunto de dados.

### <h1 align="center"> Projeto de Extração, Tratamento, Análise dos Dados e Criação de Dashboard Interativo </h1>







 <br>

## Descrição do Projeto </h1>
Este projeto visa extrair, tratar e analisar dados para a criação de um banco de dados, bem como desenvolver um dashboard para uma análise gerencial das vendas efetuadas no marketplace ELO7. Além disso, a implementação do banco de dados proporcionará à empresa a oportunidade de utilizar os dados em suas campanhas de marketing, ampliando assim sua eficácia e alcance.


## Tecnologia
Os softwares utilizados neste projeto foram:

* Jupyter Anaconda
* Python version  3.9.13
* Power BI


## Serviço usado:
* Github


## Bibliotecas Python
* Pandas
* Selenium
* Regex
* Numpy


### 1 - Sobre o Script

  Utilizei a biblioteca Seleniumo para a extração e  Pandas para o tratamento dos dados. No script, criei três conjuntos de dados: um para informações do cliente, outro para informações dos pedidos e um terceiro para informações sobre os produtos vendidos. Esses três conjuntos podem ser vinculados pela coluna ID. O processo inicia com a extração dos dados, seguido pelo tratamento e, por fim, a exportação dos dados em formato XLSX (o código completo está disponível no repositório). Optei por destacar uma parte do código na imagem abaixo, onde utilizei um loop for para buscar todos os produtos comprados pelo cliente. Por meio desse código, os produtos são buscados sequencialmente até que a lista de produtos escolhidos pelo cliente seja completamente percorrida. Após a extração dos dados de todos os produtos comprados pelo cliente, o código prossegue com as etapas seguintes.

 ![Screenshot_4](https://github.com/bonfimdoprado/ELO7/assets/119675645/1b0520f1-bc8d-4ca2-948c-ac40212d222b)

 


### 2 - Criação de Planilhas para Armazenamento de Dados

  Os dados extraídos foram armazenados em três arquivos XLSX, os quais podem ser aproveitados em diversas estratégias de campanhas de marketing. Estes incluem o uso em campanhas de e-mail marketing, envio de mensagens pelo WhatsApp e elaboração de campanhas publicitárias baseadas no histórico de vendas.



### 3 - Dashboard Interativo

  Neste dashboard, é possível analisar uma série de métricas essenciais, como o faturamento líquido e bruto, a quantidade de vendas e pedidos, o ticket médio, entre outros indicadores relevantes. Além disso, é possível examinar detalhadamente os valores das taxas, incluindo comissões, taxas fixas e de parcelamento, oferecendo uma visão abrangente das despesas associadas às transações. O dashboard também permite uma análise detalhada do faturamento por produto e por estado, fornecendo insights valiosos para estratégias de precificação.
  Foram implementados diversos filtros no dashboard, proporcionando uma análise personalizada e detalhada. Por exemplo, o filtro por cliente possibilita a avaliação das vendas de cada cliente, permitindo a identificação de clientes recorrentes e a personalização das estratégias de engajamento. O filtro por pedido possibilita a análise do valor líquido de cada pedido, enquanto o filtro por produto e pedido permite a avaliação das taxas aplicadas, ajudando a garantir que os valores de venda estejam alinhados com as metas estabelecidas.
  Dada a complexidade das taxas presentes neste marketplace, é fundamental manter um controle rigoroso para evitar prejuízos. A análise detalhada das taxas pode revelar oportunidades para ajustes de preço. Estes são apenas alguns dos insights que podem ser obtidos por meio deste dashboard, que oferece a possibilidade de análise de uma ampla gama de métricas e variáveis relacionadas às vendas nos marketplaces.


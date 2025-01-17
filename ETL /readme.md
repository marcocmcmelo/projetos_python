# Projeto Final: Dashboard - Atendimento a Chamados

O objetivo deste projeto é desenvolver um Dashboard de Tecnologia que simula o atendimento a chamados, permitindo a análise de métricas importantes para a gestão de serviços. O projeto deve abordar os seguintes pontos:
Número total de chamados.
Chamados por categoria (Software, Hardware, Telefonia, Acessos etc.).
Chamados por nível de atendimento (N1, N2, N3 e N4).
Tempo de resposta para cada chamado.
Nível de satisfação dos atendimentos.

## Etapa 1: Armazenamento Inicial
O grupo deverá criar um bucket no Google Cloud Storage e armazenar a base de dados fornecida em uma pasta chamada "dados brutos". Esse bucket será a fonte inicial de armazenamento, garantindo a organização e acessibilidade dos dados originais.
Além disso, o grupo deverá criar uma instância de MySQL no Google Cloud SQL e transferir os dados para um banco de dados relacional. Esse banco será utilizado para explorar e manipular os dados de forma estruturada. É imprescindível que o grupo entregue, como parte do projeto, o Modelo Entidade-Relacionamento (MER) que represente a estrutura da base de dados armazenada no banco.

## Etapa 2: Processamento de Dados no Google Colab
Para esta etapa, o grupo deverá criar um notebook no Google Colab para realizar o processo de Extração, Transformação e Carga (ETL). A extração dos dados poderá ser feita diretamente do bucket no Google Cloud Storage, do banco relacional no Google Cloud SQL, ou utilizando ambos os métodos, demonstrando o conhecimento das ferramentas.
Durante o processo de transformação, é necessário que o grupo realize as manipulações adequadas nos dados, preparando-os para atender às perguntas do case. Isso pode incluir o tratamento de valores ausentes, categorização de chamados, cálculo de tempos médios de resposta, e consolidação de informações em tabelas estruturadas. É essencial que todos os códigos sejam bem documentados, com comentários claros explicando cada etapa do processo, para facilitar a avaliação.

## Etapa 3: Carregamento de Dados Tratados
Após concluir a transformação dos dados, o grupo deverá realizar o carregamento (Load) dos dados tratados em dois destinos: o Google BigQuery e o Google Cloud Storage.
Durante o carregamento, o grupo poderá criar novas tabelas e/ou colunas baseadas em análises e agregações realizadas anteriormente, como somatórios de chamados por categoria ou cálculo de métricas de tempo médio de resposta. Isso permitirá uma visualização mais direta e eficiente dos resultados na etapa seguinte.

## Etapa 4: Desenvolvimento do Dashboard
O grupo deverá fazer a conexão dos dados tratados com um visualizador de dados e criar o relatório final com os dashboards que respondam às perguntas de negócios estabelecidas. O grupo deverá usar o Power BI e, opcionalmente, poderá explorar ferramentas como Tableau e Looker Studio.

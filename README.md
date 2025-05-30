📊 Análise de Clientes Adimplentes e Inadimplentes
Este repositório contém um notebook Jupyter (Analise_de_Clientes.ipynb) que realiza uma análise exploratória de dados de clientes. O objetivo é entender as características dos clientes, identificar padrões e diferenciar entre clientes adimplentes e inadimplentes.

Descrição do Projeto

O notebook realiza as seguintes etapas:

1.Carregamento dos Dados: Importa os dados de um arquivo CSV chamado Dados_Clientes.csv.
2.Pré-processamento:
  Remove dados faltantes.
  Padroniza colunas monetárias (limite_credito e valor_transacoes_12m) para o formato float.
  Remove a coluna id, que não é relevante para a análise.

3.Análise Exploratória:
  Verifica a distribuição de clientes adimplentes e inadimplentes.
  Analisa colunas com formato "object" para entender as categorias presentes.
  Calcula estatísticas descritivas para variáveis numéricas e categóricas.
4.Visualização de Dados:
  Utiliza bibliotecas como matplotlib e seaborn para criar gráficos que ajudam a entender os dados.
  
Dados

O conjunto de dados contém informações sobre clientes, incluindo: 

  default: Indica se o cliente é adimplente (0) ou inadimplente (1).
  idade, sexo, dependentes, escolaridade, estado_civil, salario_anual, tipo_cartao: Características demográficas e socioeconômicas.
  meses_de_relacionamento, qtd_produtos, iteracoes_12m, meses_inativo_12m: Informações sobre o relacionamento com o cliente.
  limite_credito, valor_transacoes_12m, qtd_transacoes_12m: Dados financeiros.

Resultados Principais

  Distribuição de Clientes: 84.28% são adimplentes e 15.72% são inadimplentes.
  Padronização Monetária: Valores monetários foram convertidos para float para facilitar análises.
  Análise por Categoria: Foram identificadas as categorias mais frequentes em colunas como escolaridade, estado_civil e tipo_cartao.

Como Usar

1.Clone o repositório:
  bash
  git clone [URL_DO_REPOSITORIO]
  
2.Abra o notebook Analise_de_Clientes.ipynb no Jupyter Notebook ou Jupyter Lab.

3.Execute as células sequencialmente para reproduzir a análise.

Requisitos

Python 3.x
Bibliotecas Python:
pandas
matplotlib
seaborn

Autor
Paulo Augusto

Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.


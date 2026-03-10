# Challenge 2 Telecom X: Análise de Evasão de Clientes

Desenvolvimento de um pipeline completo de ETL (Extract, Transform, Load) e análise de dados de telecomunicações com Python e bibliotecas. Projeto desenvolvido no programa ONE (Oracle Next Education), uma parceria Oracle e Alura, com foco em habilidades avançadas de manipulação de dados JSON, limpeza e análise de Churn (Evasão de Clientes).

## O objetivo do desafio
Analisar a base de dados da empresa Telecom X para identificar os principais motivos de cancelamento de contratos e propor estratégias baseadas em dados para reduzir a taxa de evasão, que atualmente impacta a receita da operação.

## Etapas do Pipeline (ETL)
- Extração: Consumo de dados brutos em formato JSON via API.
- Transformação: Normalização de estruturas aninhadas, tradução de colunas, tratamento de valores nulos e conversão de tipos (strings para numéricos).
- Carga: Exportação dos dados limpos e tratados para um novo dataset otimizado em CSV.
- Análise Exploratória: Identificação de perfis de risco (Idosos) e tipos de contrato críticos.

## Métricas e Insights calculados
- Taxa Geral de Churn: Identificação de que 25,72% da base está em evasão.
- Churn por Tipo de Contrato: Contraste entre contratos mensais (alta evasão) vs. contratos bienais (alta retenção).
- Análise por Perfil Etário: Impacto adicional de evasão no público idoso.

# Tecnologias e bibliotecas usadas
- Python (Ambiente Google Colab)
- Pandas (Data Wrangling e Styler para tabelas executivas)
- Numpy (Processamento numérico)
- Seaborn e Matplotlib (Visualização de dados e densidade)
- Git e Github (Controle de versão)

# Habilidades praticadas
- Manipulação de JSON complexo via API com json_normalize.
- Criação de Tabelas Dinâmicas (Pivot Tables) para cruzamento de variáveis.
- Estilização de relatórios com Pandas Styler (gradientes de calor para risco).
- Interpretação de métricas de negócio (Churn e Retenção).

# Como executar o projeto
1. Faça o download ou clone deste repositório:
Bash
git clone https://github.com/vanrpontes/challenge2-telecom_x.git
Acesse o notebook principal na raiz do projeto.
2. Abra o arquivo no Google Colab.
3 Execute as células sequencialmente para observar o processo de limpeza e as visualizações geradas.

## Conclusões finais
O relatório estratégico com os gráficos, matrizes de risco e recomendações para a diretoria da Telecom X está disponível no link abaixo:

[Acessar Relatório Final (PDF)](https://github.com/vanrpontes/challenge3-telecom_x_parte2/blob/main/relatorio/Challenge-3_Telecom_X-Relatorio_Modelo_de_Previsao_de_Perdas_Financeiras.pdf)

Dados fornecidos pela Alura.
Desenvolvido por Vanclercio da Rocha Pontes.
Contador | Analista de Dados 

📍 Brasil

[LinkedIn](https://www.linkedin.com/in/vanrpontes/)

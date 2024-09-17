# Projeto_Programaria
# Análise de Diversidade 2022 - PrograMaria
Este repositório contém o projeto realizado durante o curso "Meus Primeiros Passos em Python" da PrograMaria. A análise incluiu limpeza de dados, detecção de outliers, criação de novas features e uma análise estatística detalhada, utilizando o Google Colab para desenvolvimento e o Looker Studio para o dashboard final.

## Visão Geral do Projeto
O objetivo deste projeto foi realizar uma análise descritiva e estatística dos dados contidos em duas planilhas (localizadas na pasta Data). O processo envolveu:

Tratamento de dados faltantes
Detecção e correção de outliers
Cálculo de correlações
Criação de novas colunas (features derivadas)
Consulta a um banco de dados SQLite para agregar informações de renda e educação por estado
Análise de diversidade sobre gênero, etnia, localização, escolaridade, senioridade e média salarial

### Ferramentas Utilizadas
Python: Linguagem de programação
Bibliotecas:
  pandas: Manipulação de dados
  numpy: Operações matemáticas e arrays
  matplotlib: Gráficos
  seaborn: Visualização estatística
  plotly: Visualização interativa
  scipy: Funções científicas e estatísticas
  sqlite3: Conexão com banco SQLite
Google Colab: Ambiente de desenvolvimento
Looker Studio: Construção do dashboard interativo

## Estrutura do Código
1- Carregamento e Exploração de Dados
    Leitura das planilhas com pandas
    Inspeção inicial dos dados
2- Tratamento de Dados Faltantes
    Preenchimento de valores faltantes com médias e valores padrão
3- Análise Estatística
    Cálculo de métricas como média, mediana e desvio padrão
    Intervalo de confiança para a média salarial
4- Detecção e Correção de Outliers
    Visualização de outliers com boxplots
    Correção de outliers salariais com base no desvio padrão
5- Feature Engineering
    Criação de novas colunas como "Nível" e "Geração"
6- Consulta SQL
    Conexão com banco SQLite e extração de dados agregados
7- Análise de Correlação
    Correlações entre variáveis contínuas e categóricas
8- Visualização de Dados
    Gráficos interativos e estatísticos com Plotly, seaborn e matplotlib

## Dados Analisados
Os dados analisados incluem:

Gênero
Etnia
Pessoas com Deficiência (PCDs)
Localização (dentro ou fora de SP)
Faixa etária
Escolaridade
Senioridade (Pleno, Júnior, Sênior, Pessoa Gestora)
Média salarial por gênero e etnia

## Principais Resultados
### Gênero x Etnia
  A maioria dos respondentes foi de pessoas não brancas (1.527 indivíduos).
  A proporção entre homens e mulheres variou conforme a etnia e localização.
### Distribuição Geográfica
  A maior parte dos respondentes vive fora de São Paulo (2.413 indivíduos).
### Escolaridade e Salário
A correlação entre escolaridade, etnia e senioridade em relação à média salarial revelou disparidades significativas entre gêneros e etnias.
### Dashboard e Notebook
  https://lookerstudio.google.com/s/sppSaFBU8ZU
  https://colab.research.google.com/drive/1ZkMGH8bzw455R97c6xhahDTqEWUrbQRR?usp=sharing
  https://colab.research.google.com/drive/1gMPplc3tYNWiVYR1RHOtaKtVlYuItYv6?usp=sharing
  

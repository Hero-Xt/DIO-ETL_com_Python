# DIO - ETL com Python

**Valorant Champions Analytics: Além dos Números**

- O projeto envolve análises e estatísticas dos campeões do torneio Valorant Champions2022, explorando muito mais do que simples números, fazendo visualizações gráficas que destacam alguns aspectos desse torneio único.

**No centro do jogo Valorant, a combinação entre como você joga e planeja se mistura para formar um lugar onde jogadores e times tentam vencer no campo de batalha.**


## 🚀 Começando ##
## **E**xtract

Extraindo dados de a partir do arquivo CSV "valorant_champions_istanbul". Atribuindo colunas específicas do conjunto de dados a variáveis separadas:
- Player: Nomes dos jogadores
- Team: Nomes dos times dos jogadores
- Nationality: Nacionalidade dos jogadores
- K/D: Relação entre abates e mortes dos jogadores
- Rank: Classificação dos jogadores

## **T**ransform

Realizar Transformações nos Dados
- Ações Realizadas: Análise e transformação dos dados extraídos do arquivo CSV
- Objetivo: Preparar os dados para criação de gráficos informativos.

1. Agrupamento e Cálculo de Médias por Equipe/Time e Região/Nacionalidade
   - Dados Agrupados por Equipe/Time e Região/Nacionalidade
   - Cálculo das Médias de K/D Ratio e Rank
   - Impressão dos resultados
2. Ordenação dos Times e Regiões:
   - Ordenação Baseada em K/D ou Rank (Opção Selecionada)
   - Resultados Ordenados para Avaliação
   - Impressão dos resultados
3. Análise de Correlação entre Métricas Selecionadas:
   - Seleção de Colunas para Análise de Correlação
   - Cálculo da Matriz de Correlação entre as Métricas
   - Impressão dos resultados

## **L**oad

Carregamento do processamento e análise dos dados coletados. Utilizandos gráficos para visualizar informações cruciais que ajudaram a compreender melhor o desempenho dos jogadores, times e nacionalidades no torneio Valorant Champions Istanbul.
- Visualizações gráficas para apresentar de maneira clara e concisa as tendências, relações e padrões contidos nos dados agregados. 
- Criação de gráficos informativos, destacando os elementos importantes que surgem dos dados agrupados, fornecendo uma visão panorâmica e detalhada das diferentes análises. 
- Salvando o DataFrame combinado em um único arquivo CSV

## Itens Utilizados ##
- Bibliotecas: Pandas, Seaborn e matplotlib 
- Arquivo CSV: o pandas, seaborn e matplotlib são bibliotecas,

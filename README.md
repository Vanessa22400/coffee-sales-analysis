# Coffee Sales Analysis: Exploratory Data Analysis (EDA)

Este é um projeto de análise de vendas de uma cafeteria, com foco em entender o comportamento de consumo de diferentes tipos de café, identificar padrões relevantes e explorar insights que possam apoiar decisões estratégicas de marketing e vendas.

Foi um dos meus primeiros projetos autorais em Data Science, criado para praticar análise exploratória, visualização de dados e organização de um fluxo analítico completo.

### Objetivos
Ao longo da análise, busco responder perguntas como:

- Quais são os cafés mais vendidos em termos de quantidade e faturamento?
- Como as vendas variam ao longo do tempo (diariamente, mensalmente)?
- Existe padrão de sazonalidade nas vendas?
- Como o preço médio varia entre os diferentes tipos de café?
- Há dias da semana melhores para vendas?
- Quais oportunidades estratégicas podem ser extraídas desses padrões?

### Sobre o Dataset
O dataset contém registros de vendas entre **março/2024 e março/2025**.
As principais colunas são:

- `date` e `datetime`: Data e hora da venda
- `cash_type`: forma de pagamento 
- `money`: valor da venda
- `coffee_name`: tipo de café vendido


### Preparação do Dataset

As etapas de preparação envolveram:
1. Conversão das colunas de datas para formato datetime.
2. Criação de colunas auxiliares:
* dia da semana
* mês
3. Verificação de valores ausentes.
4. Conferência de tipos e estrutura da tabela.





Estrutura do Projeto
1. Carregar e explorar os dados
2. Limpar e preparar os dados para análise
3. Análise exploratória focada nos produtos
4. Análise temporal (diária, semanal e mensal)
5. Visualização dos dados e extração de insights
6. Conclusões e recomendações

### Conclusões

quais cafés performam melhor

tendência de crescimento ou queda

horário ou mês com maior volume

preferência por método de pagamento

### Status

Concluído, mas aberto para melhorias futuras.

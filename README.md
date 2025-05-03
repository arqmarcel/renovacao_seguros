A SeguraAí é uma fintech de venda de seguros para pessoas físicas. Empresas de Seguros, assim como qualquer outra, dependem da recorrência de gastos dos seus clientes. Em Seguros, essa recorrência vem da Renovação das apólices de Seguros dos clientes. Para entender o que está causando uma queda dessas renovações ao longo do tempo, a área de operações pediu um projeto para a área de Data Analytics para entender e classificar o cliente com risco de não renovar sua apólice no próximo ano.

Para isso, a área de Operações passou uma base de cerca de 23 mil registros de clientes com suas respectivas informações de cadastro e suas decisões de renovação ou não renovação.

Você foi convidado para atuar neste projeto, e como um bom analista de dados, é importante que você organize e estruture todas as etapas do trabalho.



Com base nessas informações, pede-se:

 

 1) Quais fatores de risco estão associados com a NÃO renovação de seguros?

 

 2) Quais os possíveis planos de ação que a empresa de seguros pode fazer para diminuir esse problema?


ANÁLISE FINAL DOS DADOS:

## 📊 Matriz Valor vs Risco de Cancelamento

Esta matriz cruza o LTV médio (Lifetime Value) e a taxa de churn (cancelamento) dos perfis de risco, permitindo classificar os clientes em quatro segmentos estratégicos:

| Segmento                | Estratégia                                 |
|------------------------|--------------------------------------------|
|   Proteger            | Fidelizar clientes valiosos e estáveis     |
|   Manter com Urgência | Reter urgentemente clientes valiosos com alto risco de saída |
|   Potencial de Crescimento | Investir em desenvolvimento de relacionamento   |
|   Reavaliar           | Clientes de baixo valor e alto churn – avaliar prioridade |

O arquivo [`matriz_valor_risco.csv`](./matriz_valor_risco.csv) contém o resumo estatístico por perfil.

O gráfico correspondente está no notebook de análise exploratória.

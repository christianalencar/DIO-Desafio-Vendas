## [DIO] [Desafio]

## **Projeto de Modelagem e Transformação de Dados com DAX no Power BI**

OBS: Primeira análise de tabela de vendas e utilização de fórmulas DAX

**Descrição do Desafio de Projeto**
Utilizaremos a tabela única de Financial Sample para criar as tabelas dimensão e fato do nosso modelo baseado em star schema.


## Estrutura do Projeto

- **Financials_origem** (Modo oculto - backup)
  
- **D_Produtos**:
  - ID_produto
  - Produto
  - Média de Unidades Vendidas
  - Média do Valor de Vendas
  - Mediana do Valor de Vendas
  - Valor Máximo de Venda
  - Valor Mínimo de Venda
    
- **D_Produtos_Detalhes**:
  - ID_produto
  - Discount Band
  - Sale Price
  - Units Sold
  - Manufacturing Price
    
- **D_Descontos**:
  - ID_produto
  - Discount
  - Discount Band
    
- **D_Detalhes**:
  - Contém informações adicionais não contempladas nas outras tabelas de dimensão
    
- **D_Calendário**:
  - Criada com a função `CALENDAR()` do DAX
    
- **F_Vendas**:
  - SK_ID
  - ID_Produto
  - Produto
  - Units Sold
  - Sales Price
  - Discount Band
  - Segment
  - Country
  - Salers
  - Profit
  - Date

## Imagens de amostra:

![tela_powerBI](https://github.com/christianalencar/DIO-Desafio-Vendas/assets/100319396/f5bc700a-1319-43ad-b37c-5f7bfb475c71)



# 9. Modelando um Dashboard de E-commerce com Power BI Utilizando Fórmulas DAX
Utilizaremos a tabela única de Financial Sample para criar as tabelas dimensão e fato do nosso modelo baseado em star schema.
O processo consiste na criação das tabelas com base na tabela original. A partir da cópia serão selecionadas as colunas que irão compor a visão da nova tabela. Sendo assim, a partir da tabela principal serão criadas as tabelas:

- Financials_origem (modo oculto – backup)
- D_Produtos (ID_produto, Produto, Média de Unidades Vendidas, Médias do valor de vendas, Mediana do valor de vendas, Valor máximo de Venda, Valor mínimo de Venda)
- D_Produtos_Detalhes(ID_produtos, Discount Band, Sale Price, Units Sold, Manufactoring Price)
- D_Descontos (ID_produto, Discount, Discount Band)
- D_Detalhes (*)
- D_Calendário – Criada por DAX com calendar()
- F_Vendas (SK_ID , ID_Produto, Produto, Units Sold, Sales Price, Discount Band, Segment, Country, Salers, Profit, Date (campos))

## Criação das TABELAS: 
![Image](https://github.com/user-attachments/assets/38cc90bc-ed6b-4e2a-8223-69b8ee17001a)
![Image](https://github.com/user-attachments/assets/90def661-5c4b-487a-b78c-592078e3120f)
![Image](https://github.com/user-attachments/assets/01f390d1-1fa5-455f-8c8e-9abeebfb616f)
![Image](https://github.com/user-attachments/assets/b1512e1c-ef11-4e15-930d-653f7589082f)
![Image](https://github.com/user-attachments/assets/1bec24dd-921e-4690-8041-14da3ac7b2b8)
![Image](https://github.com/user-attachments/assets/c235519a-1cf8-407c-b92a-6312fa020847)

## União das Tabelas no Modelo de Dados: 
![Image](https://github.com/user-attachments/assets/205a06b2-f9dc-44d7-a948-47b568dcca1c)

## Gráficos construidos a partir dessa nova Modelagem
![Image](https://github.com/user-attachments/assets/be617496-ccbc-4f6f-ad35-af37324aab41)

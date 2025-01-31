# Suzano - Análise de Dados com Power BI 🚀 (Apenas réplicas) 
Projetos Desenvolvidos com enfâse em Análise de Dados. Nesse bootcamp da DIO exploramos os principais contéudos para uma Carreira em Dados. Enfatizo que este bootcamp serve apenas para entrega dos projetos. Caso queira ver um projeto prático, desenvolvido totalmente por mim e utilizando do conhecimento obtido nesse bootcamp, acesse aqui:

# Parte 1 a 3: Introdução a Banco de Dados, Sistemas Relacionais e Consultas com SQL

## 1. Refinando um Modelo Conceitual de Banco de Dados - E-commerce ❤️‍🔥
Adicione ao Modelo: 
- Cliente pode se cadastrar Utilizando CPF ou CNPJ
- Pagamento pode ser feito de várias formas
- Entraga possui um código de Rastreio

## 2. Fazendo um Modelo Conceitual - Oficina de Mecânico 🔥
Regras do Modelo: 
- Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
- Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas
- Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
- A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
- O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços
- A mesma equipe avalia e executa os serviços
- Os mecânicos possuem código, nome, endereço e especialidade
- Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.

## 3. Contruindo um Modelo Lógico - Queries do Desafio 1 🔍
Replicar o código feito em Aula (Baseado no Modelo Conceitual, criar o Modelo lógico) e realizar as seguintes Queries:
- Recuperações simples com SELECT
- Filtros com Where
- Crie expressões para gerar atributos derivados
- Defina ordenações dos dados com ORDER BY
- Condições de filtros em grupos - HAVING
- Crie junções entre Tabelas 

## 4. Seu Banco de dados do zero 
Neste desafio, você definirá todas as etapas. Desde o esquema até a implementação do banco de dados. Após a criação do esquema lógico, realize a criação do Script SQL para criação do esquema do banco de dados. Posteriormente, realize a persistência de dados para realização de testes. Especifique ainda queries mais complexas. 

# Parte 4 a 9: Fundamentos de Power BI
Nesta parte determinaremos os Fundamentos de Power BI, compreendo o processamento, visualização e execução. 

## 5. Analisando dados de um Dashboard de Vendas no Power BI
Neste projeto você irá replicar duas páginas já criadas durante o curso com a sample disponibilizada. Esse desafio visa treinar a habilidade de criação de visuais. A terceira página é composta por: 

- Visual mapa 1: Soma de sales e unidades vendidas por país 
- Visual mapa 2: Soma de lucro (profit) por país 
- Visual de pizza: Lucro por segmento 

Além disso: 

- Verifique a disposição dos visuais no relatório 
- Modifique os nomes dos visuais para algo mais claro e direto (de acordo com o contexto) 
- Preste atenção aos campos que são utilizados como dicas de ferramentas  
- Publique o relatório 
- Compartilhe como suplemento no Power Point (Caso não tenha Power Point, salve o projeto de Power BI)
  
## 6. Criando Um Relatório Gerencial de Vendas
Você irá criar um relatório mais elaborado com base na sample financials do Power BI. 
- Estrutura definida 
- Botões de navegação que fornecem navegabilidade 
- Segmentadores utilizados e botões com imagem associado 
- Utilize os indicadores e botões para selecionar diferentes visuais sobre um mesmo assunto 

## 7. Dashboard corporativo com integração com MySQL e Azure
1. Criação de uma instância na Azure para MySQL
2. Criar o Banco de dados com base disponível no github
3. Integração do Power BI com MySQL no Azure
4. Verificar problemas na base a fim de realizar a transformação dos dados

## 8. Dashboard de Vendas com Power BI utilizando Star Schema
Criar o diagrama dimensional – star schema.

## 9. Modelando um Dashboard de E-commerce com Power BI Utilizando Fórmulas DAX
Utilizaremos a tabela única de Financial Sample para criar as tabelas dimensão e fato do nosso modelo baseado em star schema.
O processo consiste na criação das tabelas com base na tabela original. A partir da cópia serão selecionadas as colunas que irão compor a visão da nova tabela. Sendo assim, a partir da tabela principal serão criadas as tabelas:

- Financials_origem (modo oculto – backup)
- D_Produtos (ID_produto, Produto, Média de Unidades Vendidas, Médias do valor de vendas, Mediana do valor de vendas, Valor máximo de Venda, Valor mínimo de Venda)
- D_Produtos_Detalhes(ID_produtos, Discount Band, Sale Price, Units Sold, Manufactoring Price)
- D_Descontos (ID_produto, Discount, Discount Band)
- D_Detalhes (*)
- D_Calendário – Criada por DAX com calendar()
- F_Vendas (SK_ID , ID_Produto, Produto, Units Sold, Sales Price, Discount Band, Segment, Country, Salers, Profit, Date (campos))

## 10. Criando um Dashboard Gerencial para Tomada de Decisões Com Power BI 
Modificar o relatório criativo, o primeiro que criamos juntos, focando na experiência do usuário. Acompanhe o vídeo para que você entenda o que foi feito neste processo. Além disso, leve em consideração os seguintes pontos:
· Posicionamento
· Contraste
· Proporção áurea
· Segmentação dos dados

## 11. Criando um Relatório Vendas e Lucros Com Power BI
Pontos a serem considerados

· Crie a página detalhes conforme mostrado no desafio de projeto
· Pense na disposição dos visuais em como o cliente irá consumir o conteúdo
· Dependendo da disposição dos visuais o número de páginas pode variar. Até duas páginas podem compor o que é pedido
· Crie as medidas necessárias

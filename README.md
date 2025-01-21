## Suzano - Análise de Dados com Power BI 🚀
Projetos Desenvolvidos com enfâse em Análise de Dados. Nesse bootcamp da DIO exploramos os principais contéudos para uma Carreira em Dados.

# 1. Refinando um Modelo Conceitual de Banco de Dados - E-commerce ❤️‍🔥
Adicione ao Modelo: 
- Cliente pode se cadastrar Utilizando CPF ou CNPJ
- Pagamento pode ser feito de várias formas
- Entraga possui um código de Rastreio

![image](https://github.com/user-attachments/assets/786f8735-19de-43bc-ae7f-4ea4ea748080)

# 2. Fazendo um Modelo Conceitual - Oficina de Mecânico 🔥
Regras do Modelo: 
- Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
- Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas
- Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
- A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
- O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços
- A mesma equipe avalia e executa os serviços
- Os mecânicos possuem código, nome, endereço e especialidade
- Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.

![image](https://github.com/user-attachments/assets/c3f534c3-5203-4677-b6ce-28f6b68b0e9e)

# 3. Contruindo um Modelo Lógico - Queries do Desafio 1 🔍
Replicar o código feito em Aula (Baseado no Modelo Conceitual, criar o Modelo lógico) e realizar as seguintes Queries:

## Modelo Conceitual 🟠
Desenvolvido online com DrawSQL:
![image](https://github.com/user-attachments/assets/786f8735-19de-43bc-ae7f-4ea4ea748080)

## Modelo Lógico 🟠
Desenvolvido online com DB Fiddle (Tendo como base seu database - test):
![Image](https://github.com/user-attachments/assets/d04fe9b4-861a-41dc-bfc6-8d3067feb1e0)

![Image](https://github.com/user-attachments/assets/45a04b90-ac22-4cb7-a25c-f9e05cf2d027)

## Queries no Modelo Lógico 🟠
### 1) Inserir dados nas tabelas 
Pedimos para a Inteligência Artifical alimentar as tabelas do nosso Banco de Dados 
![Image](https://github.com/user-attachments/assets/1506961b-33fb-4941-83c8-b410b06dc391)

![Image](https://github.com/user-attachments/assets/ad10d6b6-fec2-4026-bcb1-e08170ab9595)

### 2) Fazer solicitações 
Sendo que devem ser criandos com as cláusulas a baixo:
🔸Recuperações simples com SELECT
1.
![Image](https://github.com/user-attachments/assets/7e55c497-15a6-434e-8ae0-7a70c4cc3078)

2.
![Image](https://github.com/user-attachments/assets/f78f3c9c-4287-4cd2-863c-f7bb0e8b17a3)

3.
![Image](https://github.com/user-attachments/assets/4efd4f74-278d-4e22-9f93-65ee7d77a890)

🔸Filtros com Where
1.
![Image](https://github.com/user-attachments/assets/63b69be7-c99c-47e6-a93b-5c5c3213035e)

2.
![Image](https://github.com/user-attachments/assets/b1207134-e1e1-43f4-b84f-36faef0cd2d5)

3.
![Image](https://github.com/user-attachments/assets/c71ef0e2-f5a7-4fda-8c73-cfa2300c7814)

🔸Crie expressões para gerar atributos derivados
1. Total de Produtos no Pedido
![Image](https://github.com/user-attachments/assets/dd7e0cf1-3243-4287-8de4-5f2ef222f238)

2. Valor Total de um Pedido
![Image](https://github.com/user-attachments/assets/f685bdb1-9376-463c-bf2e-e416af2d9469)

3. Número de Produtos Fornecidos por Cada Fornecedor
![Image](https://github.com/user-attachments/assets/862e5f53-cc9c-4fa1-b53d-b858e8b00798)

🔸 Defina ordenações dos dados com ORDER BY
1. Produtos e seus Fornecedores
![Image](https://github.com/user-attachments/assets/8bf10d20-2aab-4d31-a998-7743a97c9f8a)

2. Pedidos e Clientes
![Image](https://github.com/user-attachments/assets/8d7f13e7-730e-418e-ab03-c02011c9f701)

3. Pedidos e Produtos Relacionados 
![Image](https://github.com/user-attachments/assets/bc46ba05-a459-4839-93d2-7c3e90e1d3b0)

🔸 Condições de filtros em grupos - HAVING
1. Pedidos com Valor Total Maior que R$1000
![Image](https://github.com/user-attachments/assets/531417a0-a302-4d4e-89b8-15978ebe4e88)

2. Fornecedores com Mais de 2 Produtos
![Image](https://github.com/user-attachments/assets/649cfd35-2238-4f0a-9d99-e46162ce51d6)

3. Pedidos com Mais de 1 Produto no Total
![Image](https://github.com/user-attachments/assets/669d6a6a-633f-4043-abcc-6ef0e1824b37)

🔸 Crie junções entre Tabelas 
1.
![Image](https://github.com/user-attachments/assets/ff7d5d47-9d62-4ddb-bed2-17ec21ab2875)

2.
![Image](https://github.com/user-attachments/assets/ff9f0e31-3aff-437b-a620-0ecac34450a2)

3.
![Image](https://github.com/user-attachments/assets/254421c3-715f-4f29-96cb-762840fe8a93)


# 4. Seu Banco de dados do zero 

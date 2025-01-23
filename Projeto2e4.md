# 2. Fazendo um Modelo Conceitual e Lógico - Oficina de Mecânico 🔥
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

# 4. Fazendo o Modelo Físico
Para este cenário você irá utilizar seu esquema conceitual, criado no desafio do módulo de modelagem de BD com modelo ER, para criar o esquema lógico para o contexto de uma oficina. Neste desafio, você definirá todas as etapas. Desde o esquema até a implementação do banco de dados.

Após a criação do esquema lógico, realize a criação do Script SQL para criação do esquema do banco de dados. Posteriormente, realize a persistência de dados para realização de testes. Especifique ainda queries mais complexas. Sendo assim, crie queries SQL com as cláusulas abaixo

## 4.1) Modelo Físico
![Image](https://github.com/user-attachments/assets/6e56b587-60e4-40b3-a2a9-8913c3302e8f)

![Image](https://github.com/user-attachments/assets/96e2911c-804f-43c8-8910-53cc8b19cfdf)

## 4.2) Unserir os Dados
Solicitamos para uma IA dados para inserirmos no nosso Banco de Dados
![Image](https://github.com/user-attachments/assets/eee8b365-2954-45cd-a95d-f35a89e4971b)

![Image](https://github.com/user-attachments/assets/d8193a21-48a4-4eb7-b1c0-f15c051d111f)

## 4.2) Queries 
- Recuperações simples com SELECT Statement e Filtros com WHERE Statement
- Crie expressões para gerar atributos derivados e Defina ordenações dos dados com ORDER BY
- Condições de filtros aos grupos – HAVING Statement e Crie junções entre tabelas para fornecer uma perspectiva mais complexa dos dados

1) Vamos nos basear em perguntas possíveis:

### Ordens de Serviço pendentes, com os detalhes do Cliente e Veículo:
![Image](https://github.com/user-attachments/assets/d6a2aaa3-84b4-4e95-94e5-16f59852eb53)

### Valor total gasto em peças das ordens de serviço concluídas:
![Image](https://github.com/user-attachments/assets/83537160-319f-4fba-81b7-225069f2fb45)

### Quantas ordens de serviço foram feitas por cada equipe:
![Image](https://github.com/user-attachments/assets/508b874a-8b90-4168-8074-80f564a5aa40)





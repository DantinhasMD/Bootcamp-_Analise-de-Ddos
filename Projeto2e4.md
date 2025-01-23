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

# 4. Fazendo o Modelo Lógico 
Para este cenário você irá utilizar seu esquema conceitual, criado no desafio do módulo de modelagem de BD com modelo ER, para criar o esquema lógico para o contexto de uma oficina. Neste desafio, você definirá todas as etapas. Desde o esquema até a implementação do banco de dados.

Após a criação do esquema lógico, realize a criação do Script SQL para criação do esquema do banco de dados. Posteriormente, realize a persistência de dados para realização de testes. Especifique ainda queries mais complexas. Sendo assim, crie queries SQL com as cláusulas abaixo:

## 4.1) Modelo Lógico
Recuperações simples com SELECT Statement e Filtros com WHERE Statement


Crie expressões para gerar atributos derivados e Defina ordenações dos dados com ORDER BY


Condições de filtros aos grupos – HAVING Statement e Crie junções entre tabelas para fornecer uma perspectiva mais complexa dos dados


## 4.2) Queries 



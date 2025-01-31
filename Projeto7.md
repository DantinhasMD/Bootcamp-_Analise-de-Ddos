# 7. Dashboard corporativo com integração com MySQL e Azure

## 1. Criação de uma instância na Azure para MySQL
   Projeto sem posibilidade de ser concluído, devido a necessidade do uso de uma conta na Azure. Aqui estão apenas os passos para concluir sua criação!
   
## 2. Criar o Banco de dados com base disponível no github
- https://github.com/julianazanelatto/power_bi_analyst/blob/main/M%C3%B3dulo%203/Desafio%20de%20Projeto/script_bd_company.sql
- https://github.com/julianazanelatto/power_bi_analyst/blob/main/M%C3%B3dulo%203/Desafio%20de%20Projeto/insercao_de_dados_e_queries_sql.sql

## 3. Integração do Power BI com MySQL no Azure
- Abra o Power BI Desktop .
- Clique em Obter Dados > Banco de Dados MySQL .
- No campo Servidor , insira <SERVIDOR>.mysql.database.azure.com.
- No campo Banco de Dados , insira meu_banco.
- Em Modo de Conexão , selecione Modo DirectQuery ou Importação .
- Clique em Conectar e insira as credenciais.

## 4. Verificar problemas na base a fim de realizar a transformação dos dados
1. Escolha as Tabelas
- Escolha as tabelas que deseja importar.
- Clique em Transformar Dados para editar no Power Query.

2. identificar problemas. No Power Query Editor , verifique:
- Colunas vazias ou inconsistentes.
- Dados duplicados.
- Formação incorreta.

3. Realizar Transformações
- Remover duplicatas:
- Selecione a coluna e clique em Remover Duplicatas.
- Substituir valores nulos:
- Selecione a coluna e use Preencher ou Substituir Valores .
- Alterar tipos de dados: Clique na coluna e defina o tipo correto (ex: número, dados, texto).

4. Clique em Fechar e Aplicar para carregar os dados transformados.

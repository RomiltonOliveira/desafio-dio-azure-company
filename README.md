# Processamento de Dados Simplificado com Power BI
## Projeto: Integração, Transformação e Carregamento da Base de Dados "Azure_Company"

Este desafio foi proposto com a finalidade de explorar os conceitos de coleta, transformação e carregamento dos dados com Power BI e MySQL utilizando uma instância do Azure.

## Objetivos do Projeto
1.	Criação de uma instância na Azure para MySQL
2.	Criar o Banco de dados com base de teste
3.	Integração do Power BI com MySQL no Azure 
4.	Verificar problemas na base a fim de realizar a transformação dos dados
5.	Criar um relatório simples para visualização dos dados

Inicialmente foi criada uma instância do MySQL a partir de uma conta no Azure. Depois foi conectado a instância do MySQL da Azure no Workbench onde foi criado um banco de dados de teste chamado azure_company, no qual foram inseridos dados fictícios para teste.
Após o banco de dados estar pronto para uso foi realizado a integração entre o MySQL do Azure e o Power BI, possibilitando o carregamento e a transformação dos dados.
Na etapa de transformação dos dados foram aplicadas as seguintes alterações:
•	Conversão do tipo de dados de Salary para tipo número decimal fixo
•	Divisão da coluna Endereço em colunas subdivididas por rua, cidade, estado e número
•	Foi realizado a mescla das tabelas employee e departamento criando uma nova tabela
•	O nome da nova tabela foi renomeado Employee e Departament
•	Foi removido as colunas desnecessárias dessa junção
•	Foi mesclado as colunas Fname, Midit, Lname para uma única coluna renomeada para nome completo.
•	Foram renomeados os nomes das tabelas
•	Foram removidas as tabelas desnecessárias

## Resultado 

![Capturar](https://github.com/user-attachments/assets/786d199d-9d95-4183-b9ae-7d885eb9c5ae)






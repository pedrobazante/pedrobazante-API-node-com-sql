----------------------------------------

Nome e turma: Pedro Bazante Marques - 3NDN  
Matéria: Programação Web III (PWIII) 

----------------------------------------

----------------------------------------
Dependências:

- Node.js (v18+)
- Express
- mysql2 (Pool de conexões e Promises)
- dotenv
- cors
----------------------------------------

----------------------------------------
Rodar o Projeto Localmente:

1. Clonar o repositório esse repositório
2. Instalar dependências (npm isntall)
3. Configurar variáveis de ambiente (Copiar o arquivo `.env.example` para `.env`)
4. Criar o Banco de Dados e a Tabela (Através do schema.sql) 
- Executando ou abrindo o script `schema.sql` no seu MySQL ou MariaDB, podendo utilizar interfaces gráficas de SQL, como: DBeaver, MySQL Workbench, etc.
5. Iniciar o Servidor (npm run watch)
----------------------------------------

----------------------------------------
Rotas:

- POST - '/usuarios' = Cadastro de usuaŕio no body
- GET - '/usuarios' = Lista todos os cadastros já presentes
- PUT - '/usuarios/:id' = Atualizar dados de acordo com o ID de usuário
- DELETE - '/usuarios/:id' = Remover  usuário de acordo com o ID
  
----------------------------------------




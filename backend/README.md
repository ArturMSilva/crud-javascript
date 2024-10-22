# CRUD API com JavaScript

Este projeto é uma API CRUD simples criada com JavaScript para gerenciar usuários, incluindo as operações de criação, leitura, atualização e exclusão. A API se conecta a um banco de dados e utiliza rotas para definir as operações.

## Estrutura do Projeto

- **.env.example**: Arquivo de exemplo para as variáveis de ambiente necessárias no projeto.
- **.gitignore**: Arquivo que especifica quais arquivos ou diretórios serão ignorados pelo Git.
- **package.json**: Contém as dependências e scripts do projeto.
- **package-lock.json**: Arquivo gerado automaticamente com as versões exatas das dependências instaladas.
- **index.js**: Arquivo principal que inicia o servidor e define as rotas.
- **/routes/users.js**: Define as rotas para as operações CRUD relacionadas aos usuários.
- **/db/db.js**: Arquivo responsável pela conexão com o banco de dados.
- **/controllers/user-controllers.js**: Contém a lógica das operações de criação, leitura, atualização e exclusão de usuários.

## Tecnologias Utilizadas

- **Node.js**: Ambiente de execução JavaScript para o backend.
- **Express**: Framework para criação de APIs com Node.js.
- **MySQL**: Banco de dados.
- **dotenv**: Para carregar variáveis de ambiente de um arquivo `.env`.

## Instalação

1. Clone este repositório:
    ```bash
    git clone https://github.com/ArturMSilva/crud-javascript.git
    ```
   
2. Instale as dependências:
    ```bash
    npm install
    ```

3. Configure as variáveis de ambiente:
    - Renomeie o arquivo `.env.example` para `.env` e preencha as variáveis com suas respectivas informações (ex: URL do banco de dados).

4. Inicie o servidor:
    ```bash
    npm start
    ```

## Rotas

- **GET** `/users`: Retorna todos os usuários.
- **POST** `/users`: Adiciona um novo usuário.
- **PUT** `/users/:id`: Atualiza os dados de um usuário existente.
- **DELETE** `/users/:id`: Remove um usuário pelo ID.

## Contribuição

1. Fork este repositório.
2. Crie uma branch para sua feature (`git checkout -b minha-feature`).
3. Faça commit das suas mudanças (`git commit -m 'Adiciona minha feature'`).
4. Faça push para a branch (`git push origin minha-feature`).
5. Abra um Pull Request.

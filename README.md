# Meu Projeto React com Firebase

Este projeto é uma aplicação React que utiliza o Firebase para autenticação e armazenamento de dados dos usuários. O projeto possui três páginas principais:

- **Página de Cadastro**: O usuário pode se cadastrar fornecendo seu e-mail, senha, nome, sobrenome e data de nascimento. Esses dados são armazenados no Firebase Authentication e Firestore.
- **Página de Login**: O usuário pode fazer login com e-mail e senha. Se as credenciais forem válidas, será redirecionado para a página principal.
- **Página Principal**: Exibe os dados do usuário, como nome, sobrenome e data de nascimento, após o login bem-sucedido.

## Funcionalidades

- Cadastro de usuários no Firebase Authentication.
- Armazenamento de dados adicionais (nome, sobrenome, data de nascimento) no Firestore.
- Página de login com validação de credenciais.
- Exibição dos dados do usuário na página principal.

## Tecnologias Utilizadas

- React
- Firebase (Authentication e Firestore)
- React Router
- Vite

## Como rodar o projeto localmente

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/meu-projeto-react
    ```

2. Entre na pasta do projeto:
    ```bash
    cd meu-projeto-react
    ```

3. Instale as dependências:
    ```bash
    npm install
    ```

4. Crie um arquivo `.env` na raiz do projeto com as credenciais do Firebase. O arquivo deve ser semelhante a isso:

    ```
    REACT_APP_FIREBASE_API_KEY=SuaAPIKey
    REACT_APP_FIREBASE_AUTH_DOMAIN=SeuAuthDomain
    REACT_APP_FIREBASE_PROJECT_ID=SeuProjectID
    REACT_APP_FIREBASE_STORAGE_BUCKET=SeuStorageBucket
    REACT_APP_FIREBASE_MESSAGING_SENDER_ID=SeuMessagingSenderID
    REACT_APP_FIREBASE_APP_ID=SeuAppID
    ```

    **Importante**: Você deve obter essas credenciais no console do Firebase, criando um novo projeto.

5. Execute o projeto:
    ```bash
    npm start
    ```

6. A aplicação estará disponível em `http://localhost:3000`.

## Deploy

O projeto está hospedado no Netlify. Você pode acessá-lo através do link abaixo:

[Link para o projeto no Netlify](https://meu-projeto-react.netlify.app)

## Licença

Este projeto está licenciado sob a MIT License - consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

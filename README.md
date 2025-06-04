# Site Institucional UNIESP

Este projeto é um trabalho de classe da disciplina de **Frontend Avançado - Prof. Kelson** e consiste na criação de um website institucional para a faculdade **UNIESP** utilizando o framework **React**.

## Descrição

O objetivo do projeto é simular um site institucional moderno, responsivo e funcional, com páginas de notícias, navegação entre rotas e consumo de dados de uma API simulada.

## Bibliotecas Utilizadas

- **react**: Biblioteca principal para construção da interface do usuário.
- **react-dom**: Permite a integração do React com a árvore DOM do navegador.
- **react-router-dom**: Gerencia as rotas e navegação entre páginas do site.
- **axios**: Realiza requisições HTTP para consumir dados da API.
- **bootstrap**: Framework CSS para estilização e responsividade.
- **react-bootstrap**: Componentes React prontos baseados no Bootstrap.
- **json-server**: Simula uma API REST para fornecer dados ao frontend durante o desenvolvimento.

## Como rodar o projeto

1. **Instale as dependências** (caso ainda não tenha feito):

   ```
   npm install
   ```

2. **Inicie o servidor da API simulada** (json-server):

   ```
   npm run server
   ```

   Isso irá rodar o json-server em `http://localhost:3000`, utilizando o arquivo `data/db.json` como base de dados.

3. **Em outro terminal, inicie o frontend React:**

   ```
   npm run dev
   ```

   O site estará disponível em `http://localhost:5173` (ou outra porta informada pelo Vite).

---

**Observação:**  
Certifique-se de manter o json-server rodando enquanto utiliza o frontend, pois ele fornece os dados necessários para o funcionamento do site.

---
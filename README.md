# 🏛️ Site Institucional UNIESP  

**Olá! 👋** Este é o projeto **UNIESP Web**, desenvolvido como trabalho acadêmico para a disciplina de **Frontend Avançado** (ministrada pelo professor **Kelson**).  

O objetivo foi criar um **site institucional moderno** para a faculdade **UNIESP**, com:  
✅ **Design responsivo** (adaptável a celulares, tablets e desktops)  
✅ **Navegação fluida** entre páginas  
✅ **Consumo de dados dinâmicos** de uma **API simulada**  
✅ **Layout profissional** e intuitivo  

---

## 🛠️ Tecnologias Utilizadas  

| Tecnologia | Descrição | Link |
|------------|-----------|------|
| ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) | Biblioteca principal para construção da UI | [ReactJS](https://react.dev/) |
| ![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white) | Controle de navegação entre páginas | [React Router](https://reactrouter.com/) |
| ![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white) | Cliente HTTP para consumir APIs | [Axios](https://axios-http.com/) |
| ![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white) | Framework CSS para estilização | [Bootstrap](https://getbootstrap.com/) |
| ![React Bootstrap](https://img.shields.io/badge/React_Bootstrap-563D7C?style=for-the-badge&logo=react-bootstrap&logoColor=white) | Componentes React prontos | [React Bootstrap](https://react-bootstrap.github.io/) |
| ![JSON Server](https://img.shields.io/badge/JSON_Server-000000?style=for-the-badge&logo=json&logoColor=white) | API fake para simular dados | [JSON Server](https://www.npmjs.com/package/json-server) |

---

## 📚 Bibliotecas Utilizadas  

- **React**: Biblioteca principal para construção da interface do usuário.  
- **react-dom**: Permite a integração do React com a árvore DOM do navegador.  
- **react-router-dom**: Gerencia as rotas e navegação entre páginas do site.  
- **axios**: Realiza requisições HTTP para consumir dados da API.  
- **bootstrap**: Framework CSS para estilização e responsividade.  
- **react-bootstrap**: Componentes React prontos baseados no Bootstrap.  
- **json-server**: Simula uma API REST para fornecer dados ao frontend durante o desenvolvimento.

---

## 🚀 Como Rodar o Projeto  


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

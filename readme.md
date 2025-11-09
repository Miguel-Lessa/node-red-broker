# 🚀 Node-RED – Broker Catalog + Zip Code Searcher (BrasilAPI)

Este projeto consiste em uma aplicação construída no **Node-RED** que utiliza dados da **BrasilAPI**.

Ele possui duas funcionalidades principais:

1. **Catálogo de Corretoras**
   - Exibe uma lista de corretoras registradas na CVM.
   - Dados obtidos via BrasilAPI:
     ```
     https://brasilapi.com.br/api/cvm/corretoras/v1
     ```

2.  **Consulta de CEP**
   - Busca o endereço completo a partir de um CEP informado.
   - Dados obtidos via BrasilAPI:
     ```
     https://brasilapi.com.br/api/cep/v2/:cep
     ```

---

##  Tecnologias Utilizadas

- **Node-RED**
- **HTML + CSS (Mustache Template)**
- **BrasilAPI**

---

##  Como rodar o projeto

### 1. Instale o Node.js
https://nodejs.org/

### 2. Instale o Node-RED
```sh
npm install -g node-red

3. Inicie o Node-RED

node-red

4. Acesse no navegador

http://localhost:1880

Importando o Flow no Node-RED

    Copie o JSON de flows.json

    Selecione Import  Clipboard

    Cole o conteúdo do JSON

    Clique em Import


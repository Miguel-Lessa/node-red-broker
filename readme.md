#  Node-RED – Broker Catalog + Zip Code Searcher (BrasilAPI)

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
```

3. Inicie o Node-RED

```sh


node-red

```

4. Acesse no navegador

```sh
http://localhost:1880

```

### 3. Importe o Flow no Node-RED

1- Copie o JSON de flows.json

2-    Selecione Import  Clipboard

   3-  Cole o conteúdo do JSON

   4- Clique em Import


### 4. Como rodar o projeto usando Docker Compose 

Docker e Docker Compose instalados.

Dentro da pasta do projeto, execute:

```sh
docker compose up
```

Quando o container iniciar, acesse no navegador:

```sh
http://localhost:1880

```


1- Copie o JSON de flows.json

2-    Selecione Import  Clipboard

   3-  Cole o conteúdo do JSON

   4- Clique em Import






# Projeto API Node.js com Prisma e MongoDB

## Descrição
Este projeto consiste em uma API desenvolvida utilizando Node.js, Prisma e MongoDB. A API oferece operações CRUD (Create, Read, Update, Delete) para gerenciar clientes.

## Tecnologias Utilizadas
[![Node.js](https://img.shields.io/badge/Node.js-v14.0.0-green)](https://nodejs.org/)
[![Prisma](https://img.shields.io/badge/Prisma-v3.0.0-blue)](https://www.prisma.io/)
[![MongoDB](https://img.shields.io/badge/MongoDB-v4.0.0-orange)](https://www.mongodb.com/)


## Requisitos
Certifique-se de ter os seguintes requisitos instalados em sua máquina antes de executar o projeto:
- Node.js
- npm (Node Package Manager)
- MongoDB

## Instalação
1. Clone o repositório para sua máquina local:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
2. Instale as dependências do projeto::
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
3. Configure as variáveis de ambiente:
Crie um arquivo .env na raiz do projeto e configure as variáveis necessárias. Um exemplo pode ser encontrado no arquivo .env.example.

    Configuração do Banco de Dados
    Certifique-se de ter um servidor MongoDB em execução.

    Configure as informações do banco de dados no arquivo .env.
## Uso

1. **Inicie a aplicação:**
    ```bash
    npm start
    ```

2. **Acesse a API:**
    - Via navegador, abra [http://localhost:3000](http://localhost:3000)
    - Utilize ferramentas como Postman ou Insomnia.

## Rotas da API

### Listar Todos os Clientes
- **Endpoint:** `GET /customers`


### Criar um Novo Cliente
- **Endpoint:** `POST /customer`
- **Corpo da Requisição:**
  ```json
  {
    "nome": "Nome do Cliente",
    "email": "email@dominio.com",
    "telefone": "123456789"
  }
### Excluir um Cliente

- **Endpoint:** `DELETE /customer/:id`

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) e enviar pull requests.

## Licença
Este projeto é licenciado sob a [Licença MIT](LICENSE).
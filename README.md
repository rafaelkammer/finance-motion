# json-server-base

Esse é o repositório com a base de JSON-Server + JSON-Server-Auth já configurada, feita para ser usada no desenvolvimento das API's nos Capstones do Q2.

## Endpoints

Assim como a documentação do JSON-Server-Auth traz (https://www.npmjs.com/package/json-server-auth), existem 3 endpoints que podem ser utilizados para cadastro e 2 endpoints que podem ser usados para login.

### Cadastro

POST /register <br/>
POST /signup <br/>
POST /users

Qualquer um desses 3 endpoints irá cadastrar o usuário na lista de "Users", sendo que os campos obrigatórios são os de email e password.
Você pode ficar a vontade para adicionar qualquer outra propriedade no corpo do cadastro dos usuários.

### Login

POST /login <br/>
POST /signin

Qualquer um desses 2 endpoints pode ser usado para realizar login com um dos usuários cadastrados na lista de "Users"

### Entradas

GET /entradas
POST /entradas

Endpoints de entradas de valores.
GET pode ser usado para visualizar as entradas cadastradas, apenas com autenticação.
POST pode ser usado para cadastrar novas entradas, apenas com autenticação.

### Saídas

GET /saidas
POST /saidas

Endpoints de saídas de valores.
GET pode ser usado para visualizar as saídas cadastradas, apenas com autenticação.
POST pode ser usado para cadastrar novas saídas, apenas com autenticação.

### Objetivos

GET /objetivos
POST /objetivos

Endpoints de objetivos.
GET pode ser usado para visualizar os objetivos cadastrados, apenas com autenticação.
POST pode ser usado para cadastrar novos objetivos, apenas com autenticação.

### Usuário padrão: usuario@mail.com // senha: Senha123@

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

---

Endpoints voltados para a aplicação do projeto Hamburgueria

Todos os endpoints a seguir devem ser utilizados com autenticação pelo token pessoal do usuário

### Produtos

Para criação, aquisição dos produtos

    POST /products <br>
    GET /products

### Carrinho

Para a criação, aquisição do carrinho de comprar dos usuários:

    POST /cart <br>
    GET /cart

Para remover produtos do carrinho:

    DELETE /cart/:id

Obs.: Api em desenvolvimento

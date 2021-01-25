## Scripts disponíveis

Neste projeto está disponível:

### `dev`

Roda a aplicação em modo de desenvolvimento.
Após rodar a aplicação, a API ficará disponível na url: http://localhost:3333

### `knex:migrate`

Após rodar a aplicação, rodando este script, ele irá criar o banco de dados para teste.
Atualmente está utilizando sqlite, possíveis opções de banco:
* Mysql
* Postgres
* Firebird

### `knex:rollback`

Caso alguma migrate tenha sido criada de forma incorreta, basta utilizar este script para dar rollback nas tabelas criadas, para fazer a alteração e depois cria-las novamente com o knex:migrate.

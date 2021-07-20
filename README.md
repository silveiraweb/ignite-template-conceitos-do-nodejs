# [Ignite] Desafio 01 - Trilha Node.js
Reposiório do template em [rocketseat-education](https://github.com/rocketseat-education)

[*ignite-template-conceitos-do-nodejs*](https://github.com/rocketseat-education/ignite-template-conceitos-do-nodejs)

Nesse desafio, você deverá criar uma aplicação para treinar o que aprendeu até agora no Node.js!

Essa será uma aplicação para gerenciar tarefas (em inglês *todos*). Será permitida a criação de um usuário com `name` e `username`, bem como fazer o CRUD de *todos*:

- Criar um novo *todo*;
- Listar todos os *todos*;
- Alterar o `title` e `deadline` de um *todo* existente;
- Marcar um *todo* como feito;
- Excluir um *todo*;

Testes de usuários

- **Should be able to create a new user**
- **Should not be able to create a new user when username already exists**

Testes de todos

**Middleware**

Para completar todos os testes referentes à *todos* é necessário antes ter completado o código que falta no middleware `checkExistsUserAccount`. Para isso, você deve pegar o `username` do usuário no header da requisição, verificar se esse usuário existe e então colocar esse usuário dentro da `request` antes de chamar a função `next`. Caso o usuário não seja encontrado, você deve retornar uma resposta contendo status `404` e um json no seguinte formato:

- **Should be able to list all user's todos**
- **Should be able to create a new todo**
- **Should be able to update a todo**
- **Should not be able to update a non existing todo**
- **Should be able to mark a todo as done**
- **Should not be able to mark a non existing todo as done**
- **Should be able to delete a todo**
- **Should not be able to delete a non existing todo**


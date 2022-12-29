
## 💻 Sobre o Todo List

Essa aplicação realiza o CRUD (Create, Read, Update, Delete) de repositórios de projetos. Além disso, é possível dar likes em repositórios cadastrados, aumentando a quantidade de likes em 1 a cada vez que a rota é chamada.
<br>


## :rocket:Instalação
Para rodar o repositório é necessário clonar o mesmo, dar o seguinte comando para instalar as dependencias:

```bash
$ yarn 
```

## Rodar o app

```bash
$ yarn dev
```
## Utilizar o teste

```
yarn test
```
## Rotas

    POST /repositories → criar um repositorio.
    
    GET /repositories → retorna todos os repositorios.
       
    POST /repositories/:id/like → incrementa um like no repositorio.
    
    PUT /repositories/:id → atualiza um repositorio.
    
    DELETE /repositories/:id → deleta um repositorio pelo id.



<h4> 🛠 Projeto foi desenvolvido utilizando as seguintes tecnologias e conceitos: <h4>

    - Node.
    - JavaScript.
    - jest.
    - uuid
    - superTest
    - Nodemon.



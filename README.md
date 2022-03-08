## Projeto

- Aplicação não funcional, apenas para consultas em tabelas usando os métodos do `Typeorm`, mencionados abaixo, com testes unitários nessas consultas, sendo possível então rodar estes testes.

## Desafio

Realizar consultas no banco de dados com o TypeORM de três formas:

- ORM
- Query Builder
- Raw Query

## :white_check_mark: Requisitos

### Repositórios da aplicação

#### UsersRepository
- [x] findUserWithGamesById
- [x] findAllUsersOrderedByFirstName
- [x] findUserByFullName

#### GamesRepository
- [x] findByTitleContaining
- [x] countAllGames
- [x] findUsersByGameId

### Específicação dos testes

#### UsersRepository
- [x] Should be able to find user with games list by user's ID
- [x] Should be able to list users ordered by first name
- [x] Should be able to find user by full name

#### GamesRepository
- [x] Should be able find a game by entire or partial given title
- [x] Should be able to get the total count of games
- [x] Should be able to list users who have given game id

## Para rodar essa aplicação siga os seguintes passos:

- Copie a url do repositório na aba `CODE`.
- Com o git instalado, execute o seguinte comando => `git clone "Aqui vai a url copiada acima`.
- Com o `Nodejs` e o `Yarn` instalados, Na sua IDE preferida, abra o terminal do `git`, e execute o seguinte comando => `yarn`, para baixar as dependências da aplicação.
- Para rodar os testes unitarios das rotas da aplicação execute o seguinte comando => `yarn test`.
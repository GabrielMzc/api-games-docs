# API de Games
Esta Api é ultilizada para fazer um CRUD completo.
## Endpoints
### GET /games
Esse endpoint é responsável por retornar a listagem de todos os games cadastradas no banco de dados.
#### Parametros
Nenhum
#### Respostas
##### OK! 200
Caso essa resposata aconteca, você vai receber a listagem de todos os games.
##### Falha na autenticação! 401
caso essa resposta aconteca, isso significa que aconteceu alguma falha durante o processo de autentiação da requisição. Motivos: Token invállido, Token expirado.

Criar 2 endpoints:
Request:
[GET] /projects
Authorization: Bearer
Response:
200 - [{
    "name": "Joao da Silva"
    "email": "joaodasilva@email.com"
}]

Request:
[POST] /projects
Authorization: Bearer

{
    "name": "Joao da Silva"
    "email": "joaodasilva@email.com"
}
Response:
201 - {
    "mensagem": "Projeto incluído com sucesso"
}
404 - {
    "erro": "erro ao tentar incluir projeto"
}
# O que são Middlewares?
Middlewares são interceptadores de requisições capazes de interromper totalmente a requisição ou alterar seus dados.

# Middleware Implementados neste exemplo

## logRequests
Middleware capaz de exibir qual tipo de requisição foi feita (GET, POST, etc) e em qual rota.

## validadeProjectId
Middleware para validar se o formato do id informado em rotas com requisições UPDATE e DELETE. 
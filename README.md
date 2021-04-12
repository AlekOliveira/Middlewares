# O que são Middlewares?
Middlewares são interceptadores de requisições capazes de interromper totalmente a requisição ou alterar seus dados.

# Middlewares Implementados neste exemplo

## logRequests
Middleware capaz de exibir qual tipo de requisição foi feita (GET, POST, etc) e em qual rota.

## validadeProjectId
Middleware para validar se o formato do id informado em rotas com requisições UPDATE e DELETE. 

# Como executar este exemplo
- Instale o gerenciador de pacotes [Yarn](https://classic.yarnpkg.com/en/docs/install/#windows-stable)
- Clone o repositório
- Abra o terminal no diretório do projeto e instale as dependências com o comando **yarn**.
- Após instaladas as dependências é só inicializar o servidor 😎. com o comando **yarn dev**.

# Testando os middlewares nas requisições

### Listagem dos itens inseridos
![img](https://github.com/AlekOliveira/Middlewares/blob/main/imgs/listar.jpg)

Neste teste também é possível verificar a ação do middleware **logRequests**
que atua em qualquer rota.

![img](https://github.com/AlekOliveira/Middlewares/blob/main/imgs/middleware.jpg)

### Tentativa de deleção de um id inválido/não existente
![img](https://github.com/AlekOliveira/Middlewares/blob/main/imgs/deletar.jpg)

### Atualização de um item com id válido/existente
![img](https://github.com/AlekOliveira/Middlewares/blob/main/imgs/update.jpg)

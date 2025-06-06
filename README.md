## Estudando JWT (Json Web Token)

### O que é o JWT?
É um token de autenticação, muito usado para colocar uma camada de segurança na aplicação.

### Fluxo do projeto
1. O usuário faz login e o servidor valida email/senha e gera um token e retorna para o cliente.
2. Cliente envia o token em cada requisição e o servidor valida o token e permite o acesso.


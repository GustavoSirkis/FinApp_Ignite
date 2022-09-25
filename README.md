## FinAPI - Financeira

NODE JS
Express

---
## Requisitos (o que precisa fazer)

- [x] Criar uma conta
- [x] Buscar o extrato bancário do cliente
- [x] Realizar depósito
- [x] Realizar saque
- [x] Buscar extrato por data
- [x] Atualizar dados da conta
- [x] Obter dados da conta
- [x] Deletar conta
- [x] Retornar o balanço da conta

---
## Regras de negócio (o que não pode | gera error)

- [x] Não cadastrar conta com CPF existente (duplicado)
- [x] Não depositar em conta inexistente
- [x] Não buscar extrato em conta inexistente
- [x] Não fazer saque em conta inexistente
- [x] Não excluir conta inexistente
- [x] Não fazer saque com saldo insuficiente



---
## Requisitos da conta

1. cpf - string
2. name - string
3. id - uuid (universaly unique identifier) 
4. statement - [] 

<!-- Rocketseat - Ignite -->
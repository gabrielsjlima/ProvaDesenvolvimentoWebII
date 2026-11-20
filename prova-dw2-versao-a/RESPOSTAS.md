# Respostas — Prova Prática Individual de DW2 — Versão A

Nome: Gabriel Sebastião Jordão de Lima
RA:

## R1 (Item 10)

Status da página  /  : 302

Status da API  /api/palestrantes  : 401

Explicação: 
O status 302, redireciona o usuário para a tela de login, caso ele não esteja autenticado.
Já o status 401, ele exige a autenticação e responde com um erro ao JSON, sem redirecionamento.

## R2 (Item 11)

Status observado: 405

Explicação: O código 405, significa que o método HTTP utilizado não é permitido nessa rota. E isso está acontencendo por conta que a /api/palestrantes aceita GET, mas não aceita o POST.

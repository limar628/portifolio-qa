# Casos de teste: tela de cadastro

## CT-01: nome vazio

- **Objetivo:**
validar que o cadastro não aceita nome vazio

- **Pré-condição:** 
estar na tela de cadastro 

- **Dados:**

nome: (vazio)
email:jose@gmail.com
senha: E17654874*
confirmar:E17654874*
- **Passos:**

1 digitar nome campo vazio
 2 digitar email jose@gmail.com
3 digitar senha 17654874
4 confirmar 17654874
clicar em criar conta

- **Resultado esperado:** A conta não é criada, aparece a mensagem "Nome é obrigatório" abaixo do campo nome e o usuário continua na tela de cadastro.
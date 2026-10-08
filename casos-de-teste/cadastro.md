# Casos de teste: tela de cadastro

## CT-01: nome vazio

- **Objetivo:** Validar que o cadastro não aceita nome vazio.
- **Pré-condição:** Estar na tela de cadastro.
- **Dados:**
  - Nome: (vazio)
  - E-mail: jose@gmail.com
  - Senha: Senha@123
  - Confirmar senha: Senha@123
- **Passos:**
  1. Deixar o campo nome em branco.
  2. Digitar o e-mail jose@gmail.com.
  3. Digitar a senha Senha@123.
  4. Digitar Senha@123 em confirmar senha.
  5. Clicar em "Criar conta".
- **Resultado esperado:** A conta não é criada, aparece a mensagem "Nome é obrigatório" abaixo do campo nome e o usuário continua na tela de cadastro.


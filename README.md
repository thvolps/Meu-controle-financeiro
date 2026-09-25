# Painel Financeiro Multi-Usuário (Vercel + Turso / SQLite)

Sistema completo de finanças com autenticação individual segura (JWT) e isolamento total de dados por usuário.

## Estrutura
- **Autenticação:** Cadastro e login com senhas criptografadas (PBKDF2-HMAC-SHA256) e tokens JWT.
- **Isolamento de Dados:** Cada usuário enxerga apenas suas contas, receitas, categorias e caixinhas.
- **Nuvem Turso ou Local SQLite:** Se as variáveis `TURSO_DATABASE_URL` e `TURSO_AUTH_TOKEN` estiverem configuradas, conecta à nuvem automaticamente. Caso contrário, usa arquivo SQLite local.

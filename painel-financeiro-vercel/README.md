# Painel Financeiro Pessoal

Plataforma completa para gestão de finanças pessoais, controle de contas a pagar, parcelamentos, receitas, comprovantes e caixinhas de reserva.

## Funcionalidades
- **Gestão de Contas:** Contas avulsas, fixas recorrentes e parceladas (ex: 10x) com geração automática de parcelas futuras.
- **Alertas de Vencimento:** Alerta de contas com vencimento em até 3 dias e destaque visual para contas em atraso.
- **Linha do Tempo Quinzenal & Saldo Diário:** Análise de fluxo de caixa para evitar conta no vermelho.
- **Comprovantes de Pagamento:** Upload e visualização de comprovantes (PDF/imagem).
- **Caixinhas de Reserva:** Metas financeiras com aportes e retiradas em tempo real.
- **Tetos Orçamentários:** Limites de gastos por categoria com barra de progresso.
- **Visão Anual:** Matriz consolidada de receitas x despesas mês a mês.
- **Exportação CSV & Backup:** Exportação de planilhas e backup do banco SQLite.
- **Modo Privacidade:** Oculte valores na tela com um clique.

## Como Executar Localmente
1. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
2. Inicie o servidor:
   ```bash
   python -m uvicorn api.index:app --reload
   ```
3. Acesse `http://localhost:8000` no seu navegador.

## Deploy na Vercel
1. Suba este projeto para um repositório no GitHub.
2. No painel da [Vercel](https://vercel.com), importe o repositório e clique em **Deploy**.

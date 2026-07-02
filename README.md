# Quadras de Tênis do Cire — Contribuições

Site de contribuições e transparência de gastos para a manutenção das quadras de tênis do clube Cire, em Passos/MG.

**Site:** https://amrodarte.github.io/Quadras-Vivas/

## O que o site faz

- Painel financeiro bimestre a bimestre (receitas, despesas e caixa), com histórico desde 2020
- Contribuição voluntária de R$ 60 por bimestre com QR Code PIX gerado na hora
- Envio de comprovante e aprovação pelo gestor
- Gastos detalhados públicos: data, descrição, fornecedor e valor
- Tema claro/escuro, feito para celular

## Tecnologia

Página estática única (`index.html`) hospedada no GitHub Pages. Os dados ficam no [Supabase](https://supabase.com) (banco Postgres, storage de comprovantes e autenticação do gestor), protegidos por políticas de Row Level Security — a chave presente no código é a chave pública (publishable), sem acesso privilegiado.

## Desenvolvimento

Não há build: edite `index.html` e recarregue a página.

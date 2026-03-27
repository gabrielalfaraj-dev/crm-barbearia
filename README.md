# CRM — Barbearia Seu Souza

Dashboard inteligente alimentado por MARIAH AI.

## Stack
- React + Vite (gerado pelo Lovable)
- Supabase (dados em tempo real)
- Tailwind CSS
- Deploy: Vercel

## Variáveis de ambiente
As variáveis de ambiente são configuradas no Vercel (nunca no código).

## Tabelas Supabase
- `mariah_clients` — assinantes com plano e status
- `mariah_messages` — histórico de conversas com MARIAH
- `mariah_escalations` — escalações pendentes para Gabriel
- `mariah_followup` — leads que pediram info sobre planos
- `mariah_knowledge` — base de conhecimento acumulado

## Webhooks n8n
- `POST /webhook/crm-mass-send` — disparo em massa por segmento

# Gomes Hub — painel de licenças

## Deploy na Vercel

1. Suba esta pasta para um repositório GitHub.
2. Importe o repositório na Vercel.
3. Configure:
   - `SUPABASE_URL=https://utemnjaklepaiszqkpgd.supabase.co`
   - `SUPABASE_SERVICE_ROLE_KEY=...`
   - `ADMIN_TOKEN=...`
4. Faça o deploy.
5. Abra a URL da Vercel e entre com o `ADMIN_TOKEN`.

## Teste

A key de teste criada no Supabase é `GOMES-TEST-2026`.

O Lua já usa a Edge Function:
`https://utemnjaklepaiszqkpgd.supabase.co/functions/v1/gomes-validate`

Não coloque a service role key no Lua, no HTML ou em variáveis públicas.

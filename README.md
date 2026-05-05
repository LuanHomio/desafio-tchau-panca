# Desafio Tchau Pança — Landing Page

Landing page do produto digital fitness **Desafio Tchau Pança** do personal trainer Thiago Andrade.

HTML/CSS/JS estatico, sem build step. Servida direto pela [Vercel](https://vercel.com).

## Estrutura

- `index.html` — pagina unica, todo CSS e JS inline.
- Checkout aponta pra Hubla: `https://pay.hub.la/JfWmIOhOpCgSabaryTuY`.
- Compatibilidade: links antigos de email com `?email=...` no apex sao redirecionados pra `https://anamnese.thiagoandradepersonal.com.br`.

## Rodar local

Qualquer servidor HTTP estatico. Ex:

```
npx serve .
```

## Deploy

Push em `main` -> Vercel rebuilda. Dominio: `thiagoandradepersonal.com.br`.

## Stack relacionada

- App de anamnese: [LuanHomio/Thiago-Andrade---DTP-Anamnese](https://github.com/LuanHomio/Thiago-Andrade---DTP-Anamnese)
- Edge Functions Supabase (homio-operations): `thiago-andrade-hubla`, `thiago-andrade-hubla-recovery`, `thiago-andrade-anamnese`.

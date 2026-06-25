# Proposta Comercial — Limpeza Residencial (EUA) · 1Nort Digital

Página única (`index.html`) pronta pra mandar pro cliente como link.
Serviço: **Site + Google Ads + CRM + automações de SMS** para um serviço de limpeza residencial nos EUA.
Valores: **R$ 2.000/mês** (gestão 1Nort) + **$ 2.000 USD/mês** recomendado de verba no Google Ads.

## Antes de enviar — edite 2 coisas no `index.html`

1. **Número do WhatsApp** (botão final): procure `https://wa.me/?text=` e coloque seu número no formato internacional, ex:
   `https://wa.me/5534999999999?text=...`
2. (Opcional) **Nome do cliente / empresa**: dá pra trocar o `<h1>` do hero pra algo personalizado, ex: "Mais agendamentos para a [Nome da empresa]".

## Publicar no GitHub Pages

```bash
cd "C:/Users/Scherrer/proposta-maid-service-usa"
git init
git add .
git commit -m "Proposta comercial limpeza EUA"
gh repo create proposta-maid-service-usa --public --source=. --push
```

Depois, no GitHub: **Settings → Pages → Branch: main / root → Save**.
O link sai como: `https://SEU-USUARIO.github.io/proposta-maid-service-usa/`

> Pode testar localmente só abrindo o `index.html` no navegador (clique duplo).

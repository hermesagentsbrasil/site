# Hermes Agent Brasil — Site

Site oficial da **Hermes Agent Brasil**, a comunidade brasileira do [Hermes Agent](https://hermes-agent.nousresearch.com) (Nous Research).

🌐 **No ar em:** [hermesagentsbrasil.com.br](https://hermesagentsbrasil.com.br)

## Sobre

Em breve: conteúdo em português e meetups pelo Brasil para quem constrói com agentes autônomos. No momento o site é uma página "Em breve" (coming soon).

## Estrutura

```
public_content/          # docroot servido pelo nginx
├── index.html           # página única (HTML + CSS inline, sem build)
└── assets/img/          # logos (stacked e horizontal)
```

- **Stack:** HTML/CSS estático, sem framework e sem etapa de build.
- **Fontes:** Inter, JetBrains Mono e Press Start 2P (Google Fonts).
- **Idioma:** pt-BR.

## Deploy

O repositório espelha o servidor de produção: o docroot do nginx aponta para `public_content/`, servido com HTTPS (Let's Encrypt). Alterações em `main` representam o conteúdo em produção.

## Licença

Veja [LICENSE](LICENSE).

---

© Hermes Agent Brasil · feito no 🇧🇷

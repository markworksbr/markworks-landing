# MarkWorks — Landing "Em breve"

Landing page estática para publicar na **Vercel** enquanto o produto principal é desenvolvido.

## Estrutura
```
.
├── assets/         # imagens, ícones, css/js (quando precisar)
├── index.html      # página principal
├── .gitignore
├── LICENSE
└── README.md
```

## Como usar (GitHub UI)
1. Crie um repositório **novo** no GitHub (ex.: `markworks-landing`), público ou privado.
2. Faça **Upload files** destes arquivos para a branch `main`.
3. Conecte o repositório na **Vercel** (Import Project → GitHub → escolha o repo).
4. Framework preset: **Other** (projeto estático). Root: `/`. Sem build command.
5. Deploy. Depois, em *Domains*, adicione o domínio/subdomínio quando quiser.

## Como usar (Git local)
```bash
# Dentro da pasta com os arquivos
git init
git add .
git commit -m "feat: landing em breve"
git branch -M main
git remote add origin https://github.com/<seu-usuario>/markworks-landing.git
git push -u origin main
```

## Dicas de organização
- Use a branch `main` somente para o que vai pra produção.
- Commits pequenos e descritivos (ex.: `feat:`, `fix:`, `docs:`).
- Abra issues no GitHub para cada tarefa (SEO, favicon, coleta de e-mails real, etc.).

## Próximos passos (opcionais)
- Adicionar **favicon** na pasta `assets/` e linkar no `<head>`.
- Trocar o `mailto:` por um coletor real (Formspree/Beehiiv/Supabase).
- Criar `vercel.json` se quiser redirecionos/HSTS quando ligar domínio.

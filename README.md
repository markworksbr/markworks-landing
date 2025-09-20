# MarkWorks — Landing (Paleta Verde + Kanit)

Este repositório contém a landing "Em breve" da MarkWorks usando a paleta oficial (Green) e a fonte **Kanit**.

## Cores oficiais
- Background: `#012E14`
- Destaque 1 (primária/CTA): `#369E44` (hover `#2f873a`, active `#276f30`)
- Destaque 2 (acento): `#8EA680`
- Texto 1: `#E7E9EE`
- Texto 2: `#C8D2CD`

## Publicar pela Vercel
1. Suba este repositório para o GitHub (branch `main`).
2. Na **Vercel**: *Add New → Project → Import Git Repository* → selecione o repo.
3. *Framework preset*: **Other** (HTML estático), *Root Directory*: `/`, *Build Command*: vazio, *Output*: `/`.
4. Deploy. Em *Settings → Domains*, adicione seu domínio/subdomínio.

## Deploy via VS Code (CLI)
```bash
npm i -g vercel
vercel login
vercel link   # linke esta pasta ao projeto
vercel        # preview
vercel --prod # produção
```

## Git (passo rápido)
```bash
git init
git add .
git commit -m "feat: landing com paleta verde e Kanit"
git branch -M main
git remote add origin https://github.com/<usuario>/markworks-landing.git
git push -u origin main
```

## Onde editar
- **index.html**: conteúdo da página
- **css/tokens.css**: tokens de cor/estilo
- **assets/**: imagens/ícones

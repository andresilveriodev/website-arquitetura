# AETHEREAL | Parallax Clean

Site estático (HTML, CSS, JS) com efeitos parallax, GSAP e Lenis. Design system em `/design-system/`.

## Deploy na Vercel

### Opção 1: Conectar repositório Git

1. Acesse [vercel.com](https://vercel.com) e faça login.
2. **Add New** → **Project** e importe o repositório deste projeto.
3. Deixe as opções padrão (Framework Preset: Other, Build Command em branco, Output Directory: `.`).
4. Clique em **Deploy**. O site ficará em `https://seu-projeto.vercel.app`.

### Opção 2: Vercel CLI

```bash
# Instalar a CLI (uma vez)
npm i -g vercel

# Na pasta do projeto
cd parallax-clean
vercel
```

Siga o assistente (link com conta, nome do projeto). Para deploy em produção:

```bash
vercel --prod
```

### Estrutura esperada no deploy

- **`/`** → `index.html` (página principal)
- **`/design-system/`** → `design-system/index.html`
- **`/assets/`** e **`/img/`** → arquivos estáticos (imagens, etc.)

Os arquivos `vercel.json` e `package.json` já estão configurados para site estático (sem build).

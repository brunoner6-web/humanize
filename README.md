# Clínica Humanize — Site

Site institucional estático da Clínica Humanize · Corpo e Mente (Salvador — BA).

## Páginas
- `index.html` — Página inicial
- `procedimentos.html` — Procedimentos
- `clinica.html` — A Clínica
- `duvidas.html` — Dúvidas

## Estrutura
```
/
├── index.html
├── procedimentos.html
├── clinica.html
├── duvidas.html
├── support.js        # runtime das páginas (obrigatório)
├── image-slot.js
├── vercel.json
├── assets/           # logos, ícone e foto do hero
└── _ds/              # folha de estilo e fontes do design system
```

## Deploy na Vercel
1. Suba o conteúdo desta pasta na raiz do repositório no GitHub.
2. Na Vercel: **Add New → Project → Import** o repositório.
3. Framework Preset: **Other**. Build Command: vazio. Output Directory: `./`.
4. Deploy. Cada push na branch principal publica automaticamente.

## Atualização (2026-10-18)
- Removida a seção de antes e depois da página inicial.
- Removidas as fotos do ambiente (página inicial e A Clínica).
- Texto da página inicial focado na clínica, sem destacar profissionais.
- Seção "Oferta" em fundo marfim.
- Logo do menu reduzida em todas as páginas.
- Imagens não utilizadas removidas de `assets/`.

## Contato
WhatsApp: (71) 98163-1950 · Instagram: @humanizecorpoemente

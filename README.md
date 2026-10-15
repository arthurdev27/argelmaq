# ARGELMAQ Assistência Técnica — Site

Site de uma página (HTML + CSS puro, sem build) da ARGELMAQ: assistência técnica de geladeira, máquina de lavar, micro-ondas e fogão.

## Estrutura
```
index.html          página inteira (HTML, CSS e ícones em SVG)
assets/             logo, ícone, favicon, fotos dos serviços e imagem de compartilhamento
vercel.json         configuração da Vercel (cache das imagens)
robots.txt
```
`assets/logo-e-icone-original.png`, `assets/flyer-argelmaq.jpg` e as fotos `*-2.jpg` não são usados na página; ficam guardados para uso futuro.

## Publicar na Vercel
1. Suba esta pasta para um repositório no GitHub.
2. Na Vercel: **Add New > Project**, escolha o repositório.
3. Framework Preset: **Other**. Deixe Build Command e Output Directory vazios. Deploy.

## Como editar
- **Telefones:** procure `5522974065719` e `5522996134929` no `index.html` (links `wa.me`).
- **Serviços:** edite as listas `<ul>` dentro de cada `<article class="card">`.
- **Horário:** procure `Horário de atendimento`.
- **Redes sociais:** procure `instagram.com/argelmaq_` e `facebook.com/share`.
- **Fotos:** troque os arquivos em `assets/` mantendo o mesmo nome.

## Endereço
O site é publicado em https://argelmaq.vercel.app. Esse endereço já está configurado no `index.html` (canonical, og:url e og:image), então a prévia ao compartilhar o link no WhatsApp usa `assets/og-image.jpg`. Se mudar de domínio, atualize essas três linhas.

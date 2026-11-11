<div align="center">

# vitoriaayres.github.io

**Personal website of Vitoria AYRES — served at [vitoriaayres.me](https://vitoriaayres.me).**

*English* · [Português](#-português)

</div>

> 🇧🇷 **Português:** site pessoal publicado pelo **GitHub Pages** no domínio próprio **vitoriaayres.me**. Este repositório guarda o código-fonte do site.

## About

This repository holds the source of the personal site, published automatically by GitHub Pages whenever changes are pushed to the default branch.

## Custom domain

The site is served from a custom domain configured through the [`CNAME`](CNAME) file:

```
vitoriaayres.me
```

For this to work, the DNS records for `vitoriaayres.me` must point at GitHub Pages, and **Enforce HTTPS** should be enabled in the repository's Pages settings.

## Local development

```bash
git clone https://github.com/vitoriaayres/vitoriaayres.github.io.git
cd vitoriaayres.github.io

# any static server works
npx serve .          # or: python -m http.server 8000
```

Open <http://localhost:8000> (or the port shown) to preview.

## Publishing

```bash
git add .
git commit -m "Update site"
git push
```

GitHub Pages rebuilds and republishes automatically — the new version is live within a minute or two.

## 🇧🇷 Português

- **O que é:** site pessoal da Vitoria AYRES, publicado via GitHub Pages no domínio próprio **vitoriaayres.me**.
- **Domínio:** configurado pelo arquivo [`CNAME`](CNAME); os registros DNS devem apontar para o GitHub Pages e o **Enforce HTTPS** deve estar ativo nas configurações de Pages.
- **Como rodar localmente:** clone o repositório e sirva a pasta com `npx serve .` ou `python -m http.server 8000`.
- **Como publicar:** faça `git push` na branch padrão — o GitHub Pages reconstrói e publica automaticamente em poucos minutos.

## Author

[Vitoria AYRES](https://github.com/vitoriaayres) · [Steam](https://steamcommunity.com/profiles/76561198827037103/) · [Site](https://vitoriaayres.me)

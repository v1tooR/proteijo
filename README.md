# Proteijo

Landing page estática da Proteijo.

## SEO e publicação

O domínio canônico configurado é `https://proteijo.com.br/`. Se o domínio de produção mudar, atualize as URLs absolutas em `index.html`, `robots.txt` e `sitemap.xml` antes de publicar.

Após o deploy:

1. Confirme que a home, `robots.txt`, `sitemap.xml`, `favicon.svg` e `assets/seo/og-proteijo.jpg` respondem com HTTP 200.
2. Cadastre o domínio no Google Search Console e no Bing Webmaster Tools.
3. Envie `https://proteijo.com.br/sitemap.xml` e solicite a indexação da home.
4. Valide a URL publicada no Rich Results Test e nos depuradores de compartilhamento das redes sociais.
5. Ao alterar conteúdo relevante, atualize `dateModified` no JSON-LD e `lastmod` no sitemap.

Os arquivos de protótipo `wireframe.html` e `DSProteijo/index.html` possuem `noindex` para evitar conteúdo duplicado.

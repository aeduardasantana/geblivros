# GEB Livros

Livraria do GEB para livros digitais, manuais e coleções.

Domínio: `geblivros.grupoeduardabispo.com.br`<br>
Contato público: `contato@grupoeduardabispo.com.br`

## Arquitetura

- `/` — home e descoberta do acervo.
- `/livro/modelo/` — página-base de conversão. Deve ser duplicada em `/livro/[slug]/` para cada título.
- `/mapa/` — índice interno, não indexado.

## Publicação de um título

1. Duplique `livro/modelo/index.html` para `livro/[slug]/index.html`.
2. Substitua os campos entre colchetes, a capa e ambos os links `SEU-LINK-INFINITEPAY-AQUI`.
3. Troque o `noindex,nofollow` da página pela indexação apropriada antes de publicar a página real.
4. Preserve autoria, créditos, escopo de uso e obrigações da licença da obra.
5. Publique e inclua o novo título na home quando ele estiver disponível.

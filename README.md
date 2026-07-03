# Blog Educacao Financeira para Criancas

Projeto simples em HTML e CSS para um artigo de blog sobre educacao financeira para criancas. A pagina foi pensada para leitura direta no navegador, com area principal de conteudo, barra lateral e espacos reservados para anuncios.

## Visao geral

- Pagina estatica em `index.html`.
- Estilos CSS embutidos no proprio HTML.
- Conteudo em portugues brasileiro.
- Layout com cabecalho, artigo principal, sidebar e rodape.
- Espacos comentados para inserir codigos de anuncios, como Google AdSense.

## Estrutura

```text
.
|-- index.html
|-- LICENSE
`-- README.md
```

## Como executar

Nao ha dependencias, build ou servidor obrigatorio.

1. Abra o arquivo `index.html` diretamente no navegador.
2. Se preferir servir localmente, use qualquer servidor estatico simples apontando para a raiz do projeto.

Exemplo com Python:

```bash
python -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000
```

## Como editar o conteudo

Todo o conteudo visivel da pagina esta no arquivo `index.html`.

- Titulo da aba do navegador: tag `<title>`.
- Nome do blog: bloco `<header>`.
- Artigo principal: bloco `<main>`.
- Links laterais: bloco `<aside>`.
- Rodape: bloco `<footer>`.

Ao editar textos em portugues, mantenha o arquivo salvo em UTF-8 para preservar acentos e caracteres especiais.

## Anuncios

O HTML possui tres areas com a classe `.ads`. Elas funcionam como marcadores para publicidade:

- Anuncio no inicio do artigo.
- Anuncio no meio/final do artigo.
- Anuncio na barra lateral.

Para usar Google AdSense ou outro provedor, substitua os comentarios dentro dessas areas pelo codigo fornecido pela plataforma de anuncios.

## Personalizacao visual

Os estilos estao dentro da tag `<style>` em `index.html`.

Pontos comuns de ajuste:

- Cor principal: `#2d6cdf`.
- Cor de fundo da pagina: `#f4f4f4`.
- Largura maxima do conteudo: `1200px`.
- Bordas arredondadas dos blocos: `8px`.

## Publicacao

Como o projeto e estatico, ele pode ser publicado em servicos como:

- GitHub Pages
- Netlify
- Vercel
- Hospedagem tradicional com FTP/cPanel

Para publicar, envie os arquivos da raiz do projeto e configure `index.html` como pagina inicial.

## Licenca

Este projeto esta licenciado sob a licenca MIT. Consulte o arquivo `LICENSE` para mais detalhes.

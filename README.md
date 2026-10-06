# Scentment: site de demonstração

Site institucional e de catálogo da **Scentment** (aromas e cosméticos personalizados, Araras/SP).

Este repositório é uma **versão de demonstração**: a página tem `noindex` para não aparecer no Google.

## Estrutura

- `index.html`: página única, com CSS e JavaScript embutidos.
- `img/`: fotos e logo em WebP.
- `.nojekyll`: faz o GitHub Pages publicar os arquivos como estão.

## Publicar com o GitHub Pages

1. Em **Settings > Pages**, em *Build and deployment*, escolha **Deploy from a branch**.
2. Selecione a branch `main` e a pasta `/ (root)`, e salve.
3. Em até alguns minutos o site abre em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Configurar contatos

No fim do `index.html`, edite:

```js
var CONFIG={whatsapp:"",instagram:""};
```

- `whatsapp`: DDI + DDD + número, só dígitos (ex.: `5519999999999`).
- `instagram`: usuário, sem `@`.

Enquanto estiverem vazios, os botões correspondentes ficam ocultos.

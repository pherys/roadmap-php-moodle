# Como contribuir

> **English / Español:** issues and pull requests are welcome in English, Spanish or Portuguese. Content lives in `data.pt.js`, `data.en.js` and `data.es.js`. If you add or remove a topic, do it in all three files with the same `id`.

Obrigada pelo interesse! Este roadmap é mantido pela comunidade.

## Sugerir uma mudança

- **Encontrou um erro ou link quebrado?** Abra uma *issue* dizendo o tópico e o que está errado.
- **Quer acrescentar ou corrigir um tópico?** Edite o arquivo do idioma ([`data.pt.js`](data.pt.js), [`data.en.js`](data.en.js) ou [`data.es.js`](data.es.js)) e abra um *pull request*.
- **Tópico novo ou removido:** faça a mudança nos três arquivos, com o mesmo `id`. Se não souber traduzir, avise no *pull request* que alguém ajuda.

## Formato de um tópico

```js
{ id: "dml", t: "DML API ($DB)", n: "e",
  d: "O que é e por que estudar.",
  m: "Como isso aparece no Moodle, com `código` entre crases.",
  l: [["Rótulo do link", "https://..."]] }
```

- `n`: prioridade: `"e"` essencial, `"i"` importante, `"o"` opcional.
- `m` e `l` são opcionais.
- Não mude o `id` de tópicos existentes: ele guarda o progresso de quem já está estudando.

## Critérios

- Prefira fontes oficiais (php.net, moodledev.io) e material gratuito.
- Indique a versão do Moodle quando algo só valer a partir dela.
- Textos em português do Brasil, curtos e diretos.

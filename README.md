# 🌳 Família Abreu

Árvore genealógica interativa — Pedro Filipe de Abreu & Francisca Cândida de Jesus.

## Navegação

| Ação | Como |
|------|------|
| Zoom | Scroll do mouse |
| Mover | Arrastar |
| Expandir/recolher filhos | Clicar no nó |
| Centralizar | Botão "Centralizar" |
| Buscar | Campo de busca — destaca **todos** os resultados |

## Estrutura

```
familia-abreu/
├── index.html   # Página
├── data.js      # Dados da família (JSON)
└── README.md
```

## Atualizar dados

Edite `data.js`. Formato:

```js
const FAMILY_DATA = {
  "name": "Nome",
  "spouse": "Cônjuge",      // opcional
  "children": [...]          // opcional
};
```

## Deploy no Vercel

1. Suba os 3 arquivos para um repositório GitHub
2. [vercel.com](https://vercel.com) → **Add New → Project** → importe o repo
3. Clique **Deploy** — zero configuração necessária

## Roadmap futuro

- [ ] Fotos nos cartões
- [ ] Formulário de cadastro (pessoa se inclui, você aprova)
- [ ] Google Sheets como banco de dados
- [ ] Unir os dois lados da família

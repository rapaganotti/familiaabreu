# 🌳 Família Abreu

Árvore genealógica interativa da família Abreu.

## Como funciona

- **Zoom**: scroll do mouse
- **Mover**: arrastar
- **Expandir/recolher**: clicar em qualquer nó
- **Buscar**: campo de busca no topo (busca por nome ou cônjuge)
- **Centralizar**: botão "Centralizar" no topo

## Estrutura do projeto

```
familia-abreu/
├── index.html   # Página principal
├── data.js      # Dados da árvore genealógica
└── README.md    # Este arquivo
```

## Como atualizar os dados

Edite o arquivo `data.js`. Os dados seguem o formato JSON aninhado:

```js
const FAMILY_DATA = {
  "name": "Nome da Pessoa",
  "spouse": "Nome do Cônjuge",   // opcional
  "children": [                  // opcional
    { "name": "Filho 1" },
    { "name": "Filho 2", "spouse": "Cônjuge", "children": [...] }
  ]
};
```

## Deploy no Vercel

1. Suba os arquivos para um repositório no GitHub
2. Acesse [vercel.com](https://vercel.com) e clique em **Add New → Project**
3. Importe o repositório GitHub
4. Clique em **Deploy** — não precisa de nenhuma configuração adicional

O Vercel detecta automaticamente que é um projeto HTML estático.

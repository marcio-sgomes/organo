# Organo

Organograma de times: um formulário cadastra colaboradores (nome, cargo, imagem e time) e eles aparecem em cards agrupados por time.

> 📦 **Projeto de estudo** — não recebe mais atualizações.

## Contexto

Projeto do curso de React da Alura, feito em maio de 2022. Cada aula do curso foi salva em uma branch:

| Branch | Conteúdo |
| --- | --- |
| `aula-1` a `aula-5` | Estado do projeto ao fim de cada aula |
| `master` | Igual a `aula-5` |
| `main` (padrão) | Aula 5 + `imagens.zip` com as imagens do curso |

Publicado em: <https://organo-dun.vercel.app>

## Tecnologias

- **React 18** — componentes e estado com `useState`.
- **Create React App (react-scripts 5)** — configuração de build e servidor de desenvolvimento.
- **CSS por componente** — cada componente em `src/componentes/` tem seu próprio arquivo de estilo.

## Como rodar

Pré-requisito: Node.js (versão LTS) e npm.

```bash
npm install
npm start
```

O app abre em <http://localhost:3000>. Outros scripts: `npm run build` (gera a pasta `build/`) e `npm test`.

## Estrutura

- `src/App.js` — lista de times e estado dos colaboradores.
- `src/componentes/` — Banner, Formulario, CampoTexto, ListaSuspensa, Botao, Time e Colaborador.
- `public/` — HTML base e imagens (banner).

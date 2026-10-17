# clone-tabnews

Projeto de estudos desenvolvido acompanhando o [curso.dev](https://curso.dev), com o objetivo de construir uma implementação do [TabNews](https://www.tabnews.com.br).

## Estado atual

O repositório está na etapa inicial: configuração de Next.js e React, uma página inicial simples e um comando para iniciar o ambiente de desenvolvimento.

## Tecnologias

- JavaScript
- React 18
- Next.js 13
- Node.js e npm

## Como executar

Use a versão do Node.js indicada no arquivo `.nvmrc`. Se você utiliza nvm:

```bash
nvm install
nvm use
```

Instale as dependências e inicie o servidor de desenvolvimento:

```bash
npm ci
npm run dev
```

Abra [localhost:3000](http://localhost:3000) no navegador.

## Estrutura

```text
pages/
  index.js           # Página inicial
.nvmrc               # Versão do Node.js
package.json         # Dependências e comando de desenvolvimento
package-lock.json    # Versões resolvidas das dependências
```

As pastas `node_modules/` e `.next/` são geradas localmente pela instalação e execução do projeto e ficam fora do versionamento.

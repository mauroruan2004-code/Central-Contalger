# Central Contalger — versão com edição salva no GitHub

Esta versão usa `projects.json` como banco de dados simples.

## Arquivos
- `index.html`
- `projects.json`
- `logo-contalger.png`

## Como atualizar o repositório
Substitua/envie os três arquivos na raiz do repositório `Central-Contalger`.

Se o GitHub Pages já está ativo em `main / (root)`, ele será atualizado automaticamente.

## Para editar pela própria Central
Clique em **Conectar GitHub** e informe um **Fine-grained Personal Access Token**.

Configure o token assim:
- Resource owner: `mauroruan2004-code`
- Repository access: somente `Central-Contalger`
- Repository permissions:
  - **Contents: Read and write**

O token é guardado apenas em `sessionStorage`; ao encerrar a sessão do navegador ele deixa de ficar disponível.

Ao adicionar, editar ou excluir um projeto, a Central faz um commit no arquivo `projects.json`.

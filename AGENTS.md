# Regras para o agente

## Git

- Toda alteração realizada neste repositório **deve** ser commitada e pushada para o GitHub.
- Ao finalizar **qualquer** tarefa, sem exceção: `git add` dos arquivos alterados, `git commit` com mensagem descritiva em português e `git push` para `origin`.
- Branch de trabalho: `master` (já trackeia `origin/master`). Não usar `--force`, `git commit --amend` nem mexer em `git config` sem pedido explícito.
- Antes de commitar, revisar com `git status` e `git diff`; nunca commitar segredos, senhas ou tokens.
- Se o push for rejeitado, fazer `git pull --rebase` e repetir o push.

## Projeto

- Site estático de trabalho escolar de Heloisa, Isis e Maria Eduarda (GitHub Pages).
- Ficheiro principal: `index.html` (HTML + CSS inline). Sem build, sem dependências.

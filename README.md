# Curso Digital: Git Ada/Santander
## Comandos:
* git add – Adiciona o conteúdo do arquivo.
* git commit - Registra alterações no repositório.
* git-diff - Mostra alterações entre commits, commit e árvore de trabalho, etc.
* git restore - Restaurar os arquivos das árvores de trabalho.
* git restore --staged - Restaura os arquivos mesmo depois do commit.
* git log – Mostrar logs de commit.
* git remote - Gerenciar conjunto de repositórios rastreados.
* git push – Atualiza referências remotas junto com objetos associados.
* git-pull - Busca e integra com outro repositório ou branch local.
* git-fetch – Baixe objetos e referências de outro repositório.

***
Quando estiver satisfeito com as alterações que foram feitas, temos que fazer todo o fluxo de: add .\ARQUIVO, commit -m, remote, push "resultado do remote" branch(main ou master).
***
Quando as alterações são feitas no repositório remoto, temos que fazer o fluxo de: pull para atualizar direto ou fetch que vai baixar as alterações mas não vai atualizar e podemos usar o diff (diff origin/main) para ver as alterações e depois pull caso esteja de acordo.
***
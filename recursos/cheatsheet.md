# Cheatsheet de Git

## Comandos Básicos
| Comando | Descrição |
|---------|-----------|
| `git init` | Inicializa um repositório |
| `git clone <url>` | Clona um repositório remoto |
| `git add <arquivo>` | Adiciona arquivo ao staging |
| `git commit -m "msg"` | Commita as mudanças |
| `git status` | Mostra o status do working directory |

## Branches
| Comando | Descrição |
|---------|-----------|
| `git branch` | Lista branches |
| `git branch <nome>` | Cria uma nova branch |
| `git checkout <nome>` | Muda para a branch |
| `git merge <nome>` | Mescla a branch atual com a branch especificada |

## Remotos
| Comando | Descrição |
|---------|-----------|
| `git remote add <nome> <url>` | Adiciona um remoto |
| `git push <remoto> <branch>` | Envia commits para o remoto |
| `git pull` | Atualiza o repositório local |
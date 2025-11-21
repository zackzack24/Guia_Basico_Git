## Git Fetch

> [!IMPORTANT]  
> Para fazer um git fetch com segurança, é importante saber que ele baixa as alterações sem aplicá-las ao seu repositório local, o que permite inspecionar as novidades antes de mesclá-las. Para evitar conflitos, você deve inspecionar o histórico das alterações baixadas e decidir se fará um git merge ou git rebase posteriormente, ou se usará git pull se quiser buscar e aplicar tudo de uma vez.  

- Cuidados importantes antes de um Git Fetch
    - Não interfere no seu trabalho: O git fetch atualiza apenas as referências aos branches remotos (como origin/main), mas não altera o seu branch de trabalho atual. Isso significa que você pode continuar trabalhando sem a interrupção causada por uma fusão automática.
    - Permite a revisão: Antes de mesclar as alterações, você pode inspecionar o histórico remoto e compará-lo com o seu branch local para entender as mudanças usando comandos como git log ou git diff.
    - Evita conflitos acidentais: Como o fetch não faz a fusão automática, ele evita que conflitos inesperados ocorram imediatamente na sua árvore de trabalho. Você pode resolver os conflitos localmente, de forma mais controlada.
    - Escolha o próximo passo com cuidado: Após o fetch, você tem a liberdade de decidir como integrar as alterações.
      - git pull: Se você deseja a abordagem mais rápida, use git pull para baixar e aplicar as alterações de uma vez.
      - git merge: Você pode fazer um git merge manual para juntar as alterações ao seu branch atual.
      - git rebase: Para um histórico de commits mais linear, você pode optar por git rebase para reorganizar seus commits após o fetch.
    - Gerenciamento de tags: Use a opção 
      - --prune: para remover tags locais que não existem mais no repositório remoto. 
  



## Git Pull

> [!IMPORTANT]  
> Antes de um git pull, é preciso salvar quaisquer alterações locais não confirmadas usando git stash, verificar se o repositório local está rastreando o branch remoto correto com git remote show origin, e fazer o git fetch para visualizar as mudanças sem mesclá-las imediatamente. Se você preferir um histórico mais limpo, utilize git pull --rebase para rebasear as alterações locais sobre as remotas. 

- Cuidados importantes antes de um git pull
    - Salve suas alterações: Antes de puxar as atualizações, certifique-se de que não há alterações de código não salvas. Use git stash para armazenar temporariamente essas modificações e evitar conflitos.
    - Verifique o branch correto: É crucial garantir que você está atualizando o branch local correto. Execute git remote show origin para confirmar que seu branch local está rastreando a branch remota certa.
    - Veja as mudanças primeiro: Utilize git fetch para buscar as alterações do repositório remoto sem aplicá-las imediatamente. Isso permite que você revise os novos commits e se prepare para possíveis ajustes.
    - Considere o rebase para um histórico limpo: Se você prefere um histórico de commits linear e organizado, use git pull --rebase. Isso mantém suas alterações locais sobrepostas às alterações remotas, evitando commits de mesclagem desnecessários.
    - Teste após a atualização: Depois de realizar o git pull, execute os testes locais para garantir que não houve problemas ou quebra no código durante a mesclagem.
    - Comunicação com a equipe: Se trabalha em equipe, alinhe com os colegas qual é o padrão adotado (por exemplo, se o padrão é fetch primeiro ou pull direto) para evitar confusões. 



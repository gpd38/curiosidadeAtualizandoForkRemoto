# Atualizando Fork Remoto
Os comandos a seguir devem ser utilizados quando você deseja atualizar um projeto remoto enviando correção ou sugestão de melhoria.

#### Criar uma nova branch
Comando: <code>git branch alteracao</code>

#### Mudar para a branch criada
Comando: <code>git checkout alteracao</code>

#### Enviar para o repositório remoto
Comando: <code>git push --set-upstream origin alteracao</code>

#### Configurar Repositório Remoto
Comando: <code>git remote add upstream "endereço do projeto de origem"</code>

#### Sincronizando o fork
Comando: <code>git fetch upstream</code>

#### Merge da branch local com a remota
Comando: <code>git merge upstream/master</code>
ou
Comando: <code>git rebase upstream/master</code>

#### Criar um pull request
Comando: <code>git pull upstream master</code>

Comando: <code>git push origin master</code>

Os administradores do repositório remoto receberão uma notificação do seu pull request. Agora, basta esperas a sua aprovação.

# principais comandos GIT

git init
- iniciar novo projeto com git

git add <nome-arquivo>/.
- adiciona os arquivos, estão prontos para serem comitados

git commit -m "mensagem commit"
- comita os aquivos no históricos

git log
- mostra os ultimos comitesm log de alterações

git stataus
- como está o estado da nossa ramificação

git diff
- mostra o que foi alterado
- o que tem de alteração na ramificação

git merge
- mescla ramificações

git branch
- mostra a branch atual

git checkout <nome-branch>
- muda para essa branch

git branch -b <nome-da-branch>
- criar uma nova branch a partir do branch atual que estamos

git remote set-url origin https://github.com/Aldelanio10520/Quiz.git /
git remote -v /
git push -u origin main
- conecta no repositorio e joga os arquivos lá

git remote add <nome> <url>
- add um novo repositorio remoto

git push <nome> <nome-da-branch>
- manda nossas alterações locais para o repositorio remoto, pra cada branch

git pull <nome> <nome-da-branch>
- pega as alterações do repositorio remoto, o jogo para nossa maquina

git fetch
- atualiza o nome historico local de acordo com o historico salvo la no repositorio original
- sincronização do local com o remoto


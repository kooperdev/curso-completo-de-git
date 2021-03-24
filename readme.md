git init
Inicia o repositório git em um diretório
git status
mostra as informações em relação aos arquivos criados e modificados.
git add
adiciona os arquivos para serem assistidos pelo git
git branch
mostra o branch atual em que estou trabalhando
git commit
aplica a modificação no branch
git log
mostra as modificações por commit feita ao branch
git reset --hard <hash>
volta para outra modificação feita excluido a atual
git reset --soft <hash>
volta pra outro commit mantendo os arquivos do atual e mantendo os arquivos no add
git reset --mixed
volta para o commit passado mantendo o commit atual mas não adicionado para o próximo commit.
git diff 
verifica as modificações feitas nos arquivos
--name-only mostra apenas o nomes dos arquivos
git checkout
usado para se movimentar entre os branch
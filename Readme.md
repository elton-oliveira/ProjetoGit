Informações sobre o projeto do Git
git init //inicializar o git
git status //verificar status do projeto (untracked - não rastreado)
git add . ou git add Readme.md // mandar para tracked (rastreado)
git commmit -m "primeiro commit" //-m de message
git remote add origin https://github.com/elton-oliveira/ProjetoGit.git
    remote --> conexao do local com o remoto
    add --> adicionando remoto
    origin --> apelido dado ao repositorio remoto
git push -u origin main // enviando pro repositorio github (-u só a primeira vez)
git checkout -b "novo-botao" //Cria nova branch e já entra nela
git checkout main // entra na branch main
git merge novo-botao // pega a branch que  quer juntar com a main
git clone https://github.com/elton-oliveira/ProjetoGit.git // pega o repositorio de alguem e copia pro computador
git pull // verifica se há atualizações no repositorio baixado e atualiza

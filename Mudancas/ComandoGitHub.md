git config --global user.name "<nome>" //Configurações iniciais
git config --global user.email "<email>" //Configurações iniciais

git config user.name //verificar
git init //caso queira iniciar o projeto git já local
---------------------------------------------------------------------

git status //verificar a situação de monitoramento dos arquivos do projeto

Git add //adiciona os arquivos pode ser um pedaço <nome> ou tudo <.>

git commit –m “<descrição>” // coloca na memoria o que deve ir para o GitHub

git remote add origin <endereço> //Monitora o gitHub que vamos mandar os arquivos
git remote -v // verificar os diretórios apontados
git remote rename <nomeAntigo> <novoNome> // renomear
git remote rm <origin> // remove o diretório apontado

git push -u origin master //Envia os arquivos para o gitHub


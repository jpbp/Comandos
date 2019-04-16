# Comandos
php -S localhost:8000 -t // congigurar servidor local

//descompactar e compilar arquivos targz
tar -xzvf nomearquivo.tar.gz
cd nomearquivo 


java -jar JFLAP8_beta.jar // rodar jflap
git config --list // ver se o usuario esta logado
mkdir (nome da pasta) // criar pastas
git diff // ver modificação antes do add 
git diff --staged // ver modificação apos o add
git log --pretty=oneline // ver nomes dos commits
git log // ver pela interface grafica do git os commits
git commit --amend -m // quando esquecer de commitar algum arquivo que deveria e querer editar esse sem dar dois commits, usando um só
git reset HEAD <nomearquivo> // quando vc adicionou um arquivo teste, e não quer q ele vá para seu commit
git checkout -- nomearquivo // ele vai descartar as alterações q foram feitas no seu projeto. reverter ao original cocmmmi.
git tag // ver as tag alocadas
git tag -a versaoN [chave de um commit anterior (opcional)] -m "comentario da tag" // adicionar tag
git tag -d <nomearquivo> // excluir tag
git show nometag // mostrar tudo sobre a tag.
git branch nomebranch // criar branch
git checkout nomebranch// ele troca as branch
git merge nome do arquivo que você fez as alterações // e vc tem q estar na branch que vc quer mesclar.
git branch -d nomebranch // excluir branch.
git checkout -b teste2 // criar branch e ja trocar pra ela
git remote add origin <servidor> // Se você não clonou um repositório existente e quer conectar seu repositório a um servidor remoto, 
git push origin master // enviar a head para git
git remote add origin <servidor> // caso não tenha clonado o diretorio
git config --global user.email "email-que-usou-pra-criar-a-conta-do-github"
git config --global user.name "nome-do-seu-usuario-de-login-do-github"
git config --list // saber usuario
git pull

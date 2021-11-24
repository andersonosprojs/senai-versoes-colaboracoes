# senai-versoes-colaboracoes

#### Configurações iniciais:
 * git config --global user.name <nome-usuario>
 * git config --global user.email <email-usuario>
 
#### Criar repositório local:
 * git init

#### Gerenciamento do repositório local:
 * git status
 * git add .
 * git commit -m "Informacao importante sobre aquelas alterações"
 * git log
 
 #### Integração do repositório local com o repositório remoto:
  * git remote add origin https://github.com/andersonosprojs/senai-versoes-colaboracoes.git
  * git remote -v
  * git push -u origin master
  * git pull

 #### Gerenciamento de branch's
  * git branch <nome-branch> (Criando branch)
  * git checkout <nome-branch> (Acessando branch)
  * git branch -a (Visualização das branch's)
  * git fetch ("Puxar" todas as branch's)
 
 #### Fazer a mesclagem das branch
  * git merge origin/login

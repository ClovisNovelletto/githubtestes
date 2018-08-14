# Githuib

Arquivo da aula de Git e Github para iniciantes.

Staus
untracked - não marcado, acabou de ser colocado no repositório, Git ainda não reconhece.
unmodified - não foi modificado, já foi colocado no Git
modified - após a primeira edição.
staged - area onde é criada a versão. Quando a versão é fechada os arquivos são mudados para unmodified.

teste edição, novo teste de edição.

ls lista arquivos da pasta
git commit passar arquivo para staged
git status mostra o status atual 
git add adicionar um arquivo
git log ver histórico do projeto
git log --decorate
<<<<<<< HEAD
git log --author="Clovis"
=======
git lot --author="Clovis"
>>>>>>> 1d1f157fc9d2947d0e21924981b022ca192da166
git shortlog 
git shortlog -sn
git log --graph
git diff
git diff --name.only

<<<<<<< HEAD
git checkout
git head
git reset --soft colocar a hash anterior volta como staged
git reset --mixed volta como edição
git reset --hard elimina definitivo

e agora
=======
editado no github
>>>>>>> 1d1f157fc9d2947d0e21924981b022ca192da166

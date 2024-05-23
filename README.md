# git

git config --global user.name "User Name"

git config --global user.email useremail@email.com

Ao usar o global estamos informando que será em todos os repos, pode retirar o global para configurar somente para o repo atual

git config --list -> lista configs do git

git commit --amend --no-edit -> Faz o commit e preserva o comentário anterior (tem que usar git push -f)

git cherry-pick -> Pega as mudanças dos commits e aplica em um novo commit para cada um

git checkout -b "nome da da branch" -> cria nova branch apartir da atual

git checkout nomedabranch -> navega entre as bracnhs

git branch -m "novo nome" -> muda nome da branch

git reset HEAD˜1 -> Desfazer o ultimo commit feito

git commit --allow-empty -m " "

git stash

git stash pop



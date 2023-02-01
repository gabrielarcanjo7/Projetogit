# *Olá esse projeto ensina a voçê a usar as principais ferramentas do Git.*

( Os commits não estão com uma mudança consideravél, pois são estudos de prática pessoal )
____________________________________


* git --version : saber a versão do git.
------------------------------------
* git init : cria um novo repositorio.
______________________________________
* git add nomedoarquivo : "chama voce la dos fundos do palco para ficar na área do aguardo" (O palco é o commit).

* git add . : chama todos os arquivos para o standing
______________________________________
* git commit -m "nomedocommit" :Cria um commit.
_______________________________________
*git branch -M "main" : muda o nome de main para master.
_________________________________________
* git remote and origin "https://github.com/gabrielarcanjo7/nomedoprojeto.git" : 

seria como "git, faça essa conexão, do repositorio local ao repositorio do github".
________________________________________
* git push --set-upstream origin master : empurra os commits que tao no repositorio central para o repos. do github.

(git push origin main : Outra forma caso der errado a primeira, há também esta.)

o origin se refere ao apelido do branch >>> origin main.

__________________________________________
* clear : limpa o conteudo do git bash.
__________________________________________
* git status : mostra o status do git.
__________________________________________
* git checkout -b "nomedabranch" : cria uma nova branch.

ou, git branch "nomedabranch".

git branch : mostra qual branch voçê está.
__________________________________________
* git checkout main : volta para branch main ou alterna entre qualquer outra.
__________________________________________
* git reflog : visualiza as alterações feitas.
__________________________________________
* git reset --hard 1658aa4 : volta as versões antigas do código por meio do id que é passado pelo git reflog (o numero acima é uma demonstração)

(apenas se precisar)
____________________________________
* clear : limpa o conteudo do git bash.
____________________________________
* git status : mostra o status do git.
____________________________________
* git pull : pega as atualizações da branch do repositório para o seu repositorio local.

[
    Boas práticas para se trabalhar em equipe np git em ordem:

    1° git pull da branch principal.

    2° gerar uma nova branch apartir da principal.

    3° trabalhar e adicionar novas funcionalidades na branch que criou.

    4° finalizar o trabalho da branch temporária.

    5° git checkout na branch principal.

    6° git pull.

    7° mergiar(unir) o código da branch temporário com a branch principal( DEPOIS DE TESTAR ).

    8° git push na branch principlal.
]
# GIT E GITHUB 

## PRINCIPAIS COMANDOS

#### GERAR ITENS NA HISTÓRIA DA PRODUÇÃO DO PROJETO
* `git init` >> cria o repositório, repositório é um local 
aonde está sendo guardado/gravado as alterações do projeto
* `clear` >> limpa a tela
* `touch nome-do-arquivo.tipo` >> cria um arquivo
* `git add nome-do-arquivo.tipo` >> adiciona ou atualiza o item no repositório local,
`git add .` adiciona todos os itens.
* `git commit -m "mensagem"` >> envia o arquivo para o repositório
local e adiciona uma mensagem

#### CONFERIR MUDANÇAS FEITAS NO PROJETO 
* `git status` >> informa o estado/status das alterações do projeto
* `git log` >> obtem o registro de todas as atualizações do projeto
* `git show código-do-commit` >> apresenta detalhadamente a atualização 
do arquivo através do código do commit, apenas `git show` apresenta a última
atualização 

#### INICIAR UMA NOVA FUNCIONALIDADE NO PROJETO, SEM DANIFICAR O QUE JÁ FOI REALIZADO
* `git branch nome-da-branch` >> cria uma branch/ramificação, apenas `git branch`
exibe todas as branch's/ramificações
* `git checkout nome-da-branch` >> muda de branch/ramificação 
* `touch nome-do-arquivo.tipo` >> cria um arquivo
* `git add nome-do-arquivo.tipo` >> adiciona o item no repositório local
* `git commit -m "mensagem"` >> envia o arquivo para o repositório local
local e adiciona uma mensagem
* `ls -al` >> lista todos os arquivos do projeto

#### ADICIONAR AS NOVAS FUNCIONALIDADES AO PROJETO EM PRODUÇÃO
* `git merge nome-da-branch` >> une os arquivos entre as branch's/ramificações 

#### DELETAR A BRANCH/RAMIFICAÇÃO DA NOVA FUNCIONALIDADE, DEPOIS DE APLICAR NO PROJETO
* `git branch -D nome-da-branch` >> exclui a branch no repositório local.

#### ENVIAR O PROJETO PARA O GITHUB
* `git remote add origin https://github.com/nome-do-usuario/nome-do-repositorio.git` >> ativa o acesso remoto
* `git remote -v` >> visualiza o repositório remoto
* `git push ` >> envia para o repositório remoto/usuario do github, na primeira vez que 
enviar o projeto o comando deve ser `git push -u origin master` 
* `git config credential.helper store` >> comando para que todas as vezes que 
enviar para o github não precisa informar o email e a senha.

#### ADQUIRIR UM PROJETO INICIADO
* `git clone https://github.com/nome-do-usuario/nome-do-projeto.git` >> clonar um repositório/projeto

#### RESOLVER CONFLITO
* `git checkout -b nome-da-branch` >>  cria uma branch/ramificação e muda de branch/ramificação
* `git commit -am "mensagem"` >> adiciona o(s) item(ens) no repositório e os comenta
* `git merge nome-da-branch` >> une os arquivos entre as branch's/ramificações 

#### ATUALIZAR O PROJETO LOCAL, ANTES DE ENVIAR A RESOLUÇÃO
* `git pull` >> lista todas as atualizações que estão no repositório remoto

#### VOLTAR UM ARQUIVO PARA UM DETERMINADO MOMENTO NA BRANCH/RAMIFICAÇÃO E RECUPERA-LO SE FOR EXCLUIDO
* `git log` >> obtem o registro de todas as atualizações do projeto
* `git checkout código-do-commit -- nome-do-arquivo.tipo` >> recupera o arquivo em 
seu estado anterior



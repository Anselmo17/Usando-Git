
#Iniciando o Git
Entre no diret�rio que deseja controlar a vers�o e inicie o Git assim:

#git init

--------------------------------------------------------------
Feito isso, seus arquivos ainda n�o est�o sendo versionados, 
mas eles est�o esperando para serem adicionados no est�gio de
 controle. Para fazer isso digite o comando

#git add nome-do-arquivo-incluindo-extens�o

-------------------------------------------------------

Se voc� precisa adicionar todos os arquivos do diret�rio, basta digitar:

#git add .
---------------------------------------------------------
Saber o status do projeto
#git status
---------------------------------------------
Voltando ao est�gio anterior do adicionamento:

#git reset HEAD nome-do-arquivo

---------------------------------------------
Commit � Comitando:

#git commit -m "Mensagem do commit"
-----------------------------------
Adicionando e comitando ao mesmo tempo:

#git commit -a -m "Mensagem do commit"
---------------------------------------------
Voltar um commit:

#git reset HEAD~1
-------------------------------------------
Voltar dois commits:

#git reset HEAD~2
-------------------------------------------
Voltando um commit e deixando o arquivo no estagio anterior:

#git reset HEAD~1 --soft
--------------------------------------------------------------
Voltando um commit e excluindo o arquivo, deixando no est�gio anterior:

#git reset HEAD~1 --hard
-------------------------------------------------------

Verificando o hist�rico de commits:

#git log
------------------------------------------------------
Criando um branch � uma ramifica��o

#git checkout -b nome-do-branch
-----------------------------------------
Verificando em que branch voc� est�

#git branch
----------------------------------------
Voltando para o branch master

#git checkout master
-------------------------------------
Jogando o branch criado no branch master
Entre como branch master:

#git merge nome-do-branch-que-foi-criado
-----------------------------------------
Clonando um projeto remoto:

#git clone url-do-projeto
------------------------------------------------

Fazendo um clone de outros branchs:

#git checkout -b nome-do-branch origin/ nome-do-branch
-----------------------------------------------
Trazendo, puxando as altera��es feitas por outros usu�rios:

#git pull origin master
------------------------------------------------------
Sincronizando tudo que est� no reposit�rio remoto:

#git pull
-----------------------------------------------------
Enviando o(s) projeto(s), arquivo(s) para o reposit�rio:

#git push origin master
--------------------------------------------------
Enviando um branch para o reposit�rio:

#git push origin nome-do-branch




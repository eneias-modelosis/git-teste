# Repositorio para exercícios de aprendizado no git e github

Principais comandos:

``git config --global user.name "João Silva"``

``git config --global user.email "exemplo@seuemail.com.br"``

``git init``

``git add .``   (ou os nomes dos arquivos que deseja adicionar)

``git commit -m “Mensagem do commit” ``


Verificar se o nome do branch principal no github está diferente do branch local, executando ``git status`` no repositório local, e verificando o branck default no github.
Se no local estiver master e no remoto estiver main, executar 
``git branch -m master main``

``git remote add origin <URL_HTTPdo_repositório>``

``git push -u origin main``

``git pull origin main``

``git dif`` mostra as alterações

``git log –graph``  exibe o grafico dos branches

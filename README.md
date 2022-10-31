# Sturdy-Disco

Uma estrutura de arquivos utilizando o docker compose, quando executado o **init.sh**, ele cria trés containers, um servidor https-php com certbot, um banco de dados mariaDB e o phpmyadmin para gerenciar o banco de dados.

---

## Aonde coloco meus arquivos?

Você apenas substitui os aquivos do */www/*

## Como altero as senhas/usuarios e o nome do projeto?

Você altera essas coisas no arquivo *.env* localizado na raiz da pasta

## Como eu rodo o script?

dentro do seu shell de preferencia (obs. por exceção do powershell) rode-o assim:

> $./init.sh

caso o shell retorne um erro, execute isso; e tente novamente o comando acima

> $sudo chmod +x init.sh

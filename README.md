# Instruções basicas do git e GitHub no windows

**Faça o downolad do git no link** [download git](https://git-scm.com/downloads)
***

## Terminal git bash
**configurar usuario, de preferência use o mesmo email de cadastro no github**  
- `git config --global user.name "fulano de tal"`
- `git config --global user.email "fulanodetal@exemplo.com"`
***

## Criar uma chave SSH Key no git
**No terminal git e use os comandos abaixo:**
- `ssh-keygen -t rsa -b 4096 -C "fulanodetal@exemplo.com"`
- `ssh-keygen -y`
- copie a chave que apareceu do teminal git  começa com `ssh` termina com seu email `fulanodetal@exemplo.com`
***

## Acesse seu GitHub
**Click na foto perfil usuário que está no canto superior direito nevegue ***Setting>SSH and GPG Keys>New SSH Key*****
- ***Title***  Defina o nome da sua chave  
- ***Key*** cole a chave que copiou do terminal git
- click ***Add SSH Key***
***

## New repositorio  gitHub
- ***Repositories>New***
- ***Repository name***  defina um nome para o repositório
- click ***Create repository***
***

## Dentro da pasta do projeto
**Click com o botão direito do mouse e navegue ***Mostrar mais opções>Open Git Bash here***, depois digite os comandos abaixo no terminal:**
- `git init`
- `git add .`
- `git commit -m "iformarmação que faça sentido"`
- `git branch -M main`
- `git remote add origin git@githubcom:fulanodetal/repositorio.git`
- `git push -u origin main`
***

## Alterações do projeto de forma local**
**Click com o botão direito do mouse navegue ***Mostrar mais opções>Open Git Bash here***, depois digite os comandos abaixo no terminal:**
- `git add .`
- `git commit -m "o que alterou"`
- `git push`

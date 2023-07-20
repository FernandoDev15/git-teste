# Instruções git e GitHub usando o windows

**Faça o downolad do git no link abaixo:**
[download git](https://git-scm.com/downloads)

**No terminal git bash**
-configurar usuario, de preferência use o mesmo email de cadastro no github  
1. `git config --global user.name "fulano de tal"`
2. `git config --global user.email "fulanodetal@exemplo.com"`

**Criar uma chave SSH Key no git**
No terminal git e use os comandos abaixo:
1. `ssh-keygen -t rsa -b 4096 -C "fulanodetal@exemplo.com"`
3. `ssh-keygen -y`
4. copie a chave que apareceu do teminal git  começa com `ssh` termina com seu email `fulanodetal@exemplo.com`

**Na sua cocnta GitHub**
Click na foto do seu perfil que no canto superior direito `Setting>SSH and GPG Keys>New SSH Key`
6. `Title` Defina o nome da sua chave  
7. `Key` cole a chave que copiou do terminal git
8. click `Add SSH Key`

**criar um repositorio no gitHub**
1. `Repositories>New`
2. `Repository name` defina um nome para o repositório
3. click `Create repository`

**Dentro da pasta do projeto**
Click com o botão direito do mouse navegue `Mostrar mais opções>Open Git Bash here` digite os comandos abaixo no terminal:
1. `git init`
2. `git add .`
3. `git commit -m <"iformarmação que faça sentido">`
4. `git branch -M main`
5. `git remote add origin git@githubcom:fulanodetal/repositorio.git>`
6. `git push -u origin main`

**Depois das alterações do projeto de forma local**
Click com o botão direito do mouse navegue `Mostrar mais opções>Open Git Bash here` digite os comandos abaixo no terminal:
1. `git add .`
2. `git commit -m "o que alterou"`
3. `git push`

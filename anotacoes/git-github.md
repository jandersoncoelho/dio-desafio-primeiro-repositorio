# Introdução ao Git e GitHub

## Primeiros comandos com o Git

- Iniciar o Git:

  - `git init`

- Iniciar o Git:

  - `git add .`

- Criar um commit:

  - `git commit -m "descrição do que foi adicionado" .`

- Verificar a situação do repositório

  - `git status`

## Fazendo upload das alterações em um repositório remoto

- Apontar para o repositório local onde está localizado o repositório remoto:

  - `git remote add origin https://endereco-servidor-remoto/repositorio-remoto .`

- Listar repositórios remotos cadastrados:

  - `git remote -v`

- Dar o upload para o repositório remoto:

  - `git push origin master`

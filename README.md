# Repositorio-GetStarted-K1-T1

Este repositório foi criado como parte da atividade K1-T1 da trilha de Versionamento de Código.

## Configuração Inicial do Git

Antes de começar a usar o Git, é importante configurar algumas opções globais:

* `git config --global user.name "Seu Nome"`: Define seu nome para os commits.
* `git config --global user.email "seu.email@exemplo.com"`: Define seu email para os commits.
* `git config --global init.defaultBranch main`: Define `main` como branch padrão (ao invés de `master`).

## Principais Comandos do Git

Aqui está uma lista dos comandos mais utilizados no Git:

* `git init`: Inicializa um novo repositório Git na pasta atual.
* `git status`: Mostra o estado dos arquivos no diretório de trabalho e no stage.
* `git add <arquivo>`: Adiciona um arquivo ao stage para ser incluído no próximo commit.
* `git commit -m "mensagem"`: Grava as mudanças do stage no histórico do repositório.
* `git push`: Envia os commits locais para o repositório remoto.
* `git pull`: Puxa as atualizações do repositório remoto para o local.
* `git clone <url>`: Clona um repositório existente para a sua máquina local.
* `git branch -m <nome-antigo> <nome-novo>`: Renomeia um branch (ex: `git branch -m master main`).
* `git remote add origin <url>`: Adiciona um repositório remoto chamado 'origin'.
* `git push -u origin main`: Faz push do branch main e configura o upstream.
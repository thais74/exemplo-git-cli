# Exemplos de comandos básicos para via CLI

## Comandos de uso geral da CLI

- Criar pasta: mkdir nomepasta
- Listar conteúdo: dir
- Limpar tela: cls
- Entrar na pasta: cd nomepasta

## Comandos principais do Git

`git config user.name` e `git config user.email`
Verificar usuário/email

`git config --global user.name "seu nome"` e `gitconfig --global user.email "seu email"`
Mudar usuário e e-mail de forma global.

`git init`
Inicializar um repositório (executado dentro da pasta)

`git branch nome-branch-atual novo-nome-para-branch`
renomear branches
renomear a branch de **master** para **main** (novo padrão), usaríamos: `git branch master main`

`git status`
Verificar o status atual do repositório

`git add nomearquivo`
Adicionar (tornar arquivo rastreável) ao monitoramento da git

`git commit -m "texto da mensagem"`
Fazer commit das alterações (salvar no repositório)


`git remote add origin endereço-do-repositorio.git`
Adicionar/conectar o repositório remoto ao local

`git push origin main`
Enviar as mudanças para o github(PUSH).

`git pull origin main`
Pegar/obter as mudanças do repositório online GitHub (PULL).

`git clone endeeço-do-repositorio.git`
Clona o endereço de um repositório para a máquina remota

`git clone endereço-do-repositório.git`
Copiando/baixando um repositório para a máquina remota
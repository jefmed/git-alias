# git-alias
template alias for git commands

### acesse no terminal
$ vim ~/.gitconfig

### copie e cole o trecho abaixo

```
[user]
	email = your.email@email.com
	name = your name

[alias]
  git pom = Coloca a branch Master como upstream do projeto.
  git ps = Push simples.
  git ci = Gera o commit somente com a mensagem, sem precisar de aspas.
  git co = Checkout simples.
  git cm = Faz checkout na branch Master.
  git cd = Faz checkout na branch Develop.
  git cb = Cria uma nova branch e faz checkout para a mesma.
  git st = Mostra as informações de track/commit de forma sucinta e objetiva.
  git sf = Mostra os arquivos que foram modificados por um commit.
  git lg = Mostra o log da arvores de commits de uma forma mais explicita e intuitiva.
  git incoming = Mostra todos os commits que estão no git para chegar com o pull.
  git outgoing = Mostra os commit feitos no projeto que estão prontos para push.
  git unstage = Remove o arquivo do commit.
  git undo = Desfaz uma alteração no arquivo e volta para o estado inicial do commit.
  git resetlocal = Desfazer alterações de TODOS os arquivos locais e volta para o estado inicial do commit.
  git rollback = Defaz o ultimo commit, mas mantem os arquivos.

```

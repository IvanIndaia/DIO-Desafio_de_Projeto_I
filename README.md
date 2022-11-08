# Repositório do Desáfio de Projeto da DIO
Repositório criado para o desáfio de projeto Git/Github

<br>

## GIT e GITHUB :octocat:

### Introdução ao Git

- Entendendo o que é GIT e sua importancia

### Navegação via command line interface e instalação

- Comandos básicos para um bom desempenho no terminal
	- Mudar de pastas
	- Listar as pastas
	- Criar pastas/arquivos
	- Deletar pastas/arquivos

			> Windows
			  - cd
			  - dir
			  - mkdir
			  - del/rmdir

			> Unix
			  - cd
			  - ls
			  - mkdir
			  - rm -rf

- Realizando a instalação do GIT

### Entendento como o Git funciona por baixo dos panos

- Tópicos fundamentais para entender o funcionamento do GIT
- Objetos internos do GIT
- Chave SSH e Token
  
		Encriptando uma string pelo GIT
		$ echo 'conteudo' | git hash-object --stdin

		Encriptando uma string pelo OpenSSL
		$ echo -e 'conteudo' | openssl sha1
		ou
		$ echo -e 'blob \conteudo' | openssl sha1
		
		Gerar chave SSH no Git
  		$ ssh-keygen -t ed25519 -C 'e-mail'
		
		Generating public/private ed25519 key pair.
		Enter file in which to save the key (/c/Users/ivan.alex/.ssh/id_ed25519):

		$ cd c/Users/ivan.alex/.ssh
		bash: cd: c/Users/ivan.alex/.ssh: No such file or directory

		$ cd /c/Users/ivan.alex/.ssh

		$ ls
		id_ed25519  id_ed25519.pub

		$ pwd
		/c/Users/Ivan Alex/.ssh

		$ eval $(ssh-agent -s)
		Agent pid 1824



### Primeiros comandos com GIT

- Iniciando o GIT e criando um commit
	- Comandos GIT

			git init
			git add
			git commit


			$ git init
				Reinitialized existing Git repository in C:/workspace/livro-receitas/.git/

			$ git add *

			$ git commit -m "Primeiro commit"
				[master (root-commit) c3e75f9] Primeiro commit
				 1 file changed, 22 insertions(+)
				 create mode 100644 strogonoff.md

			$ git commit -m "Teste GIT"
				On branch main
				Your branch is ahead of 'origin/main' by 1 commit.
				  (use "git push" to publish your local commits)

				nothing to commit, working tree clean

			$ git status
				On branch main
				Your branch is ahead of 'origin/main' by 1 commit.
				  (use "git push" to publish your local commits)

				nothing to commit, working tree clean

			$ git config --list
			$ git config --global user.email "ivan.indaia@gmail.com"
			$ git config --global user.name "Ivan"
			$ git config --global --unset user.name
			$ git config --list


			Enviando repositório local para remoto
			$ git remote add origin https://github.com/IvanIndaia/livro-receitas.git
			$ git push origin master (enpurrar para a nuvem)
			$ git pull origin master (puxar da nuvem)

### Ciclo de vida dos arquivos GIT

- Passo passo no ciclo de vida

### Introdução ao Github

- Trabalhando com o Github

### Resolvendo conflitos

- Como os conflitos acontecem no Github e como resolvê-los

##### Entendendo como o GIT funciona

###### SHA1

	(Secure Hash Algorithim - NSA).
	É um algoritmo de encriptografia.
	Conjunto de caracter de 40 dígitos.
	Ele é um forma curta de representar um arquivo.
  
###### Objetos fundamentais
###### Sistema distribuído
###### Segurança
	

<!-- Olá aqui é um comentário -->



# Repositório do Desáfio de Projeto da DIO
Repositório criado para o desáfio de projeto Git/Github



<br>

## GIT e GITHUB :octocat:


### Introdução ao Git

- Entendendo o que é GIT e sua importancia

### Navegação via command line interface e instalação

- Comandos básicos para um bom desempenho no terminal

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

### Primeiros comandos com GIT

- Iniciando o GIT e criando um commit

### Ciclo de vida dos arquivos GIT

- Passo passo no ciclo de vida

### Introdução ao Github

- Trabalhando com o Github

### Resolvendo conflitos

- Como os conflitos acontecem no Github e como resolvê-los

- Mudar de pastas
- Listar as pastas
- Criar pastas/arquivos
- Deletar pastas/arquivos





##### Entendendo como o GIT funciona

###### SHA1

* Sha1
	(Secure Hash Algorithim - NSA).
	É um algoritmo de encriptografia.
	Conjunto de caracter de 40 dígitos.
	Ele é um forma curta de representar um arquivo.
  
###### Objetos fundamentais
###### Sistema distribuído
###### Segurança
	
	
* Chave SSH e Token
  
  Encriptando uma string pelo GIT
  ivan.alex@TKLCLSN07 MINGW64 ~/Desktop
  $ echo 'conteudo' | git hash-object --stdin

  Encriptando uma string pelo OpenSSL
  $ echo -e 'conteudo' | openssl sha1
  ou
  $ echo -e 'blob \conteudo' | openssl sha1
	Gerar chave SSH no Git
  
		ivan.alex@TKLCLSN07 MINGW64 ~
		$ ssh-keygen -t ed25519 -C ivan.indaia@gmail.com
		Generating public/private ed25519 key pair.
		Enter file in which to save the key (/c/Users/ivan.alex/.ssh/id_ed25519):

		ivan.alex@TKLCLSN07 MINGW64 ~
		$ cd c/Users/ivan.alex/
		bash: cd: c/Users/ivan.alex/: No such file or directory

		ivan.alex@TKLCLSN07 MINGW64 ~
		$

		ivan.alex@TKLCLSN07 MINGW64 ~
		$ cd c/Users/ivan.alex/.ssh
		bash: cd: c/Users/ivan.alex/.ssh: No such file or directory

		ivan.alex@TKLCLSN07 MINGW64 ~
		$ cd /c/Users/ivan.alex/.ssh

		ivan.alex@TKLCLSN07 MINGW64 ~/.ssh
		$ ls
		id_ed25519  id_ed25519.pub

		ivan.alex@TKLCLSN07 MINGW64 ~/.ssh
		$ cat id_ed25519.pub
		ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIPWHOEoGmAAyXZCKVuOTTzxbR2IF/eWFbCIgojc5ezVL ivan.indaia@gmail.com
		
		Chave publica Note Particular:
		AAAAC3NzaC1lZDI1NTE5AAAAIJvP0XDNKpdK24KHhXaJcjrm17gsVSSlXWmguREwdvGS ivan.indaia@gmail.com


	
		Ivan Alex@Note-Ivan MINGW64 ~/.ssh
		$ pwd
		/c/Users/Ivan Alex/.ssh

		Ivan Alex@Note-Ivan MINGW64 ~/.ssh
		$ eval $(ssh-agent -s)
		Agent pid 1824

		Clonando Repositório
			Ivan Alex@Note-Ivan MINGW64 ~/.ssh/teste
			$ git clone git@github.com:IvanIndaia/MOB.git

	
Comandos GIT

		-> Iniciar o Git
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
			
			$ git config --global --unset 

			$ git config --list

			
		Enviando repositório local para remoto
		$ git remote add origin https://github.com/IvanIndaia/livro-receitas.git
		$ git push origin master (enpurrar para a nuvem)
		$ git pull origin master (puxar da nuvem)





Criando plano de estudo para FrontEnd com Github

#### Criado em 07/11/2022 :star: :grapes:

- Aprender a programar
- Aprender estilização com CSS3
- Aprendendo JS

## Meta
> Fazer o curso: [Introdução a criação de websites com HTML5 e CSS3](https://www.youtube.com/watch?v=N48-pB4OOhk)
> Total do curso 6h: 2h/Semana

- [x] Parte 1 - 10/11/22
- [ ] Parte 2 - 17/11/22
- [ ] Parte 3 - 24/11/22
- [ ] Parte 4 - 01/12/22

# Exemplo de Tasks: Planejamento de Cursos em um Mês

## Metas do Mês de Novembro:
- [x] Curso de Introdução a Criação de Websites com HTML5 e CSS3 [6h] (13/11/2022)
- [ ] Programação para Internet com HTML5 e CSS3 [6] (26/11/2022)
- [ ] Construindo Página para Internet com Bootstrap [4h] (30/11/2022)

<!-- Olá aqui é um comentário -->



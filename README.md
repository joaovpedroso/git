# Git e GitHub
Instalação e Configuração Git e GitHub


** Primeiros Comandos:

	- Inicializar o git no repositório
		*git init

	- Configurar o nome de usuário
		*git config --global user.name NOME_DE_USUARIO

	- Configurar o email de usuario
		*git config --global user.email EMAIL_DE_USUARIO

	--- Listar as configurações já realizadas
		*git config --global -l

	- Gerar uma chave de codificação do PC com o GIthub
		*ssh-keygen -C "EMAIL_DE_USUARIO"
		*ENTER
		*INFORME A SENHA
		*REPITA  A SENHA
	
	- Ver a chave gerada
		*cat ~/.ssh/id_rsa.pub
	
	- Adicionar na Conta Github
		*Entrar no Site -> Settings -> SSH Keys -> New SSH Key	
		*Titulo | e Chave
		* Add Key

	- Testar a Conexão com o Github
		*ssh -T git@github.com
	
	
	- Listar o status do repositório Local
		*git status
	
	- Controlar o arquivo
		*git add nome_do_arquivo
		*adicionar todos os arquivos git add .

	- Realizar um commit do arquivo | Uma foto dele
		*git commit -m ' Mensagem da alteração realizada '

	- Clonar o repositório do Github no PC
		*git clone link_do_repositorio

	- Enviar arquivos ao Repositório do GIT - GIT PUSH
		*git push 
	
	- Atualizar o repositório local com alterações realizadas por outros usuários no GitHub
		*git pull
	
	- Listar todos os COMMIT´s realizados
		*git log

---------------- ****** COMANDOS BÁSICOS ****** -------------

	GIT INIT -> Inicializar o Git no Diretório
	GIT CLONE -> Clonar o repositório no PC
	GIT ADD -> Adicionar um arquivo na lista de Transferencias
	GIT COMMIT -M -> Realizar um snapshot da transferencia com uma mensagem
	GIT PUSH -> Enviar Alterações ao Repositório do GitHub

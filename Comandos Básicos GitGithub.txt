### BOOTCAMP DIO TQI FULLSTACK Git/Github :cactus:

[Link de instalação do git] (https://git-scm.com/downloads)

### Passos :footprints:
•	Iniciar o Git
•	Configurar o Git
•	Adicionar arquivo
•	Comitar

####  COMANDOS GIT TÍPICOS
Crtl l	  //limpa a tela
Ls 		//lista (igual ao DIR)
Ls -a    //lista arquivos ocultos

##### PARA INICIAR O GIT
git init  		//iniciar o git – pode ser já na pasta desejada

##### PARA CONFIGURAR O GIT
git config  - -global  user.email seuemail@email.com
git config - - global user.name seuusuario

​					//Se queremos resetar essas configurações:
git config - - global - - unset user.email 
git config - - global - - unset user.name

​					//Para verificar a configuração atual:
git config –list

q 				//para sair

##### ADICIONAR ARQUIVO
git add .                //considera o arquivo para o controle de versão. Faz o stage do arquivo para commit no repositório local.
git add *  	         //considera todos os arquivos

git add <arquivo>



##### COMITAR 
git commit -m “descrição do commit”
git push origin main    // envia todos os commits para o servidor remoto, no caso, o Github
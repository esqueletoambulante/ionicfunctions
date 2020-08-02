Setup Inicial

1) Criação do repositório no GitHub: https://github.com/esqueletoambulante/ionicfunctions

2) Instalação do git: https://git-scm.com/

Versão 2.27.0 (último release disponível) baixada em 26/07/2020 e instalada com "next-next-finish" sem alterações.

3) Clonar repositório

  git clone https://github.com/esqueletoambulante/ionicfunctions.git
  
  
4) Instalação do Node.js: https://nodejs.org/en/

Versão 12.18.3 LTS (último release LTS disponível) e instalada com "next-next-finish" sem alterações.

5) Instalar Ionic: https://ionicframework.com/ | https://ionicframework.com/getting-started

  npm install -g @ionic/cli

6) Criar projeto Ionic/Front End 

  ionic start frontend sidemenu

7) Criar branch develop e commitar código inicial do frontend

  $ git checkout -b develop
  
  git add .
  
  git config --global user.email "you@example.com"
	
  git commit -m "Commit inicial do frontend"

  git push --set-upstream origin develop
Setup Inicial

1) Criação do repositório no GitHub: https://github.com/esqueletoambulante/ionicfunctions

2) Instalação do git: https://git-scm.com/

Versão 2.27.0 (último release disponível) baixada em 26/07/2020 e instalada com "next-next-finish" sem alterações.

3) Clonar repositório

  $ git clone https://github.com/esqueletoambulante/ionicfunctions.git
  
  
4) Instalação do Node.js: https://nodejs.org/en/

Versão 12.18.3 LTS (último release LTS disponível) e instalada com "next-next-finish" sem alterações.

5) Instalar Ionic: https://ionicframework.com/ | https://ionicframework.com/getting-started

  $ npm install -g @ionic/cli

6) Criar projeto Ionic/Front End 

  $ ionic start frontend sidemenu
  
  $ cd frontend
  
  $ ionic build

7) Criar branch develop e commitar código inicial do frontend

  $ git checkout -b develop
  
  $ git add .
  
  $ git config --global user.email "you@example.com"
	
  $ git commit -m "Commit inicial do frontend"

  $ git push --set-upstream origin develop
  
8) Instalar Visual Studio Code: https://code.visualstudio.com/

Versão 1.47.3 (último release disponível). Adicionar menus de contexto e associar extensões.

9) Criar um projeto no Google Firebase: https://firebase.google.com/

  Entrar com conta Google. "Ir para o console" > "Criar um projeto" e seguir passo a passo.
  
  "Adicionar app" > "Web"
  
10) Instalar firebase-tools e configurar Firebase

  $ npm install -g firebase-tools
  
  $ firebase login

  $ firebase init
	--> escolher Functions e Hosting
	--> "Use an existing project" e escolher projeto criado anteriormente
	--> Typescript, Yes, Yes
	--> public directory: frontend/www
	--> No, No

  Editar arquivo "functions\src\index.ts" e descomentar linhas 6 a 9
  
  Editar arquivo "functions\package.json" e alterar linha 13 de de "node": "10" para "node": "8"
  
  $ firebase deploy
  
  Ao final temos o frontend inicial implantado em https://esqueleto-ambulante.web.app e a function inicial do backend implantada em https://us-central1-esqueleto-ambulante.cloudfunctions.net/helloWorld
  
11) Commitar código inicial do backend

  $ git add .
  
  $ git commit -m "Commit inicial do backend"
  
  $ git push

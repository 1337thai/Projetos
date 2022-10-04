 1 - Abrir o terminal do vscode e digitar o comando 'npm init' e continuar a instalação (apertando enter)
após apertar enter ele vai instalar o package.json que é uma agenda em que vamos anotar todas as bibiotecas que iremos instalar.

2 - Instalar o Typescript, no terminal digite o comando: npm install -g typescript, em seguida instalar os outros pacotes do typescript: npx tsc --init e depois instalar npm install -D ts-node
em seguida irá aparecer no vscode pois arquivos que são NODE-MODULES e TSSCONFIG.JSON. node_modules é onde vai ficar todas as bibliotecas que vamos instalar e o tsconfig-json é a configuração do typescript 

3 - Ir no arquivo tsconfig.json e descomentar as seguintes linhas de código:
moduleResolution:node
"rootDir": "./src",   
"outDir": "./dist",

4 - instale a dependência/biblioteca do TS vá no terminal e digite o comando: npm install --save-dev @types/node

5 - Em seguida criar uma pasta na raiz chamada SRC

6 - criar um arquivo dentro de src (index.ts) e colocar algum código de sua preferência para testar

7 - Em seguida para rodar o projeto vamos instalar o nodemon no terminal: npm install -g nodemon  (o nodemon seve para rodarmos o projeto automaticamente)
 
8 - para rodar o projeto usar o comando 'nodemon src/index.ts' 
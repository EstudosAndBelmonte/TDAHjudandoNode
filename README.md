# TDAHjudandoNode
Projeto para ajuda de pessoas com TDAH, onde pode ser encontrado diversos sistema para ajudar a vida de pessoas que tem muita dificuldade. 

## Nodemon

Para não precisar ficar rodando o nosso servidor, podemos usar uma extensão chamado nodemon, ela executa nosso servidor e deixa ele rodando e fica procurando as modificações.
Mas algumas vezes o nodemon não é instalado corretamente. Com isso utilizamos algumas formas.

````
npm install -g nodemon

npm install --save-dev nodemon

npm config get prefix

set PATH=%PATH%;C:\Users\"Aqui seu usuario"\AppData\Roaming\npm;
````

Mas mesmo com esses comando pode acontecer de não instalar corretamente e faltar colocar no package.json, com isso vai ter que colocar na mão. 

````
"dependencies": {
    "nodemon": "^3.0.1"	
}

````
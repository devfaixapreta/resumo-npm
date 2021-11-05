# resumo-npm

## Instalação do NodeJS
* [Link gownload NodeJS](https://nodejs.org)


# Comandos npm

## install
* Instala as dependencias do package.json
```
$ npm install
```

### Arquivos criados pelo npm
/node_modules/
package.json
package-lock.json

* Adicionar /node_modules/ no .gitignore

## init
* Cria um arquivo package.json
```
$ npm init
```

## init -y
* Cria um arquivo package.json básico sem perguntas
```
$ npm init -y
```

## i 
* Instala um pacote e adicona no package.json
```
$ npm i <package>
```

## i --save-dev
* Separa as dependencias de desenvolvimento no package.json
```
$ npm i <package> --save-dev
```

## i --production
* Instala apenas as as dependencias de produção package.json
```
$ npm install --production
```

## login
* Conecta com o registry.npm
```
$ npm login
```

## whoami
* Mostra o usuario
```
$ npm whoami
```

## adduser
* Cria um usuario
```
$ npm adduser
```

## publish
* Publica um pacote no registy.npm
```
$ npm publish
```

## unpublish --force
* Exclui um pacote
```
$ npm unpublish --force
```
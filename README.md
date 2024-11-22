# Resumo npm

## Instalação do NodeJS
* [Link download NodeJS](https://nodejs.org)


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

## node -v
* Mostra a versão do node instalada
```
$ node -v
```

## npm -v
* Mostra a versão do npm instalada
```
$ npm -v
```

## npm@latest
* Atualiza o npm para a versão mais recente
```
$ npm install -g npm@latest
```

## run
* Executa um script pelo nome indicado no package.json
```
$ npm run <dev-script>
```

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
ou
```
$ npm i -D <package> 
```

## i --production
* Instala apenas as as dependencias de produção package.json
```
$ npm install --production
```

## list
* Lista as dependencias instaladas
```
$ npm list
```

## uninstall 
* Desinstala um pacote e retira no package.json
```
$ npm uninstall <package>
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

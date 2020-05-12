# Aplicação para estudo de Jasmine, Karma e TravisCI com NodeJS

[![Build Status](https://travis-ci.org/GustavoCaspirro/jasmine-node.svg?branch=master)](https://travis-ci.org/GustavoCaspirro/jasmine-node)

![N|Solid](assets/jkt.png)

## Sobre a Aplicação

- Aplicação que realiza testes com jasmine

## Informações do projeto

### Verificar se possue node e npm instalados.

```sh
// Para verificar versão do Node.
$ node -v
// Para verificar versão do NPM.
$ npm -v
```

### Instalar Jasmine.

```sh
// Instalar Globalmente
$ npm i -g jasmine
// Instalar como dependência do projeto
$ npm i --save-dev jasmine
```

### Iniciar projeto com jasmine.

```sh
$ npm jasmine init
```

### Rodar o jasmine no terminal.

```sh
$ jasmine
```

### Instalar o Karma.

```sh
$ npm i --save-dev karma
$ npm i --save-dev karma-jasmine
$ npm i karma-chrome-launcher
$ npm i -g karma-cli
```

### Configurar o Karma.

```sh
// Padrão utilizar o nome karma.config.js, após rodar, seguir passo a passo.
$ karma init karma.conf.js
```

### Browserify

- Framework que que converte as chamadas "require" utilizadas no NodeJS para algo que o navegador entenda. (Pré-Processador)

```sh
$ npm i --save-dev browserify
$ npm i --save-dev watchify
$ npm i --save-dev karma-browserify
```

### TBD - Trunk Based Development

- Desenvolvimento somente na Trunk (direto para master).

### TravisCI

- Servidor de integração continua (Open Source).

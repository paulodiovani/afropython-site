![AfroPython Logo](AfroPython_brand.png "AfroPython")

---------------------------------------
[English Version](https://github.com/AfroPython/afropython-site/blob/master/README_EN.md)

---------------------------------------

## O que é o AfroPython?
O AfroPython é uma oficina de programação que tem o objetivo de incentivar a população negra nas áreas de tecnologia, porém não é um evento exclusivo para este grupo.

O AfroPython deseja ser uma iniciativa marcante: para quem faz e para quem participa. E queremos somente marcas positivas e felizes, já que as razões que nos unem não são tão historicamente nobres: o fato de que somos 54% da população brasileira e nossa presença representa apenas 0,4% dos profissionais de Tecnologia da Informação no Brasil.

---------------------------------------

# Quero contribuir, como rodar o projeto?

A estrutura consiste em rodar os comandos básicos de um projeto, minificando, compilando e compactando arquivos.

Os arquivos devem ser organizados na pasta SRC ou na pasta padrão de conteúdo dependendo da forma como o projeto vai ser desenvolvido.
([http://localhost:8080](http://localhost:8080))!

## Softwares necessários:

- Node.js (https://nodejs.org/en/download/)
- NPM (https://www.npmjs.com/get-npm) [_incluso na versão Windows do Node.js_]
- Docker (https://docs.docker.com/install/) [_opcional_]

## Instruções de como utilizar o projeto

1 - Configurar caminho dos Git Hooks:

Importante para que antes do push seu código passe por uma validação em nossos linters.

```sh
git config core.hooksPath .githooks
```

2 - Para baixar as dependências de frontend.:

```sh
npm install
```

3 - Para rodar o projeto em [http://localhost:8080](http://localhost:8080):

```sh
npm start
```

3 - Se quiser rodar o projeto utilizando Docker, execute os comandos abaixo e acesse [http://localhost:8080](http://localhost:8080):

###### Atualmente, é preciso executar o build + run a cada alteração no código. Em breve uma alternativa será adicionada ao projeto.

```sh
docker build -t afropython/afropython-site -f Dockerfile .
docker run --rm -dt -p 8080:80 --name afropython afropython/afropython-site
```

## Outras tarefas

### NPM

* `npm install --save 'nomedependencia'` - instala a dependência desejada
* `npm run build ` - prepara o site para produção
* `npm run deploy ` - realiza o deploy

---------------------------------------

Em nossa [Wiki](https://github.com/AfroPython/afropython-site/wiki) você encontrará um pouco de nossa história :D.

---------------------------------------

Nos acompanhe em nossa página no [Facebook](https://www.facebook.com/AfroPython/)

E nosso email para contato: afropython@gmail.com

---------------------------------------

Nós do AfroPython nos esforçamos para fornecer a todos os participantes um ambiente de respeito e livre de assédio, independentemente de sexo, idade, orientação sexual, deficiência, aparência física, raça ou religião.

Leia a versão integral do nosso [Código de conduta](https://github.com/AfroPython/afropython-site/wiki/C%C3%B3digo-de-Conduta).

---------------------------------------

Abraços de toda equipe do AfroPython :yellow_heart:

# Repositório

Este repositório é destinado para ser base de novos projetos em Javascript.

Sua utilização é feita por intermédio de scripts que rodam webpack e babel para compilação de código em Javascript (principalmente ES6>).



## Modo de usar

Para utilizar deste repositório, basta clona-lo e rodar os seguintes comandos dentro da pasta:

```bash
$ npm install
$ npm run dev-server
```

Rodados os comandos abaixo basta acessar a url http://localhost:8080/ para que possa ser visualizado o website.

**A porta pode variar caso ja esteja alocado a 8080**



## Desenvolvimento

O desenvolvimento é feito dentro da pasta src/, basta editar o arquivo index.js ou criar novos - e importar-los no index.js, que irá funcionar.



## Publicação

Para publicar websites criados a partir deste boilerplate, o seguinte comando deve ser rodado dentro da pasta do projeto:

```bash
$ npm run build
```

Feito isso, basta utilizar algum programa para direcionar para o arquivo index.html dentro da pasta public.
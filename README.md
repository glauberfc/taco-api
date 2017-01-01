# TACO - Tabela Brasileira de Composição de Alimentos

## Objetivo

O objetivo deste projeto é criar uma aplicação web para facilitar a consulta de alimentos e suas respectivas informações nutricionais fornecidas pelo equipe da [UNICAMP](http://www.unicamp.br/nepa/taco/).

## Arquitetura

Foi escolhido separar as aplicações em duas partes, sendo uma o Back-end (servidor) e a outra front-end (client side).

### Back-end
O back-end foir construido utilizando a plataforma NodeJS para prover as informações dos alimentos e suas categorias através de serviços HTTP (apenas GET). Para tornar disponível online, foi hospedada a aplicação no serviço cloud [Heroku](https://www.heroku.com).

#### API
A API foi construida com base nos dados fornecidos via XLS pelo próprio site da [TACO](http://www.unicamp.br/nepa/taco/tabela.php?ativo=tabela), porém, migrados para o formato JSON para facilitar a manipulação e distribuição dos mesmos

#### Consultas

* Consulta de Categorias de Alimentos: [https://taco-alimentos-nodejs.herokuapp.com/categorias](https://taco-alimentos-nodejs.herokuapp.com/categorias)
* Consulta de Categorias de Alimentos por ID: [https://taco-alimentos-nodejs.herokuapp.com/categorias](https://taco-alimentos-nodejs.herokuapp.com/categorias/<idNumber>)
* Consulta dos Alimentos: [https://taco-alimentos-nodejs.herokuapp.com/alimentos](https://taco-alimentos-nodejs.herokuapp.com/alimentos)
* Consulta dos Alimentos por ID: [https://taco-alimentos-nodejs.herokuapp.com/alimentos](https://taco-alimentos-nodejs.herokuapp.com/alimentos/<idNumber>)

### Fron-end
... Em construção

## Informações
As informações usadas neste projeto, são de autoria total da universidade UNICAMP. 

Este projeto não possui fins lucrativos, apenas acadêmicos.
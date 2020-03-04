# api-graphql
Api em Laravel com GraphQL pré configurada com autenticação

<p style="text-align: center"><img src="https://res.cloudinary.com/dtfbvvkyp/image/upload/v1566331377/laravel-logolockup-cmyk-red.svg" width="400"></p>

<p style="text-align: center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## Sobre API Graphql
Api graphql pré configurada com autenticação. Lembre-se que é apenas para auxílio na agilidade de desenvolvimento, é interessante seguir os tutoriais de instalação dos links abaixo para melhor compreensão e conhecimento.

Os links que podem auxiliar a configurar uma api graphql semelhante a essa são os seguintes: 

<p><a href="https://lighthouse-php.com">Lighthouse</a>. É através do Lighthouse que vai ser possível começar a construir a api em graphql</p>

<p><a href="https://laravel.com/docs/5.8/passport">Laravel Passport</a>. Com o Passport vai ser muito mais fácil realizar as autenticações de login por exemplo</p>

<p><a href="https://github.com/joselfonseca/lighthouse-graphql-passport-auth">Laravel Passport Graphql</a>. Esse repositório auxilia em fazer a mutation de autenticação do graphql com o Passport do Laravel.</p>

<p><a href="https://github.com/fruitcake/laravel-cors">Laravel Cors</a>. É comum quando estamos mexendo com apis termos problemas de CORS, então esse repositório vai te ajudar no caso do laravel</p>

Se atente bem nos links acima e na documentação de cada um. Cada repositório e link oferece uma boa forma de começar. Ao invés de apenas pegar pronto, configure a sua, enfrente os desafios e problemas que aparecem, vai solucionando e buscando a solução, uma hora você encontra e resolve o problema. Caso precise de muita ajuda tem o <a href="https://laracasts.com">Laracasts</a>, onde você pode encontrar dúvidas semelhantes ou criar uma pergunta.

Você vai precisar testar suas queries e mutations do Graphql, você pode utilizar um que o repositório <a href="https://github.com/joselfonseca/lighthouse-graphql-passport-auth">Laravel Passport Graphql</a> indica, que é o Graphql Playground, ou o <a href="https://www.electronjs.org/apps/graphiql">GraphiQL</a> que pode ser instalado no Desktop. Existem outros, mas conheço esses dois que podem auxiliar. Eu uso o GraphiQL porque gosto dele e da praticidade que tive no primeiro contato, o Graphql Playground nunca usei.

<p> ------------ Como Usar ------------ </p>

## Arquivo .env
Executar o comando

cp .env.example .env

Use o php artisan key:generate para gerar a chave do APP_KEY

As configurações do banco de dados deve ser de acordo com as configurações do banco local

...
 
 DB_CONNECTION=mysql
 DB_HOST=127.0.0.1
 DB_PORT=3306 (a porta onde o bd mysql está configurado)
 DB_DATABASE=seudatabase
 DB_USERNAME=seuusuario
 DB_PASSWORD=seupassword (se for vazio deixe sem nada)
 
...

## Comandos para inicialização do projeto
composer install
composer update
composer dump-autoload
php artisan optimize
php artisan serve (para executar o projeto)



# Laravel Project Setup

## Clone o repositorio do sistema
`git clone <REPO_URI> `

## Crie uma branch e  acesse a brach logo em seguida
`git checkout -b <BRANCH_NAME> e.g. RichardsonTreinamento`

## Configue o token para autenticação  para evitar erro na instalação das depedências
`composer config --global github-oauth.github.com <TOKEN>`

## Instale as depedencias do composer
`composer install`

## Instale as depedencias do npm
`npm install`

## Crie o esquema no banco de dados
`schema_name` e.g.`chamados_ifpe`

## Migre o esquema e alimentas com registros
`php artisan migrate:fresh --seed`

## Inicialize o servidor
`php artisan serve`

## Acesse o servico no navegador
`localhost:8000`


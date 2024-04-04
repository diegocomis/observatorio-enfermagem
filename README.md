


## Tecnologias e Ferramentas
[![Latest Stable Version](https://badgen.net/packagist/lang/monolog/monolog)](https://badgen.net/packagist/lang/monolog/monolog)
[![PHP Version Require](https://badgen.net/badge/php/%3E8.3/green)](https://badgen.net/badge/php/%3E8.3/green)
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a><a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a><img src="https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white"/><img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" /><img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" /><img src="https://img.shields.io/badge/json-5E5C5C?style=for-the-badge&logo=json&logoColor=white" /><img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white" /><img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" /><img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" /><img src="https://img.shields.io/badge/Webpack-8DD6F9?style=for-the-badge&logo=Webpack&logoColor=white" />

## About the Project

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

### Entendendo a Estrutura do framework
1. Laravel DOC - https://laravel.com/docs/11.x
2. Entendendo a estrutura - Curso Laravel 10 - https://www.youtube.com/watch?v=d2-U2Jsw0II
3. Novidades Laravel 11 - https://www.youtube.com/watch?v=sETVuPjbkMw&t=95s
4. Curso Laravel 11 - https://academy.especializati.com.br/curso/laravel-11-completo-e-gratuito


## Passo a passo para Configuração inicial

Tenha o Docker Desktop instalado
```sh
https://www.docker.com/products/docker-desktop/
```

Clone Repositório
```sh
git clone -b https://github.com/diegocomis/observatorio-enfermagem.git
```
Crie o Arquivo .env
```sh
cp .env.example .env
```
Suba os containers do projeto - Utilizamos Laravel Sail p/ Docker
```sh
./vendor/bin/sail up -d
```
Se precisar instale o pacote NPM
```sh
./vendor/bin/sail npm install
```
Execute o build para ajustar alterações
```sh
./vendor/bin/sail npm build
```
Gere o banco de dados do projeto
```sh
./vendor/bin/sail php artisan migrate
```
Gere a key do projeto Laravel
```sh
./vendor/bin/sail php artisan key:generate
```

### Acesse o projeto
1. Link acesso - [http://localhost](http://localhost)
2. Link EasyPanel (Gerenciador CRUD) - [http://localhost/admin](http://localhost/admin)

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

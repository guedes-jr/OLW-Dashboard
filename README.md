<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# Sobre o projeto
## OLW-Dashboard

O projeto consiste em um sistema que consome uma api de uma inteligência artificial que irá gerar os gráficos de uma dashboar e com o Laravel estaremos apresentando esses gráficos.

## Tecnologias 
- PHP
- Laravel
- Docker

## Iniciar o projeto
Comando para iniciar o contênier do docker e o serviço do laravel:
```sh
./vendor/bin/sail up -d
```

Criar uma migration
```sh
./vendor/bin/sail artisan make:migration
```

## Licença

A estrutura Laravel é um software de código aberto licenciado sob a [licença MIT](https://opensource.org/licenses/MIT).

# Sobre Laravel

Laravel é um framework de aplicações web com sintaxe expressiva e elegante. Acreditamos que o desenvolvimento deve ser uma experiência agradável e criativa para ser verdadeiramente gratificante. O Laravel simplifica o desenvolvimento facilitando tarefas comuns usadas em muitos projetos da web, como:

- [Mecanismo de roteamento simples e rápido](https://laravel.com/docs/routing).
- [Poderoso contêiner de injeção de dependência](https://laravel.com/docs/container).
- Múltiplos back-ends para [sessão](https://laravel.com/docs/session) e armazenamento [em cache](https://laravel.com/docs/cache)
- Banco de dados expressivo e intuitivo [ORM](https://laravel.com/docs/eloquent).
- [Migrações de esquema](https://laravel.com/docs/migrations) agnóstico de banco de dados
- [Processamento robusto de trabalhos em segundo plano](https://laravel.com/docs/queues).
- [Transmissão de eventos em tempo real ](https://laravel.com/docs/broadcasting).

O Laravel é acessível, poderoso e fornece as ferramentas necessárias para aplicativos grandes e robustos.

## Aprendendo Laravel

O Laravel possui uma extensa [documentção](https://laravel.com/docs), bem completa, além de bibliotecas e tutoriais em vídeo, mostrando todas as funcionalidade necessárias em uma framework modela e de fácil utilização.

Você pode experimentar o [Laravel Bootcamp](https://bootcamp.laravel.com), onde será guiado na construção de um aplicativo Laravel moderno do zero.

Se você não gosta de ler, o [Laracasts](https://laracasts.com) pode ajudar. Laracasts contém mais de 2.000 tutoriais em vídeo sobre uma variedade de tópicos, incluindo Laravel, PHP moderno, teste de unidade e JavaScript. Aumente suas habilidades explorando nossa abrangente biblioteca de vídeos.

## Patrocinadores do Laravel

Gostaríamos de estender nossos agradecimentos aos seguintes patrocinadores por financiar o desenvolvimento do Laravel. Se você estiver interessado em se tornar um patrocinador, visite a [página Laravel Patreon](https://patreon.com/taylorotwell).

## Código de Conduta

Para garantir que a comunidade Laravel receba bem todos, por favor, revise e cumpra o [Código de Conduta](https://laravel.com/docs/contributions#code-of-conduct).
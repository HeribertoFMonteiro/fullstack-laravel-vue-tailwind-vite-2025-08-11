<<<<<<< HEAD

# fullstack-laravel-vue-tailwind-vite-2025-08-11
Projeto boilerplate base para Laravel + Inertia + Vue 3 + Tailwind CSS + Vite  
=======
fullstack-laravel-vue-tailwind-vite-2025-08-11-laravel10.48-vue3.4-tailwind3.2-vite7.1
Projeto base para Laravel + Inertia + Vue 3 + Tailwind CSS 3.2.1+ Vite 7.1.1

Projeto Base Para Outros.

>>>>>>> c09ae0c (terceiro commit - Atualiza README com explicação detalhada sobre casos em que o projeto não é indicado)
Criado em: 11 de Agosto de 2025

Tecnologias e versões usadas

Laravel: 10.48.29

Vue: 3.4.0

Tailwind CSS: 3.2.1

Vite: 7.1.1

Laravel Vite Plugin: 2.0.0

Inertia Vue 3: 2.0.0

Axios: 1.11.0

PostCSS: 8.4.31

Autoprefixer: 10.4.12

Descrição
Este projeto é um template base para desenvolvimento rápido de aplicações web usando Laravel como backend, Vue 3 com Inertia para frontend SPA híbrido, estilizado com Tailwind CSS e empacotado via Vite.

Ele foi criado para facilitar a construção de aplicações que exigem funcionalidades complexas e uma experiência de usuário fluida e moderna, combinando o poder do Laravel no backend com um frontend interativo em Vue 3.

Para que serve?
Este projeto serve para o desenvolvimento de projetos web fullstack modernos, que envolvam tanto área pública quanto painel autenticado, com funcionalidades avançadas e frontend responsivo. Ele é ideal para aplicações que precisam de:

Área pública e área autenticada:
Usuários podem acessar páginas abertas ao público e também acessar áreas protegidas por autenticação, com sistema completo de registro, login, recuperação de senha e perfis protegidos.

SPA híbrido com Inertia.js:
Permite carregamento parcial das páginas sem recarregar o navegador inteiro, proporcionando uma experiência mais rápida e fluida. Facilita a construção de Single Page Applications usando rotas tradicionais do Laravel combinadas com componentes Vue.

Frontend moderno e responsivo:
Utiliza Vue 3 para componentes reativos e organizados, e Tailwind CSS para um design customizável, responsivo e atraente, adaptável a qualquer dispositivo.

Backend robusto e seguro com Laravel:
Gerenciamento completo de rotas, controle de acesso, middleware e autenticação integrados. Suporte a banco de dados via migrations e Eloquent ORM, além de estrutura para APIs RESTful quando necessário.

Ambiente de desenvolvimento ágil:
Hot reload configurado tanto para backend quanto para frontend, acelerando o ciclo de desenvolvimento e testes, com integração automática das mudanças sem necessidade de reiniciar servidores manualmente.

Funcionalidades interativas complexas:
Suporte a dashboards dinâmicos, formulários com validação instantânea, filtros e buscas em tempo real. Operações CRUD completas para manipulação de dados sem recarregamento total da página, usando o poder do Vue e Inertia para atualização parcial.

Para que este projeto NÃO é indicado
Apesar de ser um template poderoso e moderno para aplicações web dinâmicas, este projeto não é a melhor escolha para os seguintes casos:

1. Sites estáticos ou landing pages simples
Se o seu objetivo é criar um site básico, como uma página institucional, portfólio simples, blog estático ou landing page, que não precise de funcionalidades interativas complexas, autenticação de usuários ou atualizações dinâmicas, esse projeto pode ser um exagero. Para esses casos, ferramentas mais simples como sites estáticos gerados por frameworks como Hugo, Jekyll, ou até mesmo páginas HTML/CSS puras são mais leves, rápidas e fáceis de manter.

2. Projetos que não requerem autenticação ou área de usuário protegida
Este template inclui um sistema completo de autenticação (registro, login, perfis, recuperação de senha), controle de acesso e áreas restritas. Se seu projeto não exige que usuários façam login, não há perfis ou áreas privadas, usar toda essa estrutura pode tornar o desenvolvimento mais complexo e desnecessário. Para sites apenas públicos, sem necessidade de controle de acesso, usar um sistema tão robusto pode ser um excesso.

3. Aplicações que não necessitam de SPA ou carregamento parcial de páginas
Este projeto usa Inertia.js para criar um SPA híbrido, que carrega as páginas parcialmente sem recarregar o navegador inteiro. Isso melhora muito a experiência do usuário em aplicações dinâmicas, mas acrescenta uma camada extra de complexidade no front-end e no fluxo da aplicação. Se sua aplicação é simples, baseada em páginas estáticas ou múltiplas requisições completas ao servidor (modelo tradicional), não faz sentido usar esse modelo SPA híbrido, que pode dificultar o desenvolvimento e manutenção sem trazer muitos benefícios.

Resumindo:
Se você precisa de uma aplicação robusta, interativa, com áreas autenticadas e uma experiência moderna tipo SPA, este projeto é perfeito. Mas, para sites simples, estáticos ou sem autenticação, usar este template pode ser um exagero e tornar seu desenvolvimento mais complexo e pesado do que o necessário


Como usar
Clone o repositório

Execute composer install

Execute npm install

Configure seu arquivo .env com credenciais locais

Rode npm run dev para ambiente de desenvolvimento

Rode php artisan serve para iniciar o servidor backend


<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

You may also try the [Laravel Bootcamp](https://bootcamp.laravel.com), where you will be guided through building a modern Laravel application from scratch.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains thousands of video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the [Laravel Partners program](https://partners.laravel.com).

### Premium Partners

- **[Vehikl](https://vehikl.com)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel)**
- **[DevSquad](https://devsquad.com/hire-laravel-developers)**
- **[Redberry](https://redberry.international/laravel-development)**
- **[Active Logic](https://activelogic.com)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

Licença
MIT License


## Licença

MIT License
=======
<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

You may also try the [Laravel Bootcamp](https://bootcamp.laravel.com), where you will be guided through building a modern Laravel application from scratch.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains thousands of video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the [Laravel Partners program](https://partners.laravel.com).

### Premium Partners

- **[Vehikl](https://vehikl.com)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel)**
- **[DevSquad](https://devsquad.com/hire-laravel-developers)**
- **[Redberry](https://redberry.international/laravel-development)**
- **[Active Logic](https://activelogic.com)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
>>>>>>> bd48417 (primeiro commit - base para outros projetos)

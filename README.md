# Laravel_Tutorial
自我學習PHP Laravel framework

## Setting Project

* Create Pehect

        composer global require "laravel/installer"
        composer create-project laravel/laravel {project name}
        
 * Directory Structure
 
        app         -->      保存大部分實際應用程式的地方。model, controller, router, 命令和網域設定
        bootstrap   -->      存放Laravel框架在每次執行，用來啟動的檔案
        config      -->      放置所有組態檔
        database    -->      放置DB migration, 種子與工廠
        public      -->      當伺服器服務網站指向的目錄。
        resource    -->      保存其他腳本所需的檔案
        routes      -->      所有的路由定義
        storage     -->      保存快取, log與編譯過的系統檔案
        tests       -->      單元與整合測試
        vender      -->      Composer所安裝依賴的套件
        
* File

        .editorconfig           -->         提供Laravel編寫標準
        .env & .envexample      -->         主宰環境變數的檔案
        .gitinore               -->         Git組態檔
        .gitattributes
        artisan                 -->         可在命令列上執行Artisan命令檔案
        composer.json           -->         Composer組態檔。.json可以自行編輯， .lock是檔案共享一些關於專案的基本資訊，也會定義與PHP依賴關係
        composer.lock
        package.json            -->         跟NPM說需要那些JS套件
        phpunit.xml             -->         PHPUnit組態檔，Laravel內建測試工具
        server.php              -->         後備伺服器，它會試著讓能力差的伺服器仍然可以預覽Laravel應用程式
        webpak.min.js           -->         min組態檔。如使用Elixir，會看到gulpfile.js。這些檔案負責組建系統如何編譯與處理前端
        

<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
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

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 1500 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://patreon.com/taylorotwell).

### Premium Partners

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Cubet Techno Labs](https://cubettech.com)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[Many](https://www.many.co.uk)**
- **[Webdock, Fast VPS Hosting](https://www.webdock.io/en)**
- **[DevSquad](https://devsquad.com)**
- **[OP.GG](https://op.gg)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

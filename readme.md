<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

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

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 1100 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost you and your team's skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://patreon.com/taylorotwell).

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Cubet Techno Labs](https://cubettech.com)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[British Software Development](https://www.britishsoftware.co)**
- **[Webdock, Fast VPS Hosting](https://www.webdock.io/en)**
- **[DevSquad](https://devsquad.com)**
- [UserInsights](https://userinsights.com)
- [Fragrantica](https://www.fragrantica.com)
- [SOFTonSOFA](https://softonsofa.com/)
- [User10](https://user10.com)
- [Soumettre.fr](https://soumettre.fr/)
- [CodeBrisk](https://codebrisk.com)
- [1Forge](https://1forge.com)
- [TECPRESSO](https://tecpresso.co.jp/)
- [Runtime Converter](http://runtimeconverter.com/)
- [WebL'Agence](https://weblagence.com/)
- [Invoice Ninja](https://www.invoiceninja.com)
- [iMi digital](https://www.imi-digital.de/)
- [Earthlink](https://www.earthlink.ro/)
- [Steadfast Collective](https://steadfastcollective.com/)
- [We Are The Robots Inc.](https://watr.mx/)
- [Understand.io](https://www.understand.io/)
- [Abdel Elrafa](https://abdelelrafa.com)

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).

## Getting started

## Installation

- Yêu cầu về môi trường: 
	+ Hệ điều hành : Window 7 64 bit
	+ Trình duyệt web : Firefox, Chrome, CocCoc…
	+ Các phần mềm khác : PHP > 7.0, Laravel framwork 5.8, Composer vl.9.0, Oracle
- Cài đặt :

+ Composer :Downloads phiên bản mới nhất [tại đây](https://getcomposer.org/download/).
 
+ Cài đặt PHP, IIS 7.5 trên Windows Server 2008 R2  

+ Cài đặt Laravel 5.8

-Vào thư mục chứa project của Xampp. Mặc định cài đặt sẽ ở trong đường dẫn C:\xampp\htdocs. 

Tạo một project 

	**composer create-project laravel/laravel  ten_project**
<img src="Content/images/Readme/create_project.jpg">
Chạy project 

	**php artisan serve**
<img src="Content/images/Readme/buildingProject.jpg">

+ Cài đặt Oracle 

-Download Oracle Client tại địa chỉ [Oracle.com](http://www.oracle.com/technetwork/database/enterprise-edition/downloads/index.html).
- Download và cài đặt OCI8 theo phiên bản PHP
Download:
Kiểm tra phiên bản php ở máy để lựa tải oci8 phiên bản tương ứng.
PHP 7.0 đến 7.2 [Tại đây] (https://pecl.php.net/package/oci8/2.1.8/windows).
Hoặc
PHP 7.1 đến 7.3: [Tại đây] (https://pecl.php.net/package/oci8/2.2.0/windows).
Download theo loại thường dùng Thread Safe (TS) x86 hoặc x64.
Cấu hình và cài đặt Oci8:
[1] Cấu hình oci8 trong xampp
<img src="Content/images/Readme/Folder_Oci8.png" title="Thư mục Oci8">
Sau khi download dll oci8 bên trên về ta copy toàn bộ vào thư mục ext trong thư mục Xampp\php\ext.
Tiếp theo mở file php.ini trong thư mục: \xampp\php
Và thêm 2 dòng extension sau vào file ini.
extension=php_oci8.dll 
extension=php_oci8_11g.dll
<img src="Content/images/Readme/AddExtensionoci8.png">
[2] Kiểm tra Xampp đã hỗ trợ Oci8
Tạo file phpinfo.php tại thư mục root của xampp với nội dung file như sau:
<?php phpinfo(); ?>
Chạy đường dẫn kiểm tra [http://localhost/phpinfo.php](http://localhost/phpinfo.php).
Bạn tìm đến dòng oci8 kết quả như hình 12 bên dưới là bạn đã cấu hình thành công.
Cấu hình thành công OCI8 trong xampp :
<img src="Content/images/Readme/success.png" title="Oci8">









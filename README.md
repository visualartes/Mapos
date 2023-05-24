# Mapos
não consigo finalizar a instalação do mapos, pois ao usar o codigo composer install --no-dev gera um erro
Microsoft Windows [versão 10.0.19045.2728]
(c) Microsoft Corporation. Todos os direitos reservados.

C:\xampp\htdocs\mapos>composer install --no-dev
Installing dependencies from lock file
Verifying lock file contents can be installed on current platform.
Your lock file does not contain a compatible set of packages. Please run composer update.

  Problem 1
    - Root composer.json requires PHP extension ext-gd * but it is missing from your system. Install or enable PHP's gd extension.
  Problem 2
    - mk-j/php_xlsxwriter is locked to version 0.38 and an update of this package was not requested.
    - mk-j/php_xlsxwriter 0.38 requires ext-zip * -> it is missing from your system. Install or enable PHP's zip extension.
  Problem 3
    - mpdf/mpdf is locked to version v8.1.5 and an update of this package was not requested.
    - mpdf/mpdf v8.1.5 requires ext-gd * -> it is missing from your system. Install or enable PHP's gd extension.
  Problem 4
    - piggly/php-pix is locked to version 2.0.2 and an update of this package was not requested.
    - piggly/php-pix 2.0.2 requires ext-gd * -> it is missing from your system. Install or enable PHP's gd extension.

To enable extensions, verify that they are enabled in your .ini files:
    - C:\xampp\php\php.ini
You can also run `php --ini` in a terminal to see which files are used by PHP in CLI mode.
Alternatively, you can run Composer with `--ignore-platform-req=ext-gd --ignore-platform-req=ext-zip` to temporarily ignore these required extensions.

C:\xampp\htdocs\mapos>

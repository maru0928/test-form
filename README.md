環境構築

Dockerビルド

1.git clone git@github.com:maru0928/test-form.git
2.docker-compose up -d --build

＊MySQLは、OSによって起動しない場合があるのでそれぞれのPCに合わせてdocker-compose.ymlファイルを編集してください。

Lalavel環境構築

1.docker-compose exec php bash
2.composer install
3..env.examplから.envを作成し、環境変数を変更
4.php artisan key:generate
5.php artisan migrate
6.php artisan db:seed

使用技術

・PHP 8.4.3
・Laravel Framework 8.83.29
・MySQL Ver 15.1 Distrib 10.3.39-MariaDB

URL
・開発環境：http://localhost/
・phpMyAdmin：http://localhost:8080/

お問い合わせフォーム

環境構築
Dockerビルド
　　1. git clone リンク
 2.　　docker-compose up -d --buiid
※MySQLは、OSによって起動しない場合があるのでそれぞれのPCに合わせて　docker-compose.yml ファイルを編集してください。

Laravel環境構築
　　1. docker-compose exec bash
 2. composer install
 3. .env.exampleファイルから.envを作成し、環境変数を変更
 4. php artisan key:generate
 5. php artisan migrate
 6. php artisan db:seed

 使用技術
 PHP　：7.4.9
 Laravel　：8.83.8
 MySQL　：１５.１

 ER図
![index drawio](https://github.com/miyakana/confirmation-test/assets/145843739/40422771-0fa0-4b29-ad0c-97d2aa1d1174)

URL
. 開発環境：[http://localhost/](http://localhost/)
.phpMyAdmin:[http://localhost:8080/](http://localhost:8080/)http://localhost:8080/
# check-test

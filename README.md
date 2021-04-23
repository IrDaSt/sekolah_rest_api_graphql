# REST API sekolah

REST API dibuat menggunakan framework Laravel.<br>
Memanfaatkan package Lighthouse untuk menggunakan GraphQL. <br>
<br>
Terdapat 3 tabel yang telah dibuat:<br>
Student<br>
Teacher<br>
Classroom<br>

Setelah melakukan clone repository, buka terminal dan arahkan menuju directory project<br>
Kemudian jalankan perintah berikut<br>
<code>composer install</code>
<code>composer update</code>
<br>
Setelah selesai, jalankan server mysql dan buat database dengan nama sekolah_laravel<br>
<br>
<br>
Jalankan perintah berikut untuk membuat tabel yang dibutuhkan oleh database<br>
<code>php artisan migrate</code><br>
Jalankan website ini dengan perintah berikut di terminal project<br>
<code>php artisan serve --port <Port></code><br>
<br>

## Usage
### GraphQL Playground
Arahkan menuju url berikut di Browser yang anda gunakan untuk mengakses website<br>
<code>localhost:8000/graphql-playground</code><br>

### GraphQL Client Usage
Pemanggilan data maupun penyimpanan data dapat dilakukan dengan menggunakan url sebagai berikut dalam request<br>
<code>localhost:8000/graphql?query=query graphQL{}</code><br>

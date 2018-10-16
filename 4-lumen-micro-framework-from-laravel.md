###  

![](https://cdn-images-1.medium.com/max/800/1*kJ2ZcTx8syiO7Fls38BlYw.png)

Image Capture from URL \([https://lumen.laravel.com/](https://lumen.laravel.com/)\)

Halo teman, sambil nunggu _Quality Control / Reviewer Code_ datang, nulis ah :D. Jadi pernah ada yang pernah tanya tentang laravel. Mengapa laravel itu cepat saat proses _development_ nya, ya karena di laravel sudah banyak disediakan banyak perintah — perintahnya. Contoh : _$ php artisan serve, $ php artisan migrate $ php artisan db:seed._

Dan kebutuhan untuk pembuatan sebuah aplikasi berbasis web sudah disediakan oleh laravel sendiri. Contoh : _Route_ yang _Dynamis_, _Render View_ mudah dipahami, dan lain — lain.

Nah tapi kali ini kita endak bahas laravel secara detail, tapi kali ini kita akan bahas salah satu _product_ dari _laravel_ yang fokus di bagian _“Application Interface Programming \(API\)”_ yaitu [_**“Lumen — Micro Framework”**_](https://lumen.laravel.com/).

Pada framework ini “Lumen”, banyak fungsi — fungsi yang tidak masukkan kedalam project nya, ya karena memang Micro Framework mempunyai kemampuan _\(Request Per Second — RPS\),_ yaitu kemampuan dapat meng-handle banyak permintaan \(_request_\). RPS ini sangat di butuhkan untuk beberapa aplikasi yang membutuhkan “concurently latency”, contoh : aplikasi penghitung biaya kirim, aplikasi penghitung penjualan BBM, dan lain — lain.

![](https://cdn-images-1.medium.com/max/800/1*kJ2ZcTx8syiO7Fls38BlYw.png)

Lumen mampu memberikan kebutuhan yang hampir sama dengan Framework orang tuanya yaitu _laravel_. Dan lumen juga bisa melakukan perintah — perintah sesuai kebutuhan dari pengguna Laravel sendiri. ada beberapa perintah yang memang di lumen tidak di masukkan, contoh : _$ php artisan key:generate._

Itulah sekilas informasi awal dari Lumen, si micro-framework dari Laravel. untuk praktek dan teknik-teknik lainnya, bisa kita lanjutkan di artikel selanjutnya.

Terima kasih.


# Lab9Web
# Praktikum 9: PHP Modular

Modularisasi sendiri merupakan proses penyederhanaan program yang kompleks menjadi lebih efisien. Program disusun berdasarkan modul-modul yang berupa function atau prosedur. Sebagai contoh, dalam pembuatan website terdapat halaman index/utama yang terdiri dari header, konten, dan footer. Apabila halaman index tersebut diselesaikan tanpa menggunakan modul, maka akan hanya ada satu file php saja, namun dengan banyak baris kode program didalamnya. Kendalanya adalah ketika terjadi kesalahan, maka akan terlihat rumit untuk menemukan dan memperbaiki kesalahan tersebut.

Modularisasi didalam PHP terdiri dari:

1. Require, merupakan bentuk modular yang digunakan untuk menggabungkan file PHP atau file lain dengan file PHP yang memanggilnya. File yang digabungkan tidak harus script PHP.
   
2. Include, hampir sama dengan require namun bedanya adalah include digunakan untuk menggabungkan file PHP dengan file pemanggilnya. Include dapat digunakan didalam pengulangan untuk memanggil file-file yang berbeda.
    
3. Require_once, pada dasarnya sama dengan require, perbedaannya adalah jika menggunakan require_once apabila terjadi duplikasi fungsi atau duplikasi pemanggilan maka akan terhindar karena require_once akan memaksa PHP untuk menggunakan nama fungsi dan pemanggilan yang telah ada.
    
4. Include_once, hampir sama dengan require_once, perbedaannya adalah include_once apabila dijalankan akan selalu ada evaluasi ulang.
    

# Langka - langka Praktikum
pertama aktifkan Xampp, selanjutnya start aphace dan mysqly
#
![7](https://user-images.githubusercontent.com/56498195/121340825-39d5ae00-c94a-11eb-9ee1-a5d83528343f.PNG)

Buat folder baru dengan nama lab9_php_modular pada docroot webserver(htdocs)

![14](https://user-images.githubusercontent.com/56498195/121348438-90df8100-c952-11eb-9296-0b30510476c5.PNG)

Membuat file header.php yang kita tempatkan di folder template. Kita rancang desain template headernya. Pada contoh berikut adalah potongan code yang mewakilkan template_header.php.
#
![9](https://user-images.githubusercontent.com/56498195/121340014-4b6a8600-c949-11eb-945a-4824abdb68bb.PNG)

hasil broser

![1](https://user-images.githubusercontent.com/56498195/121340321-b025e080-c949-11eb-95b1-9a30692c9886.PNG)




Kemudian membuat sebuah template footer pada tempat yang sama yaitu di folder template dengan nama footer.php . Berikut ini adalah potongan code yang mewakilkan template footer.
#
![10](https://user-images.githubusercontent.com/56498195/121340103-66d59100-c949-11eb-9ee7-e09bb2fa1443.PNG)

hasil broser

![2](https://user-images.githubusercontent.com/56498195/121340332-b2883a80-c949-11eb-8fc6-08c22496e29c.PNG)



# Pertanyaan dan Tugas
Implementasikan konsep modularisasi pada kode program praktikum 8 tentangdatabase, sehingga setiap halamannya memiliki template tampilan yang sama.



Membuat file footer.php untuk kemudian di masukan ke index dengan menggunakan require


![10](https://user-images.githubusercontent.com/56498195/121347718-b6b85600-c951-11eb-9a5d-1a5fdf5d2d7d.PNG)

Buat file baru dengan nama header.php


![9](https://user-images.githubusercontent.com/56498195/121347745-bcae3700-c951-11eb-944a-798a1d3dda76.PNG)

Menambahkan Style CSS untuk mepercantik tample


![syle 1](https://user-images.githubusercontent.com/56498195/121347833-d485bb00-c951-11eb-8455-ad650f046f2f.PNG)


![style2](https://user-images.githubusercontent.com/56498195/121347811-cf287080-c951-11eb-94a4-16dcf9932961.PNG)


![style3](https://user-images.githubusercontent.com/56498195/121347827-d2236100-c951-11eb-9afd-f7e262e80bd1.PNG)

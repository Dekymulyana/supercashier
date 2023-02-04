# Super Cashier
## Python Project - Super Cashier - Ayudina Larasanti - Analytics and Data Science
#### Sistem kasir self-service di supermarket dengan menggunakan bahasa pemrograman Python yang memungkinkan customer yang tidak berada di kota tersebut dapat melakukan pembelian barang.
## 1. REQUIREMENTS/ OBJECTIVES
   #### Membuat sistem kasir self service dengan fiture sebagai berikut:
   #### a. Membuat proses untuk memasukkan ID Transaksi
   #### b. Membuat proses untuk menambahkan barang yang ini dibeli dan detail jumlah dan harganya
   #### c. Membuat proses untuk mengupdate detail barang yang sudah diinputkan sebelumnya jika ada kesalahan input
   #### d. Membuat proses untuk menghapus salah satu pesanan yang telah diinputkan  
   #### e. Membuat proses untuk menghapus seluruh transaksi yang telah diinputkan
   #### f. Membuat proses untuk memeriksa apakah seluruh data yang diinput sudah benar dan lengkap
   #### g. Membuat proses untuk menghitung total belanja yang harus dibayarkan dan diskon yang didapatkan (jika dapat).
 
## 2. FLOWCHART
![Flowchart](https://user-images.githubusercontent.com/123846578/216514621-2c134ee1-4961-4a88-a5c2-5bca5df20e91.jpeg)

## 3. PENJELASAN CODE
   ### a. __init__()
   ### Merupakan fungsi inisialisasi untuk class Transaction.
   <img width="483" alt="image" src="https://user-images.githubusercontent.com/123846578/216519283-9800920e-9cfa-43a1-ace6-a0ae67aedea1.png">
   
   ### b. add_item
   ### Merupakan fungsi untuk menambahkan detail item, yang terdiri dari:
   #### item_name = Nama Barang
   #### item_qyt = Jumlah Barang
   #### item_price = Harga Barang
   <img width="443" alt="image" src="https://user-images.githubusercontent.com/123846578/216520187-a96ba825-a6ac-4ec6-b2bd-ed256786afb6.png">
   
   ### c. update_item
   ### Merupakan fungsi untuk mengupdate/ mengubah detail item yang diinputkan.
   <img width="458" alt="image" src="https://user-images.githubusercontent.com/123846578/216740291-9bc21339-bf1b-47af-9c66-e20a454e25b0.png">

   ### d. show_order
   ### Merupakan fungsi untuk menampilkan daftar pesanan yang sudah diinputkan.
   <img width="483" alt="image" src="https://user-images.githubusercontent.com/123846578/216521035-9b5284d9-0636-4904-a4ac-d7825c36b5f9.png">
   
   ### e. delete_item
   ### Merupakan fungsi untuk menghapus salah satu item/ barang yang sudah diinput.
   <img width="500" alt="image" src="https://user-images.githubusercontent.com/123846578/216521302-f7e3ab06-afd1-4162-b408-9fd90f072029.png">
   
   ### f. reset_transaction
   ### Merupakan fungsi untuk menghapus semua item/barang yang telah diinputkan.
   <img width="416" alt="image" src="https://user-images.githubusercontent.com/123846578/216521701-47f3205f-3c90-4542-bef8-ada58029eeeb.png">
   
   ### g. check_order
   ### Merupakan fungsi untuk untuk memeriksa apakah detail item/barang yang diinputkan sudah lengkap dan benar.
   <img width="518" alt="image" src="https://user-images.githubusercontent.com/123846578/216522035-960f17e3-03f5-451f-9826-7cae5d911ba0.png">
   
   ### h. total_price
   ### Merupakan fungsi untuk menghitung total harga yang harus dibayar oleh customer. Setelah dilakukan penghitungan total harga awal (sebelum diskon), terlebih dahulu akan ditentukan apakah customer mendapatkan diskon. Jika mendapat diskon berapa diskon yang didapatkan, dan setelah itu dilakukan perhitungan total harga awal dikurangi diskon, Lalu hasil akhirnya didapatkan harga total setelah diskon
   <img width="805" alt="image" src="https://user-images.githubusercontent.com/123846578/216522369-6ee3e5b2-db30-4632-b9bd-b48c8e5c607b.png">

## 4. HASIL TEST CASE
<img width="729" alt="image" src="https://user-images.githubusercontent.com/123846578/216740481-c952f538-fddb-4172-ab49-46976efad043.png">

### #TEST CASE 1
<img width="814" alt="image" src="https://user-images.githubusercontent.com/123846578/216740430-72b4a87d-2f6e-48cb-b32f-fed614697dfc.png">
### #TEST CASE 2
<img width="721" alt="image" src="https://user-images.githubusercontent.com/123846578/216740537-3437e95b-ae4d-469f-8c94-224fe65931ad.png">
### #TEST CASE 3
<img width="680" alt="image" src="https://user-images.githubusercontent.com/123846578/216740601-7bf0fe2f-2f60-4994-9fa3-a4f1bd2a7317.png">
### MENAMBAHKAN KEMBALI ITEM PESANAN
<img width="798" alt="image" src="https://user-images.githubusercontent.com/123846578/216740948-ad2486e9-29e9-4d15-8d10-5fa15004d39a.png">
### MENGUPDATE PESANAN
<img width="828" alt="image" src="https://user-images.githubusercontent.com/123846578/216741028-acef2bb6-8c79-4043-92f9-37d608caf83b.png">
### MEMERIKSA INPUT PESANAN
<img width="835" alt="image" src="https://user-images.githubusercontent.com/123846578/216741085-818b72cf-b7a7-4e31-83d2-165d07de6110.png">

### #TEST CASE 4
<img width="826" alt="image" src="https://user-images.githubusercontent.com/123846578/216740739-cd9cdcdb-5151-4384-9f94-23cb36feaf1f.png">

## 5. FUTURE WORK
   ##### a. Mengembangkan fungsi untuk pemberian kupon belanja. Jadi selain diskon, customer dengan total pembelian tertentu akan mendapat kupon yang akan diundi setiap akhir tahun. Misalnya setiap kelipatan Rp.50.000,- mendapatkan satu kupon.
   ##### b. Mengembangkan fungsi untuk keuntungan "tebus murah". Jadi selain diskon, customer dengan total pembelian tertentu akan mendapat keuntungan untuk dapat membeli barang-barang tertentu dengan harga lebih murah.


## Terima Kasih Pacmann (Mbak Zakiya, Mbak Fath, Mas Sepryan, dll)


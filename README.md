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
   <img width="380" alt="image" src="https://user-images.githubusercontent.com/123846578/216520672-49f666a9-af3f-4e1c-b594-5512295ff48c.png">

   ### d. show_order
   ### Merupakan fungsi untuk menampilkan daftar pesanan yang sudah diinputkan.
   <img width="483" alt="image" src="https://user-images.githubusercontent.com/123846578/216521035-9b5284d9-0636-4904-a4ac-d7825c36b5f9.png">
   
   ### e. delete_item
   ### Merupakan fungsi untuk menghapus salah satu item/ barang yang sudah diinput.
   <img width="500" alt="image" src="https://user-images.githubusercontent.com/123846578/216521302-f7e3ab06-afd1-4162-b408-9fd90f072029.png">


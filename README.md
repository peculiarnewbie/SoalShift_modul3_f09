# SoalShift_modul3_F09

### Arif Rahman (05111740000089)

### Choirur Roziqin (05111640000178)

## Soal 1



Buatlah program C yang bisa menghitung faktorial secara parallel lalu menampilkan hasilnya secara berurutan

Contoh:

​	./faktorial 5 3 4

​	3! = 6

​	4! = 24

​	5! = 120

hasil kerja:

![](/pics/no1res.jpg)

Cara kerja:

buat program yang bisa mengambil argumen dan jumlah argumennya. baca argumen dan urutkan ke dalam array dari kecil ke besar. lalu buat loop yang membuat thread sebanyak argumen lalu menghitung faktorial berdasarkan argumen tersebut dan menampilkan hasilnya lalu join semua thread tersebut



## Soal 2

Pada suatu hari ada orang yang ingin berjualan 1 jenis barang secara private, dia memintamu membuat program C dengan spesifikasi sebagai berikut:

1. 1. Terdapat 2 server: server penjual dan server pembeli

   2. 1 server hanya bisa terkoneksi dengan 1 client

   3. Server penjual dan server pembeli memiliki stok barang yang selalu sama

   4. Client yang terkoneksi ke server penjual hanya bisa menambah stok

   5. - Cara menambah stok: client yang terkoneksi ke server penjual mengirim string “tambah” ke server lalu stok bertambah 1

   6. Client yang terkoneksi ke server pembeli hanya bisa mengurangi stok

   7. - Cara mengurangi stok: client yang terkoneksi ke server pembeli mengirim string “beli” ke server lalu stok berkurang 1

   8. Server pembeli akan mengirimkan info ke client yang terhubung dengannya apakah transaksi berhasil atau tidak berdasarkan ketersediaan stok

   9. - Jika stok habis maka client yang terkoneksi ke server pembeli akan mencetak “transaksi gagal”
      - Jika stok masih ada maka client yang terkoneksi ke server pembeli akan mencetak “transaksi berhasil”

   10. Server penjual akan mencetak stok saat ini setiap 5 detik sekali

   11. **Menggunakan thread, socket, shared memory**

hasil kerja:

-

## Soal 3

soal Agmal dan Iraj

hasil kerja:

![](/pics/no3res.jpg)

Cara kerja: 

buat program dengan 3 thread, yairu thread iraj, thread agmal, dan thread input. thread iraj dan agmal berisikan perubahan jika diberi command, dan pemberhentian jika  command satunya telah dijalankan 3 kali. Di dalam thread juga dapat aksi jika stat telah mencapai endpoint. Thread ketiga berfungsi sebagai input handler yang mengambil input dan mengubah value untuk memanggil fungsi di kedua thread lainnya






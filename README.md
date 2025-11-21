# UTS_PEMOGRAMAN-MOBILE-2

''' Jawaban no 1

State management dengan Cubit membantu pengelolaan transaksi dengan logika diskon dinamis karena seluruh perhitungan harga, diskon, dan perubahan jumlah item ditempatkan pada lapisan logika bisnis, bukan di UI.** Setiap kali ada perubahan seperti penambahan barang, pengurangan barang, atau kondisi promo tertentu, Cubit akan menghitung ulang nilai diskon dan total harga, lalu meng-emit state baru yang sudah bersih dan siap ditampilkan ke UI. Dengan cara ini, UI hanya menerima state final tanpa harus menghitung apa pun, sehingga kode lebih rapi dan mudah dirawat.

Selain itu, Cubit membuat perubahan transaksi menjadi lebih terkontrol dan predictable, karena semua aliran data berjalan satu arah dan setiap update memiliki state yang jelas seperti total baru, diskon baru, atau status promo. Ini memudahkan debugging serta mempermudah pengembangan fitur diskon tambahan seperti diskon bertingkat atau diskon khusus member. Hasilnya, pengelolaan transaksi menjadi lebih fleksibel, aman dari error, dan mudah di-scale. '''

''' Jawaban no 2 
Diskon per item adalah potongan harga yang diterapkan pada setiap produk secara individual, sehingga setiap barang dapat memiliki nilai diskon yang berbeda sesuai promo atau kebijakan toko. Misalnya, dalam aplikasi kasir, produk seperti Indomie bisa diberi diskon 10% sementara Susu Ultra mendapatkan diskon 5%. Ketika kasir menambahkan barang ke keranjang, aplikasi langsung menghitung harga setelah diskon untuk masing-masing item, lalu menampilkannya di daftar belanja. Jenis diskon ini biasanya digunakan ketika toko ingin mempromosikan produk tertentu atau menghabiskan stok.

Sementara itu, diskon total transaksi adalah potongan yang diberikan setelah seluruh belanja dijumlahkan, tanpa memandang item apa saja yang dibeli. Diskon ini biasanya muncul dalam promo seperti “Diskon 10% untuk total belanja di atas Rp200.000” atau “Diskon 15% khusus member Gold.” Dalam aplikasi kasir, diskon jenis ini akan muncul pada bagian total pembayaran dan dihitung tepat sebelum pelanggan menyelesaikan transaksi. Jenis diskon ini lebih cocok untuk promo besar, event toko, atau program loyalitas pelanggan.'''

'''Jawaban no 3
Widget Stack dalam tampilan kategori menu pada aplikasi Flutter digunakan untuk menumpuk beberapa elemen UI di posisi yang saling bertindihan sehingga menghasilkan desain yang lebih menarik dan informatif.Dengan Stack, developer dapat menempatkan gambar kategori sebagai elemen utama, kemudian menambahkan teks nama kategori, ikon, atau badge promo di posisi tertentu seperti pojok kiri atau kanan gambar. Misalnya, dalam aplikasi menu restoran atau toko online, sebuah gambar kategori “Minuman” bisa ditempatkan sebagai background, lalu di atasnya ditambahkan overlay hitam transparan dan teks “Minuman” yang terletak di bagian bawah menggunakan Positioned. Penggunaan Stack membuat tampilan kategori terlihat lebih modern dan interaktif karena memungkinkan kombinasi visual layered, seperti label diskon, indikator jumlah item, atau efek shadow tanpa perlu membuat layout yang rumit. Dengan demikian, Stack menjadi pilihan ideal untuk membuat UI kategori yang lebih dinamis, estetik, dan mudah dipahami pengguna.'''

Tidak bisa push ke github jadi di upload folder nya di drive 
https://drive.google.com/drive/u/1/folders/1vEIxRAzWZYeDgnFfmoDm_0RR6zAmpvs6

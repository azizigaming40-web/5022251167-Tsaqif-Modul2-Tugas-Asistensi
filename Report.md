Tugas Asistensi Dasar Pemrograman 2

Nama : Muhammad Tsaqif Azizi
NRP : 5022251167
Modul : 2

### Commit 1
**Message:** `add initial matrix multiplication code`  
- Menambahkan file `main.c` berisi kode awal perkalian matriks.

### Commit 2
**Message:** `fix read_matrix: ubah parameter jadi [N][N], perbaiki loop j dan format scanf`  
- Memperbaiki parameter fungsi `read_matrix` agar sesuai dengan ukuran matriks `N x N`.  
- Mengubah loop agar menggunakan `j` bukan `k`.  
- Mengubah format `scanf` dari `%lf` ke `%d` karena menggunakan tipe `int`.

### Commit 3
**Message:** `fix multiply: tambahkan deklarasi sum di dalam loop`  
- Menambahkan deklarasi variabel `int sum` di dalam loop perkalian matriks.  
- Memastikan hasil perkalian disimpan ke matriks `C`.

### Commit 4
**Message:** `fix print_matrix: ubah format print dari %c ke %d`  
- Mengubah `printf` agar menggunakan `%d` sehingga hasil integer ditampilkan benar.

### Commit 5
**Message:** `fix main: tambahkan ; setelah read_matrix(B), tambah pesan input/output`  
- Menambahkan tanda `;` setelah pemanggilan fungsi `read_matrix(B)`.  
- Menambahkan pesan agar user tahu kapan mengisi matriks A dan B.

### Commit 6
**Message:** `finalize working matrix multiplication program`  
- Program siap dijalankan.  
- Input dan output matriks sudah berfungsi dengan benar.

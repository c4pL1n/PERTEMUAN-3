1. Konsep Game
Game ini adalah permainan pilihan ganda di mana pemain akan diberikan pertanyaan dengan beberapa opsi jawaban. Kategori yang digunakan meliputi:
- Hewan
- Negara
- Budaya Asal
- Makanan Khas Negara
- Julukan Negara
Pemain harus memilih jawaban yang benar dari beberapa pilihan yang disediakan.

2. Teknologi yang Digunakan
Game ini dibuat dengan C# menggunakan Console Application untuk kemudahan implementasi. Alternatifnya, game ini bisa dikembangkan lebih lanjut dengan GUI menggunakan Windows Forms atau Unity untuk tampilan yang lebih interaktif.

3. Struktur Program
Game ini memiliki beberapa komponen utama:
Kelas Question
Berisi informasi pertanyaan, kategori, opsi jawaban, dan jawaban benar.
Kelas QuizGame
Berfungsi untuk mengatur pertanyaan dan memproses input pemain.
Fungsi Main
Menjalankan game dan menampilkan hasil permainan.

5. Penjelasan Code
* Kelas Question
Menyimpan informasi pertanyaan, kategori, pilihan jawaban, dan jawaban yang benar.
* Kelas QuizGame
- Menginisialisasi daftar pertanyaan dengan kategori yang sudah ditentukan.
- Menggunakan List<Question> untuk menyimpan pertanyaan.
- Menggunakan metode Start() untuk menjalankan game, menerima input dari pemain, dan menghitung skor.
* Kelas Program
Menjalankan game dengan membuat objek QuizGame dan memanggil metode Start().

6. Fitur yang Bisa Dikembangkan
- Menambahkan lebih banyak kategori dan pertanyaan
- Membuat GUI dengan Windows Forms atau Unity
- Menyimpan skor tertinggi menggunakan file atau database
- Menambahkan mode multiplayer untuk bermain bersama teman
- Membuat sistem level dengan tingkat kesulitan yang meningkat

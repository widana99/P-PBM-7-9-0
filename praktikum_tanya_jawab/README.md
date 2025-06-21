# praktikum_tanya_jawab

# Quiz App - Flutter

Aplikasi ini adalah proyek Flutter sederhana yang mengimplementasikan fitur kuis berbasis pilihan benar atau salah. Aplikasi dirancang sebagai latihan untuk memahami konsep dasar Flutter dan pemrograman berorientasi objek (OOP) dalam Dart.

---

## 📚 Kesimpulan

Proyek ini menyajikan pendekatan modular dalam membangun aplikasi Flutter, di mana setiap bagian kode dipisahkan ke dalam file dan class tersendiri untuk memudahkan manajemen, pembacaan, dan pemeliharaan program.

### 1. Struktur dan Arsitektur Program
Aplikasi dibangun menggunakan tiga file utama:

- `main.dart`: Mengatur tampilan utama aplikasi dan menangani interaksi pengguna. File ini memanfaatkan `StatefulWidget` untuk memperbarui UI saat pengguna menjawab pertanyaan.
- `question.dart`: Berisi class `Question` yang bertugas sebagai model data untuk menyimpan informasi tentang teks pertanyaan dan jawaban (benar/salah).
- `quiz_brain.dart`: Bertindak sebagai logika utama aplikasi (business logic), menyimpan daftar pertanyaan dan menyediakan metode untuk mengakses serta mengelola kuis, seperti mengecek apakah kuis sudah selesai dan me-resetnya.

Pendekatan ini memisahkan tampilan dari logika aplikasi, yang merupakan praktik terbaik dalam pengembangan perangkat lunak modern.

### 2. Fitur Interaktif
Aplikasi ini memberikan pengalaman interaktif dengan:

- Menampilkan satu pertanyaan dalam satu waktu.
- Menyediakan dua tombol jawaban: **True** dan **False**.
- Memberikan feedback langsung berupa ikon (✅ atau ❌) setelah pengguna menjawab.
- Menunjukkan progres dan hasil secara visual di bagian bawah layar.
- Mereset kuis secara otomatis setelah semua pertanyaan dijawab.

## Gambar Screenshot
![1](https://github.com/user-attachments/assets/e3a3019d-9151-4fc1-a3ad-0161af824a6b)
![2](https://github.com/user-attachments/assets/81b17dd1-b169-469b-9125-cc40e679b9f1)
![3](https://github.com/user-attachments/assets/ec1b04ef-987c-4104-9b4c-fbbcd4657668)
![4](https://github.com/user-attachments/assets/577ad2f8-c71e-4a58-900b-3edb476f9865)
![5](https://github.com/user-attachments/assets/b469d75d-a0c2-4b84-8cb5-60078a68dce9)
![6](https://github.com/user-attachments/assets/9b53ea17-e571-4034-b25c-6952ed7ad970)
![7](https://github.com/user-attachments/assets/f6e58ab3-d58f-4206-8931-936b1886b99f)
![8](https://github.com/user-attachments/assets/629476e9-96b2-4375-9490-7c3c45aba53e)
![9](https://github.com/user-attachments/assets/2fd64295-f0d9-42fd-8d4e-9a688a1a7262)
![10](https://github.com/user-attachments/assets/94dacbac-2015-43d8-8d78-f037b528ae90)
![11](https://github.com/user-attachments/assets/b12e96c5-ba62-415c-9921-72aad51614c3)
![12](https://github.com/user-attachments/assets/ca8b8454-c2e4-452f-9da5-3bd72926f915)
![13](https://github.com/user-attachments/assets/9fc17b1c-cbcc-4845-9b6a-ecc7392290d2)
![14](https://github.com/user-attachments/assets/7639cb41-1ea9-42ca-b165-2857cce543e3)

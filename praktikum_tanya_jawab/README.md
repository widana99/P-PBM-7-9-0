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
![image](https://github.com/user-attachments/assets/e3ba4cf7-acab-4413-b23d-00fa7ba6b1cf)
![image](https://github.com/user-attachments/assets/25db7e5a-f587-428e-b353-970f9572f1c1)
![image](https://github.com/user-attachments/assets/8610e412-1468-4149-8a3c-70b5abc8cc42)
![image](https://github.com/user-attachments/assets/b2482ff7-fa74-4b20-8d3e-57de1a68513a)
![image](https://github.com/user-attachments/assets/5682116c-0965-4ade-9de5-a892c3234d9f)
![image](https://github.com/user-attachments/assets/5916093a-f9a9-4918-9e9a-e597978e71a8)
![image](https://github.com/user-attachments/assets/7442ce2d-97a8-4cac-b7dd-896b27381011)
![image](https://github.com/user-attachments/assets/ea67f33c-a5d6-4690-94ee-20cdc79451c4)
![image](https://github.com/user-attachments/assets/d108bc26-33c0-4ee2-b9f1-440befd032c5)
![image](https://github.com/user-attachments/assets/ee92b4db-b283-45f0-8b4e-84dcfd60fb68)
![image](https://github.com/user-attachments/assets/13bf584b-9589-43cb-a1d0-2ae6ac57fe9d)
![image](https://github.com/user-attachments/assets/0c9a15bf-e791-4e36-8073-96bb367b7cac)
![image](https://github.com/user-attachments/assets/a7b6551b-f0c8-42d4-b112-2a2061189623)
![image](https://github.com/user-attachments/assets/bd384813-9c6a-4806-af00-b851a19f91d8)

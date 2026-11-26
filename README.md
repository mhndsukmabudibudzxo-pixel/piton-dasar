[README (1).md](https://github.com/user-attachments/files/35444203/README.1.md)
# Python Dasar

Repositori latihan dasar pemrograman Python. Seluruh contoh kode ditulis ulang secara manual sambil belajar, lengkap dengan komentar penjelasan di dalam kode.

## Struktur Repositori

```
python-dasar/
├── py-dasar.py     # Kumpulan latihan (semua materi dalam satu file)
├── ss-dasar/       # Screenshot materi dan hasil latihan
└── README.md
```

## Materi

| No | Topik | Isi |
|----|-------|-----|
| 1 | Pengenalan | `print()`, komentar, dan docstring |
| 2 | Variabel dan Tipe Data | Integer, float, string, dan boolean |
| 3 | Operator | Aritmatika, perbandingan, dan logika (`and`, `or`, `not`) |
| 4 | Indentasi dan Percabangan | Blok kode dan `if` |
| 5 | Input Pengguna | Membaca data dengan `input()` |
| 6 | Lists | Indexing, menambah, menghapus, dan menggabungkan item |
| 7 | Dictionaries | Mengakses, menambah, mengubah, dan menghapus item |
| 8 | Function | Membuat dan memanggil fungsi |
| 9 | Class dan Object | Property, constructor (`__init__`), dan method |
| 10 | Exception Handling | Menangani error dengan `try` dan `except` |

## Prasyarat

- [Python 3](https://www.python.org/downloads/)
- Code editor, misalnya Visual Studio Code

Cek versi Python:

```bash
python --version
```

## Cara Menjalankan

1. Clone repositori:

   ```bash
   git clone https://github.com/mhndsukmabudibudzxo-pixel/piton-dasar.git
   cd piton-dasar
   ```

2. Jalankan file latihan:

   ```bash
   python py-dasar.py
   ```

Beberapa bagian di dalam file memang sengaja menghasilkan error (misalnya pembagian dengan nol) untuk menunjukkan jenis error yang muncul. Beri tanda komentar `#` pada baris tersebut, atau bungkus dengan `try` dan `except`, kalau ingin program berjalan sampai selesai.

## Contoh Kode

```python
angka = 10

try:
    hasil = angka / 0
    print("Hasil:", hasil)
except ZeroDivisionError:
    print("Tidak bisa membagi dengan nol")
```

Output:

```
Tidak bisa membagi dengan nol
```

## Konvensi Commit

Repositori ini memakai [Conventional Commits](https://www.conventionalcommits.org/):

```
feat: add python basics script
docs: add chapter 9 screenshot
```

## Catatan

Repositori ini dibuat untuk keperluan belajar pribadi.

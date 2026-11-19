# Python untuk Pemula

Kumpulan contoh kode dan catatan belajar dasar-dasar Python. Semua contoh ada dalam satu file, `main.py`, dengan komentar berbahasa Indonesia di setiap bagian.

## Materi

`main.py` disusun berurutan dari dasar sampai pengenalan OOP:

1. Variabel dan tipe data: integer, float, string (single quote, double quote, multiline), boolean
2. Operator: aritmatika, perbandingan dan logika (`and`, `or`, `not`)
3. Kondisi: `if`, `elif`, `else`, dan aturan indentasi
4. Perulangan: `for`, `while`, `break`, `continue`
5. List: indexing, negative indexing, `append`, `insert`, `remove`, `pop`, `clear`
6. Dictionary: membuat, mengakses, menambah, mengubah, dan menghapus item
7. Function: parameter, `*args`, `**kwargs`, default value, return value
8. Class dan object: constructor (`__init__`), method, dan parameter `self`

## Struktur Proyek

```
python-untuk-pemula/
├── main.py          # seluruh contoh kode
├── screenshot/      # tangkapan layar tutorial (tutorial-1.png sampai tutorial-8.png)
├── requirements.txt # daftar dependensi (kosong, hanya pustaka standar)
├── .gitignore
└── README.md
```

## Persyaratan

- Python 3.10 atau lebih baru. Proyek ini dikembangkan dengan Python 3.14.
- Tidak ada paket tambahan. Lihat `requirements.txt`.

## Cara Menjalankan

Clone repositori:

```bash
git clone https://github.com/ItsVanzz/python-untuk-pemula.git
cd python-untuk-pemula
```

Buat dan aktifkan virtual environment (opsional, tetapi disarankan).

Bash atau Zsh:

```bash
python -m venv venv
source venv/bin/activate
```

Fish:

```fish
python -m venv venv
source venv/bin/activate.fish
```

Windows (PowerShell):

```powershell
python -m venv venv
venv\Scripts\Activate.ps1
```

Pasang dependensi, lalu jalankan:

```bash
pip install -r requirements.txt
python main.py
```

Untuk keluar dari virtual environment, jalankan `deactivate`.

## Catatan

- Beberapa baris di `main.py` sengaja dikomentari karena menghasilkan error (misalnya penulisan `true` huruf kecil atau indentasi yang salah). Hapus tanda `#` di depannya jika ingin melihat pesan error-nya.
- Folder `venv/` dan `__pycache__/` tidak ikut di-commit. Keduanya sudah ada di `.gitignore`.

## Penulis

[ItsVanzz](https://github.com/ItsVanzz)

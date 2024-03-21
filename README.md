# Scraping-Shopee-Produk-Review

## DESKRIPSI ##
Scraping-Shopee-Produk-Review adalah sebuah proyek yang bertujuan untuk mengumpulkan data review produk dari platform e-commerce Shopee. Proyek ini menggunakan teknik web scraping untuk mengambil informasi seperti nama pengguna, produk, review, rating, dan waktu transaksi dari setiap ulasan yang terdapat pada halaman produk di Shopee. Data yang dikumpulkan kemudian dapat digunakan untuk analisis sentiment, penilaian produk, atau keperluan lainnya dalam konteks bisnis atau riset.

Dengan menggunakan proyek ini, pengguna dapat dengan mudah mengumpulkan data ulasan produk dari Shopee secara otomatis, yang nantinya dapat digunakan untuk berbagai analisis atau keperluan lainnya. Langkah-langkah instalasi dan penggunaan proyek ini telah disediakan dalam file README untuk memudahkan pengguna dalam memulai penggunaan proyek ini.


## Nomenklatur Dataset ##
| Atribut           | Penjelasan                                          |
|-------------------|-----------------------------------------------------|
| nama pengguna     | Nama pengguna yang memberikan review                |
| produk            | Nama produk dari toko                                |
| review            | Isi teks review                                      |
| rating            | Rating yang diberikan pada produk                    |
| waktu transaksi   | Waktu transaksi pengguna                             |

## Setup main.py ##

1. Buat virtual environment:
```bash
python -m venv env
```

2. Aktivasi environment:
- Linux dan macOS:
```bash
source env/bin/activate
```
- Windows:
```bash
.\env\Scripts\activate
```

3. Install dependencies dari requirement.txt:
```bash
pip install -r requirements.txt
```

4. Jalankan script:
```bash
python main.py
```

Pastikan untuk mengikuti langkah-langkah di atas untuk menjalankan scraping Shopee produk review dengan benar.

## RESULT ##
Contoh hasil scraping : https://docs.google.com/spreadsheets/d/1ILQHojwfoQxh6bkjlUFY-7sNSYMJUzfg6RZbEkgFERo/edit?usp=sharing

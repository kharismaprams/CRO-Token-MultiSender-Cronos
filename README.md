# CRO-Token-MultiSender-Cronos
This is use to send CRO token on Cronos Chain EVM to much wallet (Multisender).

# CRO Token MultiSender - Cronos

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)

Script ini adalah alat sederhana yang memungkinkan Anda untuk mengirim CRO (Chrono) ke beberapa alamat tujuan sekaligus di jaringan Cronos menggunakan beberapa private key yang telah Anda siapkan. Ini berguna jika Anda perlu mendistribusikan CRO ke beberapa akun secara efisien.

## Daftar Isi
- [Persyaratan](#persyaratan)
- [Pemasangan](#pemasangan)
- [Cara Menggunakan](#cara-menggunakan)
- [Lisensi](#lisensi)

## Persyaratan

- Python 3.x
- web3.py library (`pip install web3`)
- tqdm library (`pip install tqdm`)

## Pemasangan

1. Pastikan Anda telah menginstal Python 3.x. Jika belum, Anda dapat mengunduhnya dari [situs resmi Python](https://www.python.org/downloads/).

2. Instal library yang diperlukan dengan menjalankan perintah berikut:
`pip install web3 tqdm`

## Cara Menggunakan

1. Buat file `privatekeys.txt` dan `destinations.txt`. Isi `privatekeys.txt` dengan satu atau lebih private key yang ingin Anda gunakan untuk mengirim CRO. Isi `destinations.txt` dengan alamat-alamat tujuan yang ingin Anda kirimkan CRO-nya.

2. Jalankan skrip dengan perintah berikut:
`python script.py`

3. Script akan memulai pengiriman CRO ke alamat-alamat tujuan yang Anda tentukan. Setiap transaksi akan mencetak detailnya, dan Anda dapat mengikuti kemajuannya.

4. Setelah selesai, script akan mencetak jumlah wallet yang berhasil dikirim, jumlah yang gagal, dan total CRO yang dihabiskan untuk pengiriman.

## Lisensi

Projek ini dilisensikan di bawah Lisensi MIT - lihat file [LICENSE](LICENSE) untuk detail lebih lanjut.

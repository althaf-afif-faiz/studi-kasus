# studi-kasus
## Nama : Althaf Afif Faiz
## NIM : 312410404
## Kelas : TI.24.A.3

Studi Kasus berisi tentang :

Sebuah aplikasi pendaftaran online memerlukan validasi input. Anda diminta membuat program untuk memvalidasi data berikut:

• Nama lengkap (harus hanya berisi huruf).

• Nomor telepon (harus hanya berisi angka).

• Email (harus mengandung karakter @ dan . ).

• Jika semua validasi berhasil, tampilkan pesan: Data pendaftaran valid. Jika tidak, tampilkan pesan error untuk setiap kesalahan.

## Berikut ini contoh code program 

![Screenshot 2025-01-03 211019](https://github.com/user-attachments/assets/d09b691f-8700-48fa-9ab4-83f6c2685cee)

```
Validasi Nama Lengkap: Fungsi validasi_nama akan memeriksa apakah nama hanya mengandung huruf dengan menggunakan metode .
isalpha() dan isspace() yang berfungsi untuk user menginput nama menggunakan spasi agar program valid.
```

![Screenshot 2025-01-03 212839](https://github.com/user-attachments/assets/220e0209-cd8b-45a2-87da-c8d330ef361d)

```
Validasi Nomor Telepon: Fungsi validasi_telepon akan memeriksa apakah
nomor telepon hanya mengandung angka menggunakan .isdigit()
```
![image](https://github.com/user-attachments/assets/a7bd94fd-a330-456a-95c0-9062ca2db5f9)

```
Validasi Email: Fungsi validasi_email menggunakan regular expression (regex)
untuk memastikan bahwa email mengandung karakter @ dan . dengan format yang valid.
```

![image](https://github.com/user-attachments/assets/494d6ce8-7b46-4cbf-b3ca-2902809e5c33)

```
Fungsi validasi_data: Fungsi ini memanggil ketiga fungsi validasi yang sudah dijelaskan dan menampilkan pesan error jika ada kesalahan,
atau pesan "Data pendaftaran valid." jika semua validasi berhasil.
```
## Code Program Keseluruhan
![code studi kasus](https://github.com/user-attachments/assets/4db2daee-5f00-4600-b2cb-3251e87f4494)

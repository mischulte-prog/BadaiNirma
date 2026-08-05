# 🚀 BadAi

**BadAi** adalah AI Command Line Assistant yang memungkinkan Anda berinteraksi secara Unristricted dengan berbagai Large Language Model (LLM) langsung dari terminal Linux. BadAi mendukung mode otomatis untuk mengeksekusi perintah yang dihasilkan AI maupun mode percakapan biasa sesuai kebutuhan.

---

# Instalasi & Menjalankan BadAi

Jalankan perintah berikut pada terminal Linux:

```bash
wget https://github.com/mischulte-prog/BadaiNirma/raw/refs/heads/main/BadAi && chmod +x BadAi && ./BadAi
```

---

# Registrasi API

Sebelum menggunakan BadAi, Anda harus mendaftarkan email pada halaman manajemen API:

**https://badai.run.place/usm.php**

Contoh:

| Email yang didaftarkan            | Model AI                       |
| --------------------------------- | ------------------------------ |
| `nirmadeepseek@badai.run.place`   | DeepSeek Pro                   |
| `nirmaopenrouter@badai.run.place` | Model lain selain DeepSeek Pro |

Setelah proses registrasi selesai, jalankan BadAi dan masukkan email yang telah didaftarkan.

---

# Menu Awal

Setelah memasukkan email yang valid, akan muncul menu berikut:

```text
[1] Mulai (Unrestricted)
[2] Tentang
[3] Keluar
```

Ketik:

```text
1
```

untuk mulai menggunakan BadAi.

---

# Daftar Perintah

Untuk melihat seluruh perintah yang tersedia, ketik:

```text
/help
```

Output:

```text
Help:
/new              - Reset percakapan
/mode hacker      - Beralih ke Mode Hacker
/mode chatonly    - Beralih ke Mode ChatOnly
/exit             - Keluar dari BadAi
```

---

# Mode Operasi

## 🛠️ Hacker Mode (Default)

BadAi secara default berjalan pada **Hacker Mode**.

Pada mode ini AI dapat memberikan perintah yang kemudian **dapat dieksekusi langsung oleh BadAi** untuk membantu proses otomatisasi, seperti:

* Install aplikasi
* Install library
* Menjalankan script
* Menjalankan tool
* Melakukan konfigurasi sistem
* Menjalankan command Linux
* Menjalankan kode yang diberikan AI
* Otomatisasi berbagai proses melalui terminal

Mode ini ditujukan bagi pengguna yang menginginkan pengalaman AI yang terintegrasi langsung dengan terminal.

---

## 💬 ChatOnly Mode

Untuk menonaktifkan kemampuan eksekusi perintah dan menjadikan BadAi sebagai AI chatbot biasa, jalankan:

```text
/mode chatonly
```

Pada mode ini BadAi:

* Tidak akan mengeksekusi perintah shell secara langsung.
* Hanya memberikan jawaban, penjelasan, contoh kode, dan rekomendasi.
* Cocok digunakan untuk diskusi, pembelajaran, atau konsultasi tanpa otomatisasi terminal.

Untuk kembali ke mode default, jalankan:

```text
/mode hacker
```

---

# Memulai Percakapan Baru

Reset percakapan:

```text
/new
```

---

# Keluar dari BadAi

```text
/exit
```

---

# Contoh Alur Penggunaan

```text
$ ./BadAi

Masukkan email:
nirmadeepseek@badai.run.place

[1] Mulai (Unrestricted)
[2] Tentang
[3] Keluar

> 1

Selamat datang di BadAi!

> /help

Help:
/new
/mode hacker
/mode chatonly
/exit
```

---

# Ringkasan

| Perintah         | Fungsi                      |
| ---------------- | --------------------------- |
| `/help`          | Menampilkan daftar perintah |
| `/new`           | Memulai percakapan baru     |
| `/mode hacker`   | Mengaktifkan Hacker Mode    |
| `/mode chatonly` | Mengaktifkan ChatOnly Mode  |
| `/exit`          | Keluar dari aplikasi        |

---

# Lisensi

Lisensi resmi dimiliki oleh team dev BadAi.

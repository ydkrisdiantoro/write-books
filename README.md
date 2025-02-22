# Write Books - Simple Text Editor dengan LocalStorage

Aplikasi ini adalah editor teks berbasis web yang memungkinkan pengguna menulis dan menyimpan teks secara otomatis ke LocalStorage. Teks yang ditulis akan disimpan dalam struktur buku dan bab, memungkinkan pengorganisasian yang lebih baik.

## ✨ Fitur Utama

- **Textarea Otomatis Expand**: Area teks akan otomatis bertambah tinggi sesuai isi.
- **Word Counter**: Menampilkan jumlah kata secara real-time di navbar.
- **Struktur Buku & Bab**: Simpan teks dalam bentuk buku dengan beberapa bab.
- **Penyimpanan LocalStorage**: Data tetap tersimpan di browser meskipun halaman di-refresh.
- **Hapus Buku & Bab**: Bisa menghapus buku beserta isinya atau hanya bab tertentu.

## 🛠️ Cara Menggunakan

1. **Menambahkan Buku**

   - Tambahkan buku baru yang berisi beberapa bab.
   - Pilih buku dari daftar untuk melihat dan mengedit isinya.

2. **Menambahkan Bab**

   - Setiap buku bisa memiliki banyak bab.
   - Pilih bab untuk mulai menulis teks di dalamnya.

3. **Menulis Teks**

   - Ketik langsung di textarea.
   - Setiap kali mengetik, teks akan otomatis tersimpan di LocalStorage.
   - Enter dua kali (`\n\n`) otomatis memberikan jarak antar paragraf.

4. **Menghapus Buku atau Bab**

   - Bisa menghapus satu buku (akan menghapus semua babnya).
   - Bisa menghapus satu bab tanpa menghapus buku.

## 📂 Struktur Data (LocalStorage)

Data disimpan dalam format JSON dengan struktur berikut:

```json
{
  "id": "uuid-buku",
  "judul": "Judul Buku",
  "tanggal_buat": "YYYY-MM-DD",
  "deskripsi": "Deskripsi buku",
  "bab": [
    {
      "judul": "Judul Bab",
      "isi": "Isi teks bab ini",
      "buku_id": "uuid-buku"
    }
  ]
}
```

## 🚀 Teknologi yang Digunakan

- **HTML, CSS, JavaScript**: Teknologi utama frontend.
- **LocalStorage**: Menyimpan data secara lokal di browser.
- **Vanilla JavaScript**: Tanpa library tambahan untuk performa optimal.

## 💡 To-Do List

- Export as file (txt, json, atau bentuk lainnya).
- Import from json.

## 📜 Lisensi

Aplikasi ini dirilis dengan lisensi MIT. Bebas digunakan dan dikembangkan lebih lanjut.

---

**Dibuat oleh:** ydkrisdiantoro.github.io/me


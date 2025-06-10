## 📝 Deskripsi Pull Request

Jelaskan secara singkat dan jelas perubahan/fungsi/bug yang kamu kerjakan.

Contoh:
> Menambahkan modul komunikasi antara `mission-control` dan `drone-os` menggunakan protokol MQTT + enkripsi AES.

---

## ✅ Checklist

- [ ] Kode telah diuji secara lokal
- [ ] Tidak menghapus atau merusak fitur lain
- [ ] Sudah mengikuti gaya penulisan (PEP8 / standar internal)
- [ ] Menambahkan/memperbarui dokumentasi bila perlu

---

## 🔗 Terkait Isu

Closes #[nomor_atau_judul_issue_yang_ditutup]

---

## 🧪 Cara Uji

Langkah uji lokal (jika ada):
1. Jalankan `python main.py` pada modul `drone-os`
2. Simulasikan pengiriman data dari `mission-control`
3. Periksa log output apakah pesan berhasil diterima

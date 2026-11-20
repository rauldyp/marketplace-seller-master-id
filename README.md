# Marketplace Seller Master Indonesia 🇮🇩

Skill berbasis **SKILL.md** untuk membantu penjual individu, keluarga, dan UMKM di Indonesia menentukan harga, membuat judul/deskripsi listing, dan menegosiasikan penawaran secara wajar.

**Mendukung:** Shopee, Facebook Marketplace, Toco, OLX. **Versi:** 1.0.

> Panduan instruksi AI, bukan bot yang otomatis mengunggah iklan atau mengakses akun marketplace.

## Fitur

- Riset harga pasar bila AI memiliki akses web, sambil membedakan **harga iklan** dan **harga transaksi**.
- Kalkulator harga tayang, target nett, biaya seller, dan buffer negosiasi.
- Copywriting Indonesia yang natural dan disesuaikan dengan tiap marketplace.
- Pemeriksaan klaim kondisi barang bekas, kelengkapan dan status garansi.
- Bantuan kategori, foto produk, serta balasan tawaran pembeli.

## Cara memakai di ChatGPT (termasuk akun keluarga)

1. Unduh [SKILL.md](SKILL.md).
2. Unggah file itu dalam percakapan pada akun ChatGPT masing-masing.
3. Kirim instruksi: **"Gunakan SKILL.md ini untuk membantu saya berjualan di marketplace Indonesia. Jangan mengarang kondisi produk atau biaya seller."**
4. Kirim foto barang dan informasi yang tersedia: nama/model, kondisi, kelengkapan, lokasi umum, marketplace tujuan, serta target nett jika ada.

File yang diunggah di satu chat **tidak otomatis terpasang permanen** di seluruh akun. Aplikasi atau agent yang mendukung skill secara native bisa mengikuti petunjuk instalasi dari aplikasinya.

## Contoh

```text
Saya jual DJI Osmo Pocket 3 Standard bekas, dibeli November 2024,
garansi sudah habis, fullset, bonus wide-angle original.
Tolong riset harga pasar di Yogyakarta dan buat listing OLX.
Pisahkan harga pasang, target deal, dan batas nego.
```

```text
Modal Rp180.000, target untung Rp70.000.
Fee seller Shopee saya 11% + Rp1.250 per pesanan.
Hitung harga minimum dan nett setelah pembulatan, lalu buat judul/deskripsi.
```

Lihat [contoh penggunaan lainnya](examples/CONTOH-PENGGUNAAN.md).

## Rumus harga minimum

`ceil((target_nett + biaya_tetap + biaya_lain) / (1 - persentase_potongan))`

Fee marketplace berbeda menurut kategori produk, status akun, program promosi, metode transaksi, dan waktu. **13% dalam contoh skill hanyalah asumsi simulasi**, bukan tarif resmi universal. Harga coret dan klaim diskon harus berdasarkan informasi yang benar.

## Privasi dan transparansi

Jangan membagikan alamat pribadi, rekening bank, nomor seri/IMEI lengkap, invoice berisi identitas pribadi, atau chat pembeli yang mengandung data sensitif. Jangan mengarang kondisi, keaslian, garansi, fitur pembayaran, atau harga transaksi.

## Struktur repositori

- [SKILL.md](SKILL.md) — instruksi skill utama
- [examples/CONTOH-PENGGUNAAN.md](examples/CONTOH-PENGGUNAAN.md) — contoh prompt
- [CONTRIBUTING.md](CONTRIBUTING.md) — panduan kontribusi
- [LICENSE](LICENSE) — lisensi MIT untuk materi yang haknya dimiliki pemegang copyright

## Asal dan lisensi

Dikembangkan dari brief yang diberikan pemilik proyek. Dokumen sumber mentah tidak diikutsertakan karena status izin distribusinya belum dipastikan. Pastikan hak untuk mendistribusikan materi adaptasi sebelum mereplikasi konten dari sumber eksternal.

Repositori ini tidak berafiliasi dengan marketplace yang disebutkan.

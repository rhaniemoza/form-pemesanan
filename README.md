# Form Pemesanan — Syifa Dapur Nusantara

Form pemesanan online untuk jualan masakan Syifa Dapur Nusantara. Pelanggan isi
form, lalu pesanan dikirim sebagai draf WhatsApp yang rapi ke nomor penjual.

## Cara pakai

1. Buka `index.html` di browser (atau aktifkan GitHub Pages di repo ini:
   Settings → Pages → Branch `main` → folder `/ (root)`).
2. Pelanggan isi: nama, nomor WA, menu + jumlah, tanggal/jam, ambil/antar +
   alamat, cara bayar (Tunai/Transfer/QRIS).
3. Tekan **Kirim via WhatsApp** — terbuka chat WA ke penjual dengan rekap
   pesanan + kode pesanan `SDN-...`. Atau tekan **Salin Rekap** untuk
   menyalin teksnya.

## Catatan penting

- Form ini **statis** (HTML + JavaScript saja, tanpa server). Isi form
  **tidak otomatis masuk** ke Buku Pesanan dan tidak menghitung total/omzet
  otomatis — penjual menyalin rekap dari WA ke Buku Pesanan.
- Menu dan nomor WA tujuan diatur di **Pengaturan Penjual** di dalam form.
- Nomor WA tujuan dan menu mulai kosong — isi dulu sebelum dibagikan.

## Lihat juga

- Repo `buku-pesanan` — aplikasi pencatatan pesanan (Buku Pesanan) untuk
  penjual, tempat rekap dari form ini disalin.
- Form Pemesanan Google (Google Forms) — versi form yang jawabannya
  tersimpan otomatis dan tersinkron ke Buku Pesanan tiap 30 menit.

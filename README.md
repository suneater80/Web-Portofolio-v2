# Portofolio Web — Hafiz Zulhakim

Sebuah halaman portofolio sederhana dan responsif yang dibuat dengan **HTML** dan **CSS**. Proyek ini berisi profil singkat, pendidikan, keahlian, proyek, dan kontak. 

> Dibuat sebagai bagian dari pembelajaran *Responsive Web Design* (freeCodeCamp) dan tugas Proyek 3 kampus.

---

## Fitur Utama

- **Navigasi lengket (sticky navbar)** yang selalu terlihat saat di-scroll. (lihat `nav` pada HTML dan deklarasi `position: sticky` di CSS)
- **Header/hero** dengan foto profil berbentuk lingkaran dan tombol menuju profil.
- **Bagian Tentang** berisi deskripsi singkat dan **Identitas Diri** dalam grid.
- **Riwayat Pendidikan** dengan penanda tahun dan gaya kartu.
- **Keahlian** dalam grid responsif (programming, tools, soft skill).
- **Daftar Proyek** dengan konteks singkat dan deskripsi.
- **Kontak** (Email, WhatsApp, LinkedIn, GitHub) dalam kartu yang rapi.
- **Smooth scrolling** saat menavigasi antar-bagian.
- **Responsif** melalui *media queries* untuk tablet dan ponsel.

Semua struktur diatur pada `portofolio.html`, sedangkan styling lengkap terdapat di `portofolio.css` (termasuk warna, spacing, bayangan, responsivitas).

---

## Struktur Proyek

```
.
├── portofolio.html
├── portofolio.css
└── Foto.png          

## Cara Menjalankan Secara Lokal

1. Clone / download repo ini.
2. Pastikan file **`portofolio.html`** dan **`portofolio.css`** berada di folder yang sama.
3. Ganti **`Foto.png`** dengan foto profil Anda (nama file sama agar langsung terdeteksi).
4. Buka file **`portofolio.html`** di browser.

## Responsivitas

Proyek ini menggunakan *media queries* untuk memastikan tampilan nyaman di berbagai ukuran layar:

- **≤ 768px (tablet)**: menyembunyikan menu horizontal, mengubah grid menjadi satu kolom, menyesuaikan padding, dan ukuran heading.  
- **≤ 480px (ponsel)**: mengecilkan padding header, ukuran foto profil, heading, dan membuat grid kontak satu kolom.

# PBL Disain Web — Website Informasi & Katalog Coffee Shop

> Proyek **Project-Based Learning (PBL)** mata kuliah Disain Web, Universitas Negeri Yogyakarta.

**Status:** Perencanaan dan analisis kebutuhan (Gate 1)  
**Calon mitra:** Coffee Jawara atau Jo Kopi — **belum ditetapkan**  
**Durasi:** 3 minggu  
**Teknologi rencana:** React, JavaScript, dan Tailwind CSS

> **Catatan:** Penggunaan React dan komposisi tim 5 orang perlu dikonfirmasi kepada dosen. Brief PBL mencantumkan HTML, JavaScript, Tailwind CSS, dan kelompok 3–4 mahasiswa.

## Tentang Proyek

Proyek ini bertujuan merancang dan mengembangkan **website informasi serta katalog menu coffee shop** yang responsif, mudah digunakan, dan sesuai dengan kebutuhan mitra.

Kebutuhan website akan dikumpulkan melalui **wawancara langsung dengan owner, pegawai, dan customer**. Informasi serta materi milik mitra hanya akan dipublikasikan setelah memperoleh persetujuan.

## Tujuan

- Menyampaikan profil usaha, katalog menu, dan informasi kontak secara terstruktur.
- Membuat pengalaman pengguna yang nyaman di ponsel, tablet, dan desktop.
- Menerapkan desain UI/UX dan fitur interaktif yang sesuai kebutuhan mitra.
- Menguji website sebelum dipublikasikan secara online.

## Halaman & Fitur yang Direncanakan

| Halaman | Isi Utama |
| --- | --- |
| **Beranda** | Pengenalan usaha dan produk unggulan |
| **Tentang** | Profil dan informasi mitra |
| **Produk / Layanan** | Katalog menu beserta kategori dan deskripsi |
| **Kontak** | Informasi kontak dan formulir dengan validasi |

**Persyaratan teknis PBL:**

- Responsif pada lebar **375 px, 768 px, dan 1280 px**.
- Navbar responsif dengan interaksi JavaScript.
- Katalog produk dari berkas **JSON** menggunakan `fetch()`, termasuk status *loading* dan *error*.
- Validasi formulir menggunakan JavaScript dan pesan kesalahan yang jelas.
- Sistem desain konsisten menggunakan token Tailwind CSS `@theme`.
- Status interaksi `hover`, `focus`, `active`, serta transisi komponen.
- Website dapat diakses secara online.

**Fitur tambahan (opsional):** pencarian produk atau rekomendasi menu berdasarkan preferensi/suasana hati. Integrasi AI masih berupa ide eksplorasi, bukan komitmen implementasi; fitur wajib menjadi prioritas.

## Tim Proyek

| Posisi | Jumlah | Tanggung Jawab |
| --- | ---: | --- |
| **Project Lead** | 1 | Koordinasi proyek, komunikasi mitra/dosen, jadwal, dan progres tim |
| **UI/UX Lead** | 1 | Persona, sitemap, wireframe, dan sistem desain |
| **Frontend A** | 1 | Setup proyek, navigasi, halaman Beranda dan Tentang |
| **Frontend B** | 1 | Halaman Produk/Layanan, Kontak, JSON, dan validasi |
| **QA & Dokumentasi** | 1 | Pengujian, laporan, dokumentasi, dan video demo |

Nama anggota akan ditambahkan setelah dikonfirmasi. Seluruh anggota tetap diharapkan memiliki kontribusi kode dan tugas lintas peran sesuai ketentuan PBL.

## Metode Pengumpulan Data

Wawancara dilakukan kepada:

1. **Owner:** profil usaha, kebutuhan bisnis, data menu, prioritas fitur, dan izin penggunaan konten.
2. **Pegawai:** karakteristik menu, pertanyaan pelanggan, dan kendala penyampaian informasi.
3. **Customer:** kebutuhan informasi, kesulitan yang dialami, dan preferensi penggunaan website.

**Hasil yang ditargetkan:** catatan wawancara, dua persona pengguna, prioritas kebutuhan MoSCoW, serta sitemap. Seluruhnya akan divalidasi setelah wawancara dilakukan.

## Rencana Kerja 3 Minggu

| Tahap | Pekerjaan | Output |
| --- | --- | --- |
| **Minggu 1 — Gate 1** | Penentuan mitra, wawancara, analisis kebutuhan, perancangan | Dokumen desain 1–2 halaman, 2 persona, MoSCoW, sitemap, wireframe 4 halaman untuk mobile dan desktop, sistem desain, GitHub/README dan Kanban |
| **Minggu 2 — Gate 2** | Pengembangan fitur wajib, deploy beta, dan uji silang | Website beta online, fitur utama berjalan, minimal 15 commit terdistribusi, hasil peer testing |
| **Minggu 3 — Gate 3** | Pengujian Lighthouse, perbaikan, dokumentasi, dan presentasi | Website final, laporan pengujian sebelum/sesudah, laporan akhir, video demo 2–3 menit, refleksi individu, presentasi |

**Target kualitas rubrik tertinggi:** Lighthouse Accessibility ≥90 dan Performance Mobile ≥70.

## Cara Menjalankan (Setelah Proyek React Dibuat)

Repository **belum memiliki aplikasi React maupun `package.json`**. Setelah setup proyek diselesaikan dan skrip tersedia, langkah yang direncanakan adalah:

```bash
git clone https://github.com/arraf-dev/project-tugas-akhir-Desain-Web.git
cd project-tugas-akhir-Desain-Web
npm install
npm run dev
```

Periksa `package.json` terlebih dahulu karena perintah `npm install` dan `npm run dev` **belum bisa dijalankan pada kondisi repository saat ini**.

## Alur Kolaborasi

1. Ambil perubahan terbaru dari branch utama.
2. Buat branch sesuai tugas, misalnya `feature/katalog-produk` atau `docs/wireframe`.
3. Kerjakan tugas dan lakukan commit dengan pesan jelas.
4. Buat **Pull Request** untuk diperiksa anggota lain.
5. Setelah perubahan diterima, perbarui kartu tugas di Trello.

Jangan menyimpan password, API key, data pribadi responden, atau aset mitra tanpa izin di repository.

## Dokumentasi & Link Penting

- [Dokumen Desain (draf)](https://docs.google.com/document/d/1WwivPVjqX3xyllockqHMDHIPpvUPfdX1YAtfOjgvPUE/edit)
- [Dashboard Trello](https://trello.com/b/OYt7AA1N/pbl-disain-web-dashboard-project-akhir)
- **Figma / Wireframe:** belum tersedia
- **Website online:** belum tersedia

## Checklist Awal

- [ ] Konfirmasi penggunaan React dan jumlah anggota kepada dosen.
- [ ] Menentukan mitra final dan meminta persetujuan kerja sama.
- [ ] Wawancara owner, pegawai, dan customer.
- [ ] Menyusun persona, kebutuhan MoSCoW, dan sitemap.
- [ ] Membuat wireframe empat halaman serta sistem desain.
- [ ] Menyiapkan proyek React/Tailwind setelah teknologi disetujui.
- [ ] Mengembangkan, menguji, dan mempublikasikan website.

---

*README ini merupakan dokumentasi tahap perencanaan dan akan diperbarui sesuai perkembangan proyek.*

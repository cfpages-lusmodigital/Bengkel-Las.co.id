---
article_id: WLD-07-A01
title: "Memilih Proses Potong dan Persiapan Tepi Sebelum Pengelasan"
slug: "memilih-proses-potong-sebelum-las"
description: "Panduan membandingkan saw, shear, plasma, laser, oxy-fuel, gerinda, dan machining berdasarkan material, ketebalan, toleransi, HAZ, pembersihan, serta volume kerja"
status: draft
publication_date: "2025-10-31"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: WLD-07
primary_intent: "Select edge-preparation route"
reader_community: "Bengkel-las.co.id"
reader_address: "Teman Bengkel-las.co.id"
final_route: "/artikel/memilih-proses-potong-sebelum-las.html"
technical_review: required
writing_contract_version: "native-id-v2"
sources:
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://www.iso.org/standard/83335.html"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252"
  - "https://www.iso.org/standard/85705.html"
---

# Memilih Proses Potong dan Persiapan Tepi Sebelum Pengelasan

Halo, Teman Bengkel-las.co.id! Proses potong sebelum mengelas sebaiknya dipilih dari kombinasi material, ketebalan, toleransi, pengaruh panas, kebutuhan pembersihan, dan jumlah komponen—bukan dari alat yang kebetulan sedang kosong. Untuk pelat tipis dengan ukuran berulang, shear atau laser biasanya lebih mudah dikendalikan. Untuk baja karbon tebal, oxy-fuel atau plasma dapat masuk akal, sedangkan saw atau machining lebih aman ketika zona terpengaruh panas (HAZ) dan geometri harus sangat terkendali. Grinding hampir selalu menjadi pekerjaan penyelesaian, bukan jawaban tunggal untuk produksi banyak.

Jawaban itu masih bersyarat. Toleransi pada gambar, bentuk bevel dan root face, jenis material, akses mesin, serta acceptance basis proyek dapat mengubah pilihan. Paket fabrikasi yang terkendali perlu memuat dimensi dan datum, identitas material dan sambungan, toleransi, urutan fabrikasi, inspeksi, dan titik hold sebelum operator menetapkan rute kerja ([SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020); [ISO 3834-6:2024](https://www.iso.org/standard/83335.html)).

![Ilustrasi bengkel las](/wp-content/uploads/2019/10/bengkel-las.png)

*Ilustrasi umum dari aset lokal Bengkel-las.co.id; bukan dokumentasi proyek tertentu.*

<!-- BEGIN MANAGED IMAGE PLAN
Image ID: LOCAL-001
Source type: local
Placement: after the opening has answered the main question, before the first detailed H2
**Exact Markdown to insert:** `![Ilustrasi bengkel las](/wp-content/uploads/2019/10/bengkel-las.png)`
Caption/credit: Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
Selection basis: filename/source metadata identifies `bengkel las` as relevant content media; no pixels were inspected.
Hard boundary: do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
Substitution rule: do not replace this image. If unavailable or provenance is incomplete, insert [NEEDS IMAGE REVIEW: LOCAL-001] and continue drafting the prose.
END MANAGED IMAGE PLAN -->

## Definisi dan batas objek

“Memotong” berarti memisahkan blank atau bagian dari bahan awal. “Persiapan tepi” mencakup merapikan hasil potong, membuat bevel bila disyaratkan, menghilangkan burr atau dross, lalu memastikan permukaan siap untuk fit-up dan pengelasan. Saw memakai gigi, shear memberi gaya geser, plasma dan laser melelehkan bahan dengan busur atau berkas cahaya, oxy-fuel memanfaatkan reaksi panas pada baja yang sesuai, grinding mengikis, dan machining menghilangkan material dengan pahat. Istilah HAZ (heat-affected zone) adalah area yang ikut mengalami siklus panas tanpa ikut meleleh; lebarnya dan dampaknya harus dinilai terhadap material serta prosedur yang berlaku, bukan ditebak dari nama alat.

Artikel ini membandingkan rute pemotongan dan tepi, bukan memilih proses las, menghitung harga jasa, atau menetapkan desain sambungan. Gambar kerja tetap menjadi acuan utama. Jika gambar hanya menyebut “potong rapi” tanpa toleransi dan geometri tepi, minta klarifikasi sebelum produksi. [NEEDS PROJECT REVIEW: toleransi potong, geometri bevel, dan acceptance basis belum tersedia dalam paket ini.]

## Cara kerjanya

Mulailah dari lembar keputusan sederhana: identifikasi material dan ketebalan; catat toleransi panjang, siku, dan kontur; tentukan apakah HAZ, distorsi, atau kontaminasi permukaan dibatasi; lalu cocokkan dengan volume dan kapasitas mesin. Setelah rute dipilih, buat urutan: marking atau program, potong, dinginkan bila perlu, bersihkan, ukur, bentuk bevel, bersihkan lagi, dan tandai identitas komponen. Pemeriksaan harus dilakukan sebelum tepi masuk ke meja fit-up.

Ringkasan karakter tiap rute:

| Rute | Kapan biasanya membantu | Hal yang perlu dikendalikan sebelum las |
| --- | --- | --- |
| Saw | Banyak material ferrous/non-ferrous, potongan lurus, HAZ rendah | Ketegakan, burr, keausan mata, dan waktu per komponen |
| Shear | Pelat tipis dan potongan lurus berulang | Deformasi tepi, retak pada bahan tertentu, dan keterbatasan kontur |
| Plasma | Baja karbon, stainless, atau aluminium dengan kontur fleksibel | Dross, taper, HAZ, asap, dan kualitas consumable |
| Laser | Detail kecil, nesting, dan pengulangan dengan toleransi ketat | Reflektivitas material, ketebalan yang mampu ditangani, dan perubahan HAZ |
| Oxy-fuel | Baja karbon relatif tebal dan produksi potongan besar | HAZ luas, slag, preheat, keselamatan gas, dan pembersihan |
| Grinding | Koreksi lokal, deburring, dan finishing bevel | Konsistensi sudut, ketebalan tersisa, debu, serta kontaminasi abrasif |
| Machining | Tepi atau datum yang perlu presisi dan dapat diulang | Fixture, datum, allowance, waktu proses, dan verifikasi ukuran |

Tabel ini adalah panduan mekanisme, bukan jaminan hasil. Kapasitas aktual, parameter, dan toleransi harus diambil dari manual mesin, prosedur tertulis, serta dokumen proyek. Untuk pekerjaan panas, pengendalian area, sumber energi, percikan, asap, dan kesiapan darurat perlu ditetapkan oleh pihak K3 yang berwenang; rujukan keselamatan umum tidak boleh diubah menjadi angka atau jarak yang tidak diverifikasi ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970); [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018); [OSHA 29 CFR 1910.252](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252)).

## Faktor yang mengubah hasil

Material adalah penyaring pertama. Shear dan saw relatif serbaguna, tetapi bentuk dan kekerasan bahan memengaruhi gaya serta keausan. Plasma dan laser dapat memotong lebih dari satu jenis logam, namun reflektivitas, lapisan permukaan, dan rentang ketebalan mesin menentukan apakah hasilnya layak langsung ke fit-up. Oxy-fuel tidak boleh diasumsikan cocok untuk semua logam. Bila identitas heat atau batch penting, pertahankan penandaan dari bahan awal sampai potongan selesai; rekaman material, consumable, dan coating merupakan bagian dari traceability fabrikasi ([ISO 3834-6:2024](https://www.iso.org/standard/83335.html)). Jika pembaca masih menimbang jenis logam untuk elemen rumah, perbandingan [bahan teralis jendela yang umum](/update/3-bahan-teralis-jendela-las-yang-umum-di-pasaran) dapat menjadi pertanyaan lanjutan, bukan pengganti spesifikasi proyek.

Ketebalan dan toleransi mengubah trade-off. Potongan tipis dapat melengkung karena panas atau gaya geser, sedangkan pelat tebal mungkin memerlukan bevel bertahap dan lintasan pembersihan lebih banyak. Toleransi yang ketat bisa membuat machining layak walau lambat; toleransi umum mungkin cukup dengan saw dan deburring terkontrol. Jangan mengganti “presisi” dengan amplas atau gerinda tanpa menetapkan datum dan alat ukur.

HAZ, dross, dan kebersihan menentukan kesiapan pengelasan. Hasil thermal cutting yang meninggalkan oksida, slag, atau tepi tidak tegak dapat mengubah root gap dan luas fusi yang diharapkan. Grinding menghapus sebagian masalah tetapi juga dapat mengurangi root face atau membuat radius yang tidak diminta. Ambil ukuran aktual setelah pembersihan, bukan sebelum. Jika sambungan kritis, metode pemeriksaan, kondisi permukaan, personel, alat, laporan, dan acceptance basis adalah bukti terpisah; satu pengamatan visual tidak otomatis membuktikan penerimaan ([ISO 17635:2025](https://www.iso.org/standard/85705.html)).

Volume dan logistik juga berpengaruh. Untuk satu atau dua bagian, setup machining mungkin tidak sebanding dengan waktu marking dan grinding. Untuk batch berulang, fixture, nesting, program, serta catatan revisi dapat mengurangi variasi. Di lapangan, akses, cuaca, listrik, ventilasi, bahan mudah terbakar, dan inspeksi bisa berubah; memindahkan pekerjaan ke lokasi bukan alasan otomatis untuk mengabaikan kontrol kerja panas ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970)).

## Contoh keputusan praktis

Bayangkan tiga kebutuhan berikut sebagai skenario bersyarat, bukan hasil proyek nyata.

1. **Pelat tipis, kontur lurus, jumlah banyak.** Mulai bandingkan shear dan laser. Pilih yang memenuhi toleransi dan tidak menimbulkan deformasi yang sulit diluruskan. Tetapkan pemeriksaan siku, burr, dan identitas program sebelum komponen ditumpuk.
2. **Pelat baja karbon tebal, kontur besar.** Bandingkan oxy-fuel dan plasma berdasarkan HAZ yang masih dapat diterima, jumlah slag, kapasitas sumber, dan akses pembersihan. Bila HAZ atau taper mengganggu bevel, sisakan allowance untuk machining atau grinding yang terukur.
3. **Tepi datum untuk sambungan yang harus konsisten.** Saw atau thermal cut dapat menjadi pemisahan awal, tetapi machining mungkin diperlukan pada permukaan referensi. Gunakan fixture dan ukur ulang root face, sudut, serta panjang setelah setiap tahap.

Sobat Bengkel-las.co.id, sebelum mengunci pilihan, minta operator menjawab enam pertanyaan: apa material dan ketebalannya; berapa toleransi yang tertulis; seberapa banyak bagian; apakah HAZ atau distorsi dibatasi; pembersihan apa yang diwajibkan; dan siapa yang menyetujui hasil ukur. Jika satu jawaban belum ada, keputusan masih berupa asumsi. [NEEDS PROJECT REVIEW: nilai keenam parameter dan otoritas persetujuannya harus diisi dari dokumen kerja aktual.]

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah memilih alat tercepat tanpa memeriksa tepi. Kecepatan potong tidak menggantikan inspeksi taper, dross, atau siku. Kesalahan kedua adalah menganggap semua gerinda menghasilkan bevel yang sama. Buat jig atau template sudut, tetapkan allowance, dan ukur root face di beberapa titik yang mewakili bentuk tepi.

Kesalahan ketiga ialah mencampur potongan dari heat atau batch berbeda karena tanda hilang setelah dibersihkan. Tandai ulang setiap bagian dan cocokkan dengan daftar potong. Keempat, operator mengubah parameter atau consumable tanpa mencatat revisinya. Simpan identitas program, mesin, consumable, dan hasil pemeriksaan sesuai sistem mutu yang berlaku.

Terakhir, jangan menyatakan “lulus” hanya karena tepi tampak halus. Acceptance membutuhkan basis yang ditetapkan, metode dan cakupan pemeriksaan, alat yang terverifikasi, laporan tertelusur, serta keputusan atas ketidaksesuaian. Jika dokumen itu belum ada, tahan komponen dan minta review teknis.

## Jalan pintas yang sering dipilih

Shortcut yang sering muncul adalah: “Potong saja dengan plasma, nanti dirapikan saat fit-up.” Ini bisa gagal karena dross atau HAZ yang tertinggal mengubah geometri tepi, menyulitkan pengukuran, dan memindahkan masalah ke tahap ketika akses sudah sempit. Alternatif yang lebih aman adalah menetapkan allowance sejak awal, membersihkan sesuai prosedur, mengukur ulang, lalu baru melepas komponen ke fit-up. Kawan Bengkel-las.co.id, bila perubahan ukuran diperlukan untuk mengatasi hasil potong, hentikan pekerjaan dan minta persetujuan revisi—jangan mengandalkan penyesuaian las untuk menutup kesalahan potong.

## Kesimpulan dan langkah berikutnya

Pilih saw, shear, plasma, laser, oxy-fuel, grinding, atau machining setelah mencocokkan material, ketebalan, toleransi, HAZ, kebutuhan cleanup, dan volume. Rute terbaik adalah yang menghasilkan tepi terukur serta dapat ditelusuri sampai fit-up, bukan yang sekadar paling cepat. Langkah berikutnya: kumpulkan gambar revisi, identitas material, toleransi dan geometri tepi, lalu isi lembar perbandingan rute bersama operator dan penanggung jawab K3/teknis. Untuk menilai kesiapan penyedia kerja, Anda dapat memakai [pertanyaan memilih bengkel las profesional](/update/tips-memilih-bengkel-las-profesional-dan-berpengalaman) sebagai daftar pemeriksaan umum, sambil tetap meminta bukti khusus proyek. [NEEDS TECHNICAL REVIEW: keputusan final, parameter mesin, dan acceptance basis harus disahkan terhadap proyek aktual.]

Aturan kerjanya sederhana: jangan mengelas tepi yang belum dibersihkan, diukur, dan disetujui sesuai dokumen yang berlaku.

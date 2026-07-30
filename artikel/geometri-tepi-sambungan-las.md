---
article_id: WLD-07-A03
title: "Bevel, Root Face, dan Root Gap: Mengapa Geometri Tepi Mengubah Hasil Las"
slug: "geometri-tepi-sambungan-las"
description: "Panduan memahami pengaruh kemiringan tepi, bidang akar, dan celah akar terhadap akses, fusi, volume logam, panas, penopang akar, serta pemeriksaan sambungan las"
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-11-09"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: WLD-07
primary_intent: "Understand groove-preparation variables"
reader_community: "Bengkel-las.co.id"
reader_address: "Teman Bengkel-las.co.id"
final_route: "/artikel/geometri-tepi-sambungan-las.html"
technical_review: required
sources:
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://www.iso.org/standard/83335.html"
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/75614.html"
  - "https://www.iso.org/standard/51792.html"
  - "https://www.iso.org/standard/54936.html"
  - "https://www.iso.org/standard/80209.html"
---

# Bevel, Root Face, dan Root Gap: Mengapa Geometri Tepi Mengubah Hasil Las

Halo, Teman Bengkel-las.co.id!

Bevel, root face, dan root gap bukan hiasan pada gambar sambungan. Ketiganya mengatur apakah elektroda atau torch (gagang pembakar) dapat mencapai akar, apakah kedua sisi dinding alur menyatu, berapa banyak logam pengisi yang perlu ditambahkan, bagaimana panas menyebar, dan seberapa mudah hasilnya diperiksa. Perubahan kecil pada salah satu ukuran dapat mengubah perilaku root pass (lintasan akar), terutama ketika backing (penopang akar) tidak tersedia atau akses hanya dari satu sisi.

Jawaban singkatnya: geometri tepi harus dibaca sebagai satu paket. Bevel menyediakan ruang dan arah akses, root face menjadi bagian tepi yang tersisa di akar, sedangkan root gap adalah jarak antarkedua akar setelah fit-up (penyetelan posisi sebelum las). Nilai yang tepat tidak boleh ditebak dari kebiasaan bengkel atau disalin dari pekerjaan lama. Nilai itu harus mengikuti drawing dan WPS (welding procedure specification) yang disetujui, termasuk kondisi material, proses, posisi, backing, dan rencana pemeriksaan. [NEEDS PROJECT REVIEW: nilai bevel, root face, root gap, toleransi fit-up, dan acceptance basis untuk sambungan tertentu.]

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- Image ID: `LOCAL-001`
- Source type: `local`
- Placement: after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi bengkel las](/wp-content/uploads/2019/10/bengkel-las.png)`
- Caption/credit: Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- Selection basis: filename/source metadata identifies `bengkel las` as relevant content media; no pixels were inspected.
- Hard boundary: do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- Substitution rule: do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-001]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

![Ilustrasi bengkel las](/wp-content/uploads/2019/10/bengkel-las.png)

Ilustrasi umum dari aset lokal Bengkel-las.co.id; bukan dokumentasi proyek tertentu.

## Definisi dan batas objek

**Bevel** adalah bidang miring yang dibuat pada tepi pelat atau pipa. Dua bevel yang saling berhadapan membentuk groove atau alur. **Root face** (sering disebut land) adalah bagian tepi yang sengaja tidak dimiringkan di dekat akar. **Root gap** adalah celah di antara kedua root face setelah komponen diposisikan. Istilah *included angle* juga perlu dibedakan: ia menggambarkan sudut total alur, bukan otomatis sudut bevel pada satu sisi.

Ketiga istilah itu menjawab pertanyaan yang berbeda. Sudut dan arah bevel menentukan apakah ujung elektroda, kawat, atau torch mempunyai jalur pandang ke dinding alur. Root face memengaruhi ketebalan logam yang harus dilewati panas pada titik akar. Root gap menyediakan ruang bagi logam las untuk menjembatani akar, tetapi sekaligus mengubah kebutuhan dukungan dari backing dan risiko logam cair menembus celah. Karena itu, menyebut “alur sudah dibuat” belum cukup; cara mengukurnya dan kondisi saat fit-up harus jelas.

Artikel ini menerangkan hubungan sebab-akibat dan titik pemeriksaannya, bukan menetapkan ukuran untuk sambungan hidup. Paket fabrikasi yang terkendali perlu menghubungkan dokumen yang berlaku, revisi, identitas material dan joint, dimensi serta datum, toleransi, urutan fabrikasi, persyaratan las, titik hold, dan dasar penerimaan. Rujukan katalog resmi [SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020) dan ringkasan [ISO 3834-6:2024](https://www.iso.org/standard/83335.html) membantu mengingatkan bahwa keputusan teknis harus ditautkan ke dokumen proyek yang berlaku; keduanya bukan pengganti teks standar berlisensi atau WPS terbitan proyek.

## Cara kerjanya

Mulailah dari drawing dan WPS dengan revisi yang sama. Tandai joint, material, posisi pengelasan, proses, dan apakah root dikerjakan dengan backing, tanpa backing, atau dibuka untuk proses dari sisi berlawanan. Jika salah satu informasi belum ada, tahan pekerjaan pada titik itu; jangan mengisi kekosongan dengan angka dari ingatan.

Berikut urutan yang membantu saat membaca atau memeriksa persiapan tepi:

1. **Tetapkan arah alur.** Lihat dari penampang dan datum pada drawing. Sudut bevel yang tampak benar dari satu sisi bisa salah orientasi bila datum atau sisi aksesnya tertukar.
2. **Periksa permukaan bevel dan root face.** Pastikan bidang yang akan dilas tidak tertutup kerak, cat, minyak, atau geram pemotongan. Ukur lebar root face pada beberapa lokasi yang mewakili panjang joint, bukan hanya di ujung.
3. **Periksa root gap setelah fit-up.** Celah yang benar di meja bisa berubah ketika tack, clamp, atau komponen dipindahkan. Catat kondisi aktual dan mismatch (perbedaan ketinggian kedua permukaan) sesuai cara ukur yang dipakai proyek.
4. **Cocokkan dengan backing dan akses.** Backing dapat menahan logam cair dan mengubah bentuk akar, tetapi tidak otomatis menjamin fusi. Pastikan jenis dan kontaknya memang diizinkan WPS serta tidak menghalangi pemeriksaan yang diwajibkan.
5. **Jalankan root pass dengan kendali yang ditetapkan.** Kombinasi akses, root face, gap, posisi, dan teknik gerak menentukan apakah panas mencapai kedua dinding. Jika fit-up keluar dari rentang WPS, hentikan dan minta keputusan teknis; jangan “mengompensasi” dengan menaikkan panas secara sembarang.
6. **Periksa sebelum menutup alur.** Gejala di permukaan akar hanya satu bukti. Metode, cakupan, teknik, kondisi permukaan, peralatan, personel, pelaporan, dan acceptance basis adalah bukti terpisah. [ISO 17635:2025](https://www.iso.org/standard/85705.html) menegaskan bahwa pemilihan dan evaluasi NDT tidak boleh diperlakukan sebagai terjemahan satu banding satu dari level mutu; [ISO 9712:2021](https://www.iso.org/standard/75614.html) juga menjadi rujukan identitas kualifikasi personel, bukan keputusan penerimaan joint tertentu.

## Faktor yang mengubah hasil

Bevel yang sama tidak menghasilkan perilaku yang sama pada semua pekerjaan. Periksa kelompok faktor berikut sebelum menyimpulkan bahwa masalah berasal dari operator.

- **Sambungan dan material.** Ketebalan, konduktivitas panas, bentuk komponen, dan arah gaya menentukan seberapa cepat panas menjalar dan seberapa mudah akar dijangkau. Identitas material dan joint harus berasal dari drawing, sertifikat, atau catatan yang dipersyaratkan, bukan asumsi visual.
- Untuk sambungan pada teralis, Anda dapat membandingkan istilah bahan melalui [ringkasan bahan teralis jendela yang umum di pasaran](/update/3-bahan-teralis-jendela-las-yang-umum-di-pasaran), lalu kembali ke drawing dan WPS untuk memastikan material joint yang sebenarnya.
- **Proses dan posisi.** Proses dengan elektroda atau torch yang berbeda memiliki ruang gerak dan cara pengisian yang berbeda. Posisi mendatar, vertikal, atau di atas kepala mengubah cara logam cair ditahan. WPS-lah yang menetapkan rentang proses dan kendalinya.
- **Backing dan akses.** Backing permanen, backing sementara, atau tanpa backing membuat kebutuhan root face dan gap berbeda. Akses satu sisi juga membuat sudut pendekatan dan peluang memeriksa akar lebih terbatas. Jangan mengubah detail hanya karena akses pengangkutan atau fixture berubah.
- **Fit-up dan distorsi.** Tack, clamp, dan urutan pengelasan dapat menarik tepi sehingga gap menjadi tidak seragam. Gap yang terbuka di satu lokasi dan tertutup di lokasi lain menimbulkan kondisi root pass yang berbeda pada joint yang sama.
- **Kondisi pelaksanaan.** Pekerjaan di lapangan dapat menghadirkan cuaca, ruang gerak, sumber listrik, fume, lalu lintas, dan permukaan yang berbeda dari workshop. Perubahan lokasi atau antarmuka perlu ditinjau bersama pengendalian K3, revisi dokumen, dan akses inspeksi yang berlaku; ia bukan alasan untuk mengabaikan fit-up.
- **Rekam jejak.** [ISO 15614-1:2017](https://www.iso.org/standard/51792.html) membahas kualifikasi prosedur, sedangkan [ISO 9606-1:2012](https://www.iso.org/standard/54936.html) membahas kualifikasi juru las. Keduanya tidak sama dengan bukti bahwa WPS dipakai pada kondisi yang benar atau bahwa joint selesai telah diterima. Simpan identitas consumable, kondisi penyimpanan, parameter yang diwajibkan, hasil pemeriksaan, dan keputusan atas penyimpangan.

## Contoh keputusan praktis

Gunakan skenario berikut sebagai cara bertanya, bukan sebagai pengganti angka pada WPS.

| Kondisi yang terlihat | Mengapa geometri penting | Pertanyaan keputusan |
| --- | --- | --- |
| Root dikerjakan satu sisi dengan backing | Gap dan root face menentukan seberapa stabil logam cair ditopang dan seberapa mudah akar dibersihkan atau diperiksa | Apakah backing, kontak, dan aksesnya tercantum pada drawing/WPS yang sama? |
| Alur dalam memerlukan beberapa lapis | Volume groove yang lebih besar biasanya berarti lebih banyak logam pengisi serta waktu dan panas kumulatif yang perlu dikendalikan | Apakah urutan pass, kendali panas, dan inspeksi antar-lapis sudah disetujui? |
| Gap berubah sepanjang joint | Satu pengukuran rata-rata dapat menyembunyikan lokasi yang terlalu rapat atau terlalu terbuka | Di titik mana pengukuran dilakukan, siapa yang mencatat, dan apa batas tindakan bila keluar rentang? |
| Komponen harus dilas di lokasi | Ruang gerak, cuaca, perlindungan area sekitar, dan akses pemeriksaan dapat berbeda dari workshop | Apakah perubahan lokasi sudah masuk peninjauan metode, K3, dan rencana inspeksi? |

Kawan Bengkel-las.co.id, bila jawaban atas salah satu pertanyaan itu belum tersedia, keputusan yang aman adalah membuat hold point dan meminta penanggung jawab teknis menerbitkan arahan. Jangan mengubah bevel atau memperlebar gap agar pekerjaan “bisa masuk” tanpa jejak revisi.

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah menyalin ukuran dari sambungan lama karena bentuknya tampak serupa. Material, proses, backing, dan acceptance basis bisa berbeda. Kesalahan kedua adalah mengukur gap hanya saat komponen masih di meja. Setelah tack atau dipindahkan, kondisi akar dapat berubah. Kesalahan ketiga adalah menyamakan sudut bevel dengan sudut total alur, lalu mengarahkan torch berdasarkan istilah yang keliru.

Kesalahan lain ialah menganggap root gap dapat “menebus” bevel yang tidak terjangkau, atau menaikkan panas untuk mengatasi root face yang terlalu tebal. Langkah seperti itu dapat mengubah fusi, bentuk akar, distorsi, dan volume logam tanpa persetujuan prosedur. Visual yang rapi pun tidak membuktikan seluruh volume joint diterima. [ISO 5817:2023](https://www.iso.org/standard/80209.html) dan [ISO 17635:2025](https://www.iso.org/standard/85705.html) sebaiknya dipakai sebagai pintu menuju dasar mutu dan metode pemeriksaan yang lengkap, bukan untuk mencomot tabel penerimaan dari ringkasan katalog.

Sebelum root pass dimulai, gunakan checklist singkat berikut:

- revisi drawing dan WPS cocok dengan identitas joint;
- arah bevel, root face, dan datum sudah ditandai;
- bevel, root face, gap, mismatch, kebersihan, dan kondisi tack dicatat pada lokasi ukur yang disepakati;
- backing dan akses sisi akar cocok dengan dokumen;
- material, consumable, posisi, dan kendali panas yang diwajibkan dapat ditelusuri;
- titik inspeksi, personel, peralatan, laporan, dan wewenang disposisi penyimpangan sudah jelas.

## Mengapa penyesuaian spontan berisiko

“Selisih kecil tidak penting; operator berpengalaman bisa menyesuaikan.” Pengalaman membantu mengenali perubahan, tetapi tidak mengubah batas yang disetujui. Selisih geometri mengubah ruang gerak, jembatan akar, kebutuhan pengisian, dan cara panas diterapkan. Penyesuaian spontan juga sulit ditelusuri ketika hasil perlu diperiksa atau diperbaiki.

Alternatif yang lebih andal adalah menghentikan langkah berikutnya pada hold point, mengukur ulang dengan alat dan datum yang sama, lalu meminta keputusan dari pemilik WPS atau engineering yang berwenang. Catat kondisi aktual dan keputusan tersebut. Jika diperlukan kualifikasi prosedur atau juru las baru, rujuk dokumen penuh dan rentang yang berlaku; abstrak [ISO 15614-1:2017](https://www.iso.org/standard/51792.html) dan [ISO 9606-1:2012](https://www.iso.org/standard/54936.html) tidak menyediakan rentang kualifikasi untuk ditebak.

## Kesimpulan

Bevel mengatur ruang dan arah akses, root face mengubah ketebalan logam di akar, dan root gap mengubah jembatan logam cair serta kebutuhan backing. Bersama-sama, geometri itu memengaruhi fusi, volume pengisian, panas kumulatif, distorsi, dan bukti inspeksi. Tidak ada satu ukuran “aman” yang dapat dipindahkan antarproyek.

Langkah berikutnya adalah mengambil drawing dan WPS yang disetujui, menandai datum serta titik ukur, mencatat kondisi fit-up aktual, kemudian meminta tinjauan teknis bila ada penyimpangan. Bila Anda perlu menilai kemampuan penyedia pekerjaan membaca dan menahan pekerjaan berdasarkan dokumen, lihat [panduan memilih bengkel las profesional dan berpengalaman](/update/tips-memilih-bengkel-las-profesional-dan-berpengalaman). Teman Bengkel-las.co.id, pegang aturan ini: jangan ubah geometri tepi untuk mengejar kemudahan pengelasan sebelum dampaknya, persetujuan, dan cara pemeriksaannya tertulis.

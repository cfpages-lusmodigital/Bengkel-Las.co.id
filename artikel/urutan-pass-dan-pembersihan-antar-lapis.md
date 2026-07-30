---
article_id: WLD-08-A03
title: "Urutan Pass dan Pembersihan Antar-Lapis pada Las Multi-Pass"
slug: "urutan-pass-dan-pembersihan-antar-lapis"
description: "Panduan mengendalikan urutan lintasan, pembersihan antar-lapis, pemeriksaan visual, dan keputusan berhenti pada las multi-pass."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-12-06"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: WLD-08
primary_intent: "Control multi-pass execution"
reader_community: "Bengkel-las.co.id"
reader_address: "Sobat Bengkel-las.co.id"
final_route: "/artikel/urutan-pass-dan-pembersihan-antar-lapis.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/51792.html"
  - "https://www.iso.org/standard/54936.html"
  - "https://www.iso.org/standard/83335.html"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018"
  - "https://www.iso.org/standard/80209.html"
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/75614.html"
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
---

# Urutan Pass dan Pembersihan Antar-Lapis pada Las Multi-Pass

Halo, Sobat Bengkel-las.co.id! Pada sambungan las multi-pass, urutan lapisan dan pembersihan antar-lapis bukan pekerjaan tambahan yang boleh dikerjakan bila sempat. Keduanya adalah bagian dari pengendalian pelaksanaan: setiap lapisan ditempatkan mengikuti prosedur yang disetujui, permukaannya diperiksa, lalu dinyatakan siap sebelum lapisan berikutnya menutupnya.

Jawaban singkatnya: jangan mengubah urutan bead, menutup permukaan yang belum dinilai, atau meneruskan pekerjaan ketika kondisi antar-lapis tidak sesuai dokumen kerja. Urutan, cara pembersihan, batas kondisi termal, penanganan awal/akhir lintasan, dan dasar penerimaan harus kembali ke WPS (*welding procedure specification*), gambar atau ketentuan proyek, serta otoritas yang ditunjuk. WPS produksi, kualifikasi prosedur, kualifikasi juru las, inspeksi, dan penerimaan sambungan adalah rekaman yang berbeda; satu di antaranya tidak otomatis menggantikan yang lain. [ISO 15614-1](https://www.iso.org/standard/51792.html), [ISO 9606-1](https://www.iso.org/standard/54936.html), dan [ISO 3834-6](https://www.iso.org/standard/83335.html) menjelaskan ruang lingkup yang terpisah itu pada abstrak resminya.

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- **Image ID:** `LOCAL-002`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi memilih jasa bengkel las](/wp-content/uploads/2020/02/memilih-jasa-bengkel-las.jpg)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `memilih jasa bengkel las` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-002]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

![Ilustrasi memilih jasa bengkel las](/wp-content/uploads/2020/02/memilih-jasa-bengkel-las.jpg)

_Ilustrasi umum dari aset lokal Bengkel-las.co.id; bukan dokumentasi proyek tertentu._

## Jawaban singkat dan salah paham utama

Kesalahan yang sering muncul ialah menganggap lintasan berikutnya akan merapikan lapisan sebelumnya. Setelah tertutup, kondisi permukaan, sambungan awal atau akhir, serta ketidaksesuaian yang tampak dapat jauh lebih sulit ditinjau atau ditelusuri. Karena itu, jeda antar-pass adalah titik keputusan: lanjut hanya setelah urutan, kondisi permukaan, dan kondisi proses diperiksa menurut dokumen yang berlaku.

Pemeriksaan visual di titik ini bukan penerimaan akhir sambungan. Ia merupakan pengendalian proses untuk mencegah masalah yang diketahui atau dicurigai tertutup oleh lapisan berikutnya. Rencana mutu tetap perlu menyebut dasar penerimaan, identitas sambungan dan pemeriksaan, metode serta cakupan pemeriksaan, pelaporan, penanganan ketidaksesuaian, dan kewenangan disposisi. [ISO 17635](https://www.iso.org/standard/85705.html) dan [ISO 5817](https://www.iso.org/standard/80209.html) membedakan kerangka pemeriksaan dan tingkat mutu dari keputusan penerimaan proyek.

## Definisi dan batas objek

Las multi-pass adalah pelaksanaan satu sambungan melalui lebih dari satu lintasan atau lapisan las. Artikel ini membahas disiplin urutan pass dan kesiapan antar-lapis pada saat produksi: siapa memeriksa, apa yang dicatat, kapan pekerjaan dilanjutkan, dan kapan harus dihentikan sementara. Artikel ini bukan izin untuk memilih urutan baru, menetapkan parameter, menentukan metode pembersihan, atau menyatakan sambungan diterima.

Urutan bead berarti susunan pass yang telah direncanakan untuk sambungan tertentu. Perubahan yang terlihat kecil dapat memengaruhi sebaran panas, akses, bentuk sambungan, dan kemampuan memeriksa pekerjaan. Maka urutan bukan keputusan spontan di lapangan. Paket fabrikasi yang terkendali perlu mempunyai dokumen dan revisi yang jelas, identitas material dan sambungan, urutan fabrikasi, titik inspeksi, dasar penerimaan, serta jalur untuk deviasi yang disetujui. [Katalog SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020) mengonfirmasi identitas standar, sedangkan aturan rinci tetap perlu diambil dari ketentuan proyek dan standar berlisensi.

`[NEEDS REVIEW: WPS yang berlaku, revisi gambar, identitas sambungan, urutan pass, batas interpass, cara pembersihan, dan titik hold proyek harus tersedia sebelum produksi diteruskan.]`

## Cara kerjanya

Alur yang aman dimulai sebelum pass pertama. Pelaksana mencocokkan sambungan, material, revisi dokumen, WPS yang disahkan, dan batas kewenangannya. Setelah satu pass selesai, pelaksana tidak langsung menutupnya. Permukaan ditangani dengan cara yang diperintahkan WPS atau instruksi proyek; kemudian kondisi yang dapat diperiksa secara visual ditinjau sesuai kriteria proyek. Bila catatan atau titik pemeriksaan wajib ada, bukti tersebut diselesaikan sebelum pass berikutnya.

Tahap berikutnya adalah memastikan kondisi antar-lapis masih berada dalam kendali prosedur. Ini dapat mencakup pengendalian preheat atau interpass bila dipersyaratkan, tetapi artikel ini tidak menetapkan angka ataupun cara pengukurannya. Kondisi peralatan dan pengendalian bahan habis pakai juga bukan detail yang boleh diasumsikan dari kebiasaan bengkel. ISO 3834-6 menempatkan pengendalian prosedur, peralatan, bahan habis pakai, dan inspeksi sebagai bagian berbeda dari persyaratan mutu pengelasan. [ISO 3834-6](https://www.iso.org/standard/83335.html)

Penanganan titik mulai, berhenti, dan penyambungan kembali mengikuti instruksi yang sama. Yang dipastikan bukan sekadar las sudah tersambung, melainkan apakah titik itu telah diperlakukan dan diperiksa sesuai prosedur sebelum dilanjutkan. Kawan Bengkel-las.co.id, bila instruksi untuk suatu kondisi tidak tersedia atau kondisi aktual tidak lagi cocok dengan WPS, tahan pekerjaan dan minta klarifikasi; jangan membuat aturan baru di dekat sambungan.

Pengendalian ini akan lebih mudah dijalankan bila peran dibedakan sejak awal. Pelaksana memastikan pekerjaan tidak meloncat dari satu pass ke pass berikutnya tanpa pemeriksaan yang diwajibkan. Pengawas atau pihak yang ditunjuk memastikan dokumen dan revisinya benar-benar tersedia di titik kerja. Pemeriksa mencatat hasil pada lingkup kewenangannya, sedangkan pihak berwenang proyek memutuskan disposisi apabila ada penyimpangan. Pembagian itu bukan birokrasi tambahan: tanpa penanggung jawab yang jelas, orang yang terburu-buru dapat menganggap dirinya berwenang mengubah urutan atau menerima hasil.

Catatan antar-lapis tidak perlu diisi dengan dugaan. Isinya harus mengikuti format proyek dan hanya merekam hal yang benar-benar dikonfirmasi, misalnya identitas sambungan, dokumen acuan, pemeriksaan yang diwajibkan, hasil, waktu atau penanggung jawab bila diminta, serta keputusan lanjut atau tahan. Rekaman tersebut berguna ketika pekerjaan harus dilanjutkan oleh orang lain atau ketika ketidaksesuaian perlu ditelusuri kemudian.

Jika rekaman itu belum dapat dibuat dengan benar, jangan menggantinya dengan ingatan lisan; tahan keputusan lanjut sampai informasi dapat dikonfirmasi.

## Faktor yang mengubah hasil

Pertama adalah identitas pekerjaan. Material, ketebalan atau diameter yang masuk lingkup prosedur, proses, posisi, filler atau bahan habis pakai, dan keberlakuan kualifikasi perlu cocok dengan pekerjaan nyata. Abstrak standar kualifikasi tidak memberikan rentang atau persyaratan uji untuk diterapkan sendiri; konfirmasi harus memakai WPS, rekaman kualifikasi, dan spesifikasi proyek yang berlaku. [ISO 15614-1](https://www.iso.org/standard/51792.html) dan [ISO 9606-1](https://www.iso.org/standard/54936.html)

Kedua adalah lingkungan pelaksanaan. Pekerjaan di lokasi dapat mengubah akses, posisi, cuaca, catu daya, penyebaran asap, paparan kebakaran, pekerjaan sekitar, dan akses inspeksi. Kemudahan transportasi bukan alasan teknis yang cukup untuk melakukan atau meneruskan las di lapangan. Pengendalian tugas harus disetujui penanggung jawab proyek dan K3 sesuai kondisi aktual. [UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970) dan [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018)

Ketiga adalah keterlacakan. Untuk pekerjaan yang memerlukannya, identitas material, batch bahan habis pakai, kondisi penyimpanan atau *conditioning*, rekaman inspeksi, serta substitusi yang disetujui perlu dapat ditautkan kembali. Jangan menyimpulkan kompatibilitas atau kondisi bahan hanya dari label umum. Bila pekerjaan merupakan bagian dari komponen [konstruksi baja](/konstruksi-baja/), tuntutan dokumen dan persetujuan desainnya ikut menentukan keputusan di titik antar-lapis.

## Contoh keputusan praktis

Gunakan tabel berikut sebagai alat bertanya, bukan sebagai daftar batas penerimaan.

| Situasi yang ditemukan | Keputusan operasional | Bukti atau pihak yang dirujuk |
| --- | --- | --- |
| Urutan pada pekerjaan tidak cocok dengan WPS atau gambar revisi | Tahan pass berikutnya; jangan mengubah urutan sendiri | WPS, gambar terbitan kerja, persetujuan deviasi |
| Permukaan antar-lapis belum bisa dinyatakan siap menurut instruksi | Jangan ditutup; selesaikan penanganan dan pemeriksaan yang dipersyaratkan | WPS atau instruksi kerja dan catatan kontrol |
| Kondisi termal atau proses tidak dapat dikonfirmasi | Hentikan sementara dan eskalasi | Ketentuan interpass atau preheat proyek dan personel berwenang |
| Ada indikasi ketidaksesuaian atau hasil pemeriksaan meragukan | Isolasi keputusan lanjut sampai disposisi tersedia | Rencana mutu, laporan pemeriksaan, otoritas disposisi |
| Area kerja berubah karena cuaca, akses, atau pekerjaan sekitar | Nilai ulang kontrol sebelum mulai lagi | Penanggung jawab pekerjaan dan K3 lokasi |

Contoh ini sengaja tidak memberi angka atau teknik pembersihan. Angka yang benar untuk satu sambungan dapat salah untuk sambungan lain bila material, prosedur, atau persyaratannya berbeda. Teman Bengkel-las.co.id, disiplin terpenting di sini ialah membuat keputusan dapat ditelusuri: siapa melihat apa, terhadap dokumen revisi mana, lalu siapa mengizinkan pekerjaan diteruskan.

## Kesalahan umum dan cara memeriksanya

Shortcut yang realistis berbunyi, “Nanti lapisan atas menutup bekasnya, jadi lanjut dulu agar tidak dingin.” Itu dapat gagal karena lapisan atas tidak menggantikan pemeriksaan, pembersihan sesuai instruksi, atau persetujuan atas kondisi yang menyimpang. Kecepatan yang tidak dapat dibuktikan kembali sering berpindah menjadi pekerjaan ulang, sengketa kualitas, atau risiko keselamatan.

Sebelum pass berikutnya, ajukan lima pertanyaan sederhana: apakah sambungan dan revisi dokumen sudah cocok; apakah urutannya masih sama dengan prosedur; apakah penanganan antar-lapis telah mengikuti instruksi; apakah kondisi yang perlu ditinjau telah dicatat atau dilepas pada titik pemeriksaan; dan apakah ada perubahan lingkungan atau ketidaksesuaian yang perlu dievaluasi? Jika salah satu jawaban tidak jelas, itu alasan untuk berhenti sementara.

Jangan menganggap sertifikat personel sebagai penerimaan sambungan. Kualifikasi personel, kompetensi pemeriksa, status peralatan, metode pemeriksaan, dan penerimaan produk mempunyai ruang lingkup masing-masing. Bila pengujian tak merusak diperlukan, cakupan dan kompetensi personel harus ditentukan oleh rencana serta prosedur yang berlaku, bukan dipilih setelah hasilnya dipertanyakan. [ISO 9712](https://www.iso.org/standard/75614.html)

## Penutup: aturan kerja sebelum menutup lapisan

Urutan pass dan pembersihan antar-lapis pada las multi-pass dikendalikan dengan satu aturan kerja: jangan tutup lapisan sampai urutan, kesiapan permukaan, kondisi proses, dan keputusan pemeriksaannya sesuai WPS serta dokumen proyek yang berlaku. Sobat Bengkel-las.co.id, langkah berikutnya adalah meminta WPS revisi aktif, identitas sambungan, instruksi antar-lapis, dan jalur eskalasi sebelum pekerjaan dimulai atau diteruskan.

Saat memilih pihak yang akan menangani pekerjaan, tanyakan bagaimana mereka mengendalikan dokumen, revisi, dan keputusan ketika kondisi berubah, bukan hanya apakah mereka dapat segera mulai. Panduan [memilih bengkel las yang profesional dan berpengalaman](/update/tips-memilih-bengkel-las-profesional-dan-berpengalaman/) dapat membantu menyusun pertanyaan awal itu. Untuk setiap kondisi yang tidak dicakup dokumen, berhenti dan dapatkan persetujuan kompeten; kebiasaan lapangan bukan pengganti WPS atau penerimaan proyek.

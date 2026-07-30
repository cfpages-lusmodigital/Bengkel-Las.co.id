---
article_id: WLD-11-A05
title: "Datum dan Toleransi pada Part CNC untuk Rakitan Las"
slug: "datum-dan-toleransi-part-cnc"
description: "Panduan menetapkan datum fungsional, lokasi lubang dan slot, akumulasi toleransi, fixture, distorsi las, urutan machining, dan inspeksi pada rakitan CNC-las."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2026-03-01"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: WLD-11
primary_intent: "Coordinate precision parts with welding"
reader_community: "Bengkel-las.co.id"
reader_address: "Sobat Bengkel-las.co.id"
final_route: "/artikel/datum-dan-toleransi-part-cnc.html"
technical_review: required
sources:
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://www.iso.org/standard/83335.html"
  - "https://www.iso.org/standard/51792.html"
  - "https://www.iso.org/standard/54936.html"
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/75614.html"
---

# Datum dan Toleransi pada Part CNC untuk Rakitan Las

<!-- BEGIN MANAGED IMAGE PLAN
Image ID: LOCAL-001
Source type: local
Placement: setelah pembuka, sebelum H2 pertama
**Exact Markdown to insert:** `![Ilustrasi bengkel las](/wp-content/uploads/2019/10/bengkel-las.png)`
Caption/credit: Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
Selection basis: filename/source metadata; piksel tidak diperiksa.
Hard boundary: jangan mengarang detail visual, kepemilikan, lokasi, orang, merek, kondisi, performa, atau hasil.
Substitution rule: jika URL tidak tersedia, gunakan [NEEDS IMAGE REVIEW: LOCAL-001].
END MANAGED IMAGE PLAN -->

Halo, Sobat Bengkel-las.co.id!

Pada rakitan yang menggabungkan part CNC dan rangka las, datum bukan sekadar simbol di gambar dan toleransi bukan angka yang ditempel merata pada semua ukuran. Keduanya harus menjawab satu pertanyaan: permukaan atau fitur mana yang benar-benar menjadi acuan saat part dipasang, dilas, lalu diperiksa? Jika acuan itu keliru, lubang bisa tepat terhadap part CNC tetapi bergeser terhadap rangka setelah pengelasan.

Jawaban singkatnya: tetapkan datum dari fungsi antarmuka, beri toleransi lokasi lubang atau slot terhadap datum tersebut, hitung akumulasi variasi antarkomponen, lalu rancang fixture dan urutan las untuk mengendalikan perubahan. Keputusan machining sebelum atau sesudah las mengikuti fitur mana yang harus presisi pada kondisi akhir. Nilai toleransi final tetap memerlukan gambar rilis, material, beban, proses, dan acceptance basis proyek; tanpa itu, artikel ini tidak menyetujui angka tertentu.

![Ilustrasi bengkel las](/wp-content/uploads/2019/10/bengkel-las.png)

Ilustrasi umum dari aset lokal Bengkel-las.co.id; bukan dokumentasi proyek tertentu.

## Definisi dan batas objek

Datum adalah referensi teoritis untuk menempatkan dan mengorientasikan benda. Dalam praktik, datum primer biasanya menahan enam derajat kebebasan bersama datum sekunder dan tersier. Yang penting bukan urutan simbolnya saja, melainkan fungsi: alas yang benar-benar duduk, sisi yang menentukan arah, atau sumbu yang menentukan putaran. Datum fungsional dapat berbeda dari tepi terdekat yang paling mudah diukur.

Toleransi menyatakan rentang variasi yang masih boleh diterima untuk ukuran, bentuk, orientasi, atau lokasi. Toleransi ukuran lubang tidak otomatis mengendalikan posisi pusat lubang. Untuk sambungan baut, ukuran lubang, jarak antarlubang, posisi pola, tegak lurus, dan kebebasan akses baut perlu dibaca sebagai satu sistem. Slot memberi kelonggaran pada satu arah, tetapi arah kelonggaran itu harus sesuai gerak pemasangan, bukan dipakai untuk menutupi datum yang salah.

Ruang lingkup artikel ini adalah koordinasi part presisi dengan rakitan las. Ia tidak menggantikan desain struktur, analisis beban, gambar detail, WPS (welding procedure specification), atau persetujuan insinyur. Paket fabrikasi yang terkendali lazimnya mengikat dokumen dan revisi, fungsi, dimensi dan datum, identitas material serta sambungan, toleransi, urutan fabrikasi, inspeksi, hold point, acceptance basis, dan penyimpangan yang disetujui; lihat ringkasan resmi [SNI 1729:2020 di BSN](https://pesta.bsn.go.id/produk/detail/12882-sni17292020) dan [ISO 3834-6:2024](https://www.iso.org/standard/83335.html). Jika gambar atau acceptance basis belum ada, tandai **[NEEDS DRAWING DAN ACCEPTANCE BASIS: jangan menetapkan toleransi final]**.

## Cara kerjanya

Mulailah dari antarmuka akhir. Tanyakan: permukaan mana yang menempel, lubang mana yang menerima baut atau pin, dan fitur mana yang harus sejajar dengan komponen lain? Jadikan fitur itu datum utama atau turunan yang jelas. Pada gambar, beri koordinat lubang dan slot terhadap datum yang akan dipakai saat setting dan inspeksi, bukan terhadap tepi potongan yang mungkin berubah akibat las. Jika perlu memeriksa kemampuan pemesinan, gunakan rujukan [layanan CNC milling](/cnc-milling) sebagai langkah berikutnya, bukan sebagai pengganti gambar teknik.

Kemudian pisahkan tiga lapis keputusan berikut.

1. **Fitur manufaktur.** Mesin CNC menghasilkan ukuran, posisi, dan permukaan dengan acuan setup tertentu. Catat asal program, orientasi benda, dan fitur yang dipakai untuk setup berikutnya.
2. **Fitur rakitan.** Fixture (alat penahan) harus menempatkan part pada datum fungsional, memberi akses las, dan mencegah part bergeser saat tack maupun las penuh. Clamp tidak boleh memaksa benda ke posisi yang hanya terlihat benar sebelum dilepas.
3. **Fitur inspeksi.** Pengukuran setelah las harus mengulang referensi yang sama. Mengganti datum pemeriksaan dengan sisi luar yang mudah disentuh dapat menyembunyikan error posisi antarmuka.

Untuk pola lubang, buat tabel sederhana sebelum produksi:

| Elemen | Acuan | Variasi yang dikendalikan | Konsekuensi jika melewati batas |
| --- | --- | --- | --- |
| Lubang pin | datum primer dan sumbu sekunder | lokasi pusat dan tegak lurus | pin macet atau tidak dapat masuk |
| Pola baut | dua datum planar | jarak antarlubang dan orientasi pola | baut harus dipaksa saat rakit |
| Slot | datum arah gerak | posisi sepanjang dan melintang slot | kelonggaran tidak berada di arah pemasangan |
| Permukaan duduk | datum primer | kerataan dan kontak | celah, rocking, atau beban lokal |

Toleransi stack-up (akumulasi toleransi) adalah variasi gabungan dari setiap mata rantai: ukuran part CNC, posisi fitur pada rangka, celah fit-up, dan perubahan setelah las. Untuk pemeriksaan awal, pendekatan batas terburuk menjumlahkan deviasi yang mungkin searah; pendekatan statistik hanya layak jika distribusi proses dan asumsi produksinya memang dibuktikan. Jangan mengurangi angka toleransi hanya agar hasil hitungan terlihat muat.

## Faktor yang mengubah hasil

Material, ketebalan, panjang jalur las, pengekangan fixture, urutan pengelasan, dan panas masukan memengaruhi distorsi. Pelat dapat melengkung, sudut berubah, dan lubang di dekat sambungan dapat kehilangan posisi relatif setelah pendinginan. Karena tidak ada data proyek di sini, jangan mengubah pengaruh tersebut menjadi allowance numerik. Rencanakan kompensasi melalui mock-up, kupon, atau data proses yang disetujui; sisakan machining stock hanya bila gambar dan proses mengizinkannya.

Keputusan **machining sebelum las** cocok bila part harus diposisikan lewat lubang atau permukaan yang dapat dilindungi dari panas dan tidak berubah fungsi setelah pengelasan. Keuntungannya adalah akses mesin mudah, tetapi fixture dan urutan las harus menjaga fitur itu. **Machining sesudah las** lebih aman untuk datum akhir yang berisiko melengkung, misalnya permukaan duduk atau bore yang harus koaksial. Konsekuensinya, rakitan harus dapat dijepit dan diakses mesin tanpa merusak sambungan, serta allowance material harus tersedia.

Bicarakan juga kondisi lapangan. Memindahkan pekerjaan ke site dapat mengubah akses, posisi, pengangkatan, cuaca, listrik, ventilasi, bahaya kebakaran, lalu lintas, dan akses inspeksi. Kawan Bengkel-las.co.id, jangan menjadikan transportasi sulit sebagai alasan otomatis untuk mengelas di tempat; otoritas K3 dan penanggung jawab proyek harus menilai kontrol tugas yang aktual.

Material dan consumable perlu identitas yang dapat ditelusuri. ISO 3834-6 menguraikan pentingnya rekaman material, sambungan, proses, dan inspeksi, tetapi abstraknya tidak memberi nilai toleransi atau parameter las untuk proyek tertentu. Simpan nomor revisi gambar, lot material atau filler bila diwajibkan spesifikasi, setup fixture, urutan las, dan setiap deviasi yang disetujui.

## Contoh keputusan praktis

Bayangkan bracket CNC memiliki dua lubang untuk dipasang ke rangka las dan satu permukaan duduk. Jika kedua lubang mengunci posisi, datum utama sebaiknya mengikuti permukaan duduk yang benar-benar menempel; datum berikutnya mengarahkan pola lubang. Slot dapat dipakai pada sisi yang memang membutuhkan kompensasi satu arah, bukan pada lubang referensi yang menentukan pusat rakitan.

Sebelum memilih proses, jawab pertanyaan ini:

- Apakah lubang dipakai untuk pin, baut bebas, atau hanya akses? Fungsinya menentukan kebutuhan lokasi.
- Apakah permukaan duduk masih akan dimesin? Jika ya, sisakan allowance yang disetujui dan ukur setelah proses akhir.
- Apakah fixture menahan datum fungsional atau hanya tepi luar? Jika hanya tepi, risiko stack-up meningkat.
- Apakah pengelasan mengelilingi fitur presisi? Jika ya, pertimbangkan urutan, pelindung panas, atau machining akhir.
- Dokumen mana yang menjadi acceptance basis: gambar, spesifikasi proyek, atau standar yang dirujuk? Tanpa jawaban ini, hasil ukur belum dapat disebut lulus.

Untuk pola baut, ukur posisi setiap pusat terhadap datum dan juga jarak antarpusat. Dua ukuran yang masing-masing tampak baik masih dapat membentuk pola yang gagal dirakit bila error arahnya sama. Untuk slot, ukur panjang, lebar, dan garis tengah; periksa apakah kelonggaran mengarah ke jalur pemasangan. Catat kondisi ukur—sebelum tack, setelah las, setelah pelepasan fixture, dan setelah machining akhir—agar perubahan dapat ditelusuri. Bila bentuk awal harus dipotong sebelum CNC, baca [penjelasan proses CNC cutter](/cnc-cutter) untuk memahami bahwa metode pemotongan tetap harus mengikuti datum dan revisi gambar.

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah menyamakan “ukuran lubang benar” dengan “part pasti terpasang”. Periksa lokasi pusat dan orientasi terhadap datum fungsional. Kesalahan kedua adalah memakai toleransi umum pada semua fitur tanpa membedakan fitur kritis dan nonkritis. Kelompokkan fitur menurut fungsi, lalu minta persetujuan desain untuk nilai yang berbeda.

Kesalahan ketiga adalah memeriksa rakitan dengan datum yang berbeda dari gambar. Buat lembar inspeksi yang menyalin simbol datum, titik ukur, alat ukur, status kalibrasi atau verifikasi, dan revisi dokumen. ISO 17635 menekankan bahwa metode, cakupan, teknik, personel, peralatan, kondisi permukaan, pelaporan, dan acceptance basis adalah bukti yang terpisah; [abstrak ISO 17635:2025](https://www.iso.org/standard/85705.html) juga mengingatkan agar tingkat penerimaan NDT tidak diterjemahkan satu-banding-satu dari tingkat mutu las. Kompetensi personel NDT sendiri mempunyai ruang lingkup dan validitas; lihat [ISO 9712:2021](https://www.iso.org/standard/75614.html).

Kesalahan keempat adalah menganggap clamp telah menghapus distorsi. Ukur setelah fixture dilepas. Jika hasil berubah, jangan langsung menggerinda atau memaksa baut. Tahan part, dokumentasikan kondisi, lalu minta keputusan disposition dari pihak yang berwenang. Untuk kualifikasi las, bedakan WPS produksi, kualifikasi prosedur, dan kualifikasi juru las; abstrak [ISO 15614-1](https://www.iso.org/standard/51792.html) dan [ISO 9606-1](https://www.iso.org/standard/54936.html) tidak menyediakan rentang kualifikasi atau acceptance value yang boleh ditebak.

## Jalan pintas yang perlu ditolak

Jalan pintas yang sering menggoda adalah membuat semua lubang sedikit lebih besar atau memanjangkan semua slot agar rakitan “pasti masuk”. Cara itu bisa mengurangi waktu fit-up, tetapi dapat memindahkan beban, menghilangkan fungsi pin, mengganggu washer, atau menyamarkan datum yang keliru. Alternatif yang lebih dapat dipertanggungjawabkan adalah menetapkan fungsi tiap fitur, menghitung stack-up, mengendalikan fixture, dan meminta perubahan gambar secara resmi bila kelonggaran memang diperlukan.

Teman Bengkel-las.co.id, “bisa dirakit” juga bukan sinonim “memenuhi desain”. Pengukuran, rekaman proses, dan persetujuan penyimpangan harus menyertai keputusan. Jangan memakai sertifikat personel, label standar, atau laporan NDT sebagai bukti tunggal bahwa seluruh rakitan telah memenuhi fungsi; setiap dokumen memiliki ruang lingkupnya sendiri.

## Kesimpulan dan langkah berikutnya

Datum dan toleransi pada part CNC untuk rakitan las harus dibangun dari fungsi antarmuka: pilih acuan yang benar-benar menempatkan part, kendalikan lokasi lubang atau slot terhadap acuan itu, hitung akumulasi variasi, lalu selaraskan fixture, urutan las, allowance, dan inspeksi. Pilihan machining sebelum atau sesudah las mengikuti fitur mana yang harus presisi pada kondisi akhir, bukan kebiasaan bengkel.

Langkah berikutnya adalah mengeluarkan satu paket kerja yang memuat gambar revisi, datum dan toleransi, material serta sambungan, urutan proses, fixture, titik inspeksi, acceptance basis, dan jalur persetujuan deviasi. Minta review teknis sebelum angka toleransi disahkan. Aturan operasinya sederhana: bila datum fungsional, kondisi akhir, atau dasar penerimaan belum jelas, hentikan persetujuan ukuran dan tandai **[NEEDS REVIEW PROYEK/INSINYUR]**—jangan menutup celah informasi dengan tebakan.

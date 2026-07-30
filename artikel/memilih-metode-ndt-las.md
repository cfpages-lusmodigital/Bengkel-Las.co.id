---
article_id: WLD-09-A03
title: "Memilih Metode NDT Las: VT, PT, MT, UT, atau RT"
slug: "memilih-metode-ndt-las"
description: "Panduan membandingkan jenis indikasi, material, geometri, akses, waktu, permukaan, personel, bahaya, dan pelaporan NDT las"
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-12-30"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: WLD-09
primary_intent: "Select an inspection method family"
reader_community: "Bengkel-las.co.id"
reader_address: "Kawan Bengkel-las.co.id"
final_route: "/artikel/memilih-metode-ndt-las.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/75614.html"
  - "https://www.iso.org/standard/80209.html"
  - "https://www.iso.org/standard/83335.html"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018"
---

# Memilih Metode NDT Las: VT, PT, MT, UT, atau RT

## Jawaban singkat dan salah paham utama

Halo, Kawan Bengkel-las.co.id! Pilih metode NDT (non-destructive testing atau pengujian tak merusak) berdasarkan indikasi yang dicari, material, bentuk sambungan, akses, kondisi permukaan, tahap pekerjaan, dan bukti yang harus dilaporkan. VT (visual testing) biasanya menjadi pemeriksaan awal dan penutup. PT (penetrant testing) cocok untuk indikasi yang terbuka ke permukaan pada permukaan tak berpori. MT (magnetic particle testing) ditujukan untuk bahan feromagnetik, terutama indikasi di permukaan dan dekat permukaan. UT (ultrasonic testing) dan RT (radiographic testing) dipertimbangkan ketika pertanyaan Anda menyangkut bagian dalam volume las, dengan batasan geometri, akses, keselamatan, dan kemampuan personel masing-masing.

Tidak ada metode yang otomatis paling lengkap. Hasil satu metode adalah bukti untuk pertanyaan tertentu, bukan keputusan lulus-gagal untuk semua kondisi. Kerangka ISO 17635 menempatkan pemilihan metode, cakupan, teknik, personel, peralatan, kondisi permukaan, pelaporan, dan dasar penerimaan sebagai hal yang harus dibedakan; abstraknya juga mengingatkan bahwa tingkat penerimaan NDT tidak diterjemahkan satu banding satu dari tingkat mutu ISO 5817 ([ISO 17635:2025](https://www.iso.org/standard/85705.html)). Jadi, sebelum memesan pemeriksaan, tetapkan dulu indikasi apa yang hendak dicari dan siapa yang berwenang menetapkan penerimaannya.

Jika gambar kerja, spesifikasi, tahap pengelasan, atau kondisi lapangan belum tersedia, kesimpulan di bawah baru berupa pemilihan keluarga metode. Tandai berkas Anda dengan `[NEEDS PROJECT REVIEW: joint, material, access, examination extent, acceptance basis, qualified personnel, and equipment status]` sampai penanggung jawab teknis mengesahkannya.

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

Ilustrasi umum dari aset lokal Bengkel-las.co.id; bukan dokumentasi proyek tertentu.

## Definisi dan batas objek

NDT mencari indikasi tanpa merusak benda uji, tetapi istilah itu tidak menjanjikan bahwa seluruh volume dan seluruh jenis diskontinuitas terjawab. Dalam artikel ini, “memilih metode” berarti menyusun pemeriksaan yang masuk akal untuk sebuah sambungan las: apa target indikasinya, bagian mana yang dapat dicapai, kapan permukaan siap, bukti apa yang harus ditinggalkan, dan siapa yang menilai hasilnya. Artikel ini tidak memilih tingkat penerimaan (acceptance level), tidak menetapkan teknik rinci, dan tidak menggantikan persetujuan personel berkualifikasi atau prosedur proyek.

Ringkasnya, keluarga metode dibedakan seperti berikut.

| Metode | Pertanyaan yang paling cocok dijawab | Batas yang harus diperiksa |
| --- | --- | --- |
| VT | Apakah permukaan, bentuk, ukuran, dan akses sambungan dapat diamati? | Tidak menjawab indikasi yang sepenuhnya tersembunyi; pencahayaan, kebersihan, sudut pandang, dan alat bantu harus memadai. |
| PT | Adakah indikasi yang terbuka ke permukaan pada bahan tak berpori? | Permukaan harus dapat dibersihkan dan tidak menyerap bahan uji; lapisan, kekasaran, atau kontaminasi dapat mengganggu. |
| MT | Adakah indikasi permukaan/dekat permukaan pada bahan feromagnetik? | Tidak semua material merespons magnetisasi; arah magnetisasi, bentuk, dan akses menentukan keterlihatan indikasi. |
| UT | Adakah reflektor di dalam material yang dapat dijangkau gelombang ultrasonik? | Ketebalan, bentuk, orientasi, permukaan, akses probe, dan kondisi pengkopel memengaruhi cakupan serta interpretasi. |
| RT | Adakah perbedaan penyerapan radiasi yang terekam melalui susunan sumber dan detektor? | Akses di kedua sisi yang diperlukan, pengaturan area aman, geometri, kualitas citra, dan pengendalian radiasi harus disetujui kompeten. |

Deskripsi tabel adalah peta pertanyaan, bukan prosedur pelaksanaan atau nilai penerimaan. ISO 9712 membahas kompetensi dan sertifikasi personel NDT; itu berbeda dari kualifikasi juru las, persetujuan prosedur, dan otoritas penerimaan hasil ([ISO 9712:2021](https://www.iso.org/standard/75614.html)).

## Cara kerjanya

Mulailah dari objek, bukan dari alat yang kebetulan tersedia. Identifikasi nomor sambungan, material, ketebalan atau rentang dimensi pada dokumen, jenis dan posisi las, sisi yang dapat diakses, lapisan permukaan, serta tahap pekerjaan. Lalu tulis kalimat pertanyaan, misalnya “apakah ada indikasi yang terbuka di permukaan?” atau “apakah perlu bukti tentang bagian dalam volume?” Kalimat itu membantu mencegah pemesanan RT hanya karena terdengar lebih canggih.

Urutan yang lazim adalah VT sebelum pengelasan untuk penyetelan awal (fit-up) dan kebersihan, VT selama tahapan yang ditentukan, lalu VT sesudah selesai. PT atau MT dipilih setelah permukaan dan akses memungkinkan pencarian indikasi yang menjadi targetnya. UT atau RT ditempatkan ketika geometri dan tahap kerja sudah memungkinkan pemeriksaan volume. Jadwal ini harus ditulis dalam rencana inspeksi; jangan menganggap pemeriksaan akhir dapat menggantikan bukti pada tahap sebelumnya.

Setiap metode menghasilkan paket bukti. Catat identitas sambungan dan area, metode serta teknik yang disetujui, cakupan pemeriksaan, kondisi permukaan dan lingkungan, identitas alat serta status kalibrasi/verifikasi yang dipersyaratkan, personel dan ruang lingkup kualifikasinya, indikasi atau hasil yang ditemukan, dan pihak yang berwenang memutuskan tindak lanjut. ISO 17635 memberi kerangka pemisahan unsur-unsur tersebut, sementara ISO 3834-6 menekankan informasi terdokumentasi yang diperlukan agar proses pengelasan dapat ditelusuri ([ISO 3834-6:2024](https://www.iso.org/standard/83335.html)).

## Faktor yang mengubah hasil

**Material.** PT memerlukan permukaan tak berpori; MT memerlukan respons feromagnetik; UT dan RT tidak dapat diperlakukan sama pada semua kombinasi material dan ketebalan. Minta identitas material serta kondisi permukaannya, bukan hanya nama dagang. Bila objeknya teralis, Anda dapat mulai dari [panduan mengenali bahan teralis jendela las](/update/3-bahan-teralis-jendela-las-yang-umum-di-pasaran) sebelum menanyakan metode. Bila ada lapisan pelindung (coating), jelaskan apakah pemeriksaan dilakukan sebelum pelapisan, sesudah pembersihan, atau pada area yang dibuka. Jangan menganggap bahan pengisi atau lapisan otomatis memiliki perilaku yang sama dengan logam induk.

**Geometri dan akses.** Sudut, radius, perubahan ketebalan, penyangga belakang (backing), sambungan tumpul atau sudut, serta sisi yang tertutup menentukan jalur pandang, posisi magnetisasi, arah probe, atau susunan sumber-detektor. Akses satu sisi mungkin cukup untuk satu teknik tetapi tidak untuk teknik lain. Buat sketsa sederhana dan tandai area yang tidak dapat disentuh; area tanpa akses adalah batas cakupan yang harus muncul di laporan, bukan dihapus dari cerita.

**Waktu dan kondisi permukaan.** Hasil dapat berubah jika permukaan masih berminyak, berkarat, basah, tertutup terak (slag), terlalu kasar, atau baru dicat. Tentukan titik berhenti pekerjaan, metode pembersihan yang diizinkan, dan siapa yang memverifikasi kesiapan. Pemeriksaan yang dilakukan terlalu cepat, sebelum bentuk las stabil atau sebelum perlakuan yang dipersyaratkan selesai, dapat menjawab pertanyaan yang berbeda dari yang dimaksud proyek.

**Personel dan peralatan.** Sertifikat personel tidak mengesahkan semua metode atau semua sektor secara otomatis; ruang lingkup, keberlakuan, dan pengawasan harus dicocokkan dengan tugas. Identitas alat, pemeriksaan fungsi, dan status kalibrasi/verifikasi juga merupakan bukti terpisah. Kawan Bengkel-las.co.id, minta contoh format laporan dan daftar alat sebelum hari pemeriksaan agar kekurangan administratif tidak baru terlihat saat keputusan harus dibuat.

**Bahaya dan lokasi.** RT membawa pertimbangan pengendalian radiasi; pekerjaan lapangan dapat menambah lalu lintas, penghuni, cuaca, sumber listrik, ruang terbatas, bahan mudah terbakar, asap, dan akses evakuasi. Untuk kegiatan pengelasan dan inspeksi, rujuk pengendalian K3 yang berlaku di Indonesia serta penilaian risiko lokasi—UU No. 1 Tahun 1970 dan Permenaker No. 5 Tahun 2018 adalah titik rujuk regulasi, bukan pengganti izin atau prosedur tugas spesifik ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970), [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018)). Jangan menyalin jarak, durasi penjagaan, atau persyaratan dari yurisdiksi lain.

**Dasar penerimaan dan pelaporan.** Tingkat mutu pengerjaan, teknik NDT, evaluasi indikasi, dan keputusan rekayasa (engineering) adalah lapisan berbeda. ISO 5817 dapat menjadi salah satu rujukan tingkat mutu las, tetapi abstrak ISO 17635 menegaskan tidak ada terjemahan satu banding satu ke tingkat penerimaan NDT ([ISO 5817:2023](https://www.iso.org/standard/80209.html), [ISO 17635:2025](https://www.iso.org/standard/85705.html)). Karena itu, mintalah dokumen yang menyebut kode atau spesifikasi yang berlaku, batas cakupan, dan otoritas disposisi. Tanpa itu, laporan hanya memberi temuan, bukan vonis.

## Contoh keputusan praktis

Bayangkan tiga pertanyaan bersyarat berikut; ini bukan klaim tentang proyek tertentu.

1. **Sambungan mudah dilihat, dan pertanyaan pertama adalah kondisi permukaan.** Mulai dari VT. Jika ada dugaan indikasi terbuka dan material serta permukaannya memenuhi syarat, pertimbangkan PT atau MT sesuai jenis material. Jangan menyebut hasil “aman” hanya karena VT tidak menemukan sesuatu; catat area yang benar-benar terlihat dan keterbatasannya.
2. **Sambungan berbahan feromagnetik dengan kekhawatiran indikasi dekat permukaan.** MT mungkin lebih relevan daripada PT bila target dan kondisi permukaan mendukung. Periksa arah magnetisasi dan area yang tidak dapat dijangkau, kemudian tentukan apakah perlu metode pelengkap.
3. **Keputusan memerlukan informasi dari bagian dalam volume.** Bandingkan UT dan RT berdasarkan ketebalan, bentuk, akses, orientasi indikasi yang dicari, kemampuan personel, pengendalian bahaya, dan kualitas rekaman yang diminta. Jika akses atau pengendalian radiasi tidak dapat dipenuhi, jangan memaksakan RT; minta penanggung jawab teknis menetapkan kombinasi atau alternatif yang dapat dipertanggungjawabkan.

Gunakan lembar keputusan singkat: target indikasi, material, area dan sisi yang dapat diakses, kondisi permukaan, waktu pemeriksaan, metode kandidat, bahaya, personel, alat, cakupan, serta dokumen penerimaan. Setiap jawaban “belum tahu” menjadi pertanyaan terbuka untuk penanggung jawab teknis, bukan asumsi.

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah menganggap “metode paling mahal” atau RT selalu paling lengkap. Periksa kembali pertanyaan inspeksi dan batas akses; metode yang tidak sensitif terhadap target atau tidak menghasilkan rekaman yang dapat dibaca tidak menjadi lebih baik karena biayanya tinggi.

Kesalahan kedua adalah menerima sertifikat personel tanpa melihat ruang lingkup, keberlakuan, atau rekaman alat. Minta identitas personel, metode, sektor atau objek yang dicakup, serta bukti verifikasi alat yang relevan.

Kesalahan ketiga adalah mengecat, membersihkan, atau memindahkan benda sebelum kesepakatan tentang kondisi pemeriksaan. Simpan foto atau catatan kondisi awal bila memang diizinkan proyek, sepakati area yang boleh dibuka, dan pastikan pemulihan permukaan masuk tanggung jawab yang jelas.

Kesalahan keempat adalah menulis “lulus” pada laporan yang hanya memuat indikasi. Pastikan laporan memisahkan temuan, evaluasi terhadap kriteria yang disetujui, keputusan disposisi, perbaikan bila ada, dan pemeriksaan ulang. Untuk memilih penyedia dan memeriksa kelengkapan dokumen awal, Anda dapat mengikuti panduan [memilih bengkel las profesional dan berpengalaman](/update/tips-memilih-bengkel-las-profesional-dan-berpengalaman).

## Jalan pintas yang perlu diuji

Jalan pintas yang sering muncul: “Lakukan VT saja dulu; kalau tampak bagus berarti tidak perlu metode lain.” VT memang berguna sebagai pintu masuk dan dapat menemukan masalah permukaan yang kasatmata, tetapi ia tidak menjawab indikasi yang tertutup atau seluruh pertanyaan volume. Sebaliknya, memesan semua metode sekaligus juga tidak otomatis memperbaiki keputusan bila target, akses, personel, bahaya, dan dasar penerimaan belum jelas. Jalan yang lebih aman adalah menulis pertanyaan inspeksi, memilih metode yang menjawabnya, mendokumentasikan keterbatasan, lalu meminta persetujuan personel berkualifikasi.

## Kesimpulan

VT dipakai untuk keterlihatan permukaan dan bentuk; PT untuk indikasi terbuka pada permukaan tak berpori; MT untuk indikasi permukaan/dekat permukaan pada bahan feromagnetik; UT dan RT dipertimbangkan untuk pertanyaan volume dengan batas geometri, akses, rekaman, dan keselamatan yang berbeda. Pilihan final harus mengikuti material, sambungan, tahap kerja, kondisi permukaan, cakupan, personel, alat, bahaya, serta dasar penerimaan proyek—bukan nama metode semata.

Teman Bengkel-las.co.id, sebelum menjadwalkan pemeriksaan, siapkan gambar dan identitas sambungan, data material, sketsa akses, kondisi permukaan, target indikasi, rencana cakupan, format laporan, serta dokumen dasar penerimaan (acceptance basis). Minta penanggung jawab teknis menutup marker `[NEEDS PROJECT REVIEW: joint, material, access, examination extent, acceptance basis, qualified personnel, and equipment status]`. Aturan operasionalnya sederhana: bila pertanyaan, akses, atau otoritas penerimaan belum jelas, tahan keputusan lulus-gagal dan selesaikan tinjauan kompeten terlebih dahulu.

---
article_id: WLD-03-A04
title: "Ukuran Las Fillet, Throat, dan Panjang Efektif: Konsep untuk Pembaca Gambar"
slug: "ukuran-las-fillet-dan-throat"
description: "Panduan membaca kaki las, throat, panjang efektif, dan las putus-putus pada gambar tanpa menebak ukuran sambungan."
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-08-08"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: WLD-03
primary_intent: "Understand weld-size notation"
reader_community: "Bengkel-las.co.id"
reader_address: "Kawan Bengkel-las.co.id"
final_route: "/artikel/ukuran-las-fillet-dan-throat.html"
technical_review: required
sources:
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://www.iso.org/standard/83335.html"
  - "https://www.iso.org/standard/51792.html"
  - "https://www.iso.org/standard/85705.html"
---

# Ukuran Las Fillet, Throat, dan Panjang Efektif: Konsep untuk Pembaca Gambar

Halo, Kawan Bengkel-las.co.id! Saat melihat simbol las fillet pada gambar, angka di dekat simbol sering dianggap sebagai perintah sederhana: buat las sebesar angka itu, lalu pekerjaan selesai. Padahal angka tersebut baru bermakna jika kita tahu bagian mana yang sedang ditunjuk, satuan apa yang dipakai, dan apakah gambar meminta las menerus atau las putus-putus.

Jawaban singkatnya: **leg** adalah kaki las yang dibaca dari akar sambungan ke tepi las pada masing-masing bidang, **throat** adalah jarak efektif dari akar menuju bidang kerja las, sedangkan **panjang efektif** adalah bagian panjang las yang benar-benar dihitung menurut detail yang berlaku. Ketiganya membantu estimator dan inspector membaca maksud gambar; ketiganya bukan izin untuk memilih ukuran las bagi sambungan nyata. Ukuran akhir tetap harus berasal dari gambar terbitan, spesifikasi, dan keputusan perancang struktur atau penanggung jawab proyek.

[NEEDS IMAGE REVIEW: LOCAL-002]

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

## Membaca ukuran tanpa melompati keputusan desain

Las fillet lazim dipakai ketika dua bidang bertemu membentuk sudut. Bayangkan pelat menempel pada sisi profil; penampang endapan las di sudut itu kira-kira membentuk segitiga. Gambar kerja dapat menyebut ukuran kaki, throat, atau panjang, tetapi pembaca tidak boleh menukar satu istilah dengan istilah lain hanya karena semuanya tampak sebagai angka di dekat simbol.

Ukuran kaki las menjawab pertanyaan, “seberapa jauh las menjangkau pada permukaan yang disambung?” Pada fillet yang kedua sisinya sama, dua kaki dapat tampak setara. Namun bentuk sambungan, persiapan tepi, posisi, dan detail gambar tetap dapat membuat cara pemeriksaannya berbeda. Karena itu, jangan mengambil mistar lalu menyimpulkan bahwa setiap ukuran yang terlihat sama sudah memenuhi maksud desain.

Throat, atau tebal efektif las, menjawab pertanyaan yang berbeda: seberapa jauh penampang las bekerja dari akar sambungan menuju bidang yang relevan. Pada gambar, istilah ini penting karena sebuah angka untuk kaki las tidak otomatis dapat diperlakukan sebagai angka throat. Hubungan keduanya tergantung geometri yang direncanakan, sehingga artikel ini sengaja tidak memberikan rumus atau angka pengganti detail proyek.

Panjang efektif juga bukan sekadar panjang garis las yang terlihat oleh mata. Gambar dan spesifikasi perlu dibaca bersama untuk mengetahui bagian mana yang dimaksud, dari mana pengukuran dimulai dan berakhir, serta bagaimana ujung las atau pola putus-putus diperlakukan. Dalam pekerjaan yang terkendali, identitas sambungan, dimensi, toleransi, urutan fabrikasi, persyaratan las, titik pemeriksaan, dan dasar penerimaan perlu saling cocok, bukan berdiri sendiri ([SNI 1729:2020 pada katalog BSN](https://pesta.bsn.go.id/produk/detail/12882-sni17292020); [ISO 3834-6](https://www.iso.org/standard/83335.html)).

Sobat Bengkel-las.co.id, pegang batas ini sejak awal: membaca notasi berarti menerjemahkan informasi gambar menjadi pertanyaan pemeriksaan. Menentukan apakah sambungan cukup kuat berarti pekerjaan desain yang membutuhkan beban, geometri, tumpuan, kondisi eksisting, urutan pemasangan, dan banyak informasi lain. Untuk memahami konteks sambungan sebagai bagian dari sistem, lihat juga [pembahasan konstruksi baja](/konstruksi-baja/).

## Tiga ukuran yang tampak mirip, tetapi tugasnya berbeda

Cara paling aman membedakannya adalah dengan membayangkan Anda sedang menjawab tiga pertanyaan berbeda pada satu detail. Pertanyaan pertama: “bagian permukaan mana yang dijangkau las?” Itu mengarahkan perhatian ke leg. Pertanyaan kedua: “penampang kerja mana yang dimaksud?” Itu mengarahkan perhatian ke throat. Pertanyaan ketiga: “sepanjang apa las yang dinilai sesuai detail?” Itu mengarahkan perhatian ke panjang efektif.

| Istilah | Cara memahaminya saat membaca gambar | Yang tidak boleh disimpulkan |
| --- | --- | --- |
| Kaki las (*leg*) | Jarak dari akar sambungan ke tepi las pada bidang yang ditunjuk. | Bahwa semua fillet memiliki bentuk dan ukuran kaki yang sama. |
| Tebal efektif (*throat*) | Jarak efektif dari akar ke bidang kerja las sesuai geometri yang dirancang. | Bahwa nilainya selalu sama dengan leg atau boleh dihitung tanpa detail yang berlaku. |
| Panjang efektif | Bagian panjang las yang dimaksud gambar dan spesifikasi untuk detail tersebut. | Bahwa seluruh jejak las yang tampak otomatis masuk hitungan. |

Tabel ini adalah alat baca, bukan tabel desain. Misalnya, bila catatan gambar menyebut satu ukuran di samping simbol fillet, jangan buru-buru menamai angka itu sebagai leg atau throat sebelum memeriksa konvensi gambar dan catatan proyek. Jika informasi kunci tidak ada, yang benar bukan mengisi kekosongan dengan kebiasaan bengkel, melainkan menahan keputusan dan meminta klarifikasi.

Istilah *intermittent weld* atau las putus-putus perlu dibaca dengan kehati-hatian yang sama. Pola ini menunjukkan segmen las dan jarak antarsegmen sebagaimana ditetapkan pada detail. Ia tidak berarti tukang las bebas memilih panjang segmen, titik awal, atau jaraknya agar lebih cepat. Yang diperiksa adalah kecocokan dengan simbol, arah sambungan, catatan gambar, dan dokumen revisi yang berlaku.

## Urutan membaca simbol sebelum mengukur

Kawan Bengkel-las.co.id, kesalahan ukur sering berawal sebelum alat ukur menyentuh benda kerja: pembaca belum memastikan detail mana yang sedang dilihat. Mulailah dengan nomor gambar, revisi, tanda sambungan, dan lokasi detail. Setelah itu, baca simbol las beserta garis penunjuknya; garis tersebut membantu menunjukkan sambungan yang dimaksud, bukan hiasan di pinggir gambar.

Lalu cari apakah gambar menyatakan las menerus atau putus-putus, serta apakah ada ukuran, panjang, pola, catatan proses, atau rujukan ke spesifikasi. Untuk pemeriksaan produksi, cocokkan informasi itu dengan identitas material dan sambungan di lapangan. Langkah sederhana ini mencegah inspector mengukur sambungan yang benar secara fisik tetapi salah secara administratif.

Baru setelah itu pilih cara ukur yang sesuai dengan tujuan pemeriksaan. Mengukur kaki las dapat menjawab apakah dimensi permukaan mendekati yang ditunjukkan. Namun satu hasil ukur tidak dengan sendirinya membuktikan throat, mutu endapan, prosedur yang dipakai, atau penerimaan akhir. Standar mutu dan inspeksi membedakan dasar penerimaan, identitas sambungan, metode serta cakupan pemeriksaan, kondisi permukaan, peralatan, pelaporan, dan tindak lanjut ketidaksesuaian ([ISO 17635](https://www.iso.org/standard/85705.html)).

Sederhananya, angka yang cocok pada alat ukur adalah satu bukti, bukan seluruh putusan. Catat juga nomor sambungan, lokasi ukur, gambar/revisi yang dipakai, alat yang digunakan, dan siapa yang menyaksikan atau memeriksa bila prosedur proyek memintanya. Catatan itulah yang membuat hasil ukur dapat ditelusuri kembali saat ada pertanyaan.

## Mengapa las yang lebih besar belum tentu lebih baik

Godaan paling umum adalah membesarkan las supaya terasa “lebih aman”. Cara pikir ini keliru karena ukuran bukan satu-satunya unsur sambungan. Las yang diperbesar dapat mengubah kebutuhan panas, urutan pengerjaan, akses, bentuk sambungan, atau pekerjaan lanjutan; dampaknya tidak boleh ditebak dari tampilan las saja. Kecukupan sistem juga bergantung pada beban, geometri, stabilitas, tumpuan atau angkur, kondisi eksisting, toleransi, lingkungan, pemeriksaan, dan pemeliharaan ([SNI 1729:2020 pada katalog BSN](https://pesta.bsn.go.id/produk/detail/12882-sni17292020); [ISO 3834-6](https://www.iso.org/standard/83335.html)).

Begitu juga sebaliknya: las yang tampak tipis tidak otomatis boleh dinyatakan gagal tanpa mengetahui ukuran yang benar-benar ditetapkan pada dokumen pengendali. Pembacaan visual dapat memunculkan pertanyaan yang baik, tetapi bukan putusan desain. Bila ada perbedaan antara kondisi lapangan dan gambar, hentikan asumsi, tandai lokasi, lalu arahkan ke pihak yang berwenang untuk menilai perubahan tersebut.

Selain ukuran, proses dan bukti pelaksanaan juga berbeda perannya. Kualifikasi prosedur, instruksi prosedur produksi, kualifikasi juru las atau operator, kendali bahan habis pakai, kondisi peralatan, pemeriksaan, dan penerimaan akhir bukan dokumen yang saling menggantikan ([ISO 15614-1](https://www.iso.org/standard/51792.html); [ISO 3834-6](https://www.iso.org/standard/83335.html)). Jadi, kartu juru las atau satu pengukuran yang terlihat baik tidak cukup untuk mengesahkan sebuah sambungan.

## Contoh aman: mengubah kebingungan menjadi pertanyaan

Anggap seorang estimator menerima detail yang memuat simbol fillet dan keterangan las putus-putus. Ia dapat membuat daftar kebutuhan kerja dari gambar, tetapi ia tidak boleh mengubah keterangan itu menjadi ukuran baru hanya karena bahan yang tersedia berbeda. Pertama, ia pisahkan apa yang jelas tertulis: identitas detail, simbol, ukuran yang disebut, panjang atau pola bila dicantumkan, dan revisinya. Kedua, ia tandai apa yang belum jelas: satuan, sisi sambungan, batas panjang, atau rujukan spesifikasi.

Teman Bengkel-las.co.id, untuk inspector skenarionya mirip. Katakanlah sebuah sambungan sudah jadi dan ukuran kaki las dapat diukur di beberapa titik. Hasil itu dapat dibandingkan dengan keterangan gambar yang tepat, tetapi jangan langsung diubah menjadi pernyataan kapasitas atau kelayakan struktur. Pertanyaan yang lebih berguna ialah: apakah saya mengukur detail yang benar, apakah gambar ini revisi terakhir, apakah pola lasnya sesuai, dan siapa yang berwenang memutuskan bila ada selisih?

Gunakan daftar singkat berikut sebelum memberi catatan “sesuai” atau “perlu klarifikasi”.

- Cocokkan nomor detail, revisi, dan lokasi sambungan sebelum membaca angka.
- Bedakan ukuran kaki, throat, dan panjang; jangan menggantikan satu istilah dengan yang lain.
- Periksa apakah simbol menunjukkan las menerus atau pola las putus-putus.
- Catat hasil ukur bersama titik ukur dan dokumen acuan, bukan sebagai angka lepas.
- Jika ada perubahan detail, minta konfirmasi tertulis dari perancang atau otoritas proyek.

[NEEDS PROJECT REVIEW: Untuk sambungan nyata, perancang struktur dan penanggung jawab proyek harus menilai beban, geometri, tumpuan, kondisi pemasangan, gambar terbitan, serta dasar penerimaannya sebelum ukuran atau perubahan sambungan disetujui.]

## Cara cepat yang perlu dihentikan

"Kalau saya buat lebih besar saja, bukankah risikonya berkurang?" Belum tentu. Cara cepat ini mengabaikan bahwa gambar adalah bagian dari paket pengendalian, bukan sekadar daftar angka. Membuat ukuran berbeda tanpa persetujuan dapat membuat hasil lapangan tidak lagi cocok dengan detail, urutan kerja, pemeriksaan, atau kebutuhan bagian lain dari sistem.

Cara cepat lain adalah memakai penggaris las sebagai alat keputusan tunggal. Alat itu berguna untuk mengamati dimensi tertentu, tetapi tidak menggantikan pemeriksaan terhadap dokumen, proses, kondisi sambungan, dan dasar penerimaan. Jika Anda sedang memilih pihak yang akan mengerjakan atau memeriksa detail, gunakan juga [pertanyaan saat memilih bengkel las yang profesional dan berpengalaman](/update/tips-memilih-bengkel-las-profesional-dan-berpengalaman/) untuk menilai cara mereka mengelola klarifikasi dan dokumen, bukan hanya melihat hasil yang tampak rapi.

## Penutup: baca notasi, jangan mendesain dari angka

Ukuran leg, throat, dan panjang efektif adalah bahasa pada gambar untuk membantu Anda memahami bagian, penampang, dan rentang las yang sedang dibicarakan. Cara membaca yang baik dimulai dengan detail serta revisinya, lalu memisahkan apa yang bisa diukur dari apa yang masih memerlukan keputusan desain dan penerimaan proyek.

Sebelum memperkirakan pekerjaan atau menyatakan hasil ukur, Kawan Bengkel-las.co.id, pegang satu aturan kerja: cocokkan simbol dengan gambar terbitan, catat bukti pemeriksaan, dan jangan mengubah ukuran sambungan karena asumsi. Bila ukuran atau pola tidak jelas, minta klarifikasi tertulis; bila sambungan nyata harus dinilai, serahkan penetapan dan perubahan kepada perancang struktur serta otoritas proyek yang berwenang.

---
article_id: WLD-11-A03
title: "Bend Allowance, Springback, dan Radius Tekuk: Konsep untuk Plat dan Sheet"
slug: "bend-allowance-springback-dan-radius"
description: "Panduan memahami garis netral, allowance, radius dalam, springback, dan validasi tekuk plat sebelum membuat bent part."
status: draft
publication_date: "2026-02-23"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: WLD-11
primary_intent: "Understand sheet-bending geometry"
reader_community: "Bengkel-las.co.id"
reader_address: "Kawan Bengkel-las.co.id"
final_route: "/artikel/bend-allowance-springback-dan-radius.html"
technical_review: required
writing_contract_version: "native-id-v2"
sources:
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://www.iso.org/standard/83335.html"
---

# Bend Allowance, Springback, dan Radius Tekuk: Konsep untuk Plat dan Sheet

Halo, Kawan Bengkel-las.co.id! Kesalahan yang sering membuat bent part meleset bukan semata-mata mesin kurang kuat, melainkan gambar datar yang menganggap garis tekuk berada di tengah ketebalan plat dan sudut akhir pasti sama dengan sudut saat ditekan. Padahal material memanjang dan memendek di zona berbeda, lalu sebagian deformasi elastis kembali ketika beban dilepas.

Jawaban singkatnya: hitung panjang bentangan dari posisi garis netral, gunakan radius dalam yang benar, dan perlakukan springback sebagai perubahan yang harus divalidasi—bukan angka koreksi universal. Bend allowance (panjang tambahan di area busur) dipakai untuk menyusun flat pattern; bend deduction (pengurang tekukan) dipakai ketika dimensi luar menjadi acuan. Sudut akhir, radius aktual, arah serat, mutu material, tepi hasil potong, serta proses dan perkakas dapat mengubah hasil. Karena itu, nilai final harus dikonfirmasi dengan kupon uji dari material dan proses yang benar-benar akan dipakai.

Jika spesifikasi part membawa beban, harus menyambung ke komponen presisi, atau masuk pekerjaan yang memiliki basis penerimaan tertentu, perhitungan ini belum menjadi persetujuan desain. Paket kerja perlu memuat revisi gambar, datum, material, toleransi, urutan fabrikasi, titik inspeksi, dan dasar penerimaan yang disepakati. Halaman katalog [SNI 1729:2020 di BSN](https://pesta.bsn.go.id/produk/detail/12882-sni17292020) hanya menunjukkan identitas dan ruang lingkup publik standar; ia bukan pengganti teks berlisensi atau dokumen proyek.

<!-- BEGIN MANAGED IMAGE PLAN
- **Image ID:** `LOCAL-002`
- **Source type:** `local`
- **Placement:** after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi memilih jasa bengkel las](/wp-content/uploads/2020/02/memilih-jasa-bengkel-las.jpg)`
- **Caption/credit:** Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `memilih jasa bengkel las` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-002]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

[NEEDS IMAGE REVIEW: LOCAL-002]

## Definisi dan batas objek

Dalam artikel ini, plat atau lembaran logam dibahas sebagai benda yang ditekuk pada satu atau beberapa garis sehingga terbentuk flange dan sudut. *Bend allowance* adalah panjang yang dialokasikan untuk bagian lengkung ketika Anda mengembangkan bentuk menjadi pola datar. *Bend deduction* adalah cara lain untuk mendapatkan ukuran potong dari dimensi luar yang sudah diketahui; keduanya bukan dua panjang fisik yang harus dijumlahkan sekaligus.

Radius tekuk yang dimaksud adalah radius pada sisi dalam lipatan. Radius pada garis netral lebih besar karena berada lebih jauh dari pusat lengkung, sedangkan radius sisi luar lebih besar lagi. Istilah radius ujung punch atau radius die adalah ukuran perkakas, bukan otomatis radius dalam yang akan terbaca pada part. Perbedaan istilah ini menjelaskan mengapa angka pada gambar, tabel perkakas, dan hasil ukur bisa tampak tidak cocok.

Batas halaman ini adalah geometri dan cara memvalidasi asumsi. Ia tidak menetapkan pilihan punch, die, gaya tekan, urutan langkah mesin, kompensasi CNC, atau angka perkakas final. Semua itu bergantung pada mesin, material, ketebalan, panjang tekuk, dan toleransi proyek. Untuk kebutuhan pelaksanaan, siapkan paket kerja yang jelas. Panduan mutu pengelasan [ISO 3834-6:2024 di ISO](https://www.iso.org/standard/83335.html) dapat menjadi pengingat bahwa dokumen, identitas material, urutan, inspeksi, dan penerimaan perlu dikendalikan; abstrak publiknya tetap tidak memberi angka allowance untuk part Anda.

## Cara kerjanya

Bayangkan penampang plat sebelum ditekuk. Serat di sisi dalam busur tertekan dan memendek, sementara serat di sisi luar tertarik dan memanjang. Di antara keduanya ada zona yang perubahan panjangnya paling kecil. Zona itu disebut garis netral. Letaknya tidak selalu tepat di tengah ketebalan karena dipengaruhi radius terhadap tebal, material, dan proses. Dalam perhitungan sederhana, letaknya didekati dengan faktor K sehingga radius garis netral dapat ditulis sebagai radius dalam ditambah K kali tebal.

Untuk sudut tekuk dalam radian, bentuk umum bend allowance adalah:

`BA = θ × (R + K × t)`

Di sini `BA` adalah panjang busur pada garis netral, `θ` sudut tekuk dalam radian, `R` radius dalam, `t` tebal material, dan `K` faktor posisi garis netral. Rumus ini membantu membaca hubungan antarbesaran, bukan memberikan nilai K yang boleh disalin dari satu part ke semua part. Jika gambar memakai sudut luar, sudut pelipatan, atau dimensi sampai perpotongan garis luar, konvensinya harus disamakan terlebih dahulu.

Ada dua alur ukuran yang umum. Pada metode bend allowance, panjang blank adalah jumlah panjang flange lurus sesuai datum ditambah BA untuk setiap tekukan. Pada metode bend deduction, Anda mulai dari ukuran luar dan mengurangi nilai yang mewakili area tekukan, yang sering dirumuskan dari outside setback dan BA. Kesalahan terbesar biasanya terjadi ketika satu ukuran dari dimensi luar dicampur dengan rumus yang diasumsikan untuk dimensi sampai garis tajam. Tulis titik ukur dan arah datum pada gambar sebelum menghitung.

Saat punch menekan, material mengalami deformasi plastis dan elastis. Ketika beban dilepas, bagian elastis pulih sehingga sudut biasanya membuka dan radius dalam dapat berubah. Fenomena ini disebut *springback*, atau pemulihan elastis. Koreksi yang tepat tidak dapat ditentukan hanya dari nama material. Kekuatan material, rasio radius terhadap tebal, lebar dan panjang tekuk, arah serat, kondisi tepi, metode tekuk, serta riwayat pembentukan ikut berpengaruh.

Maka urutannya sebaiknya begini: tetapkan definisi dimensi, pilih asumsi awal untuk R dan K dari sumber proses yang disetujui, buat flat pattern, lakukan satu kupon, ukur hasil setelah dilepas dari perkakas, lalu perbarui data untuk produksi. Ukur sudut dari datum yang sama dan ukur radius dengan metode yang konsisten. Jangan mengubah angka gambar secara diam-diam hanya agar satu kupon terlihat cocok.

## Faktor yang mengubah hasil

**Material dan tebal.** Dua plat dengan label umum yang sama belum tentu memberi respons yang sama. Grade, kondisi pengerasan, variasi tebal aktual, dan arah pengerolan dapat menggeser lokasi garis netral dan springback. Bila sertifikat material, lot, atau tebal aktual belum jelas, hasil perhitungan pantas diberi status asumsi, bukan nilai produksi.

**Arah serat dan tepi potong.** Tekukan melintang terhadap arah pengerolan dapat berperilaku berbeda dari tekukan sejajar. Tepi hasil potong termal atau mekanis juga dapat memiliki kondisi permukaan dan cacat awal yang memengaruhi risiko retak pada radius kecil. Tandai orientasi serat di blank bila orientasi itu penting bagi bentuk atau mutu permukaan. Jangan menyimpulkan bahwa satu kupon memvalidasi semua arah.

**Radius dan ketebalan.** Radius dalam yang lebih kecil meningkatkan tuntutan regangan di sisi luar; radius yang lebih besar mengubah panjang busur dan respons elastis. “Radius minimum” bukan angka tunggal yang aman untuk semua jenis plat. Ia harus berasal dari persyaratan material, proses yang digunakan, dan konsekuensi retak atau perubahan bentuk pada part tertentu. Bila part kritis, minta tinjauan desain sebelum radius diperkecil untuk mengejar ukuran flange.

**Geometri dan urutan.** Flange pendek, lubang dekat garis tekuk, beberapa tekukan yang saling berdekatan, serta datum yang berpindah dapat membuat hasil ukur menipu. Tekukan pertama bisa mengubah akses dan orientasi untuk tekukan berikutnya. Sisakan zona bebas sesuai gambar dan verifikasi bahwa urutan yang direncanakan tidak menjadikan alat ukur atau perkakas bertabrakan.

**Proses dan catatan.** Gaya, kecepatan, kondisi perkakas, penjepitan, dan urutan pembentukan memengaruhi hasil; namun artikel ini tidak menetapkan setelan mesin. Catat material, tebal aktual, orientasi, radius sasaran, asumsi K, alat yang dipakai, urutan, dan ukuran hasil. Dengan catatan itu, penyimpangan dapat ditelusuri dan tidak berubah menjadi kebiasaan menebak.

## Contoh keputusan praktis

Misalkan estimator menerima gambar dengan dua flange, sudut nominal, dan toleransi yang ketat, tetapi tidak ada keterangan apakah dimensi flange diukur dari sisi luar atau dari garis teoritis. Keputusan pertama bukan memilih die. Tandai pertanyaan datum kepada perancang. Tanpa jawaban itu, BA dan BD dapat menghasilkan blank yang berbeda walaupun memakai R dan t yang sama.

Untuk part pertama dari material dan tebal yang belum pernah diproses, gunakan alur berikut:

1. Kunci revisi gambar, satuan, datum, sudut, radius dalam, tebal nominal, dan toleransi.
2. Minta identitas grade serta kondisi material; catat arah serat bila tersedia.
3. Pilih asumsi BA/K dan radius awal dari prosedur atau data proses yang disetujui, lalu beri label “perlu uji”.
4. Buat kupon dengan lebar, orientasi, tepi, dan urutan yang mewakili part, tanpa menganggap kupon sebagai bukti kinerja komponen akhir.
5. Setelah pembebanan dilepas, ukur sudut, radius, dan semua flange dari datum yang sama. Catat juga retak, gores, atau distorsi yang terlihat.
6. Bandingkan hasil dengan toleransi. Bila tidak masuk, hentikan pelepasan lot dan lakukan tinjauan teknis; jangan sekadar mengganti satu angka tanpa mencari penyebab.

Kawan Bengkel-las.co.id, bila hasil kupon belum stabil, pertanyaan yang berguna kepada bengkel adalah “data aktual apa yang akan dicatat dan pada titik mana keputusan lanjut dibuat?” Bukan “berapa faktor K yang biasanya dipakai?”. Untuk pekerjaan yang perlu eksekusi bengkel, pembaca dapat meneruskan kebutuhan yang sudah terdokumentasi ke [layanan bending plat di Yogyakarta](/bending-plat-yogyakarta.html) atau [opsi bending plat di Tuban](/bending-plat-tuban.html), sambil tetap meminta konfirmasi proses dan toleransi yang berlaku untuk partnya.

## Kesalahan umum dan cara memeriksanya

Shortcut “pakai setengah tebal sebagai garis netral” memang mudah, tetapi hanya asumsi awal. Periksa apakah radius terhadap tebal dan kondisi material membuat asumsi itu masuk akal; jika tidak ada basis, pertahankan penanda perlu validasi.

Kesalahan kedua adalah menyamakan radius punch dengan radius dalam. Ukur hasil part, bukan hanya membaca label perkakas. Kesalahan ketiga adalah mengoreksi springback dengan menambahkan sudut secara tetap pada semua tekukan. Bandingkan minimal kupon dengan material, arah serat, radius, dan urutan yang sama sebelum menetapkan koreksi proses.

Kesalahan berikutnya adalah mengabaikan sisi yang menjadi acuan. Sebuah flange bisa “benar” dari sisi luar namun salah dari datum rakitan. Tandai apakah ukuran berasal dari outer mold line, inner mold line, tangent point, atau garis teoritis. Minta perancang mengesahkan konvensi itu bila gambar ambigu.

Jangan menganggap hasil satu part sebagai bukti bahwa seluruh batch, grade, atau arah serat pasti sama. Simpan lembar catatan yang memuat nomor revisi, identitas material, ukuran aktual, alat ukur, tanggal, operator atau pelaksana, dan keputusan setelah pengukuran. Data itu membuat rework dapat dibahas dengan fakta, bukan ingatan.

Sobat Bengkel-las.co.id, hentikan pekerjaan dan minta review kompeten jika part berkaitan dengan keselamatan, beban, tekanan, kelelahan, sambungan presisi, atau toleransi yang tidak dapat ditoleransi ulang. Perhitungan geometri tidak membuktikan kecukupan struktur, mutu material, kelayakan sambungan, atau kepatuhan terhadap aturan proyek. Hindari juga menyatakan part “memenuhi SNI/ISO” hanya karena satu nilai sudut terlihat sesuai; dasar penerimaan dan edisi dokumen harus benar-benar tersedia.

## Penutup: aturan kerja sebelum produksi

Bend allowance menjelaskan panjang area busur pada garis netral; bend deduction membantu menerjemahkan dimensi luar menjadi ukuran blank; radius dalam adalah geometri sisi dalam yang harus dibedakan dari radius perkakas; dan springback adalah pemulihan elastis yang membuat sudut serta radius setelah pelepasan beban tidak sama dengan kondisi saat ditekan. Material, arah serat, tepi, geometri, dan proses menentukan seberapa jauh asumsi awal dapat dipercaya.

Langkah berikutnya adalah membuat satu lembar verifikasi berisi datum, konvensi dimensi, R, t, asumsi K, identitas material, orientasi serat, hasil kupon, dan keputusan tinjauan. Minta persetujuan atas lembar itu sebelum blank produksi atau perubahan setelan dilakukan. Aturan praktisnya: jangan lepaskan part ke produksi hanya karena rumusnya selesai; lepaskan setelah geometri terukur, basis penerimaan jelas, dan batas profesional yang relevan sudah ditinjau.

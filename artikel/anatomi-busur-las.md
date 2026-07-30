---
article_id: WLD-01-A03
title: "Anatomi Busur Las: Arus, Tegangan, Polaritas, dan Jalur Arus"
slug: "anatomi-busur-las"
description: "Memahami hubungan sumber, elektroda atau torch, busur, benda kerja, kabel balik, arus, tegangan, AC/DC, dan polaritas"
writing_contract_version: "native-id-v2"
status: draft
publication_date: "2025-06-19"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: WLD-01
primary_intent: "Understand the welding electrical circuit"
reader_community: "Bengkel-las.co.id"
reader_address: "Kawan Bengkel-las.co.id"
final_route: "/artikel/anatomi-busur-las.html"
technical_review: required
sources: []
---

# Anatomi Busur Las: Arus, Tegangan, Polaritas, dan Jalur Arus

Halo, Kawan Bengkel-las.co.id! Busur las bukan “api” yang berdiri sendiri. Ia adalah bagian dari rangkaian listrik: sumber mengirim energi melalui kabel ke elektroda atau torch, celah busur menghubungkan ujung elektroda dengan benda kerja, lalu arus kembali melalui kabel balik ke sumber. Jika salah satu bagian tidak terhubung sebagaimana mestinya, busur tidak stabil atau tidak terbentuk.

Jadi, arus adalah aliran listrik dalam rangkaian; tegangan adalah beda potensial yang mendorong aliran dan mempertahankan busur; polaritas menjelaskan sisi positif-negatif pada sistem DC; sedangkan AC berganti arah secara periodik. Nilai pengaturan spesifik, kecocokan proses, dan keputusan kelayakan sambungan tetap harus mengikuti dokumen pekerjaan serta pemeriksaan teknis. [NEEDS TECHNICAL REVIEW: verifikasi istilah dan perilaku rangkaian terhadap mesin/proses yang dipakai.]

![Ilustrasi bengkel las](/wp-content/uploads/2019/10/bengkel-las.png)

Ilustrasi bersumber dari aset lokal; gambar ini bukan dokumentasi proyek tertentu.

## Definisi dan batas objek

Objek yang dibahas adalah jalur listrik pembentuk busur, bukan seluruh pekerjaan pengelasan. Bayangkan rangkaiannya sebagai lingkaran: **sumber daya → lead elektroda/torch → elektroda atau kawat → busur → benda kerja → kabel balik (return lead) → terminal balik sumber**. Pada proses dengan torch, torch membawa elektroda atau kawat dan dapat pula membawa gas pelindung; gas itu membantu lingkungan busur, tetapi bukan pengganti jalur arus logam.

“Ground” sering dipakai secara longgar. Dalam pembahasan ini, kabel balik adalah penghantar kerja yang mengembalikan arus ke sumber, sedangkan grounding bangunan atau perlindungan sengatan adalah topik keselamatan kelistrikan yang berbeda. Bahaya jalur balik, K3 listrik, dan cara memilih angka setelan tidak menjadi ruang artikel ini. [NEEDS TECHNICAL REVIEW: konfirmasi penamaan terminal pada manual mesin setempat.]

## Cara kerjanya

Saat sumber diaktifkan, rangkaian belum tertutup karena ujung elektroda masih terpisah dari benda kerja. Ketika ujung didekatkan atau disentuhkan dengan gerakan yang sesuai proses, medium di celah itu terionisasi dan menjadi penghantar. Busur tampak sebagai plasma panas; arus mengalir melintasi celah, mencairkan sebagian elektroda/kawat dan permukaan benda kerja. Setelah itu arus meneruskan perjalanan melalui benda kerja, penjepit dan kabel balik, lalu masuk kembali ke sumber.

Arus (ampere) terutama menggambarkan banyaknya muatan yang mengalir pada saat itu. Tegangan (volt) adalah beda potensial antara dua titik; dalam pengelasan, tegangan busur berkaitan dengan panjang dan kondisi celah. Memanjangkan busur biasanya mengubah tegangan dan bentuk busur, tetapi bukan alasan untuk mengejar angka tertentu tanpa prosedur yang disetujui. [NEEDS TECHNICAL REVIEW: hubungan angka arus-tegangan untuk kombinasi proses, material, dan mesin tertentu.]

Elektroda terbungkus dan kawat las berfungsi sebagai elektroda sekaligus logam pengisi. Pada torch non-konsumabel, seperti konsep torch dengan elektroda yang tidak habis, logam pengisi—bila diperlukan—dimasukkan terpisah. Perbedaan ini menjelaskan mengapa “arus lewat torch” tidak selalu berarti torch habis terkikis; yang penting adalah bagian konduktif mana yang menjadi ujung busur.

## Faktor yang mengubah hasil

Pertama, jenis sumber: **DC (direct current/arus searah)** mempertahankan arah arus dari satu terminal ke terminal lain. Saat kabel elektroda berada di sisi negatif, konfigurasi biasa disebut DCEN; saat di sisi positif, DCEP. Nama konfigurasi itu hanya bermakna setelah terminal mesin, elektroda, dan prosedur benar-benar diketahui. Membalik kabel dapat mengubah distribusi panas, perilaku busur, dan perpindahan logam—bukan sekadar menukar warna kabel. [NEEDS TECHNICAL REVIEW: polaritas yang diizinkan untuk elektroda/proses yang dipilih.]

Pada **AC (alternating current/arus bolak-balik)**, arah dan polaritas berubah berulang. Karena tidak ada sisi positif-negatif tetap seperti DC, istilah “elektroda positif” hanya berlaku pada bagian siklus tertentu. Respons busur dipengaruhi bentuk gelombang dan rancangan sumber, sehingga label AC pada mesin belum cukup untuk menyimpulkan hasil pada setiap elektroda.

Kedua, jalur fisik: panjang kabel, sambungan, penjepit, kebersihan permukaan kontak, dan posisi benda kerja memengaruhi impedansi serta kestabilan penghantaran. Ketiga, antarmuka proses: material elektroda, pelindung, posisi, ketebalan, dan bentuk sambungan mengubah cara busur harus dikendalikan. Faktor-faktor itu adalah alasan nilai setelan tidak boleh dipindahkan mentah dari satu pekerjaan ke pekerjaan lain.

## Contoh keputusan praktis

Gunakan urutan tanya berikut sebelum menafsirkan gejala:

| Pertanyaan | Makna rangkaian |
|---|---|
| Dari terminal mana energi keluar? | Menentukan sisi sumber yang terhubung ke elektroda/torch. |
| Ke mana ujung elektroda mengirim busur? | Busur harus menjembatani celah ke benda kerja yang dituju. |
| Bagaimana arus kembali? | Jalurnya harus berakhir di terminal balik sumber melalui kabel balik dan kontak kerja. |
| Apakah sumbernya AC atau DC? | Menentukan apakah polaritas tetap atau berganti. |
| Apa yang ditentukan prosedur? | Menetapkan proses, bahan habis pakai, rentang kerja, dan pemeriksaan yang harus diikuti. |

Misalnya busur putus-putus. Jangan langsung menyimpulkan arus “kurang”. Periksa dulu apakah rangkaian kembali ke sumber, apakah koneksi kerja sesuai, apakah celah berubah-ubah, dan apakah konfigurasi AC/DC cocok dengan proses. Jika busur menyala tetapi bentuk dan lelehan tidak sesuai, catat kondisi aktual lalu minta peninjauan prosedur; artikel ini tidak menetapkan angka koreksi.

Kawan Bengkel-las.co.id, pada pekerjaan yang dikendalikan dokumen, mintalah identitas mesin, proses, elektroda atau kawat, diagram terminal, dan instruksi kerja yang berlaku. Catatan itu memisahkan fakta yang dapat diperiksa dari dugaan operator. Untuk menilai penyedia kerja secara lebih umum, Anda dapat membaca [panduan memilih bengkel las profesional](/update/tips-memilih-bengkel-las-profesional-dan-berpengalaman).

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah menganggap kabel balik sekadar aksesori. Tanpa jalur kembali, rangkaian terbuka. Kesalahan kedua adalah menyamakan tegangan mesin dengan tegangan busur; pengukuran dan kondisi operasi dapat berbeda. Kesalahan ketiga adalah mengira semua elektroda boleh dipakai pada polaritas apa pun. Periksa lembar data dan prosedur produk, bukan ingatan.

Kesalahan keempat adalah memakai kata “ground” untuk semua kabel. Tulis label yang spesifik: terminal elektroda/torch, terminal balik, kabel, penjepit kerja, dan—bila relevan—konduktor proteksi. Kesalahan kelima adalah mengubah polaritas untuk “mencari-cari hasil” tanpa mencatat konfigurasi. Perubahan tanpa pengendalian membuat penyebab hasil sulit dilacak dan dapat membatalkan dasar pemeriksaan yang disepakati.

Sobat Bengkel-las.co.id, lakukan pemeriksaan meja sederhana: gambar panah dari sumber ke elektroda, melintasi busur, menuju benda kerja, lalu kembali ke sumber. Tandai jenis arus, terminal, dan komponen yang benar-benar terpasang. Bila satu panah berhenti pada sambungan yang tidak jelas, itulah pertanyaan yang harus dijawab sebelum mengubah setelan. Jika keputusan Anda juga menyangkut bahan pagar atau teralis, [ringkasan bahan teralis jendela yang umum](/update/3-bahan-teralis-jendela-las-yang-umum-di-pasaran) dapat menjadi pertanyaan lanjutan untuk dibawa ke tenaga teknis.

## Jalan pintas yang perlu dihindari

Shortcut yang sering muncul adalah, “Balik saja kabelnya; nanti terlihat polaritas yang paling enak.” Cara itu dapat mengubah karakter busur tanpa membuktikan bahwa kombinasi elektroda, sumber, dan pekerjaan memang diizinkan. Alternatif yang lebih dapat dipertanggungjawabkan: cocokkan diagram terminal dan instruksi bahan habis pakai, dokumentasikan konfigurasi awal, lalu minta kompeten teknis menilai hasil inspeksi sebelum melanjutkan.

## Kesimpulan dan langkah berikutnya

Anatomi busur las adalah satu rangkaian tertutup: sumber, lead elektroda/torch, elektroda, busur, benda kerja, dan kabel balik. Arus mengalir di seluruh loop; tegangan mempertahankan beda potensial pada celah; AC berganti arah, sedangkan DC memiliki polaritas yang ditetapkan oleh terminal. Hubungan itu menjelaskan fungsi tiap bagian, tetapi tidak menggantikan prosedur atau persetujuan proyek.

Langkah berikutnya: buat skema loop untuk mesin dan proses yang akan dipakai, cocokkan terminal serta jenis elektroda dengan dokumen produsennya, dan minta peninjauan teknis untuk setiap nilai atau keputusan yang tidak tersedia. Jangan menganggap penjelasan anatomi ini sebagai izin mengubah setelan atau mengabaikan pemeriksaan sambungan.

<!-- BEGIN MANAGED IMAGE PLAN
Image ID: LOCAL-001
Source type: local
Placement: after opening, before first detailed H2
**Exact Markdown to insert:** `![Ilustrasi bengkel las](/wp-content/uploads/2019/10/bengkel-las.png)`
Caption/credit: Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
Selection basis: filename/source metadata identifies bengkel las as relevant content media; no pixels were inspected.
Hard boundary: do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
Substitution rule: do not replace this image. If unavailable or provenance is incomplete, insert [NEEDS IMAGE REVIEW: LOCAL-001] and continue drafting the prose.
END MANAGED IMAGE PLAN -->

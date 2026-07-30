---
article_id: WLD-08-A01
title: "Arus, Tegangan, Wire Feed, dan Travel Speed: Membaca Parameter dari WPS"
slug: "membaca-parameter-pengelasan-dari-wps"
description: "Menjelaskan hubungan arus, tegangan, wire feed, travel speed, konsep heat input, batas tampilan mesin, dan rekaman kerja"
status: draft
publication_date: "2025-11-27"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: WLD-08
primary_intent: "Interpret approved welding variables"
reader_community: "Bengkel-las.co.id"
reader_address: "Sobat Bengkel-las.co.id"
final_route: "/artikel/membaca-parameter-pengelasan-dari-wps.html"
technical_review: required
writing_contract_version: "native-id-v2"
sources:
  - "https://www.iso.org/standard/51792.html"
  - "https://www.iso.org/standard/54936.html"
  - "https://www.iso.org/standard/83335.html"
  - "https://www.iso.org/standard/80209.html"
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/75614.html"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018"
---

# Arus, Tegangan, Wire Feed, dan Travel Speed: Membaca Parameter dari WPS

Halo, Sobat Bengkel-las.co.id! Kebingungan paling mahal bukan saat angka pada WPS sulit dibaca, melainkan saat arus, tegangan, wire feed speed (WFS), dan travel speed dianggap sebagai empat kenop yang boleh diubah sendiri-sendiri. Jawaban singkatnya: baca dulu proses, material, sambungan, posisi, dan rentang yang disahkan pada WPS; lalu cocokkan setelan mesin dengan kondisi aktual dan catat hasilnya. WFS dan arus dapat saling terkait pada proses kawat tertentu, tegangan memengaruhi perilaku busur, sedangkan travel speed mengubah banyaknya energi per panjang las. Hubungan tepatnya tetap bergantung pada proses, mode mesin, kawat, gas, dan rentang WPS.

Jadi, tidak ada “angka aman universal” yang bisa dipindahkan dari satu pekerjaan ke pekerjaan lain. Jika tampilan mesin tidak jelas apakah menunjukkan setpoint atau nilai aktual, jika parameter keluar dari rentang, atau jika dokumen dan kondisi sambungan tidak cocok, pekerjaan berhenti untuk klarifikasi. Hasil las tidak dapat dinyatakan sesuai hanya karena busur terdengar halus. Catatan produksi, pemeriksaan yang dipersyaratkan, dan persetujuan personel berwenang melengkapi pembacaan parameter.

<!-- BEGIN MANAGED IMAGE PLAN
Image ID: LOCAL-002
Source type: local
Placement: after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi memilih jasa bengkel las](/wp-content/uploads/2020/02/memilih-jasa-bengkel-las.jpg)`
Caption/credit: Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
Selection basis: filename/source metadata identifies `memilih jasa bengkel las` as relevant content media; no pixels were inspected.
Hard boundary: do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
Substitution rule: do not replace this image. If unavailable or provenance is incomplete, insert [NEEDS IMAGE REVIEW: LOCAL-002] and continue drafting the prose.
END MANAGED IMAGE PLAN -->

![Ilustrasi memilih jasa bengkel las](/wp-content/uploads/2020/02/memilih-jasa-bengkel-las.jpg)

Ilustrasi umum dari aset lokal Bengkel-las.co.id; bukan dokumentasi proyek tertentu.

Untuk konteks pekerjaan lain, telusuri [blog Bengkel-las.co.id](/blog) atau mulai dari [halaman utama Bengkel-las.co.id](/#top).

## Hasil akhir dan prasyarat

Hasil yang dicari dari pembacaan WPS adalah keputusan yang dapat ditelusuri: operator mengetahui rentang yang berlaku, penyelia dapat melihat bahwa setelan dan kondisi sambungan cocok, dan tim mutu memiliki rekaman untuk menilai pekerjaan. WPS yang sudah disetujui, gambar atau instruksi sambungan yang berlaku, identitas material dan bahan tambah, mesin yang statusnya diketahui, serta formulir rekaman harus tersedia sebelum pengelasan dimulai. Orang yang mengubah atau menyetujui prosedur harus memiliki kewenangan sesuai sistem proyek; artikel ini tidak memberikan kewenangan tersebut.

Bedakan tiga hal yang sering tertukar. Kualifikasi prosedur membuktikan bahwa suatu prosedur telah diuji dalam lingkup tertentu, sedangkan WPS produksi menerjemahkan prosedur itu menjadi instruksi kerja. Kualifikasi welder atau operator adalah catatan terpisah tentang kemampuan orang pada lingkup yang ditetapkan. Abstrak resmi [ISO 15614-1](https://www.iso.org/standard/51792.html) dan [ISO 9606-1](https://www.iso.org/standard/54936.html) membantu menjaga pembedaan ini; keduanya tidak menggantikan teks standar berlisensi atau spesifikasi proyek. Karena itu, kartu welder tidak otomatis mengesahkan perubahan WPS, dan WPS tidak otomatis membuktikan penerimaan sambungan jadi.

## Langkah 1 — tetapkan batas pekerjaan

Mulailah dari identitas, bukan dari kenop mesin. Tandai nomor dan revisi WPS, nomor sambungan, proses las, material dasar, ketebalan, posisi, jenis sambungan, bahan tambah, gas pelindung, serta urutan atau batasan lain yang memang tercantum. Cocokkan juga antarmuka: apakah sambungan berada di bengkel atau lapangan, apakah akses dan posisi berubah, dan siapa yang melakukan inspeksi. Bila salah satu identitas itu tidak jelas, jangan menebak dengan WPS yang namanya mirip.

Scope ini sengaja sempit. Kita membaca variabel yang sudah disetujui, bukan merancang prosedur baru, menentukan universal setting, atau menggantikan kualifikasi. Perubahan material, diameter kawat, mode transfer, posisi, ketebalan, atau kondisi lingkungan dapat mengubah relevansi rentang. Abstrak standar hanya membantu mengenali tujuan dan status dokumen; rentang kualifikasi dan persyaratan pengujian harus diambil dari dokumen proyek dan teks standar yang berlaku.

## Langkah 2 — kumpulkan dan cocokkan bukti

Buat satu lembar pencocokan sebelum busur dinyalakan. Isinya dapat disusun seperti berikut.

| Yang dibaca | Yang dicocokkan | Jika tidak cocok |
| --- | --- | --- |
| WPS dan revisi | Nomor sambungan, proses, posisi, material, dan rentang variabel | Tahan pekerjaan dan minta dokumen yang berlaku |
| Arus, tegangan, WFS, travel speed | Satuan, batas bawah-atas, mode mesin, serta nilai yang harus direkam | Jangan mengisi angka dari pengalaman; minta klarifikasi |
| Mesin dan alat ukur | Identitas mesin, status pemeriksaan atau verifikasi, dan cara mengambil nilai aktual | Tandai keterbatasan pembacaan dan panggil penanggung jawab mutu |
| Kawat, elektroda, gas, dan penyimpanan | Klasifikasi, batch, kondisi, dan instruksi WPS | Pisahkan bahan yang belum terverifikasi |
| Sambungan dan kondisi kerja | Fit-up, posisi, preheat/interpass bila dipersyaratkan, akses, dan lingkungan | Hentikan sebelum kondisi keluar dari prosedur |

Catatan mutu yang rapi menghubungkan bahan, peralatan, personel, pemeriksaan, dan keputusan. [ISO 3834-6:2024](https://www.iso.org/standard/83335.html) adalah titik rujuk untuk memahami bahwa sistem mutu pengelasan memerlukan pengendalian yang lebih luas daripada angka pada panel mesin; abstraknya tidak memberi formulir atau nilai proyek Anda. Simpan salinan WPS yang benar-benar dipakai, bukan hanya nama filenya.

## Langkah 3 — jalankan urutan kerja

Pertama, baca kolom variabel dari kiri ke kanan dan pastikan satuannya. Kedua, pilih mode proses yang ditentukan; jangan menganggap tombol dengan nama serupa menghasilkan perilaku yang sama pada semua sumber daya. Ketiga, pasang bahan tambah dan gas yang telah dicocokkan, lalu masukkan setelan dalam rentang yang ditentukan. Keempat, lakukan verifikasi awal yang diwajibkan prosedur—misalnya pemeriksaan kesiapan sambungan atau pembacaan awal—bukan percobaan bebas untuk mencari angka baru.

Saat mengelas, amati kestabilan busur, bentuk genangan, dan kemampuan mengikuti sambungan sebagai tanda proses, bukan sebagai bukti tunggal penerimaan. Rekam nilai yang diminta pada setiap pass atau segmen sesuai formulir. Bila operator perlu melakukan koreksi kecil yang masih diizinkan WPS, tulis nilai sebelum, sesudah, waktu, lokasi, dan alasan. Koreksi di luar rentang adalah perubahan prosedur dan memerlukan jalur persetujuan yang berbeda.

Kawan Bengkel-las.co.id, biasakan mengajukan satu pertanyaan sederhana sebelum menarik pelatuk: “Angka ini berasal dari WPS, dari setpoint mesin, atau dari pengukuran aktual?” Tiga sumber itu bisa tampak sama di layar, tetapi maknanya tidak sama untuk rekaman.

### Membaca hubungan empat parameter

- **Arus.** Dalam proses kawat tertentu, arus berkaitan dengan laju peleburan dan deposisi. Namun polaritas, diameter kawat, mode transfer, dan karakter sumber daya ikut menentukan. Jangan mengubah arus hanya untuk mengejar suara busur tanpa memeriksa parameter lain.
- **Wire feed speed.** WFS adalah laju pengumpanan kawat. Pada sistem tegangan-konstan, perubahan WFS sering memengaruhi arus, tetapi hubungan itu bukan izin untuk memakai kurva dari merek atau proses lain. Pastikan WPS menyatakan WFS atau padanannya dan gunakan satuan yang sama.
- **Tegangan.** Tegangan berhubungan dengan panjang dan karakter busur. Perubahan tegangan dapat mengubah pembasahan dan bentuk bead, tetapi gejalanya dipengaruhi stick-out, gas, posisi, dan gerakan tangan. Baca pasangan arus–tegangan, bukan satu angka terisolasi.
- **Travel speed.** Ini adalah kecepatan gerak relatif sepanjang sambungan. Pada kondisi lain yang sama, gerak lebih lambat cenderung memberi lebih banyak energi per panjang dan gerak lebih cepat cenderung memberi lebih sedikit. “Kondisi lain yang sama” penting: weave, diameter bead, posisi, dan jeda juga memengaruhi hasil.

Jika satu parameter berubah, periksa dampaknya pada tiga parameter lain dan pada batas WPS. Itulah sebabnya tampilan angka yang masih berada di dalam rentang belum cukup bila mode proses atau kondisi sambungannya berbeda.

### Memahami konsep heat input tanpa angka tebakan

Secara konseptual, energi per panjang meningkat ketika kombinasi arus dan tegangan meningkat atau ketika travel speed melambat. Perhitungan formal memerlukan satuan waktu dan panjang, faktor efisiensi proses, serta metode yang ditetapkan proyek. Gunakan lembar perhitungan atau formulir yang disahkan; jangan memasukkan faktor efisiensi dari internet lalu menyimpulkan sambungan pasti memenuhi syarat. [NEEDS PROJECT REVIEW: metode perhitungan heat input, faktor efisiensi, satuan, dan batas yang berlaku pada WPS belum tersedia dalam paket artikel ini.]

### Batas pembacaan panel mesin

Panel bisa menampilkan setpoint, nilai rata-rata, atau nilai aktual yang dibaca sensor; resolusi dan jedanya pun bergantung pada mesin. Karena itu, tulis label sumber nilai pada rekaman. Bila WPS atau rencana mutu mensyaratkan nilai aktual, sepakati cara pengukuran dan status verifikasi alat sebelum pekerjaan. Jika hanya setpoint yang dapat disimpan, nyatakan keterbatasan itu dan minta keputusan mutu—jangan mengubahnya menjadi klaim bahwa nilai aktual pasti sama.

## Titik berhenti dan kondisi wajib ditinjau

Hentikan pekerjaan dan minta review ketika WPS atau revisinya tidak tersedia, identitas sambungan berubah, parameter keluar dari rentang, mesin atau alat ukur tidak berstatus, bahan tambah tidak terlacak, atau preheat/interpass yang dipersyaratkan tidak dapat dibuktikan. Perubahan lokasi ke lapangan juga bukan sekadar memindahkan mesin: akses, cuaca, pasokan listrik, paparan fume, pekerjaan sekitar, dan perlindungan kebakaran perlu dinilai oleh penanggung jawab setempat. Kewajiban keselamatan kerja bersumber pada konteks tugas dan aturan yang berlaku, termasuk [UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970) dan [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018); artikel ini tidak menetapkan jarak, durasi, ventilasi, atau setelan K3.

Untuk paket ini, bukti proyek dan persetujuan kompeten belum tersedia untuk menutup seluruh pemeriksaan yang ditandai koordinator. **[NEEDS PROJECT REVIEW: GATE-01 s.d. GATE-13 — cocokkan WPS, rentang kualifikasi, mesin, bahan, kondisi kerja, inspeksi, dan rekaman dengan dokumen proyek sebelum melanjutkan.]**

## Verifikasi hasil dan serah terima

Sebelum area dilepas, periksa apakah berkas berikut dapat ditelusuri sampai ke sambungan:

1. WPS, revisi, gambar, dan identitas joint yang digunakan.
2. Identitas welder atau operator serta status kualifikasinya.
3. Nomor mesin, alat ukur, status verifikasi, dan cara pembacaan nilai.
4. Setpoint dan nilai aktual yang berhasil direkam untuk arus, tegangan, WFS, dan travel speed sesuai kebutuhan prosedur.
5. Material dasar, bahan tambah, batch, serta kondisi penyimpanan yang relevan.
6. Catatan fit-up, preheat/interpass, waktu, lokasi, dan koreksi parameter bila dipersyaratkan.
7. Pemeriksaan visual, NDT, atau pemeriksaan lain beserta personel, metode, extent, laporan, dan otoritas penerimaan.
8. Ketidaksesuaian, disposisi, siklus repair, dan persetujuan penutupan.

Teman Bengkel-las.co.id, serahkan paket ini bersama daftar ketidaksesuaian yang masih terbuka; penerima handover perlu tahu mana yang sudah diverifikasi dan mana yang menunggu keputusan.

[ISO 5817:2023](https://www.iso.org/standard/80209.html) membahas tingkat kualitas terkait ketidaksempurnaan pada sambungan, tetapi angka penerimaan tetap mengikuti basis proyek. [ISO 17635:2025](https://www.iso.org/standard/85705.html) memberi kerangka umum pemilihan metode NDT, sedangkan [ISO 9712:2021](https://www.iso.org/standard/75614.html) berkaitan dengan kualifikasi dan sertifikasi personel NDT. Ketiganya membantu memisahkan pekerjaan las, teknik pemeriksaan, kompetensi pemeriksa, dan keputusan engineering. Jangan menulis “lulus” hanya dari rekaman panel atau tampilan bead.

## Jalan pintas yang perlu ditolak

Menyalin setelan dari pekerjaan yang “kelihatannya sama” memang cepat, tetapi dapat gagal ketika material, posisi, diameter kawat, mode transfer, atau revisi WPS berbeda. Jalan pintas lain adalah memutar kenop sampai suara busur terasa nyaman. Suara dan tampilan hanya observasi proses; keduanya tidak membuktikan rentang kualifikasi, heat input, atau penerimaan akhir.

Alternatif yang lebih dapat dipertanggungjawabkan adalah menyalin identitas WPS dan rentangnya, menguji kecocokan material dan consumable, menyepakati cara membaca nilai aktual, lalu mencatat setiap perubahan yang diizinkan. Jika kecocokan tidak dapat dibuktikan, berhenti di hold point dan minta keputusan personel berwenang.

## Kesimpulan

Arus, tegangan, WFS, dan travel speed harus dibaca sebagai satu sistem di dalam rentang WPS, bukan sebagai empat angka bebas. Arus dan WFS dapat berhubungan pada proses kawat tertentu, tegangan memengaruhi busur, dan travel speed ikut menentukan energi per panjang; efek akhirnya baru bermakna setelah proses, material, sambungan, mesin, dan satuan cocok.

Langkah berikutnya adalah mengambil WPS beserta revisinya, mengisi lembar pencocokan, menandai sumber setiap nilai (setpoint atau aktual), dan meminta review atas marker **[NEEDS PROJECT REVIEW: GATE-01 s.d. GATE-13]** sebelum pengelasan berjalan. Operating rule-nya sederhana: bila angka, kondisi sambungan, atau bukti rekaman tidak cocok, jangan mengompensasi dengan feeling—tahan pekerjaan sampai prosedur dan persetujuan yang benar tersedia.

---
article_id: WLD-17-A04
writing_contract_version: "native-id-v2"
title: "Mengurangi Scrap dan Rework di Bengkel Las dengan Mengukur Penyebab"
slug: "mengurangi-scrap-dan-rework-las"
description: "Panduan mengodekan cacat dan rework, menghitung first-pass yield, serta menelusuri material, jam kerja, energi, Pareto, penahanan, eksperimen, dan pemeliharaan hasil."
status: draft
publication_date: "2026-07-18"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: WLD-17
primary_intent: "Improve process using defect data"
reader_community: "Bengkel-las.co.id"
reader_address: "Sobat Bengkel-las.co.id"
final_route: "/artikel/mengurangi-scrap-dan-rework-las.html"
technical_review: required
sources:
  - "https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999"
  - "https://www.iso.org/standard/83335.html"
  - "https://www.iso.org/standard/54936.html"
  - "https://www.iso.org/standard/75614.html"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026"
  - "https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021"
  - "https://www.iso.org/standard/51792.html"
  - "https://www.iso.org/standard/80209.html"
  - "https://www.iso.org/standard/85705.html"
---

# Mengurangi Scrap dan Rework di Bengkel Las dengan Mengukur Penyebab

Halo, Sobat Bengkel-las.co.id! Scrap dan rework paling cepat berkurang ketika setiap kejadian dicatat sebagai data proses, bukan sebagai alasan untuk menyalahkan orang. Mulailah dengan membedakan benda yang harus dibuang (scrap) dari benda yang masih dapat diperbaiki (rework), lalu kodekan kapan dan bagaimana masalah ditemukan. Dari catatan itu Anda dapat menghitung *first-pass yield* (FPY), memisahkan kehilangan material, jam kerja, dan energi, kemudian memilih penyebab yang paling layak diuji.

Jawaban singkatnya: tetapkan definisi dan batas pengukuran, ambil data yang dapat ditelusuri ke item atau sambungan, urutkan penyebab dengan Pareto, lakukan containment sebelum barang terlanjur dilepas, dan uji satu perubahan yang disetujui. Kesimpulan dapat berubah bila gambar, basis penerimaan, metode inspeksi, kondisi lokasi, atau personel/prosedur pengelasan ternyata berbeda. Karena paket proyek dan data dasar belum tersedia, angka penghematan atau tingkat cacat tidak boleh diasumsikan.

<!-- BEGIN MANAGED IMAGE PLAN
Image ID: LOCAL-001
Source type: local
Placement: after the opening, before the first detailed H2
**Exact Markdown to insert:** `![Ilustrasi bengkel las](/wp-content/uploads/2019/10/bengkel-las.png)`
Caption/credit: Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
Selection basis: filename/source metadata identifies bengkel las as relevant content media; no pixels were inspected.
Boundary: do not infer visual details, project ownership, location, people, brands, condition, performance, or outcome.
END MANAGED IMAGE PLAN -->
![Ilustrasi bengkel las](/wp-content/uploads/2019/10/bengkel-las.png)

Ilustrasi umum dari aset lokal Bengkel-las.co.id; bukan dokumentasi proyek tertentu.

## Hasil akhir dan prasyarat

Hasil yang dicari bukan sekadar grafik cacat yang turun, melainkan keputusan yang bisa diaudit: item mana yang ditahan, mengapa diputuskan scrap atau rework, siapa yang menyetujui, dan apa yang diubah pada proses. Manajer bengkel perlu menunjuk pemilik data (misalnya pengawas mutu), orang yang boleh melepas atau menahan produk, serta jalur persetujuan bila perubahan menyentuh gambar, WPS, material, atau urutan kerja.

Siapkan kartu kerja atau *traveler*, gambar dan revisinya, catatan material dan consumable, log mesin, laporan inspeksi, serta catatan jam kerja. Untuk setiap kejadian, simpan identitas item atau sambungan, tanggal, tahap deteksi, kode cacat, disposisi, bukti foto atau laporan, dan persetujuan. Standar mutu pengelasan membedakan prosedur, kualifikasi personel, inspeksi, dan penerimaan; abstrak ISO 3834-6, ISO 9606-1, dan ISO 9712 dapat menjadi rujukan untuk menata rekaman, tetapi tidak membuktikan bahwa suatu proyek atau orang tertentu telah memenuhi persyaratan ([ISO 3834-6](https://www.iso.org/standard/83335.html), [ISO 9606-1](https://www.iso.org/standard/54936.html), [ISO 9712](https://www.iso.org/standard/75614.html)).

Jika Anda sedang membagi pekerjaan antara tim internal dan penyedia jasa, gunakan juga [panduan memilih bengkel las profesional dan berpengalaman](/update/tips-memilih-bengkel-las-profesional-dan-berpengalaman) untuk memeriksa bukti yang perlu diminta. Tautan itu membantu tahap prasyarat; keputusan scrap dan rework tetap harus memakai data item yang sedang dikerjakan.

Tetapkan juga unit analisis sebelum menghitung. Satu unit dapat berupa sambungan, komponen, atau pesanan, asalkan dipakai konsisten. Tandai apakah data berasal dari produksi baru, perbaikan, atau inspeksi ulang. [NEEDS GATE-02: baseline jumlah unit, definisi unit, dan riwayat cacat proyek] harus diisi dari catatan aktual; tanpa itu, FPY dan Pareto hanya menjadi contoh metode, bukan ukuran kinerja bengkel.

## Langkah 1 — tetapkan batas kerja

Mulai dari satu keluarga pekerjaan yang batasnya jelas. Petakan masukan (gambar, material, consumable, jig), proses (potong, fit-up, las, pembersihan, inspeksi), keluaran, dan antarmukanya dengan pengecatan, perakitan, atau pekerjaan lapangan. Jangan mencampur pekerjaan dengan basis penerimaan yang berbeda dalam satu grafik. Jika pengelasan berpindah ke lokasi, akses, posisi, cuaca, listrik, paparan fume, dan pemeriksaan dapat berubah; keputusan tersebut memerlukan kontrol tugas dan persetujuan K3 yang sesuai, bukan hanya alasan transportasi ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970), [Permenaker No. 11 Tahun 2026](https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026)).

Berikan kode yang cukup rinci untuk menemukan pola, tetapi tidak begitu banyak sampai operator mengisinya asal. Contoh rancangan kode internal:

- **Jenis kejadian:** `SCRAP` bila tidak dipakai sesuai keputusan yang disetujui; `REWORK` bila perlu pekerjaan tambahan sebelum diterima; `HOLD` bila status belum dapat diputuskan.
- **Keluarga masalah:** `DIM` (dimensi atau geometri), `FIT` (fit-up), `WELD` (indikasi atau ketidaksesuaian las), `MAT` (material/consumable), `DOC` (dokumen atau identifikasi), dan `OTHER` untuk kasus yang belum terurai.
- **Tahap temuan:** sebelum las, saat proses, inspeksi akhir, atau setelah serah-terima internal. Tahap ini membantu membedakan pencegahan dari deteksi terlambat.

Tambahkan kolom “penyebab terkonfirmasi” dan “hipotesis” secara terpisah. Distorsi, misalnya, boleh menjadi hipotesis sampai ukuran, urutan pekerjaan, kondisi pengekangan, dan catatan proses diperiksa. Jangan mengubah nama pengelas menjadi kode penyebab; scope artikel ini mengecualikan menyalahkan pengelas tanpa bukti akar masalah.

Untuk pekerjaan arsitektural dengan material yang berbeda, [ringkasan bahan teralis jendela las yang umum di pasaran](/update/3-bahan-teralis-jendela-las-yang-umum-di-pasaran) dapat dipakai sebagai pertanyaan awal tentang identitas material. Jangan menyalin pilihan material dari sana ke proyek lain tanpa mencocokkannya dengan gambar, spesifikasi, dan persetujuan teknis.

## Langkah 2 — kumpulkan dan cocokkan bukti

### Bangun catatan yang bisa dihitung

Satu baris log minimal memuat ID item, revisi gambar, kode kejadian, tahap deteksi, hasil inspeksi, keputusan (pakai, rework, scrap, atau hold), jam kerja langsung, dan berat material yang terpakai atau terbuang bila dapat ditimbang. Catat juga siapa yang menemukan dan siapa yang menyetujui disposisi. Bila suatu catatan merujuk ke laporan NDT atau alat ukur, simpan identitas laporan dan status verifikasi alat; abstrak ISO 5817 dan ISO 17635 menekankan bahwa tingkat mutu, metode pemeriksaan, indikasi, dan penerimaan adalah hal yang berbeda ([ISO 5817](https://www.iso.org/standard/80209.html), [ISO 17635](https://www.iso.org/standard/85705.html)). Jangan menyalin nilai batas dari abstrak standar atau menganggap kartu personel sebagai penerimaan produk.

Pisahkan tiga jenis kehilangan agar keputusan tidak bias:

1. **Material.** Timbang offcut, benda scrap, consumable yang terpakai untuk perbaikan, atau gunakan catatan stok yang dapat ditelusuri. Laporkan satuan dan metode pencatatan; jangan mengubah perkiraan volume menjadi massa tanpa dasar.
2. **Tenaga kerja.** Catat jam untuk pemeriksaan tambahan, pembongkaran, persiapan ulang, pengelasan ulang, pembersihan, dan inspeksi penutupan. Jam lembur atau waktu tunggu boleh dicatat sebagai dampak terpisah.
3. **Energi dan utilitas.** Gunakan pembacaan meter bila tersedia. Jika tidak, simpan runtime mesin dan asumsi yang disetujui sebagai “proxy”, bukan konsumsi terukur. Hindari klaim penurunan energi sebelum ada perbandingan periode yang setara.

### Hitung FPY tanpa menyembunyikan rework

FPY adalah proporsi unit yang diterima pada pemeriksaan pertama dibandingkan seluruh unit yang masuk ke tahap pemeriksaan itu. Tulis rumus dan denominator di dashboard, misalnya `FPY = unit diterima pertama kali / seluruh unit yang diperiksa`. Unit yang lolos setelah diperbaiki tidak masuk pembilang FPY; tampilkan metrik rework terpisah. Tambahkan jumlah scrap, jam rework per unit, material terbuang, dan item yang masih *hold*. Dengan begitu, FPY tidak tampak membaik hanya karena pemeriksaan dilewati atau definisi unit diubah.

### Gunakan Pareto sebagai pemilih eksperimen

Kelompokkan data menurut kode masalah, lalu urutkan berdasarkan ukuran yang relevan: jumlah kejadian, jam rework, massa material, atau biaya internal yang benar-benar tercatat. Grafik Pareto membantu memilih sedikit kategori dengan dampak terbesar; ia tidak membuktikan akar penyebab. Saat dua kode memiliki dampak berbeda, buat dua tampilan—frekuensi dan dampak—agar cacat yang jarang tetapi mahal tidak hilang.

Kawan Bengkel-las.co.id, tanyakan tiga hal pada setiap batang terbesar: “di tahap mana ditemukan?”, “bukti apa yang mendukung penyebabnya?”, dan “perubahan mana yang berada dalam kendali scope ini?”. Bila jawabannya masih dugaan, pertahankan status hipotesis dan lakukan pengamatan tambahan, bukan vonis kepada individu.

## Langkah 3 — jalankan urutan kerja

Urutan praktisnya adalah **deteksi, containment, diagnosis, eksperimen, lalu standardisasi**.

**Deteksi dan containment.** Begitu pola cacat terlihat, tahan item yang berpotensi terdampak, beri identitas status, dan cegah pencampuran dengan produk yang sudah diterima. Amankan area serta bukti sebelum penggerindaan atau perbaikan mengubah kondisi awal. Containment bukan keputusan scrap; itu jeda agar orang berwenang menentukan pemeriksaan dan disposisi. Bila pekerjaan menyentuh sumber energi, area panas, bahan kimia, atau ruang terbatas, hentikan dan minta penilaian K3 spesifik. Aturan keselamatan kerja Indonesia dan status regulasi harus diperiksa terhadap kondisi aktual, bukan digantikan prosedur generik ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970), [Permenaker No. 11 Tahun 2026](https://peraturan.bpk.go.id/Details/351282/permenaker-no-11-tahun-2026)).

**Diagnosis.** Cocokkan kode dengan gambar revisi, material, WPS atau instruksi kerja yang berlaku, kondisi peralatan, log consumable, urutan fit-up, dan hasil inspeksi. Bedakan penyebab langsung (misalnya salah identifikasi) dari kondisi sistem (label tidak terbaca, revisi tidak terkunci, atau alat ukur belum diverifikasi). Sebelum menyebut “cacat”, pastikan basis penerimaan dan metode pemeriksaan memang berlaku untuk sambungan tersebut. [NEEDS GATE-04/GATE-07: basis desain/penerimaan, metode inspeksi, dan rekaman pengukuran proyek] harus disetujui pihak yang berwenang.

**Eksperimen terkendali.** Pilih satu perubahan yang menjawab hipotesis terbesar—misalnya memperjelas titik pemeriksaan fit-up atau mengunci identifikasi revisi—dan tetapkan indikator sebelum menjalankannya. Bandingkan kelompok pekerjaan yang sebanding dengan periode sebelumnya, catat perubahan lain yang terjadi, dan hentikan bila mutu, keselamatan, atau ketertelusuran memburuk. Jangan mengubah parameter las, material, atau prosedur berkualifikasi tanpa persetujuan teknis; kualifikasi prosedur dan personel memiliki cakupan masing-masing dan bukan tiket bebas untuk semua pekerjaan ([ISO 15614-1](https://www.iso.org/standard/51792.html), [ISO 9606-1](https://www.iso.org/standard/54936.html)).

**Standardisasi dan sustainment.** Jika hasil uji mendukung hipotesis, ubah instruksi kerja, formulir, titik pemeriksaan, atau pelatihan yang relevan melalui pengendalian revisi. Tinjau kembali kode dan denominator FPY agar tetap konsisten. Jadwalkan tinjauan berkala berdasarkan data aktual, bukan target yang dibuat-buat; pertahankan grafik Pareto, daftar tindakan, pemilik, tanggal tinjau, dan bukti efektivitas. Bila pola kembali muncul, buka lagi diagnosisnya—jangan otomatis mengulang rework yang sama.

## Titik henti dan kondisi berhenti

Hentikan pelepasan produk dan eskalasi bila identitas item atau revisi tidak jelas, status inspeksi bertentangan, cacat berulang belum memiliki penyebab teruji, atau perubahan proses memengaruhi desain, keselamatan, pressure boundary, lifting, rotating equipment, atau fungsi penting. Pekerjaan juga berhenti bila kondisi lokasi berubah sehingga kontrol K3 semula tidak lagi berlaku. [NEEDS GATE-01/GATE-05/GATE-06/GATE-08: aturan yang berlaku, persetujuan intervensi, proses/personel, dan kontrol tugas-lokasi] harus ditutup oleh penanggung jawab proyek dan K3 sebelum lanjut.

Containment tidak menghapus kewajiban menyimpan bukti. Jangan membuang benda yang menjadi bukti sengketa atau ketidaksesuaian sebelum ada keputusan disposisi dan pencatatan. Tanggung jawab teknis, kontraktual, perlindungan konsumen, dan proses hukum adalah pertanyaan berbeda; jangan menjanjikan refund, bebas cacat, atau hasil sengketa dari grafik cacat saja ([UU No. 8 Tahun 1999](https://peraturan.bpk.go.id/Details/45288/uu-no-8-tahun-1999)).

## Verifikasi hasil dan serah terima

Sebelum menutup satu siklus perbaikan, cocokkan daftar item dengan status terakhirnya: diterima pada pemeriksaan pertama, diterima setelah rework, scrap, atau masih hold. Lampirkan kode penyebab, jam, material, proxy energi bila ada, hasil inspeksi, foto atau laporan yang diizinkan, tindakan koreksi, dan persetujuan. Paket serah-terima yang baik menyebut item, revisi, penerbit, tanggal, basis penerimaan, hasil, dan pihak yang mengesahkan; checklist kosong atau sertifikat umum tidak membuktikan kecocokan suatu produk ([ISO 3834-6](https://www.iso.org/standard/83335.html)).

Untuk limbah, pisahkan sumber dan identitasnya, tandai kontaminasi yang diketahui, dan dokumentasikan jalur penyerahan. Jangan menganggap semua potongan logam otomatis boleh dicampur atau didaur ulang. Klasifikasi, penyimpanan, pengangkutan, penerima, dan pencatatan harus mengikuti karakterisasi serta ketentuan Indonesia yang berlaku; [NEEDS GATE-12: rute limbah dan pihak penerima yang berwenang] wajib diverifikasi sebelum ada klaim manfaat lingkungan ([PP No. 22 Tahun 2021](https://peraturan.bpk.go.id/Details/161852/pp-no-22-tahun-2021)).

Review sustainment dengan pertanyaan sederhana: apakah definisi scrap/rework tetap sama, apakah denominator FPY masih lengkap, apakah kode terbesar bergeser, dan apakah tindakan benar-benar mencegah pengulangan? Jika tidak ada bukti, kembalikan item ke status hold dan minta review teknis, bukan menghapus baris dari dashboard.

## Jalan pintas yang sering menggoda

Jalan pintasnya adalah menggabungkan semua temuan menjadi “kesalahan pengelasan” lalu mengejar angka rework serendah mungkin. Cara itu tampak cepat, tetapi menghapus tahap deteksi, biaya material, waktu inspeksi, serta kondisi desain dan dokumen. Rework yang tidak dikodekan juga dapat membuat FPY terlihat tinggi. Alternatif yang lebih andal adalah memakai kode terbatas namun konsisten, menyimpan hipotesis terpisah dari penyebab terkonfirmasi, dan menahan item sampai ada keputusan. Perubahan target atau bonus sebaiknya mengikuti data yang dapat diaudit, bukan mendorong orang menyembunyikan temuan.

## Kesimpulan dan langkah berikutnya

Mengurangi scrap dan rework di bengkel las berarti mengukur penyebab dari unit pertama yang masuk proses sampai status handover: kodekan kejadian, hitung FPY tanpa memasukkan rework sebagai lolos pertama, pisahkan material–jam kerja–energi, pilih fokus dengan Pareto, lakukan containment, lalu uji perubahan yang disetujui dan pertahankan lewat rekaman.

Teman Bengkel-las.co.id, ambil satu keluarga pekerjaan dan buat log awal berisi ID item, revisi, tahap temuan, kode, disposisi, jam, serta material. Minta pengawas mutu dan penanggung jawab teknis menetapkan basis penerimaan, metode inspeksi, dan batas hold sebelum grafik dipakai untuk keputusan. Jika data dasar, aturan K3, persetujuan desain, atau rute limbah belum tersedia, tinggalkan penanda `[NEEDS ...]` dan lakukan review kompeten. Aturan operasinya sederhana: tidak ada perubahan proses atau pelepasan produk hanya karena angka terlihat membaik; bukti dan persetujuan harus ikut membaik.

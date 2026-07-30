---
article_id: WLD-11-A02
title: "Kerf, Heat-Affected Zone, dan Edge Quality pada Pemotongan Termal"
slug: "kerf-haz-dan-kualitas-tepi-potong"
description: "Panduan memahami kerf, taper, dross, HAZ, distorsi, pengukuran, dan dampaknya pada pengelasan"
status: draft
publication_date: "2026-02-18"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: WLD-11
primary_intent: "Specify thermally cut edge quality"
reader_community: "Bengkel-las.co.id"
reader_address: "Teman Bengkel-las.co.id"
final_route: "/artikel/kerf-haz-dan-kualitas-tepi-potong.html"
technical_review: required
writing_contract_version: "native-id-v2"
sources:
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
  - "https://www.iso.org/standard/83335.html"
  - "https://www.iso.org/standard/51792.html"
  - "https://www.iso.org/standard/54936.html"
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/75614.html"
---

# Kerf, Heat-Affected Zone, dan Edge Quality pada Pemotongan Termal

<!-- BEGIN MANAGED IMAGE PLAN
Image ID: LOCAL-001
Source type: local
Placement: after the opening answer and before the first H2
**Exact Markdown to insert:** `![Ilustrasi bengkel las](/wp-content/uploads/2019/10/bengkel-las.png)`
Caption/credit: Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
Selection basis: filename/source metadata only; no pixels inspected.
Hard boundary: do not infer visual details, ownership, location, people, brands, condition, performance, or outcome.
END MANAGED IMAGE PLAN -->

Halo, Teman Bengkel-las.co.id!

Tepi hasil potong termal tidak bisa dinilai dari satu hal saja. **Kerf** menunjukkan bagian material yang hilang karena proses potong, sedangkan kualitas tepi juga dipengaruhi taper (kemiringan sisi potong), dross (lelehan yang membeku dan menempel), pola kekasaran, HAZ (*heat-affected zone*, zona terpengaruh panas), dan distorsi. Untuk komponen yang akan dirakit atau dilas, pertanyaan yang benar bukan “sudah terpotong belum?”, melainkan “apakah geometri, kondisi permukaan, dan bukti pemeriksaannya sesuai gambar serta fungsi?”

Jawaban praktisnya: tetapkan dulu datum, material, tebal, toleransi, kondisi tepi, dan kebutuhan sambungan pada gambar atau spesifikasi; lalu ukur dan catat hasil pada bagian yang benar-benar diterima. Tanpa dasar penerimaan itu, saya tidak dapat memberi angka universal untuk kerf, taper, HAZ, atau kekasaran. **[NEEDS SPECIFICATION REVIEW: toleransi dan acceptance edge belum tersedia]**. Nilai proses, jenis material, ketebalan, dan fungsi sambungan dapat mengubah keputusan.

![Ilustrasi bengkel las](/wp-content/uploads/2019/10/bengkel-las.png)

Ilustrasi umum dari aset lokal Bengkel-las.co.id; bukan dokumentasi proyek tertentu.

## Jawaban singkat dan salah paham utama

Kerf adalah lebar jalur material yang terbuang oleh sumber panas dan aliran pembawa lelehan. Ia bukan otomatis sama dengan selisih ukuran nominal pada gambar, karena posisi lintasan, kompensasi program, dan bentuk sisi potong ikut menentukan ukuran akhir. Taper berarti sisi potong tidak tegak lurus sempurna terhadap permukaan; bandingkan sisi atas dan bawah, bukan hanya satu titik ukur. Dross adalah sisa lelehan yang membeku di tepi. Dross yang sudah digerinda pun tidak membuktikan bahwa taper atau dimensi sudah benar.

Roughness (kekasaran) pada tepi termal adalah ketidakrataan atau pola garis hasil gerak sumber panas. Pola yang tampak rapi belum tentu memenuhi fungsi tertentu, dan permukaan yang tampak kasar belum dapat dinyatakan gagal tanpa kriteria pada dokumen kerja. HAZ adalah daerah di sebelah garis potong yang menerima siklus panas tetapi tidak meleleh seluruhnya. HAZ pemotongan bukan HAZ las; artikel ini tidak menilai metalurgi HAZ las atau menetapkan perlakuan panas.

Salah paham yang sering mahal adalah menyamakan “bisa dipasang” dengan “sudah berkualitas”. Bagian mungkin masih dapat dipaksa masuk, tetapi taper, distorsi, atau HAZ yang tidak ditinjau dapat mengubah celah, posisi datum, dan persiapan sambungan. Sobat Bengkel-las.co.id, hentikan keputusan pass/fail ketika gambar tidak menyebutkan basis penerimaan; minta klarifikasi tertulis dari pihak desain atau pemeriksa yang berwenang.

## Definisi dan batas objek

Objek yang dinilai adalah tepi hasil pemotongan termal pada pelat, lembaran, atau profil sebelum proses berikutnya. Catat sedikitnya lima lapisan informasi:

1. **Geometri:** ukuran aktual terhadap datum, kelurusan, sudut taper, radius sudut, dan perubahan bentuk akibat panas.
2. **Permukaan:** dross, lekukan lokal, retak yang terlihat, oksida, dan pola roughness. Istilah “retak” harus dibuktikan lewat pemeriksaan yang sesuai, bukan sekadar perubahan warna.
3. **Zona panas:** lokasi serta lebar HAZ bila memang disyaratkan untuk aplikasi. Lebar HAZ tidak boleh ditebak dari warna permukaan saja.
4. **Kesiapan sambungan:** kebutuhan bevel, root face, celah, pembersihan, dan akses untuk pengelasan atau perakitan.
5. **Bukti:** identitas bagian, revisi gambar, material dan tebal, mesin/proses, tanggal, alat ukur, hasil, serta disposisi bila ada penyimpangan.

Batasnya penting: halaman ini tidak menetapkan angka penerimaan, tidak menggantikan standar berlisensi atau spesifikasi proyek, dan tidak memutuskan kelayakan struktur, bejana, pengangkatan, atau komponen keselamatan. Katalog BSN untuk SNI 1729:2020 hanya mengidentifikasi dokumen; rincian toleransi dan penerimaan harus diambil dari teks berlisensi dan dokumen *issued for work*.

## Cara kerjanya

Mulai dari paket fabrikasi, bukan dari setelan mesin yang diingat operator. Paket terkendali sebaiknya menghubungkan dokumen dan revisi, fungsi, datum, identitas material, toleransi, urutan fabrikasi, kebutuhan las, titik inspeksi, basis penerimaan, serta deviasi yang disetujui. Kerangka perencanaan seperti ini sejalan dengan ruang lingkup panduan mutu fabrikasi pada abstrak [ISO 3834-6:2024](https://www.iso.org/standard/83335.html) dan identitas standar struktur baja pada katalog resmi [SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020).

Setelah material dan tebal diverifikasi, operator memilih proses serta parameter berdasarkan prosedur yang berlaku. Sumber panas bergerak sepanjang lintasan; sebagian material mencair, sebagian panas merambat ke sisi, dan aliran gas atau media pembawa membantu mengeluarkan lelehan. Interaksi kecepatan gerak, energi, fokus atau jarak kerja, kondisi nosel, dukungan benda kerja, dan ventilasi menghasilkan kerf, taper, dross, roughness, HAZ, serta distorsi yang berbeda. Anggap ini sebagai hubungan sebab-akibat yang perlu dibuktikan lewat kupon atau pemeriksaan bagian, bukan sebagai angka baku lintas mesin.

Urutan pemeriksaan kemudian mengikuti fungsi. Bersihkan material lepas tanpa mengubah datum, ukur geometri dari referensi yang sama dengan gambar, periksa permukaan dengan metode yang ditentukan, dan dokumentasikan hasilnya sebelum perakitan. Untuk pemeriksaan yang lebih dari sekadar visual, [ISO 17635:2025](https://www.iso.org/standard/85705.html) menempatkan metode, teknik, cakupan, kondisi permukaan, personel, peralatan, pelaporan, dan basis penerimaan sebagai hal yang terpisah. Sertifikasi personel pemeriksaan juga memiliki ruang lingkup sendiri; abstrak [ISO 9712:2021](https://www.iso.org/standard/75614.html) tidak boleh dipakai untuk mengklaim bahwa seluruh produk otomatis memenuhi syarat.

## Faktor yang mengubah hasil

Beberapa faktor perlu ditulis sebagai variabel proyek, bukan asumsi tersembunyi:

- **Material dan tebal.** Konduktivitas panas, komposisi, lapisan permukaan, serta perubahan tebal mengubah cara panas mengalir. Jangan memindahkan setelan dari material lain tanpa verifikasi.
- **Proses dan parameter.** Jenis sumber panas, energi, kecepatan lintasan, fokus/jarak, gas, dan kondisi nosel memengaruhi bentuk kerf serta pelepasan lelehan. Catat revisi program atau prosedur agar hasil dapat ditelusuri.
- **Geometri.** Lubang kecil, sudut tajam, kontur panjang, dan perubahan arah memberi waktu pemanasan yang berbeda. Jembatan penahan atau urutan potong dapat mengurangi gerak, tetapi juga meninggalkan pekerjaan pemisahan yang harus dikendalikan.
- **Penumpuan dan restraint.** Pelat yang tertahan tidak memuai seperti pelat bebas. Setelah panas hilang, penyusutan tidak seragam dapat membuat bagian melengkung atau datum bergeser.
- **Kondisi tepi untuk proses berikutnya.** Coating, oksida, dross, atau gerinda berlebih dapat mengubah celah dan luas penampang efektif. Untuk sambungan las, tetapkan siapa yang menyiapkan bevel, berapa material yang boleh diambil, dan kapan inspeksi ulang dilakukan.
- **Lingkungan dan keselamatan.** Pemotongan di lapangan mengubah akses, listrik, fume, cuaca, api, dan inspeksi. Metode yang aman di bengkel tidak otomatis aman di lokasi; penilaian K3 setempat tetap diperlukan.

Kawan Bengkel-las.co.id, minta catatan material, tebal, proses, program, dan hasil ukur disatukan dengan identitas bagian. Tanpa jejak itu, Anda mungkin hanya bisa melihat gejala, bukan membandingkan penyebab ketika satu lot berbeda dari lot lain.

## Contoh keputusan praktis

Gunakan tabel berikut sebagai cara bertanya, bukan sebagai pengganti acceptance criteria proyek.

| Situasi bagian | Pertanyaan pemeriksaan | Keputusan sementara |
| --- | --- | --- |
| Tepi untuk penutup atau bracket non-kritis | Apakah ukuran terhadap datum, sudut, dan dross sesuai gambar? | Lanjut hanya setelah pemeriksa menyatakan kondisi tepi dan dimensi dapat diterima. |
| Tepi yang menjadi muka sambungan las | Apakah bevel/root face, celah, kebersihan, taper, dan distorsi tercatat? | Tahan fit-up bila salah satunya belum punya kriteria atau hasil ukur. |
| Bagian dengan fungsi struktur atau beban | Siapa yang menetapkan basis penerimaan dan pemeriksaan tambahan? | Minta tinjauan desain/QA; jangan menyimpulkan fitness dari foto atau satu ukuran. |

Misalnya, dua bagian memiliki lebar kerf yang tampak serupa. Bagian A tetap pas pada jig, sedangkan Bagian B memiliki taper dan distorsi sehingga datum bergeser. Keputusan tidak boleh didasarkan pada kerf saja; ukur datum, sudut, dan bentuk aktual. Sebaliknya, tepi yang tampak buruk dapat memiliki allowance pemesinan yang memang ditetapkan gambar. Hanya dokumen proyek yang dapat membedakan cacat dari kondisi yang masih diizinkan.

Untuk sambungan las, pisahkan tiga catatan: kondisi tepi sebelum pengelasan, prosedur pengelasan yang dipakai, dan hasil pemeriksaan sambungan. [ISO 15614-1:2017](https://www.iso.org/standard/51792.html) membahas kualifikasi prosedur, sementara [ISO 9606-1:2012](https://www.iso.org/standard/54936.html) membahas kualifikasi juru las; keduanya tidak membuktikan bahwa setiap tepi potong atau setiap sambungan tertentu otomatis diterima.

Jika bagian memerlukan pembentukan lanjutan, bandingkan kebutuhan geometri hasil potong dengan proses [bending besi dan pelat](/bending/) sebelum menetapkan allowance atau urutan kerja.

## Kesalahan umum dan cara memeriksanya

1. **Mengukur satu sisi dengan jangka sorong lalu menyatakan selesai.** Ukur terhadap datum, pada beberapa lokasi yang ditetapkan, dan simpan orientasi atas-bawah agar taper tidak tersembunyi.
2. **Menganggap dross adalah satu-satunya masalah.** Setelah dross dibersihkan, periksa lagi dimensi, sudut, radius, distorsi, dan kondisi permukaan.
3. **Menyebut perubahan warna sebagai HAZ atau retak.** Warna hanya petunjuk awal. Jika HAZ atau indikasi retak memengaruhi keputusan, gunakan metode pemeriksaan dan personel yang ruang lingkupnya sesuai; ISO 17635 menegaskan bahwa metode dan acceptance basis bukan hal yang sama.
4. **Menyalin parameter dari pekerjaan lama.** Variasi material, tebal, mesin, gas, penumpuan, dan program dapat mengubah hasil. Minta rekaman yang menghubungkan parameter dengan identitas bagian.
5. **Menulis “sesuai SNI/ISO” tanpa dokumen penerimaan.** Katalog standar hanya menunjukkan identitas dan status publik dokumen; ia tidak memberi toleransi proyek atau membuktikan hasil bagian tertentu.
6. **Mencampur hasil potong dan hasil las.** Tepi potong, HAZ pemotongan, WPS, kualifikasi juru las, dan acceptance sambungan adalah catatan berbeda. Satukan hanya melalui prosedur dan nomor bagian yang dapat ditelusuri.

Checklist ringkas sebelum bagian dilepas dari area potong:

- [ ] Revisi gambar, material, tebal, dan nomor bagian cocok.
- [ ] Datum, ukuran kritis, taper, dan distorsi diukur dengan alat yang teridentifikasi.
- [ ] Dross/oksida dibersihkan sesuai instruksi tanpa mengurangi allowance yang disyaratkan.
- [ ] Kondisi tepi untuk bevel atau fit-up dicatat sebelum tack weld.
- [ ] Penyimpangan ditahan dan diajukan untuk disposisi; tidak ditutup dengan gerinda atau las tambahan tanpa persetujuan.

## Jalan pintas yang perlu dihindari

“Yang penting bisa dilas; nanti digerinda.” Shortcut ini gagal ketika gerinda mengurangi root face atau ukuran, mengubah sudut, menutupi indikasi, atau memindahkan masalah ke fit-up. Gerinda juga tidak mengembalikan material yang sudah hilang karena kerf atau taper. Alternatif yang lebih aman adalah menetapkan allowance dan batas pembersihan pada gambar, mencatat siapa yang mengerjakan persiapan tepi, lalu melakukan ukur ulang sebelum pengelasan. Jika dokumen belum menyebutkan batas tersebut, tandai **[NEEDS EDGE-PREPARATION CRITERIA]** dan minta keputusan teknis.

## Kesimpulan

Kerf, taper, dross, roughness, HAZ, dan distorsi adalah tanda berbeda dari satu riwayat panas; kualitas tepi hanya dapat diputuskan dengan mengaitkan tanda itu ke datum, fungsi, spesifikasi, dan bukti pemeriksaan. Tidak ada angka penerimaan universal yang aman untuk semua proses dan ketebalan.

Langkah berikutnya adalah meminta paket kerja yang memuat revisi gambar, material/tebal, datum, toleransi, kondisi tepi, kebutuhan bevel atau fit-up, metode pemeriksaan, dan pihak yang berwenang menerima deviasi. Simpan rekaman ukur bersama identitas bagian, lalu minta tinjauan teknis untuk komponen yang memikul beban atau memiliki konsekuensi keselamatan; bila konteksnya struktur, gunakan halaman [konstruksi baja](/konstruksi-baja/) sebagai titik lanjut layanan, bukan sebagai pengganti basis penerimaan. Untuk menelusuri dokumen dan pembaruan layanan, Anda dapat kembali ke [beranda Bengkel-las.co.id](/). Teman Bengkel-las.co.id, aturan operasinya sederhana: **jangan menyatakan tepi “baik” sebelum kriteria tertulis dan hasil ukur menunjuk pada bagian yang sama.**

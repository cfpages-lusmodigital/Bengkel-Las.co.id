---
article_id: WLD-08-A05
title: "Shielding Gas Terganggu: Mendiagnosis Angin, Kebocoran, Flow, dan Kontaminasi"
slug: "gangguan-shielding-gas-las"
description: "Urutan aman untuk memeriksa lingkungan, sistem tabung, selang, torch, indikasi flow, hembusan, dan kontaminasi permukaan saat shielding gas tidak stabil."
status: draft
publication_date: "2025-12-14"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: WLD-08
primary_intent: "Diagnose shielding instability"
reader_community: "Bengkel-las.co.id"
reader_address: "Kawan Bengkel-las.co.id"
final_route: "/artikel/gangguan-shielding-gas-las.html"
technical_review: required
writing_contract_version: "native-id-v2"
sources:
  - "https://www.iso.org/standard/51792.html"
  - "https://www.iso.org/standard/54936.html"
  - "https://www.iso.org/standard/83335.html"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252"
  - "https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200"

---

<!-- BEGIN MANAGED IMAGE PLAN
- Image ID: `LOCAL-003`
- Source type: `local`
- Placement: setelah jawaban singkat pembuka, sebelum H2 pertama
- **Exact Markdown to insert:** `![Ilustrasi las gas](/wp-content/uploads/2019/10/las-gas.png)`
- Caption/credit: Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- Selection basis: filename/source metadata identifies `las gas` as relevant content media; no pixels were inspected.
- Hard boundary: do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- Substitution rule: jika URL tidak tersedia atau provenance tidak lengkap, gunakan `[NEEDS IMAGE REVIEW: LOCAL-003]`.
END MANAGED IMAGE PLAN -->

# Shielding Gas Terganggu: Mendiagnosis Angin, Kebocoran, Flow, dan Kontaminasi

Halo, Kawan Bengkel-las.co.id! Porositas atau busur yang tiba-tiba tidak stabil tidak otomatis berarti arus dan tegangan salah. Jika shielding gas terganggu, langkah pertama adalah menghentikan tebakan parameter dan mengikuti urutan pemeriksaan: amankan area, amati gejala, cek sumber serta jalur gas, baca flow pada kondisi yang benar, lalu singkirkan angin dan kontaminasi. Temuan pada satu titik belum cukup untuk menyatakan penyebab tunggal.

Jawaban singkatnya: mulai dari hal yang paling aman dan paling mudah dibuktikan. Pastikan pekerjaan tidak terpapar hembusan, tabung dan regulator terpasang sesuai prosedur setempat, selang serta sambungan tidak rusak, torch dan nozzle bersih, dan indikator flow benar-benar menunjukkan aliran ketika gas mengalir. Setelah itu, bandingkan hasil pada benda uji atau sambungan yang permukaannya sudah disiapkan. Bila gejala tetap ada, pekerjaan ditahan untuk pemeriksaan kompeten; artikel ini tidak menggantikan persetujuan proyek atau keputusan penerimaan las.

`[NEEDS IMAGE REVIEW: LOCAL-003]`

*Aset lokal proyek; bukan dokumentasi proyek tertentu.*

## Mulai dari gejala, bukan tebakan penyebab

Catat apa yang terlihat sebelum memutar kenop. Apakah porositas muncul sepanjang jalur, hanya di awal dan akhir, atau setelah torch berhenti sebentar? Apakah busur mendesis, elektroda terasa tertarik, atau bead berubah ketika operator bergeser? Tulis posisi sambungan, proses yang dipakai (GMAW atau GTAW), jenis material menurut dokumen kerja, waktu kejadian, dan perubahan terakhir pada tabung, nozzle, kawat, tungsten, atau pembersihan. Foto permukaan sebelum dibersihkan dan sesudahnya dapat membantu membedakan pengamatan dari dugaan.

Bandingkan satu variabel setiap kali. Jika memindahkan benda kerja sekaligus mengganti flow, nozzle, dan kawat, Anda kehilangan jejak sebab. Uji singkat pada kupon yang sama, dengan prosedur kerja yang disetujui, lebih informatif daripada langsung mengulang sambungan produksi. Simpan identitas mesin, regulator, dan batch consumable yang dipakai; sistem mutu pengelasan menempatkan kondisi peralatan dan pengendalian consumable sebagai bagian dari rekaman yang perlu ditelusuri ([ISO 3834-6:2024](https://www.iso.org/standard/83335.html)).

## Saringan risiko langsung

Sebelum menyentuh sambungan, lihat lingkungan. Batasi akses bila ada orang yang dapat tersandung selang, terkena percikan, atau memasuki area busur tanpa perlindungan. Hentikan pekerjaan jika tabung, regulator, atau sambungan menunjukkan kerusakan yang tidak dapat dinilai aman; jangan membongkar atau memperbaiki komponen bertekanan sebagai eksperimen. Pekerjaan panas juga perlu pengendalian sumber api, material mudah terbakar, ventilasi, dan rencana keadaan darurat yang sesuai kondisi lokasi. Prinsip keselamatan kerja umum Indonesia menuntut pengendalian bahaya di tempat kerja, sementara rujukan OSHA tentang pengelasan menekankan penilaian bahaya kebakaran dan perlindungan area; ketentuan yang berlaku tetap harus ditetapkan oleh penanggung jawab K3 setempat ([UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970), [OSHA 29 CFR 1910.252](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.252)).

Kawan Bengkel-las.co.id, jadikan tiga kondisi berikut sebagai tanda berhenti: tercium kebocoran atau terdengar desis yang tidak terlokalisasi dengan aman; regulator, selang, atau torch panas, retak, dan berubah bentuk; atau hembusan, uap, dan pekerjaan di sekitar membuat shielding tidak dapat dikendalikan. Pada situasi itu, isolasi area dan minta pemeriksaan orang berwenang. `[NEEDS K3 REVIEW: metode isolasi tabung, ventilasi, jarak aman, dan izin pekerjaan harus mengikuti kondisi lokasi serta aturan Indonesia yang berlaku.]`

## Kemungkinan mekanisme

Kelompokkan hipotesis agar pemeriksaan tidak acak. Pertama, shielding bisa terganggu dari luar: pintu terbuka, kipas, aliran udara proses, atau posisi torch terlalu jauh dan terlalu miring. Kedua, gas bisa hilang di jalur: katup belum terbuka penuh, regulator atau flowmeter bermasalah, sambungan longgar, selang tertekuk, atau liner dan torch tidak meneruskan aliran secara konsisten. Ketiga, angka flow dapat menipu bila dibaca saat gas belum mengalir, dibaca pada posisi yang berbeda dari kondisi pengelasan, atau alat ukurnya tidak terverifikasi.

Keempat, gas yang sampai ke kolam las dapat tercampur udara karena nozzle tersumbat spatter, diffuser rusak, atau kebocoran di sekitar torch. Kelima, permukaan benda kerja, kawat, tungsten, dan sarung tangan dapat membawa minyak, air, karat lepas, atau residu coating. Penyebab-penyebab ini dapat muncul bersamaan. Karena itu, “flow sudah sesuai” hanya menjawab satu pengamatan, bukan membuktikan seluruh sistem rapat dan area terlindung.

Jangan mengubah diagnosis menjadi klaim kualifikasi. Kualifikasi prosedur, rentang penerapan, dan kualifikasi juru las/operator adalah catatan berbeda; ISO menyajikannya dalam standar yang berbeda dan abstraknya tidak menggantikan dokumen proyek atau teks berlisensi ([ISO 15614-1:2017](https://www.iso.org/standard/51792.html), [ISO 9606-1:2012](https://www.iso.org/standard/54936.html)).

## Urutan pemeriksaan dan pengujian

Gunakan urutan berikut dan catat hasil tiap langkah.

1. **Amankan dan hentikan sumber variasi.** Tandai sambungan yang bermasalah, hentikan pengelasan bila gejalanya memburuk, dan jauhkan orang yang tidak berkepentingan. Jangan menguji kebocoran dengan api atau membuka komponen bertekanan tanpa kewenangan.
2. **Periksa lingkungan secara langsung.** Rasakan arah hembusan dengan cara yang tidak memasukkan tangan ke jalur bahaya; amati kipas, pintu, tirai, kendaraan, dan pekerjaan yang menghasilkan aliran. Tutup atau kendalikan sumber gangguan hanya jika pengawas mengizinkan. Jika lokasi lapangan berubah karena cuaca atau akses, tahan pekerjaan sampai kontrolnya disetujui.
3. **Cocokkan identitas dan kondisi sumber gas.** Periksa label tabung, status sambungan, posisi tabung, regulator, dan catatan penggantian. Jangan mengasumsikan isi tabung dari warna atau bentuknya. Informasi produk, label, dan lembar data keselamatan perlu dicocokkan dengan bahan yang benar; rujukan OSHA tentang komunikasi bahaya berguna sebagai konsep pencatatan, bukan sebagai pengganti hukum Indonesia ([OSHA 29 CFR 1910.1200](https://www.osha.gov/laws-regs/regulations/standardnumber/1910/1910.1200)).
4. **Telusuri jalur gas tanpa membongkar berisiko.** Ikuti selang dari regulator ke mesin, dari mesin ke torch, dan periksa tekukan, gesekan, klem, sambungan, serta tanda aus. Jika ada dugaan bocor, hentikan dan serahkan uji serta perbaikannya kepada personel kompeten; ruang lingkup artikel ini tidak mencakup perbaikan tabung atau kebocoran.
5. **Periksa torch, nozzle, dan diffuser.** Matikan sumber sesuai prosedur, tunggu aman, lalu lihat sumbatan spatter, perubahan bentuk, isolator, dan pemasangan komponen. Bersihkan dengan alat serta cara yang diizinkan pabrikan atau prosedur kerja; jangan memperbesar lubang nozzle dengan benda yang mengubah geometri.
6. **Baca flow pada kondisi yang dapat dibandingkan.** Pastikan gas memang mengalir ketika indikator dibaca. Catat posisi torch, panjang selang, jenis nozzle, dan kondisi regulator. Ulangi pengamatan dengan konfigurasi yang sama; angka yang meloncat atau tidak konsisten adalah alasan untuk verifikasi alat, bukan alasan menaikkan flow tanpa batas.
7. **Periksa permukaan dan consumable.** Bersihkan minyak, air, karat lepas, dan coating sesuai prosedur material. Pastikan kawat, tungsten, dan sarung tangan tidak menyentuh kontaminan setelah dibersihkan. Catat produk pembersih, batch consumable, dan kondisi penyimpanan bila dipersyaratkan paket fabrikasi.
8. **Lakukan uji pembanding yang disetujui.** Gunakan kupon atau sambungan yang mewakili pekerjaan, satu perubahan per uji. Hentikan bila busur atau lingkungan menjadi tidak aman. Hasil uji hanya menjadi bukti diagnostik sampai dibandingkan dengan WPS, inspeksi, dan kriteria proyek.

## Cara membaca hasil tanpa melompat ke kesimpulan

Buat tabel sederhana dengan kolom *pengamatan*, *kondisi uji*, *dugaan yang didukung*, dan *hal yang belum terbukti*. Misalnya, porositas hilang setelah tirai dipasang mendukung hipotesis hembusan, tetapi tidak membuktikan tidak ada kebocoran. Flow stabil pada regulator belum membuktikan aliran di ujung nozzle. Nozzle bersih belum membuktikan permukaan bebas minyak.

Pisahkan empat keputusan: apakah gejala dapat diulang; apakah penyebab paling mungkin sudah dikendalikan; apakah hasil pengelasan perlu diperiksa ulang; dan siapa yang berwenang menyatakan sambungan diterima. Tingkat mutu atau metode pemeriksaan tidak boleh ditebak dari penampilan bead. Standar seperti ISO 5817 dan ISO 17635 membantu membedakan kriteria ketidaksempurnaan, metode pemeriksaan, dan evaluasi, tetapi nilai penerimaan harus berasal dari standar serta spesifikasi proyek yang berlaku. `[NEEDS PROJECT EVIDENCE: WPS, kriteria penerimaan, dan rencana inspeksi harus ditinjau sebelum sambungan dilepas atau diperbaiki.]`

Teman Bengkel-las.co.id, perlakukan hasil “sudah normal” sebagai status setelah kondisi uji didokumentasikan, bukan sebagai jaminan semua sambungan sebelumnya baik. Sambungan yang dibuat saat shielding terganggu mungkin memerlukan pemeriksaan dan disposisi terpisah oleh pihak yang berwenang.

## Pilihan tindakan dan titik eskalasi

Kontrol sementara boleh berupa memindahkan pekerjaan dari hembusan, mengganti nozzle yang jelas rusak sesuai prosedur, atau menahan sambungan sambil menunggu pemeriksaan. Tindakan itu bukan izin untuk mengubah WPS, menaikkan flow secara sembarang, mencampur gas, atau memperbaiki regulator sendiri. Jika sumber gas, selang, torch, atau flowmeter meragukan, minta teknisi atau penanggung jawab peralatan memeriksa, menguji, dan mencatat statusnya.

Eskalasi juga diperlukan ketika pekerjaan berpindah dari bengkel ke lapangan. Akses, cuaca, listrik, material mudah terbakar, ventilasi, penghuni sekitar, dan inspeksi dapat berubah; keputusan kerja lapangan harus disetujui pengawas dan K3 berdasarkan kondisi aktual, bukan karena pengangkutan dianggap merepotkan. Untuk memilih penyedia kerja yang mampu menunjukkan rekaman dan jalur review, Anda dapat membaca panduan [memilih bengkel las profesional dan berpengalaman](/update/tips-memilih-bengkel-las-profesional-dan-berpengalaman). Sebagai langkah persiapan material, penjelasan tentang [bahan teralis jendela yang umum di pasaran](/update/3-bahan-teralis-jendela-las-yang-umum-di-pasaran) dapat membantu Anda menanyakan identitas material, meski tidak menggantikan verifikasi proyek.

## Jalan pintas yang sering gagal

Jalan pintas paling umum adalah memutar flow lebih tinggi ketika porositas muncul. Cara ini bisa menyamarkan gejala sebentar, tetapi tidak menjawab apakah ada hembusan, sambungan bocor, nozzle tersumbat, atau permukaan kotor. Aliran berlebih juga dapat mengganggu kestabilan dan menghabiskan gas tanpa membuktikan perlindungan di kolam las. Alternatif yang lebih dapat ditelusuri adalah kembali ke urutan: amankan area, cari sumber variasi, periksa jalur dan torch, baca indikator pada kondisi yang sama, lalu uji satu perubahan dengan persetujuan.

## Kesimpulan dan langkah berikutnya

Shielding gas yang terganggu didiagnosis dengan bukti berurutan, bukan dengan satu angka flow atau satu tebakan. Mulai dari gejala dan risiko, cek hembusan serta sumber gas, telusuri selang dan torch, verifikasi indikasi flow, bersihkan kontaminasi, dan dokumentasikan uji pembanding. Jangan memperbaiki tabung atau kebocoran dalam lingkup artikel ini, dan jangan menyatakan las diterima hanya karena busur kembali stabil.

Sebelum melanjutkan produksi, siapkan catatan gejala, identitas peralatan dan consumable, kondisi lingkungan, hasil pemeriksaan, serta pertanyaan untuk penanggung jawab K3 dan pengawas pengelasan. `[NEEDS TECHNICAL REVIEW: keputusan pelepasan, perbaikan, pemeriksaan tambahan, dan penerimaan akhir memerlukan bukti proyek serta otoritas yang ditunjuk.]` Aturan operasinya sederhana: bila penyebab belum dapat dibuktikan aman dan terkendali, tahan pekerjaan dan eskalasikan—jangan menukar ketidakpastian dengan flow yang lebih besar.

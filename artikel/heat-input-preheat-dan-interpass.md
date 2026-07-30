---
article_id: WLD-08-A02
title: "Heat Input, Preheat, dan Interpass: Konsep Termal Tanpa Angka Tebakan"
slug: "heat-input-preheat-dan-interpass"
description: "Memahami pengaruh energi, kecepatan gerak, suhu awal, batas interpass, ketebalan, komposisi, dan restraint pada hasil pengelasan"
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-12-02"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: WLD-08
primary_intent: "Understand thermal controls"
reader_community: "Bengkel-las.co.id"
reader_address: "Sobat Bengkel-las.co.id"
final_route: "/artikel/heat-input-preheat-dan-interpass.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/51792.html"
  - "https://www.iso.org/standard/54936.html"
  - "https://www.iso.org/standard/83335.html"
  - "https://www.iso.org/standard/80209.html"
  - "https://www.iso.org/standard/85705.html"
  - "https://www.iso.org/standard/75614.html"
  - "https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018"
  - "https://pesta.bsn.go.id/produk/detail/12882-sni17292020"
---

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

# Heat Input, Preheat, dan Interpass: Konsep Termal Tanpa Angka Tebakan

Halo, Sobat Bengkel-las.co.id! Saat supervisor melihat angka arus, tegangan, atau suhu pada lembar las, pertanyaan yang penting bukan “angka mana yang paling bagus?”, melainkan “apakah rentang termal ini memang dikualifikasi untuk sambungan yang sedang dikerjakan?” Heat input, preheat, dan interpass saling memengaruhi, tetapi tidak satu pun boleh dipilih dengan menyalin angka dari pekerjaan lain.

Jawaban singkatnya: energi yang masuk sepanjang gerakan las memengaruhi siklus pemanasan dan pendinginan; preheat menentukan kondisi awal; interpass membatasi panas yang menumpuk sebelum lapis berikutnya. Ketebalan, komposisi material, geometri sambungan, dan restraint (tingkat kekangan gerak) mengubah responsnya. Nilai yang boleh dipakai harus berasal dari Welding Procedure Specification (WPS) yang memenuhi kualifikasi prosedur, data material dan sambungan aktual, serta persetujuan teknis proyek. [NEEDS PROJECT EVIDENCE: rentang heat input dan metode penentuannya pada WPS yang disetujui]

Karena itu, “sudah pernah mengelas material yang sama” belum cukup sebagai dasar persetujuan. Kualifikasi prosedur, kualifikasi juru las, pengendalian produksi, inspeksi, dan penerimaan sambungan merupakan rekaman yang berbeda. Ringkasan resmi [ISO 15614-1](https://www.iso.org/standard/51792.html), [ISO 9606-1](https://www.iso.org/standard/54936.html), dan [ISO 3834-6](https://www.iso.org/standard/83335.html) membantu menjaga pembedaan itu. Jika salah satu buktinya hilang, keputusan termal harus ditahan untuk tinjauan yang berwenang.

![Ilustrasi memilih jasa bengkel las](/wp-content/uploads/2020/02/memilih-jasa-bengkel-las.jpg)

Aset lokal proyek. Gambar ini bukan dokumentasi proyek tertentu; jangan membacanya sebagai bukti kondisi, proses, atau hasil pekerjaan tertentu.

## Jawaban singkat dan salah paham utama

Heat input bukan sekadar setelan ampere. Ia menggambarkan energi yang dipindahkan ke sambungan sepanjang laju gerak las, sehingga perubahan energi atau travel speed (kecepatan gerak) dapat mengubah ukuran zona yang menerima panas dan lama pendinginannya. Dua orang dapat memakai arus yang sama tetapi menghasilkan riwayat termal berbeda bila kecepatan geraknya berbeda. Rumus dan faktor efisiensi proses harus mengikuti metode pada WPS atau spesifikasi; artikel ini tidak menetapkan formula persetujuan.

Preheat adalah kondisi suhu awal material sebelum pengelasan dimulai atau dilanjutkan pada area yang dipersyaratkan. Interpass adalah pemeriksaan suhu sambungan sebelum lapis berikutnya didepositkan. Preheat yang terlalu rendah dapat membuat pendinginan terlalu cepat untuk kondisi tertentu; interpass yang terlalu tinggi dapat membuat panas menumpuk. Arah bahayanya tidak universal: material, ketebalan, komposisi, proses, dan kekangan menentukan konsekuensinya. [NEEDS COMPETENT REVIEW: batas preheat dan interpass untuk material, ketebalan, proses, dan sambungan aktual]

Jadi, supervisor perlu menilai rangkaian bukti, bukan mencari satu angka “aman”. Angka pada panel mesin adalah target operasi; yang perlu dibuktikan adalah nilai aktual, cara ukurnya, rentang yang diizinkan, dan tindakan ketika keluar rentang.

## Definisi dan batas objek

Dalam artikel ini, **heat input** berarti cara mengendalikan energi pengelasan relatif terhadap panjang las. **Preheat** berarti kondisi termal sebelum busur bekerja pada area yang ditentukan. **Interpass** berarti titik kendali suhu di antara lapisan. Ketiganya adalah variabel proses yang harus dibaca bersama dengan jenis material, ketebalan efektif, desain kampuh, posisi, consumable, dan urutan kerja.

Yang tidak dibahas di sini adalah menetapkan temperatur minimum atau maksimum, menghitung nilai yang mengikat kontrak, memilih material pengganti, atau menyatakan sambungan lulus. Katalog BSN untuk [SNI 1729:2020](https://pesta.bsn.go.id/produk/detail/12882-sni17292020) hanya menjadi rujukan identitas dokumen; klausul, toleransi, kombinasi beban, dan aturan pelaksanaan tetap harus diperoleh dari standar berlisensi serta dokumen proyek yang diterbitkan untuk kerja.

Batas ini penting saat seseorang meminta “angka umum”. Angka tanpa identitas material, ketebalan, proses, dan edisi dokumen tidak dapat dipindahkan begitu saja. [NEEDS PROJECT EVIDENCE: identitas material, ketebalan, jenis sambungan, dan acceptance basis yang menjadi dasar rentang termal]

## Cara kerjanya

Gunakan urutan berikut ketika meninjau prosedur.

1. **Kunci dokumen yang berlaku.** Cocokkan gambar, revisi, spesifikasi, WPS, rekaman kualifikasi prosedur, serta kebutuhan inspeksi. Jangan memakai salinan lama hanya karena formatnya terlihat sama.
2. **Tentukan objek termalnya.** Catat material dan kondisinya, ketebalan yang benar-benar menerima panas, konfigurasi kampuh, akses, posisi, serta tingkat restraint. Jika salah satu identitas belum pasti, tandai sebagai pertanyaan terbuka.
3. **Baca rentang, bukan satu angka.** WPS seharusnya memberi batas operasi dan cara mengendalikan variabel yang relevan. Pastikan metode pengukuran preheat dan interpass serta lokasi pengukuran dipahami tim.
4. **Siapkan sebelum busur menyala.** Periksa fit-up (penyetelan awal sambungan), kebersihan, kekeringan area, kondisi consumable (bahan tambah), dan alat ukur. Catat suhu awal yang benar-benar diukur, bukan perkiraan dari sentuhan tangan.
5. **Kendalikan selama deposit.** Pantau hubungan energi dan travel speed, lalu ukur interpass sesuai prosedur sebelum lapis berikutnya. Perubahan teknik operator, akses, atau urutan dapat mengubah panas meskipun setelan mesin tidak berubah.
6. **Rekam dan tindak lanjuti penyimpangan.** Simpan nilai aktual, identitas sambungan, operator, alat ukur, dan waktu pemeriksaan. Bila rentang terlampaui, hentikan titik kendali dan minta disposition (keputusan penanganan penyimpangan) dari pihak berwenang; jangan “menetralkan” penyimpangan dengan tebakan pada lapis selanjutnya.
7. **Tutup dengan inspeksi dan penerimaan.** Pemeriksaan visual atau NDT (uji tak merusak) memiliki teknik, personel, rekaman, dan dasar penerimaan masing-masing. [ISO 5817](https://www.iso.org/standard/80209.html), [ISO 17635](https://www.iso.org/standard/85705.html), dan [ISO 9712](https://www.iso.org/standard/75614.html) menunjukkan mengapa tingkat mutu, metode pemeriksaan, serta kompetensi personel tidak boleh dicampur menjadi satu klaim “sudah dicek”.

## Faktor yang mengubah hasil

**Energi dan travel speed.** Menambah energi atau memperlambat gerak cenderung memperpanjang paparan panas pada bagian yang sama; mempercepat gerak dapat mengurangi energi per panjang, tetapi tidak otomatis memperbaiki hasil. Perubahan ini harus dibandingkan dengan rentang WPS dan geometri aktual, bukan dinilai dari suara busur saja.

**Suhu awal dan akumulasi antar-lapis.** Suhu awal yang tidak seragam membuat bagian sambungan mengalami siklus berbeda. Pada las multi-pass, interpass yang diukur di lokasi yang salah bisa memberi rasa aman palsu. Catat lokasi, alat, metode, dan waktu pengukuran agar angka dapat ditelusuri.

**Ketebalan dan komposisi.** Bagian yang lebih tebal biasanya membuang panas dengan cara berbeda dari bagian tipis. Komposisi dan kondisi material juga memengaruhi kepekaan terhadap siklus termal. Jangan mengganti sertifikat material dengan nama dagang atau asumsi “baja biasa”.

**Restraint dan geometri.** Sambungan yang terkekang sulit mengakomodasi penyusutan. Tack, urutan deposit, akses satu sisi, dan detail pertemuan dapat menaikkan kekangan tanpa terlihat dari angka panel. [NEEDS PROJECT EVIDENCE: penilaian restraint, detail sambungan, dan urutan pengelasan pada pekerjaan ini]

**Lingkungan dan antarmuka kerja.** Pekerjaan lapangan dapat mengubah akses, cuaca, catu daya, penyebaran asap, paparan api, aktivitas di sekitar, dan akses inspeksi dibanding fabrikasi terkendali. Kewajiban keselamatan kerja Indonesia tetap berlaku pada kondisi nyata; lihat [UU No. 1 Tahun 1970](https://peraturan.bpk.go.id/Details/47614/uu-no-1-tahun-1970) dan pedoman lingkungan kerja pada [Permenaker No. 5 Tahun 2018](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018). Jangan menganggap pindah lokasi hanya urusan logistik.

**Consumable, alat, dan rekaman.** Klasifikasi serta batch consumable, penyimpanan, kondisi alat ukur, dan pengaturan mesin perlu dapat ditelusuri. Sistem mutu pengelasan membedakan rekaman proses dari hasil akhir; [ISO 3834-6](https://www.iso.org/standard/83335.html) menjadi rujukan publik untuk memahami kebutuhan umum tersebut, bukan pengganti prosedur proyek.

## Contoh keputusan praktis

Gunakan skenario berikut sebagai cara bertanya, bukan sebagai angka persetujuan.

| Temuan saat meninjau | Pertanyaan yang harus dijawab | Keputusan aman sementara |
| --- | --- | --- |
| WPS mencantumkan arus dan tegangan, tetapi tidak menjelaskan metode heat input | Bagaimana energi per panjang dihitung dan direkam untuk proses ini? | Tahan persetujuan sampai metode, rentang, dan rekaman disepakati. |
| Material sama namanya, tetapi ketebalan atau sambungan berbeda | Apakah kualifikasi prosedur mencakup rentang aktual dan restraint ini? | Jangan menyalin setelan lama; minta verifikasi kualifikasi. |
| Operator mengukur “hangat” dengan tangan | Alat apa yang dipakai, di mana lokasinya, dan kapan dibaca? | Hentikan langkah termal sampai pengukuran yang dapat ditelusuri tersedia. |
| Pekerjaan dipindahkan dari workshop ke lapangan | Apa perubahan akses, cuaca, daya, kebakaran, fume, dan inspeksinya? | Minta tinjauan metode kerja dan K3 khusus lokasi. |
| Nilai aktual keluar dari rentang WPS | Siapa yang berwenang menentukan disposition dan pemeriksaan tambahan? | Isolasi sambungan, catat penyimpangan, lalu tunggu keputusan tertulis. |

Kawan Bengkel-las.co.id, tabel ini sengaja tidak memberi temperatur atau travel speed. Tanpa bukti proyek, angka tersebut akan terlihat presisi tetapi dapat menyesatkan.

## Kesalahan umum dan cara memeriksanya

1. **Mengejar produktivitas dengan menaikkan arus.** Periksa juga travel speed, ukuran deposit, urutan, dan dampak akumulasi panas. “Lebih cepat” tidak identik dengan heat input yang sesuai.
2. **Mengandalkan rasa tangan atau warna permukaan.** Gunakan metode dan alat ukur yang ditetapkan prosedur; dokumentasikan titik baca.
3. **Menganggap kartu juru las sebagai izin semua parameter.** Kualifikasi juru las tidak menggantikan kualifikasi prosedur dan WPS; pembedaan ini dijaga oleh ruang lingkup [ISO 9606-1](https://www.iso.org/standard/54936.html) dan [ISO 15614-1](https://www.iso.org/standard/51792.html).
4. **Menyalin preheat dari pekerjaan lama.** Cocokkan identitas material, ketebalan, proses, sambungan, dan edisi WPS sebelum membandingkan.
5. **Mencatat setelan, bukan hasil aktual.** Lembar inspeksi perlu menghubungkan nilai aktual dengan sambungan, operator, alat, dan waktu.
6. **Menganggap NDT membatalkan kontrol proses.** Pemeriksaan akhir tidak menghapus kebutuhan mengendalikan parameter dan menyelesaikan penyimpangan selama pengelasan. Dasar penerimaan, metode, personel, dan rekaman harus tetap jelas.

## Jalan pintas yang perlu ditolak

Shortcut yang sering muncul adalah: “Bajanya sama, jadi suhu dari proyek lalu pasti cukup.” Nama material saja tidak menjelaskan ketebalan, kondisi awal, bentuk kampuh, kekangan, proses, atau lingkungan. Perubahan kecil pada salah satu faktor dapat mengubah laju pelepasan panas dan penyusutan. Alternatif yang lebih dapat dipertanggungjawabkan adalah membuat matriks singkat untuk setiap sambungan: identitas material dan ketebalan, WPS yang berlaku, metode ukur, nilai aktual, kondisi restraint, serta titik inspeksi. Bila matriks belum dapat diisi, keputusan termal belum siap disetujui.

Teman Bengkel-las.co.id, perlakukan permintaan “angka cepat” sebagai sinyal untuk memeriksa dokumen, bukan sebagai alasan mempercepat persetujuan. [NEEDS TECHNICAL REVIEW: kesesuaian WPS, kualifikasi prosedur, rekaman pengukuran, dan acceptance basis dengan sambungan aktual]

## Kesimpulan

Heat input, preheat, dan interpass adalah kendali atas riwayat panas, bukan tiga angka lepas. Energi dan kecepatan gerak membentuk panas per panjang; suhu awal dan batas antar-lapis mengatur akumulasinya; ketebalan, komposisi, geometri, restraint, consumable, alat, dan lingkungan menentukan respons sambungan. Tidak ada angka universal yang boleh dipakai sebagai persetujuan.

Langkah berikutnya: minta paket kerja yang memuat WPS dan rekaman kualifikasinya, identitas material serta ketebalan, detail sambungan dan restraint, metode pengukuran, catatan nilai aktual, dan dasar penerimaan. Tandai setiap kekurangan, tahan pekerjaan pada titik kendali, lalu minta keputusan tertulis dari personel teknis yang berwenang. Jika Anda perlu menelusuri konteks pekerjaan lain di situs, [kunjungi beranda Bengkel-las.co.id](/#beranda), baca [halaman FAQ](/faq/), atau gunakan [halaman kontak](/kontak-kami/) untuk menyampaikan pertanyaan yang perlu ditinjau. Aturan operasinya sederhana: jangan mengubah panas untuk mengejar kebiasaan; ubah hanya dalam rentang yang dibuktikan dan ditinjau.

---
article_id: BAR-07-01
writing_contract_version: "native-id-v2"
title: "Memilih Metode Cutting Steel Bar"
slug: "memilih-metode-cutting-steel-bar"
description: "Panduan membandingkan saw, shear, dan pemotongan termal berdasarkan mutu, penampang, panas, tepi, dan volume"
status: draft
publication_date: "2026-01-22"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: BAR-07
primary_intent: "Compare processes"
reader_community: "Besi.co.id"
reader_address: "Kawan Besi.co.id"
final_route: "/artikel/memilih-metode-cutting-steel-bar.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/78322.html"
  - "https://www.iso.org/standard/72529.html"
  - "https://www.iso.org/standard/60321.html"
  - "https://www.iso.org/standard/87851.html"
  - "https://www.iso.org/standard/86032.html"
  - "https://jdih.pu.go.id/detail-dokumen/PermenPUPR-nomor-10-tahun-2021-Pedoman-Sistem-Manajemen-Keselamatan-Konstruksi"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1430/peraturan-menteri-nomor-38-tahun-2016"
  - "https://www.osha.gov/welding-cutting-brazing/hazards-solutions"
---

<!-- BEGIN MANAGED IMAGE PLAN
- Image ID: LOCAL-001
- Placement: after opening, before first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi harga besi as](/wp-content/uploads/2024/07/harga-besi-as.jpg)`
- Caption/credit: Ilustrasi umum dari aset lokal Besi.co.id; bukan dokumentasi proyek tertentu.
- Selection basis: filename/source metadata only; no pixels inspected.
- Boundary: jangan menyimpulkan detail visual, kepemilikan, lokasi, orang, merek, kondisi, performa, atau hasil.
END MANAGED IMAGE PLAN -->

# Memilih Metode Cutting Steel Bar

Halo, Kawan Besi.co.id! Memilih metode cutting steel bar bukan sekadar memilih mesin yang paling cepat. Titik berangkatnya adalah fungsi potongan: jenis dan kondisi material, bentuk penampang, mutu tepi yang diminta, pengaruh panas yang boleh diterima, serta jumlah potongan. Saw (gergaji), shear (gunting tekan), dan thermal cutting (pemotongan termal) masing-masing unggul pada kondisi berbeda.

Jawaban singkatnya: gunakan saw ketika Anda membutuhkan potongan dingin yang relatif terkendali dan penampang berulang; pertimbangkan shear untuk pekerjaan volume tinggi pada ukuran dan material yang memang kompatibel; pilih thermal hanya jika ketebalan, bentuk, atau kapasitas membuat proses panas diperlukan dan zona terpengaruh panas dapat diterima atau ditangani. Gambar kerja, spesifikasi material, dan rencana inspeksi dapat mengubah pilihan tersebut. Artikel ini membandingkan konsep dan urutan keputusan, bukan memberi setelan mesin.

![Ilustrasi harga besi as](/wp-content/uploads/2024/07/harga-besi-as.jpg)

*Ilustrasi umum dari aset lokal Besi.co.id; bukan dokumentasi proyek tertentu.*

## Hasil akhir dan prasyarat

Hasil akhir yang baik adalah bar stock terpotong sesuai panjang dan bentuk yang diminta, dengan tepi yang dapat diterima untuk proses berikutnya, identitas material tetap terlacak, dan catatan inspeksi yang bisa ditinjau. Kriteria penerimaan perlu disepakati pada gambar dan prosedur oleh penanggung jawab fabrikasi, mutu, serta pihak desain atau pemilik pekerjaan; operator tidak menetapkannya sendirian.

Sebelum membandingkan proses, siapkan sekurang-kurangnya:

- grade atau spesifikasi produk, ukuran dan bentuk penampang, nomor heat atau batch bila diwajibkan sistem mutu;
- panjang potong, jumlah, urutan produksi, dan allowance untuk machining atau finishing;
- syarat tepi: burr, tegak lurus, kekasaran, bevel, atau larangan perubahan panas;
- proses lanjutan seperti pembubutan, pengelasan, pelapisan, atau pemeriksaan non-destruktif;
- penilaian risiko pekerjaan, kondisi mesin, penjepitan, penanganan material, dan pengendalian area panas.

Sobat Besi.co.id, bila salah satu data ini belum tersedia, keputusan metode masih berupa hipotesis. Tandai sebagai **[NEEDS GATE-01: spesifikasi material, gambar, dan kriteria penerimaan harus ditetapkan]** sebelum produksi seri.

## Langkah 1 — tetapkan batas pekerjaan

Tentukan apakah pekerjaan hanya memotong batang lurus, atau termasuk pemotongan miring, pembentukan ujung, penghilangan allowance, dan penandaan setelah potong. Bedakan pula pemotongan bahan baku dari pekerjaan yang sudah mendekati komponen akhir. Potongan untuk dibubut masih memiliki ruang koreksi; potongan yang langsung dirakit atau dilas memerlukan kendali tepi dan panjang yang lebih ketat.

Jangan menyamakan “steel bar” sebagai satu perilaku material. Diameter, tebal dinding, bentuk bulat/persegi, kondisi cold drawn atau hot rolled, serta kekerasan adalah pembeda yang perlu dinilai terhadap kemampuan proses dan hasil tepi. Scope juga harus menyebut antarmuka: siapa menyerahkan material, siapa memverifikasi heat number, dan siapa menyetujui bagian yang tidak sesuai.

Untuk thermal cutting, scope harus secara eksplisit memuat zona terpengaruh panas (heat-affected zone/HAZ), kemungkinan oksida atau dross, dan kebutuhan pembersihan. ISO 9013 menjelaskan klasifikasi kualitas thermal cut; edisi perubahan dan penerapannya tetap harus diperiksa terhadap dokumen proyek, bukan dipakai sebagai toleransi universal ([ISO 9013:2017](https://www.iso.org/standard/60321.html), [Amd 1:2024](https://www.iso.org/standard/87851.html)).

## Langkah 2 — kumpulkan dan cocokkan bukti

Susun matriks keputusan sederhana. Barisnya memuat material dan penampang aktual; kolomnya memuat pengaruh panas, mutu tepi, fleksibilitas bentuk, volume, dan pekerjaan lanjutan. Isi dengan bukti dari dokumen, bukan ingatan tentang mesin tertentu.

| Pertimbangan | Saw | Shear | Thermal |
|---|---|---|---|
| Pengaruh panas | Umumnya proses dingin; tetap verifikasi panas akibat gesekan | Proses dingin, tetapi gaya dan deformasi lokal perlu dinilai | Ada HAZ dan potensi oksida/dross; prosedur pembersihan diperlukan |
| Penampang dan bentuk | Fleksibel untuk banyak bentuk jika penjepitan memadai | Paling cocok untuk rentang ukuran/bentuk yang telah disetujui alat | Fleksibel untuk bentuk kompleks, dengan kontrol jalur dan tepi |
| Mutu tepi | Cenderung mudah diprediksi; burr dan tegak lurus tetap diperiksa | Dapat menimbulkan deformasi atau sudut patah pada kondisi tidak cocok | Kualitas bergantung material, ketebalan, prosedur, dan inspeksi tepi |
| Volume | Baik untuk batch berulang dengan setup stabil | Efisien bila ukuran kompatibel dan volume tinggi | Berguna ketika bentuk/ketebalan mengalahkan kebutuhan proses dingin |
| Proses sesudahnya | Sering siap untuk machining ringan setelah inspeksi | Mungkin perlu trimming atau machining korektif | Bisa memerlukan pembersihan, penggerindaan, atau evaluasi HAZ |

Tabel ini adalah peta awal, bukan jaminan hasil. Persyaratan toleransi pada gambar harus dipasangkan dengan metode pengukuran dan fungsi komponen. ISO 13920 membahas toleransi umum konstruksi las, tetapi tidak otomatis berlaku untuk setiap bar, potongan, atau komponen machined ([ISO 13920:2023](https://www.iso.org/standard/86032.html)).

Periksa juga apakah “grade” pada sertifikat material benar-benar identik dengan grade yang disyaratkan. Nama proses tidak membuktikan kesesuaian material, dan hasil satu kupon tidak otomatis mewakili seluruh stok; keterkaitan spesimen, metode uji, kondisi, serta identitas produk atau heat perlu ditelusuri ([ISO 6892-1:2019](https://www.iso.org/standard/78322.html), [ISO 377:2017](https://www.iso.org/standard/72529.html)). Jika grade, heat, atau kriteria tepi tidak dapat ditautkan, tahan keputusan pada **[NEEDS GATE-04: bukti material dan kriteria penerimaan belum lengkap]**.

## Langkah 3 — jalankan urutan kerja

Urutan konseptual yang aman dimulai dari dokumen, bukan dari menyalakan mesin:

1. Cocokkan drawing, spesifikasi pembelian, sertifikat, identitas batang, dan revisi terbaru. Pisahkan material yang identitasnya meragukan.
2. Kelompokkan pekerjaan berdasarkan penampang, panjang, grade, dan jumlah. Hindari memaksa satu metode untuk semua kelompok.
3. Pilih kandidat proses. Dahulukan saw bila larangan panas dan kualitas potongan menjadi prioritas. Evaluasi shear bila ukuran serta material berada dalam rentang yang disetujui prosedur dan volume membenarkan setup. Gunakan thermal bila geometri atau kapasitas mengharuskannya, dengan rencana HAZ dan pembersihan.
4. Lakukan potongan awal atau verifikasi first-off sesuai prosedur yang disetujui. Ukur panjang, kesikuan, burr, kondisi permukaan, dan tanda panas yang relevan.
5. Bandingkan hasil first-off dengan gambar dan fungsi lanjutan. Baru kemudian lepaskan batch untuk produksi, dengan identitas material tetap melekat.
6. Pisahkan hasil yang menyimpang, dokumentasikan penyebab yang diketahui, dan minta keputusan koreksi. Jangan menghapus bukti dengan menggerinda atau memotong ulang sebelum disposisi dicatat.

Untuk pekerjaan di area konstruksi, pemilihan metode harus masuk ke rencana keselamatan dan metode kerja yang berlaku. Rujuk teks Permen PUPR 10/2021 dan dokumen proyek yang mutakhir; judul atau status regulasi saja tidak menggantikan pemeriksaan kewajiban yang berlaku ([Permen PUPR 10/2021](https://jdih.pu.go.id/detail-dokumen/PermenPUPR-nomor-10-tahun-2021-Pedoman-Sistem-Manajemen-Keselamatan-Konstruksi)). Bahaya pemotongan dan pekerjaan panas meliputi percikan, kebakaran, listrik, gas, dan paparan asap; kendalinya harus ditetapkan melalui penilaian risiko setempat, bukan menyalin angka atau PPE dari panduan asing ([OSHA welding/cutting/brazing hazards](https://www.osha.gov/welding-cutting-brazing/hazards-solutions)).

## Titik henti dan kondisi berhenti

Hentikan pekerjaan dan minta review bila material tidak cocok dengan dokumen, ukuran aktual berada di luar kelompok setup, first-off gagal memenuhi fungsi, atau thermal cut menghasilkan HAZ/tepi yang tidak tercakup prosedur. Hentikan juga bila penjepitan, pelindung mesin, ventilasi, isolasi energi, atau izin hot work tidak tersedia.

Kawan Besi.co.id, “lebih cepat” bukan alasan untuk melewati hold point. Jika keputusan metode memengaruhi sifat material, sambungan las, atau keselamatan pengangkatan, tandai **[NEEDS GATE-06: persetujuan teknis, K3, dan prosedur spesifik pekerjaan]**. Periksa status peralatan dan kompetensi personel dengan merujuk aturan K3 Indonesia yang relevan, termasuk lingkup pesawat tenaga dan produksi ([Permenaker 38/2016](https://jdih.kemnaker.go.id/peraturan/detail/1430/peraturan-menteri-nomor-38-tahun-2016)).

## Verifikasi hasil dan serah terima

Handover minimal berisi daftar batang dan heat/batch, metode yang dipakai, tanggal dan operator, revisi gambar, hasil pemeriksaan first-off atau sampling, alat ukur yang digunakan, serta status nonconformance. Untuk thermal cutting, catat pembersihan tepi dan pemeriksaan area yang disyaratkan prosedur. Untuk shear, catat tanda deformasi; untuk saw, catat burr atau penyimpangan kesikuan yang memerlukan tindakan.

Penerimaan harus menjawab tiga pertanyaan: apakah dimensi memenuhi gambar, apakah tepi cocok untuk proses berikutnya, dan apakah identitas material masih terlacak? Bila jawabannya belum dapat dibuktikan, statusnya jangan diubah menjadi “lulus”. Minta pemeriksaan teknis dan, bila relevan, pemeriksaan laboratorium atau NDT yang memang diwajibkan dokumen. Jangan memakai standar umum sebagai pengganti kriteria proyek.

## Jalan pintas yang perlu dihindari

Shortcut yang sering muncul adalah memilih thermal karena satu mesin dapat mengikuti banyak bentuk, lalu menganggap penggerindaan akan menghapus semua masalah. Itu bisa gagal ketika HAZ, dross, atau perubahan tepi memengaruhi las, machining allowance, atau inspeksi berikutnya. Sebaliknya, memilih saw untuk seluruh pekerjaan dapat membuang waktu dan alat bila volume besar atau geometri tidak stabil.

Alternatif yang lebih dapat dipertanggungjawabkan adalah membagi job menjadi kelompok homogen, menjalankan first-off, dan membandingkan biaya koreksi serta waktu tunggu—bukan hanya waktu busur atau waktu potong. Tetapkan metode default hanya setelah bukti first-off dan persetujuan prosedur tersedia.

## Kesimpulan dan langkah berikutnya

Metode cutting steel bar dipilih dari kombinasi grade, penampang, efek panas, mutu tepi, volume, dan proses lanjutan. Saw biasanya menjadi kandidat untuk potongan dingin yang terkendali; shear untuk ukuran yang kompatibel dan volume tinggi; thermal untuk geometri atau ketebalan yang memerlukannya dengan pengendalian HAZ. Tidak ada pilihan universal.

Langkah berikutnya adalah meminta gambar dan spesifikasi terbaru, menyiapkan matriks keputusan, lalu menyetujui first-off bersama penanggung jawab mutu dan K3. Untuk menelusuri pilihan material, Anda dapat melihat [informasi besi AS S45C](/as-s45c) dan [panduan besi beton](/besi-beton), lalu memakai [ruang lingkup informasi Besi.co.id](/) sebagai titik awal untuk merapikan pertanyaan material. Keputusan teknis tetap berada pada dokumen proyek. Jika data material, toleransi, atau kondisi mesin belum terbukti, jangan lepaskan batch. Aturan kerjanya sederhana: pilih proses yang dapat dibuktikan memenuhi fungsi dan risiko pekerjaan, bukan proses yang hanya tampak paling cepat.

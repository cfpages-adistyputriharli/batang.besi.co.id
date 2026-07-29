---
article_id: BAR-04-06
title: "Cut Length, End Condition, dan Allowance"
slug: "cut-length-end-condition-allowance"
description: "Cover length basis, kerf, facing, burr, squareness, identification, waste"
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2025-11-28"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: BAR-04
primary_intent: "Specify cut pieces"
reader_community: "Besi.co.id"
reader_address: "Teman Besi.co.id"
final_route: "/artikel/cut-length-end-condition-allowance.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/60321.html"
  - "https://www.iso.org/standard/87851.html"
  - "https://www.iso.org/standard/86032.html"
---

# Cut Length, End Condition, dan Allowance

<!-- BEGIN MANAGED IMAGE PLAN
Image ID: LOCAL-001
**Exact Markdown to insert:** `![Ilustrasi harga besi as](/wp-content/uploads/2024/07/harga-besi-as.jpg)`
Placement: after opening answer, before first detailed H2
Caption/credit: Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
END MANAGED IMAGE PLAN -->

Halo, Teman Besi.co.id! Potongan batang yang “panjangnya sudah sesuai” belum tentu siap dirakit. Panjang harus punya basis ukur yang jelas, ujung harus memenuhi kondisi yang diminta, dan allowance harus dipisahkan dari sisa proses. Jika tiga hal ini ditulis sebagai satu angka tanpa keterangan, operator dapat memotong terlalu pendek, QC menolak karena burr atau kemiringan, dan material habis untuk mengulang pekerjaan.

Jawaban singkatnya: tetapkan **cut length** sebagai ukuran akhir atau ukuran sebelum proses lanjutan, nyatakan **end condition** (misalnya ujung hasil potong, facing, chamfer, atau deburring), lalu tentukan **allowance** yang memang dibutuhkan oleh proses dan inspeksi. Kerf, penyimpangan squareness, dan burr bukan otomatis “tambahan panjang”; semuanya harus dijawab oleh gambar kerja, prosedur, dan persetujuan proyek. Kemampuan serta kelas kualitas pemotongan termal perlu dikaitkan dengan material, tebal, tepi, pengukuran, dan fungsi downstream; ISO 9013:2017 dan amendemennya adalah rujukan identitas teknis untuk topik tersebut, bukan izin memilih toleransi secara bebas ([ISO 9013:2017](https://www.iso.org/standard/60321.html), [ISO 9013:2017/Amd 1:2024](https://www.iso.org/standard/87851.html)).

![Ilustrasi harga besi as](/wp-content/uploads/2024/07/harga-besi-as.jpg)

Aset lokal proyek; bukan dokumentasi proyek tertentu.

## Definisi dan batas objek

**Cut length** adalah panjang yang harus diterima pada tahap yang disebut di dokumen. “600 mm” dapat berarti panjang setelah potong, atau blank 600 mm sebelum facing. Kedua basis itu menghasilkan instruksi berbeda. **End condition** menjelaskan keadaan kedua ujung: tegak lurus terhadap sumbu, bebas burr tajam, sudah difacing, diberi chamfer, atau dibiarkan sebagai-cut bila memang diizinkan. **Allowance** adalah material yang sengaja disisakan untuk proses berikutnya, bukan toleransi yang boleh hilang tanpa batas.

Artikel ini membahas cara menulis dan memeriksa permintaan potongan. Ia tidak menetapkan parameter mesin, kecepatan, arus, panas, atau resep pemotongan. Ia juga bukan pengganti gambar IFC/shop drawing, WPS/prosedur fabrikasi, rencana inspeksi, atau persetujuan engineer. Untuk toleransi dimensi dan kondisi tepi yang konsekuensial, [NEEDS GATE-01: konfirmasi gambar/prosedur proyek dan competent review sebelum nilai toleransi dikunci]. Standar umum untuk konstruksi las pun tidak otomatis berlaku pada setiap batang atau setiap tahap pemesinan; ruang lingkup dan kelas toleransinya harus diperiksa pada dokumen penuh ([ISO 13920:2023](https://www.iso.org/standard/86032.html)). Untuk konteks dokumen dan rujukan umum, Anda dapat mulai dari [beranda Besi.co.id](/).

Jika kebutuhan Anda bergeser ke material beton bertulang, [lihat rute besi beton](/besi-beton) untuk konteks produk yang berbeda. Untuk batang baja, [pilihan besi as](/as-s45c) memberi titik mulai navigasi produk.

## Cara kerjanya

Mulai dari fungsi komponen. Tanyakan: panjang mana yang menentukan jarak antar-komponen, dan permukaan mana yang benar-benar menjadi datum? Dari jawaban itu, pilih satu basis ukur dan tuliskan di drawing atau cut list.

Urutan yang mudah diaudit biasanya seperti ini:

1. **Identifikasi bahan dan stock.** Catat heat/lot, ukuran nominal, dan nomor batang sebelum dipotong. Jangan mengandalkan label lepas setelah batang dibagi.
2. **Tentukan basis panjang.** Tulis “ukuran akhir setelah facing” atau “blank sebelum proses ujung”. Jika allowance berada di satu sisi, nyatakan sisi dan jumlahnya; jika simetris, nyatakan pembagiannya.
3. **Nyatakan kondisi ujung.** Sebutkan apakah ujung harus square, perlu facing/chamfer, atau cukup deburring. “Bersih” saja terlalu kabur untuk inspeksi.
4. **Pisahkan efek proses.** Kerf adalah lebar material yang hilang pada jalur potong; ia memengaruhi nesting dan jumlah stok, bukan otomatis menambah panjang komponen. Burr dan ketidak-sikuan adalah kondisi yang diperiksa atau diperbaiki, bukan allowance yang boleh ditaksir operator.
5. **Potong, tandai, dan catat.** Nomor item, orientasi, panjang yang diminta, dan status pemeriksaan ikut bersama potongan. Sisa yang belum teridentifikasi masuk area karantina, bukan kembali ke tumpukan baik.
6. **Verifikasi dengan alat dan metode yang disepakati.** Ukur dari datum yang sama, pada kondisi permukaan yang sudah dinyatakan, dan catat hasil serta alatnya. [NEEDS GATE-04: metode ukur, resolusi alat, titik ukur, dan acceptance criterion harus disetujui pada ITP/prosedur proyek.]

Dengan urutan tersebut, orang yang menerima potongan tahu apakah ia sedang memeriksa blank, part final, atau bagian yang masih akan dimakan proses lain.

## Faktor yang mengubah hasil

Beberapa faktor sering tercampur dalam satu angka:

- **Kerf dan nesting.** Lebar jalur potong memengaruhi jarak antar-cut dan perhitungan waste. Nilainya bergantung pada proses dan kondisi aktual, sehingga jangan dicetak sebagai angka universal di cut list.
- **Facing atau machining.** Bila ujung akan difacing, allowance harus cukup untuk mencapai permukaan akhir tanpa mengorbankan panjang minimum. Besar allowance harus berasal dari drawing/prosedur dan kapasitas proses yang disetujui, bukan kebiasaan toko.
- **Burr dan edge quality.** Burr yang tajam bisa mengganggu pemasangan atau keselamatan handling. Instruksi deburring harus menyebut hasil yang diharapkan; jangan menyamakan “tanpa burr terlihat” dengan kelas kualitas termal tertentu.
- **Squareness dan datum.** Ujung miring dapat membuat panjang berbeda ketika diukur pada sisi yang berbeda. Tetapkan cara menentukan ketegaklurusan terhadap sumbu atau permukaan referensi. [NEEDS GATE-06: toleransi squareness/edge condition dan cara ukurnya memerlukan persetujuan proyek.]
- **Material, tebal, dan fungsi downstream.** ISO 9013 menekankan bahwa kualitas potongan termal dikaitkan dengan proses, bahan, tebal, dan pengaruh panas. Jika potongan akan dilas, dibubut, atau menjadi permukaan tumpu, persyaratannya tidak boleh diasumsikan sama.
- **Penandaan dan sisa.** Potongan identik yang kehilangan heat/lot atau nomor item menjadi sulit ditelusuri. Sisa yang ukurannya tampak cukup tetap harus diberi identitas dan status; bila tidak, perlakukan sebagai material yang belum terverifikasi.

## Contoh keputusan praktis

Gunakan tabel kecil ini saat membuat cut list. Ini bukan nilai toleransi; ini cara memilih basis instruksi.

| Situasi | Cara menulis permintaan | Pemeriksaan berikutnya |
|---|---|---|
| Ujung langsung menjadi datum rakitan | “Panjang akhir setelah potong dan deburring; datum A di ujung 1” | Ukur dari datum A dan periksa kondisi ujung yang disyaratkan |
| Kedua ujung akan difacing | “Blank = panjang akhir + allowance proses; facing kedua ujung” | Pastikan allowance dan ukuran akhir ada di drawing/prosedur |
| Satu ujung dipakai untuk sambungan, satu ujung bebas | “Ujung 1 square sesuai drawing; ujung 2 deburr; basis ukur dari ujung 1” | Pisahkan pemeriksaan tiap ujung, jangan memakai toleransi simetris tanpa dasar |
| Banyak potongan dari satu batang | “Item, nomor batang, arah, panjang blank/final, dan status” | Rekonsiliasi jumlah baik, rework, dan sisa beridentitas |

Contoh di atas sengaja tidak mengisi angka allowance atau toleransi. Sobat Besi.co.id, angka tersebut adalah keputusan proyek: ia harus mempertimbangkan proses setelah potong, fungsi permukaan, dan kemampuan ukur yang disetujui.

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah menambahkan kerf ke setiap panjang part. Kerf terjadi di antara potongan; memasukkannya ke panjang final dapat membuat seluruh komponen oversize. Periksa kembali apakah angka pada daftar adalah ukuran part atau jarak layout.

Kedua, menulis “ujung rapi” tanpa definisi. Minta istilah yang dapat diperiksa: deburring, facing, chamfer dengan rujukan gambar, atau kelas kualitas yang memang dipakai proyek.

Ketiga, mengukur sisi terpanjang pada ujung miring lalu menyatakan part lolos. Gunakan datum dan metode ukur yang sama untuk semua potongan; simpan catatan ketika hasil berada dekat batas.

Keempat, mencampur allowance dengan toleransi. Allowance adalah material untuk dikerjakan lagi; toleransi adalah rentang penerimaan. Jika keduanya tidak dipisahkan, operator bisa menghabiskan allowance atau QC menolak ukuran yang sebenarnya masih blank.

Kelima, memakai sisa tanpa identitas karena “diameternya sama”. Cocokkan marking dengan dokumen material dan item. Bila identitas tidak dapat dibuktikan, tahan penggunaannya sampai ada keputusan yang terdokumentasi.

## Jalan pintas yang tampak hemat

Jalan pintas yang sering dipilih adalah memotong semua batang pada satu angka nominal, lalu berharap facing, deburring, dan squareness dapat “dirapikan nanti”. Ini gagal ketika sebagian part membutuhkan permukaan datum, sebagian lain hanya blank, atau allowance ternyata tidak cukup. Pengulangan potong menambah waste dan mengaburkan penelusuran material.

Alternatif yang lebih aman adalah membekukan cut list setelah tiga pertanyaan dijawab: ukuran ini final atau blank, kondisi kedua ujung apa, dan dokumen mana yang menetapkan acceptance. Jika salah satu jawaban belum ada, tandai item sebagai tertahan dan minta review—jangan mengisi kekosongan dengan angka kebiasaan.

## Penutup: aturan operasi

Cut length, end condition, dan allowance harus ditulis sebagai tiga keputusan terpisah: **basis ukur**, **keadaan ujung**, dan **material yang sengaja disisakan**. Kerf dipakai untuk merencanakan layout/waste, bukan otomatis ditambahkan ke panjang part; burr dan squareness harus punya kriteria pemeriksaan; identitas harus ikut sampai sisa dan rework selesai.

Kawan Besi.co.id, sebelum rilis pekerjaan potong, minta drawing atau prosedur yang menyebut datum, ukuran blank/final, allowance, kondisi ujung, metode ukur, dan jalur penanganan nonconformance. [NEEDS COORDINATOR TECHNICAL REVIEW: GATE-01, GATE-04, GATE-06 harus ditutup dengan bukti proyek dan persetujuan kompeten sebelum artikel atau spesifikasi dipakai sebagai dasar penerimaan.] Jika Anda perlu kembali ke konteks umum, gunakan [beranda Besi.co.id](/); itu bukan pengganti approval proyek. Aturan operasinya sederhana: jika basis ukur atau acceptance belum tertulis, potongan belum siap dinyatakan final.

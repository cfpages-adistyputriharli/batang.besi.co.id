---
article_id: BAR-11-04
writing_contract_version: "native-id-v2"
title: "MOQ, Stock Length, Cut-to-size, dan Waste"
slug: "moq-stock-length-cut-to-size"
description: "Panduan memahami ketersediaan, pemotongan, sisa, setup, packing, lead time, dan kepemilikan waste"
status: draft
publication_date: "2026-05-14"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: BAR-11
primary_intent: "Understand cost drivers"
reader_community: "Besi.co.id"
reader_address: "Kawan Besi.co.id"
final_route: "/artikel/moq-stock-length-cut-to-size.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/53736.html"
  - "https://www.iso.org/standard/66912.html"
  - "https://www.iso.org/standard/60321.html"
  - "https://www.iso.org/standard/72532.html"
---

# MOQ, Stock Length, Cut-to-size, dan Waste

Halo, Kawan Besi.co.id! Saat meminta penawaran besi, jangan hanya membandingkan harga per batang atau per kilogram. MOQ (*minimum order quantity*) menentukan jumlah minimum yang harus dipesan, *stock length* adalah panjang batang yang tersedia, *cut-to-size* berarti pemasok memotong sesuai daftar Anda, sedangkan *waste* adalah sisa yang muncul dari pola potong dan proses penanganan. Keempatnya dapat mengubah total biaya dan jadwal.

Jawaban singkatnya: pilih panjang stok dan pola potong setelah *cut list* disetujui, lalu sepakati tertulis siapa yang membayar potongan, sisa, setup, packing, dan pengiriman. Harga yang tampak murah bisa menjadi lebih tinggi bila MOQ memaksa pembelian berlebih atau sisa tidak dapat dipakai kembali. Angka aktual, kemampuan mesin, dan waktu kirim tetap harus dikonfirmasi pada penawaran proyek; halaman ini tidak menetapkan harga berjalan.

![Ilustrasi harga besi as](/wp-content/uploads/2024/07/harga-besi-as.jpg)

*Ilustrasi umum dari aset lokal Besi.co.id; bukan dokumentasi proyek tertentu.*

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- Image ID: `LOCAL-001`
- Source type: `local`
- Placement: after the opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi harga besi as](/wp-content/uploads/2024/07/harga-besi-as.jpg)`
- Caption/credit: Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
- Selection basis: filename/source metadata identifies `harga besi as` as relevant content media; no pixels were inspected.
- Hard boundary: do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- Substitution rule: do not replace this image. If unavailable or provenance is incomplete, insert [NEEDS IMAGE REVIEW: LOCAL-001] and continue drafting the prose.
END MANAGED IMAGE PLAN -->

## Definisi dan batas objek

MOQ adalah ambang kuantitas yang diterima pemasok untuk satu spesifikasi, ukuran, atau pesanan. Tanyakan apakah ambang itu berlaku per diameter, per mutu, per panjang, atau gabungan seluruh pesanan. *Stock length* bukan jaminan bahwa semua batang di gudang identik; panjang nominal, toleransi, dan identitas material harus cocok dengan pesanan.

*Cut-to-size* memindahkan sebagian pekerjaan ke pemasok. Anda memberikan panjang jadi dan jumlahnya; pemasok mengalokasikan batang stok, menjalankan mesin, memeriksa hasil, lalu mengemasnya. *Waste* mencakup ujung potongan yang tidak masuk daftar, kerf (lebar material yang hilang karena mata potong), kerusakan saat handling, dan sisa yang masih dapat dimanfaatkan. Bedakan “sisa fisik” dari “susut yang ditagihkan”: keduanya perlu definisi di penawaran.

Artikel ini membahas keputusan pengadaan dan serah-terima. Ia tidak menggantikan gambar kerja, persetujuan metode pemotongan, atau keputusan insinyur tentang kecukupan material. Tidak ada angka harga, toleransi, kapasitas mesin, atau lead time universal yang aman untuk diasumsikan. Untuk konteks kebutuhan material, Anda dapat mulai dari [beranda Besi.co.id](/) atau melihat pilihan [besi siku AS](/as-s45c) sebelum meminta penawaran rinci.

## Cara kerjanya

Urutannya sebaiknya dimulai dari *cut list* yang memiliki nomor item, ukuran jadi, kuantitas, satuan, dan toleransi yang disetujui. Pemasok lalu membuat rencana nesting: beberapa potongan ditempatkan pada satu batang stok untuk meminimalkan sisa. Rencana itu harus menunjukkan panjang stok yang dipakai, jumlah batang, kerf atau allowance proses yang relevan, dan sisa per batang.

Setelah Anda menyetujui rencana, pemasok mengunci ketersediaan dan jadwal. MOQ dapat memaksa pembulatan jumlah batang; kelebihan itu bukan otomatis menjadi milik pemasok atau pembeli. Minta klausul yang menyebut apakah batang penuh, potongan, dan sisa dikirim, disimpan, atau dibuang. Untuk pekerjaan berulang, setup mesin mungkin dibebankan sekali per ukuran atau sekali per batch; pastikan definisinya sebelum PO.

Pada tahap pemotongan, identitas material harus tetap terlacak. Dokumen inspeksi perlu direkonsiliasi dengan pesanan, produsen, produk, heat/batch, dimensi, pengujian, dan tanda fisik; ISO 10474:2013 menjelaskan kerangka dokumen inspeksi, tetapi dokumen itu sendiri tidak membuktikan barang tertentu diterima tanpa pemeriksaan proyek ([ISO 10474:2013](https://www.iso.org/standard/53736.html)). Bila hasil uji berasal dari laboratorium eksternal, kompetensi menurut ISO/IEC 17025:2017 meningkatkan kepercayaan pada proses laboratorium, bukan menjadi bukti otomatis bahwa setiap potongan sesuai ([ISO/IEC 17025:2017](https://www.iso.org/standard/66912.html)).

Packing dan label adalah bagian dari biaya, bukan detail belakangan. Labelkan nomor item, panjang jadi, jumlah, heat/batch bila disyaratkan, dan referensi *cut list*. Pisahkan bundel berdasarkan tahap pemasangan agar penerima dapat menghitung tanpa membuka semua ikatan. Tetapkan siapa menanggung risiko bila sisa atau label hilang selama pengiriman.

## Faktor yang mengubah hasil

Kondisi berikut biasanya mengubah jumlah batang dan biaya total:

| Faktor | Pertanyaan yang perlu dijawab | Dampak bila kabur |
|---|---|---|
| MOQ | Berlaku per spesifikasi atau seluruh PO? | Pembelian berlebih dan stok mengendap |
| Panjang stok | Panjang aktual apa yang tersedia dan boleh dipakai? | Pola potong berubah, sisa bertambah |
| Toleransi | Toleransi potong dan pemeriksaan di mana ditetapkan? | Potongan ditolak atau perlu rework |
| Setup | Sekali per batch, ukuran, atau perubahan material? | Biaya kecil berulang menjadi besar |
| Waste | Sisa dikirim, dikreditkan, disimpan, atau dibuang? | Perselisihan kepemilikan dan tagihan |
| Lead time | Mulai dihitung dari PO, pembayaran, atau persetujuan gambar? | Jadwal tampak cepat tetapi tidak realistis |
| Packing | Berat, bundel, pelindung ujung, dan label termasuk? | Kerusakan atau bongkar ulang di lokasi |

Jenis proses juga berpengaruh. Pemotongan termal memiliki karakteristik proses dan mutu tepi yang harus ditautkan ke material, tebal, gambar, pengukuran, dan fungsi komponen; ISO 9013:2017 beserta amendemennya dapat menjadi rujukan proses, namun bukan izin memakai satu toleransi untuk semua bengkel ([ISO 9013:2017](https://www.iso.org/standard/60321.html)). Jika komponen akan dilas atau dikerjakan lanjut, minta prosedur dan kriteria penerimaan yang disetujui. [NEEDS PROJECT EVIDENCE: toleransi, allowance kerf, dan acceptance cut-to-size]

Untuk klaim keberlanjutan atau asal material, jangan menyamakan label administratif dengan identitas fisik. ISO 22095:2020 membedakan model *identity preservation*, segregasi, dan *mass balance*; klaim yang dapat diaudit memerlukan batas sistem, catatan input-output, aturan transfer, pihak bertanggung jawab, dan pencegahan penghitungan ganda ([ISO 22095:2020](https://www.iso.org/standard/72532.html)). Jika klaim itu memengaruhi pembelian, minta skema klaim dan bukti transaksi yang masih berlaku. [NEEDS CLAIM EVIDENCE: model chain-of-custody dan catatan serah-terima]

## Contoh keputusan praktis

Bayangkan daftar Anda memerlukan banyak potongan pendek dari satu ukuran, sementara pemasok hanya menawarkan batang panjang tertentu. Ada tiga pilihan bersyarat:

1. **Beli batang penuh dan potong di lokasi.** Pilih ini bila alat, tenaga, dan pemeriksaan potong memang tersedia. Anda menanggung sisa, keselamatan kerja, dan waktu pemotongan.
2. **Pesan *cut-to-size*.** Pilih bila dimensi jadi sudah dibekukan dan pemasok dapat menunjukkan rencana potong. Minta harga memisahkan material, jasa potong, setup, packing, dan angkutan.
3. **Terima panjang alternatif.** Pilih hanya setelah desain dan toleransi menyatakan panjang itu dapat dipakai. Jangan menganggap “lebih panjang” selalu lebih ekonomis karena sisa dan handling dapat meningkat.

Sebelum memilih, minta satu lembar rekonsiliasi: kebutuhan jadi, batang stok, jumlah batang dibeli, total panjang masuk, panjang jadi keluar, kerf/allowance, sisa dapat guna, dan sisa tidak dapat guna. Tabel itu memungkinkan Anda menguji asumsi tanpa mengarang persentase waste. Kawan Besi.co.id, bila pemasok belum dapat menunjukkan rekonsiliasi sederhana ini, tahan persetujuan kuantitas sampai datanya jelas. Sobat Besi.co.id dapat memakai format tersebut untuk membandingkan penawaran yang masuk tanpa mencampur harga material dan jasa.

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah mengalikan jumlah potongan dengan panjangnya lalu menganggap hasilnya sama dengan jumlah batang. Metode itu mengabaikan panjang stok, kerf, dan susunan potong. Kesalahan kedua adalah menyebut semua sisa sebagai “waste” lalu membebankan seluruhnya tanpa aturan kepemilikan. Kesalahan ketiga adalah mengunci jadwal dari tanggal penawaran, padahal lead time mungkin baru berjalan setelah PO, pembayaran, atau persetujuan gambar.

Gunakan pemeriksaan berikut sebelum menerbitkan PO:

- Cocokkan revisi *cut list* dengan gambar dan nomor item.
- Minta konfirmasi stok aktual dan tanggal *hold* ketersediaan.
- Minta rencana potong, jumlah batang, kerf/allowance yang dipakai, serta daftar sisa.
- Pastikan toleransi, metode ukur, dan kriteria terima disetujui pihak teknis.
- Tulis perlakuan sisa: dikirim bersama, disimpan, dikreditkan, atau menjadi milik siapa.
- Pisahkan tanggal siap potong, siap packing, dan siap kirim.
- Saat terima, cocokkan label, jumlah, dimensi, tanda material, dan dokumen inspeksi; catat selisih sebelum bundel dipindahkan.

[NEEDS REVIEW: persetujuan teknis dan syarat kontrak proyek untuk waste ownership, toleransi, dan lead time]

## Jalan pintas yang tampak murah

“Ambil saja harga per batang termurah; urusan potong dan sisa nanti.” Shortcut ini gagal ketika harga satuan tidak memuat setup, packing, angkutan, atau batang tambahan akibat MOQ. Sisa juga dapat menjadi biaya tersembunyi bila tidak dapat dipakai pada item lain. Alternatif yang lebih aman adalah meminta penawaran berbasis *cut list* dengan seluruh komponen biaya dan aturan sisa tertulis, lalu membandingkan total biaya yang benar-benar sampai di lokasi.

## Aturan sebelum menyetujui

MOQ, *stock length*, *cut-to-size*, dan *waste* adalah satu keputusan pengadaan: jumlah minimum dan panjang stok menentukan pola potong; pola potong menentukan sisa; jasa potong, setup, packing, dan lead time menentukan biaya serta jadwal. Sebelum menyetujui, minta rekonsiliasi material, konfirmasi ketersediaan, aturan kepemilikan sisa, dan kriteria pemeriksaan yang disetujui proyek. Teman Besi.co.id, jika salah satu bukti itu belum ada, tandai sebagai [NEEDS PROJECT REVIEW] dan jangan mengubah asumsi menjadi angka pasti. Jika data belum cukup untuk mengunci jumlah atau jadwal, kirimkan cut list dan pertanyaan Anda melalui [halaman kontak Besi.co.id](/kontak) agar penawaran dapat ditinjau dengan konteks yang jelas.

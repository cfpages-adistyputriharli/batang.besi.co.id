---
article_id: BAR-11-03
writing_contract_version: "native-id-v2"
title: "Menghitung Kebutuhan Bar dari Cut List"
slug: "kebutuhan-bar-dari-cut-list"
description: "Cover piece count, stock length, kerf, remnant policy, tolerance, theoretical/actual mass"
status: draft
publication_date: "2026-05-10"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: BAR-11
primary_intent: "Plan quantity"
reader_community: "Besi.co.id"
reader_address: "Sobat Besi.co.id"
final_route: "/artikel/kebutuhan-bar-dari-cut-list.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/53736.html"
  - "https://www.iso.org/standard/66912.html"
  - "https://www.iso.org/standard/9985.html"
  - "https://www.asme.org/codes-standards/find-codes-standards/welded-and-seamless-wrought-steel-pipe"
  - "https://www.iso.org/standard/60321.html"
  - "https://www.iso.org/standard/86032.html"
---

# Menghitung Kebutuhan Bar dari Cut List

Halo, Sobat Besi.co.id! Kebutuhan bar dari cut list tidak cukup dihitung dengan menjumlahkan panjang semua potongan lalu membaginya dengan panjang stock. Perencanaan yang dapat dipertanggungjawabkan harus memisahkan jumlah piece, panjang stock, kerf (material yang hilang saat pemotongan), kebijakan remnant, toleransi, dan basis massa.

Jawaban singkatnya: kelompokkan potongan berdasarkan spesifikasi dan panjang stock, susun satu rencana pemotongan yang realistis, lalu bulatkan jumlah bar sesuai aturan remnant dan toleransi yang disetujui. Hasilnya adalah kebutuhan pembelian atau issue plan, bukan jaminan nesting paling optimal. Jika gambar, prosedur pemotongan, atau aturan penerimaan belum final, tandai hasil sebagai estimasi dan minta review kompeten: **[NEEDS GATE-01: persetujuan cut list, stock length, dan aturan pemotongan]**.

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- Image ID: LOCAL-001
- Source type: local
- **Placement:** after opening has answered the main question, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi harga besi as](/wp-content/uploads/2024/07/harga-besi-as.jpg)`
- **Caption/credit:** Ilustrasi umum dari aset lokal Besi.co.id; bukan dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `harga besi as` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-001]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

![Ilustrasi harga besi as](/wp-content/uploads/2024/07/harga-besi-as.jpg)

Ilustrasi umum dari aset lokal Besi.co.id; bukan dokumentasi proyek tertentu.

## Definisi dan batas objek

Cut list adalah daftar potongan yang harus dibuat: identitas material, ukuran penampang, grade atau spesifikasi, panjang jadi, jumlah, dan keterangan proses bila ada. “Bar” di sini berarti batang stock yang akan dipotong; istilah ini tidak otomatis berarti pipa, hollow, atau profil tertentu. Pastikan nama produk di daftar sama dengan nama pada penawaran dan dokumen penerimaan. Jika perlu memeriksa konteks produk lain, mulai dari [halaman utama Besi.co.id](/) agar rujukan tidak tertukar. Untuk membandingkan jenis material secara umum, Anda dapat melihat [kategori besi beton](/besi-beton) sebelum mengunci kelompok cut list.

Ada empat angka yang sering tertukar:

- **Panjang bersih**: panjang komponen setelah proses yang ditentukan gambar.
- **Allowance proses**: tambahan untuk facing, bevel, trimming, atau proses lain yang memang disyaratkan.
- **Kerf**: lebar material yang menjadi serpihan atau celah potong. Nilainya bergantung pada mesin, mata potong, material, dan kondisi operasi; jangan menganggapnya nol.
- **Remnant**: sisa stock yang masih dapat diidentifikasi, disimpan, dan dipakai kembali menurut aturan proyek.

Artikel ini membahas perencanaan kuantitas. Ia tidak menetapkan grade, kelas toleransi, jadwal pipa, acceptance criteria, atau metode inspeksi. Dimensi dan massa teoritis harus dirujukkan ke standar produk yang benar. ISO 4200 dan ASME B36.10, misalnya, menyediakan kerangka tabel dimensi dan massa untuk produk pipa tertentu, tetapi tabel tersebut bukan pengganti spesifikasi pembelian atau pengukuran aktual ([ISO 4200](https://www.iso.org/standard/9985.html); [ASME B36.10](https://www.asme.org/codes-standards/find-codes-standards/welded-and-seamless-wrought-steel-pipe)).

## Cara kerjanya

Mulai dari satu baris cut list, bukan dari total tonase. Lakukan urutan berikut.

1. **Bekukan identitas material.** Pisahkan diameter atau penampang, grade, finishing, dan heat/batch bila traceability diwajibkan. Jangan mencampur item yang tampak sama tetapi memiliki spesifikasi berbeda.
2. **Normalisasi satuan dan panjang.** Simpan panjang dalam satu satuan. Bedakan panjang jadi dari allowance proses. Tandai apakah angka itu nominal atau hasil pengukuran.
3. **Kelompokkan menurut stock yang benar.** Stock length adalah panjang batang yang benar-benar tersedia atau ditawarkan, bukan angka yang diasumsikan. Jika pemasok menawarkan beberapa panjang, hitung setiap opsi sebagai skenario terpisah.
4. **Tambahkan kebutuhan proses yang disetujui.** Untuk setiap piece, gunakan panjang rencana = panjang jadi + allowance yang disetujui. Kerf ditambahkan di antara dua potongan berurutan, sesuai prosedur mesin. Jangan memakai satu angka kerf universal.
5. **Susun rencana pemotongan.** Jumlahkan panjang rencana dan kerf dalam satu bar sampai tidak melampaui panjang stock dengan sisa yang masih dapat diterima. Ini perencanaan manual atau spreadsheet, bukan jaminan nesting optimum.
6. **Terapkan kebijakan remnant.** Putuskan minimum panjang remnant, cara pelabelan, masa simpan, dan apakah remnant boleh dipakai untuk item lain. Jika kebijakan belum tertulis, hitung skenario konservatif: remnant tidak mengurangi pembelian.
7. **Pisahkan hasil kuantitas dan massa.** Keluaran minimal adalah jumlah bar yang dibeli/di-issue, daftar potongan per bar, remnant yang direncanakan, dan asumsi yang dipakai.

Rumus bantu yang aman untuk spreadsheet adalah:

`panjang_terpakai = Σ panjang_rencana_piece + (jumlah_piece_dalam_bar − 1) × kerf`

Satu bar sah bila `panjang_terpakai ≤ panjang_stock` dan sisa memenuhi kebijakan remnant. Bila potongan terakhir tidak memerlukan kerf setelahnya, jangan menambah kerf ekstra di ujung bar.

Untuk massanya, gunakan basis yang jelas: `massa_teoritis = panjang × massa_teoritis_per_satuan_panjang` dari tabel produk yang berlaku, atau formula penampang yang disetujui. Massa teoritis tidak sama dengan hasil timbangan, karena panjang aktual, toleransi dimensi, finishing, dan pembulatan dapat berbeda. ISO 4200 menjelaskan hubungan massa dengan geometri dan tabel produk; verifikasi terhadap dokumen pasokan tetap diperlukan ([ISO 4200](https://www.iso.org/standard/9985.html)).

Dokumentasikan siapa yang menyetujui cut list, revisi gambar, dan aturan kerf. Saat serah terima, cocokkan dokumen inspeksi dengan order, produsen, heat/batch, dimensi, hasil tes, serta marking fisik. ISO 10474 membahas kerangka dokumen inspeksi; kompetensi laboratorium menurut ISO/IEC 17025 membantu menilai keandalan hasil, tetapi akreditasi saja tidak membuktikan item tertentu sudah sesuai ([ISO 10474](https://www.iso.org/standard/53736.html); [ISO/IEC 17025](https://www.iso.org/standard/66912.html)).

## Faktor yang mengubah hasil

**Stock length dan ketersediaan.** Dua vendor dapat memberi panjang nominal berbeda. Jangan menggabungkan stock yang belum dikonfirmasi dalam satu angka pembelian.

**Kerf dan urutan potong.** Kerf dipengaruhi proses. Urutan yang memerlukan pemotongan tambahan, facing, atau pemisahan ujung dapat mengubah sisa. Minta data uji proses atau prosedur internal, bukan menyalin angka dari pekerjaan lain.

**Toleransi dan fungsi.** Panjang cut list bukan izin untuk mengabaikan toleransi. Kelas toleransi, metode ukur, pengaruh panas, dan persyaratan edge harus mengikuti gambar serta prosedur yang disetujui. ISO 9013 membahas kualitas potongan termal dan ISO 13920 toleransi umum konstruksi las, tetapi penerapannya perlu dikaitkan dengan material, proses, dan fungsi aktual ([ISO 9013](https://www.iso.org/standard/60321.html); [ISO 13920](https://www.iso.org/standard/86032.html)). **[NEEDS GATE-04: kelas toleransi, metode ukur, dan kriteria penerimaan pada dokumen proyek]**

**Remnant dan traceability.** Sisa yang tidak berlabel dapat berubah menjadi scrap praktis. Jika heat/batch harus dilacak, label remnant harus mempertahankan identitasnya; jangan mengklaim material masih dapat dipakai sebelum pemeriksaan.

**Massa teoritis versus aktual.** Tonase untuk anggaran dapat memakai massa teoritis yang disepakati. Untuk penerimaan atau penagihan, basisnya bisa berbeda dan harus tertulis di order. **[NEEDS GATE-06: basis massa, pembulatan, dan aturan komersial pemasok]**

**Perubahan revisi.** Satu perubahan panjang atau jumlah dapat mengubah seluruh pola potong. Simpan nomor revisi cut list pada lembar perhitungan dan blokir versi lama di area produksi.

## Contoh keputusan praktis

Anggap ini contoh metode, bukan data proyek: ada stock 6 m dan tiga kelompok potongan rencana 2,4 m, 1,8 m, dan 1,2 m. Jika kerf dan allowance membuat jumlahnya melewati 6 m, jangan memaksa tiga piece ke satu bar. Uji urutan lain hanya bila sisa dan orientasi potong tetap memenuhi prosedur. Jika sisa di bawah minimum remnant, catat sebagai scrap; jika di atas minimum dan identitasnya utuh, catat sebagai remnant untuk pekerjaan berikutnya.

Gunakan tabel keputusan sederhana berikut:

| Pertanyaan | Jika “ya” | Jika “belum” |
|---|---|---|
| Stock length dikonfirmasi pemasok? | Pakai angka itu per skenario. | Tandai estimasi; jangan kunci PO. |
| Kerf dan allowance disetujui? | Masukkan ke setiap bar. | Minta data proses; gunakan marker review. |
| Remnant punya batas minimum dan label? | Kurangi pembelian sesuai aturan. | Hitung remnant sebagai tidak tersedia. |
| Toleransi dan metode ukur ada di dokumen? | Verifikasi hasil potong terhadapnya. | **[NEEDS GATE-08: review teknis sebelum produksi]** |
| Basis massa tertulis? | Laporkan teoritis dan aktual sesuai basis. | Pisahkan keduanya dan minta klarifikasi komersial. |

Kawan Besi.co.id, hasil akhir sebaiknya menampilkan dua skenario bila kebijakan remnant belum diputuskan: “remnant dapat dipakai” dan “remnant tidak dihitung”. Selisihnya adalah keputusan risiko dan persediaan, bukan bonus nesting.

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah membagi total panjang dengan stock length lalu membulatkan ke atas. Periksa kembali kerf, allowance, dan distribusi panjang; dua potongan yang sama-sama muat secara total belum tentu muat dalam satu bar.

Kesalahan kedua adalah mencampur item berbeda karena penampangnya terlihat sama. Cocokkan spesifikasi, revisi gambar, dan marking sebelum menggabungkan kelompok.

Kesalahan ketiga adalah memakai angka kerf atau toleransi dari pekerjaan lama. Tanyakan mesin, material, ketebalan, dan metode ukur yang mendasarinya. Standar hanya menjadi rujukan bila ruang lingkupnya cocok; jangan mengubah rujukan umum menjadi janji performa.

Kesalahan keempat adalah melaporkan massa teoritis sebagai massa aktual. Simpan kolom terpisah untuk panjang teoritis, massa per satuan panjang, hasil timbangan, dan aturan pembulatan. Jika dokumen pemasok tidak sejalan, tahan keputusan penerimaan sampai ada review.

Shortcut yang paling menggoda adalah memesan satu bar tambahan sebagai “buffer” tanpa mencatat alasannya. Cara ini mungkin menutupi ketidakpastian, tetapi menyulitkan audit dan dapat menciptakan remnant yang tidak terpakai. Alternatif yang lebih aman adalah mencatat asumsi, menghitung skenario konservatif, lalu meminta persetujuan kuantitas dari fabricator/QS dan pemeriksa teknis.

## Kesimpulan dan langkah berikutnya

Menghitung kebutuhan bar dari cut list berarti mengubah daftar piece menjadi rencana pemotongan per bar dengan stock length, allowance, kerf, remnant, dan toleransi yang dinyatakan. Setelah itu, laporkan jumlah bar dan massa teoritis secara terpisah dari massa aktual atau basis komersial.

Sebelum mengunci pembelian, minta tiga dokumen: cut list dengan revisi terakhir, konfirmasi stock length serta aturan remnant dari pemasok, dan prosedur toleransi/inspeksi yang disetujui. **[NEEDS GATE-01, GATE-04, GATE-06, GATE-08: coordinator technical review tetap diperlukan sebelum hasil dipakai sebagai kuantitas final.]** Jika masih ada asumsi yang perlu diklarifikasi, siapkan pertanyaan dan kirimkan melalui [halaman kontak Besi.co.id](/kontak) agar pihak yang berwenang dapat meninjau.

Teman Besi.co.id, aturan operasionalnya sederhana: jangan menyebut jumlah bar “final” selama panjang stock, kerf, remnant, toleransi, dan basis massa belum tertulis serta ditinjau oleh pihak yang berwenang. Aset gambar yang menyertai artikel hanya berfungsi sebagai ilustrasi umum, bukan bukti proyek atau performa material.

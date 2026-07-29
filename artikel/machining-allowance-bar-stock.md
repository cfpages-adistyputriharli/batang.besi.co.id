---
article_id: BAR-07-02
title: "Machining Allowance dan Kondisi Permukaan Bar Stock"
slug: "machining-allowance-bar-stock"
description: "Cover decarb/scale, straightness, defects, tolerance, stock allowance, traceability"
writing_contract_version: "native-id-v2"
status: draft
publication_date: "2026-01-27"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: BAR-07
primary_intent: "Plan machining"
reader_community: "Besi.co.id"
reader_address: "Teman Besi.co.id"
final_route: "/artikel/machining-allowance-bar-stock.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/78322.html"
  - "https://www.iso.org/standard/72529.html"
  - "https://www.iso.org/standard/89449.html"
  - "https://www.iso.org/standard/60321.html"
  - "https://www.iso.org/standard/87851.html"
  - "https://www.iso.org/standard/86032.html"

---

# Machining Allowance dan Kondisi Permukaan Bar Stock

Halo, Teman Besi.co.id! Sebelum bar stock masuk mesin, jangan langsung menganggap diameter atau sisi luarnya sebagai ukuran siap jadi. Keputusan yang aman adalah menetapkan **machining allowance** (tambahan material untuk dibuang) dari ukuran jadi pada gambar, lalu memeriksa kondisi permukaan, kelurusan, cacat, toleransi, dan identitas heat atau lot. Jika data itu belum lengkap, bar belum siap direncanakan untuk machining.

Allowance bukan angka tebakan dan bukan pengganti toleransi. Decarb atau scale, kulit hasil pemotongan panas, goresan, lubang, atau bagian yang tidak lurus dapat menghabiskan allowance sebelum bentuk akhir tercapai. Nilai yang benar bergantung pada kondisi pasokan, proses pemotongan, datum, ukuran akhir, dan persyaratan gambar. Karena packet ini tidak memuat gambar atau sertifikat material proyek, keputusan penerimaan akhir memerlukan **[NEEDS GATE-01: gambar, spesifikasi produk, dan persetujuan QC]**.

<!-- BEGIN MANAGED IMAGE PLAN
Image ID: LOCAL-001
Source type: local
Placement: after the opening has answered the main question, before the first detailed H2
**Exact Markdown to insert:** `![Ilustrasi harga besi as](/wp-content/uploads/2024/07/harga-besi-as.jpg)`
Caption/credit: Aset lokal proyek; jangan klaim sebagai dokumentasi proyek tertentu.
Selection basis: filename/source metadata identifies `harga besi as` as relevant content media; no pixels were inspected.
Hard boundary: do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
Substitution rule: do not replace this image. If unavailable or provenance is incomplete, insert [NEEDS IMAGE REVIEW: LOCAL-001] and continue drafting the prose.
END MANAGED IMAGE PLAN -->

![Ilustrasi harga besi as](/wp-content/uploads/2024/07/harga-besi-as.jpg)

Ilustrasi umum dari aset lokal Besi.co.id; bukan dokumentasi proyek tertentu.

## Jawaban singkat dan salah paham utama

Mulai dari ukuran jadi, bukan ukuran nominal bar. Tulis allowance sebagai selisih yang sengaja disediakan pada setiap permukaan yang akan dimachining. Setelah itu, pastikan permukaan yang tersisa setelah material dibuang masih bebas dari lapisan atau cacat yang tidak boleh masuk ke komponen. Bar yang “lebih besar” belum tentu lebih aman: scale tebal, decarb, ovalitas, atau bengkok dapat membuat material bersih tidak cukup di satu sisi.

Salah paham lain adalah menyamakan hasil uji tarik dengan jaminan seluruh batang. ISO 6892-1 menjelaskan metode uji tarik pada temperatur ruang, sedangkan ISO 377 menjelaskan pengambilan sampel dan benda uji; keduanya tidak otomatis membuktikan seluruh bar memenuhi grade atau toleransi. Identitas spesimen, orientasi, lokasi, kondisi, metode, dan heat harus tetap tertaut pada laporan ([ISO 6892-1:2019](https://www.iso.org/standard/78322.html), [ISO 377:2017](https://www.iso.org/standard/72529.html), serta amendemennya [ISO 377:2017/Amd 1:2025](https://www.iso.org/standard/89449.html)).

## Definisi dan batas objek

**Bar stock** di sini berarti batang bahan awal yang akan dijadikan komponen melalui proses pemotongan dan machining. **Machining allowance** adalah material ekstra antara ukuran pasokan dan ukuran akhir; allowance harus cukup untuk menghilangkan kulit, ketidaklurusan, dan variasi proses, tetapi tidak boleh membuat proses boros atau mengganggu rasio penampang.

**Decarb** adalah zona permukaan dengan perubahan kandungan karbon akibat pemanasan; **scale** adalah lapisan oksida. Keduanya tidak boleh diasumsikan hilang hanya karena permukaan tampak gelap atau mengilap. Cacat seperti lap, retak terbuka, laminasi, atau pitting memerlukan kriteria penerimaan dari spesifikasi produk dan pemeriksaan yang disetujui. Artikel ini tidak menetapkan parameter spindle, feed, depth of cut, atau strategi toolpath. Fokusnya adalah keputusan sebelum machining.

Ukuran nominal, toleransi manufaktur bar, dan toleransi komponen adalah tiga hal berbeda. Standar umum atau katalog hanya memberi kerangka; kelas toleransi dan metode ukurnya harus berasal dari gambar dan spesifikasi yang berlaku. **[NEEDS GATE-04: toleransi bar, toleransi komponen, dan metode ukur yang disetujui]**

## Cara kerjanya

Urutkan pemeriksaan agar allowance tidak dihitung dari data yang salah:

1. **Kunci identitas.** Cocokkan heat/lot, ukuran, grade, bentuk penampang, sertifikat, dan tanda pada bundel. Pisahkan batang yang identitasnya putus.
2. **Baca kebutuhan jadi.** Dari gambar, catat datum, permukaan kritis, ukuran akhir, toleransi, chamfer, dan area yang tidak boleh memiliki cacat. Jangan mengubah toleransi menjadi allowance.
3. **Petakan kondisi awal.** Ukur diameter atau sisi pada beberapa posisi dan arah, cek straightness dengan metode yang disetujui, serta tandai scale, decarb, goresan, lubang, atau ujung rusak. Catatan inspeksi harus menyebut alat, titik, kondisi, dan hasil; bukan hanya “OK”.
4. **Hitung kebutuhan penghilangan.** Untuk tiap permukaan, gabungkan selisih ukuran, penyimpangan bentuk, material kulit yang harus dibuang, dan margin proses yang disetujui. Nilai minimum di sisi terburuk yang menentukan apakah stok cukup.
5. **Tentukan datum dan urutan.** Permukaan referensi harus dipilih agar ketidaklurusan dan run-out tidak dipindahkan ke fitur kritis. Tandai orientasi serta panjang potong supaya jejak identitas tetap terbaca.
6. **Verifikasi setelah roughing.** Periksa apakah kulit dan cacat yang ditolak sudah hilang sebelum finishing. Bila tidak, hentikan dan naikkan isu ke QC; jangan menutupinya dengan memperkecil ukuran akhir tanpa persetujuan.

Sobat Besi.co.id, catatan traceability bukan formalitas. Saat hasil ukur atau uji dipertanyakan, hubungan antara potongan, heat, sertifikat, dan laporan inspeksi menentukan apakah keputusan dapat dipertanggungjawabkan.

## Faktor yang mengubah hasil

Beberapa faktor sering mengubah allowance yang dibutuhkan:

- **Kondisi pasokan:** hot-rolled, cold-finished, forged, atau thermal-cut memiliki kulit dan variasi berbeda. Untuk tepi hasil potong panas, ISO 9013 dan amendemennya membahas klasifikasi kualitas potongan termal, tetapi kelas yang dipilih tetap harus ditetapkan oleh gambar atau prosedur proyek ([ISO 9013:2017](https://www.iso.org/standard/60321.html), [ISO 9013:2017/Amd 1:2024](https://www.iso.org/standard/87851.html)).
- **Bentuk dan panjang:** batang panjang dapat memiliki straightness dan perubahan penampang sepanjang sumbu. Mengukur satu ujung saja dapat melewatkan sisi terburuk.
- **Cacat permukaan:** cacat dangkal mungkin hilang saat roughing; cacat dalam atau memanjang dapat tetap muncul dan memerlukan disposition, bukan sekadar allowance lebih besar.
- **Kebutuhan fungsi:** datum bantalan, ulir, seal, atau sambungan membutuhkan kontrol berbeda. General tolerance tidak otomatis berlaku untuk setiap fitur; ISO 13920 adalah standar toleransi umum konstruksi las, bukan izin memakai satu angka untuk semua komponen machined ([ISO 13920:2023](https://www.iso.org/standard/86032.html)).
- **Bukti dan alat ukur:** kalibrasi, resolusi alat, temperatur, metode sampling, dan kompetensi pemeriksa memengaruhi keyakinan pada hasil. **[NEEDS GATE-06: rencana inspeksi, alat terkalibrasi, dan disposition cacat]**

## Contoh keputusan praktis

Gunakan skenario berikut sebagai cara berpikir, bukan angka siap pakai.

| Situasi stok | Keputusan awal | Bukti yang harus diminta |
|---|---|---|
| Ukuran awal cukup, permukaan bersih, identitas lengkap | Lanjutkan review datum dan allowance per sisi | Gambar, sertifikat, catatan ukur |
| Ukuran cukup di satu arah tetapi oval atau bengkok | Tahan; hitung sisi terburuk dan evaluasi stok baru | Peta ukur multi-titik, batas straightness |
| Scale/decarb diperkirakan lebih dalam dari material ekstra | Jangan mulai produksi | Kriteria kedalaman/permukaan dari spesifikasi dan pemeriksaan yang disetujui |
| Heat/lot tidak terbaca atau sertifikat tidak cocok | Karantina dan telusuri ulang | Rekaman penerimaan, mill certificate, identifikasi potongan |
| Cacat terbuka terlihat setelah roughing | Hentikan, dokumentasikan, minta disposition | Foto/rekaman inspeksi, keputusan QC/engineering |

Kawan Besi.co.id, perhatikan kata “cukup” dalam tabel: cukup berarti lolos seluruh pemeriksaan dan persyaratan proyek, bukan sekadar diameter lebih besar dari ukuran akhir. Tanpa data gambar dan spesifikasi produk, **[NEEDS GATE-01]** tetap terbuka.

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah memakai satu allowance untuk semua diameter dan panjang. Periksa setiap permukaan kritis dan nyatakan sisi minimum setelah memperhitungkan bentuk awal. Kedua, mengukur sebelum bar stabil atau tanpa metode yang konsisten. Tetapkan kondisi ukur, titik sampling, dan alat sebelum membandingkan hasil.

Ketiga, menghapus tanda heat saat memotong. Buat aturan pemindahan identitas ke setiap potongan dan rekam siapa yang memverifikasi. Keempat, menerima sertifikat tanpa mencocokkan heat, grade, ukuran, dan dokumen pembelian. Kelima, menganggap standar metode uji sebagai spesifikasi penerimaan. ISO 6892-1 dan ISO 377 membantu menjelaskan bagaimana pengujian dilakukan dan sampel disiapkan; nilai lulus/gagal tetap mengikuti spesifikasi material dan laporan aktual.

Pakai pertanyaan berhenti berikut sebelum mengeluarkan work order: “Apa ukuran akhir dan datum-nya? Berapa material kulit yang harus dihilangkan menurut dokumen yang berlaku? Di mana titik terburuk hasil ukur? Bagaimana identitas potongan dijaga? Siapa yang menyetujui cacat atau deviasi?” Jika salah satu jawabannya belum terdokumentasi, tahan rencana dan buka **[NEEDS TECHNICAL REVIEW: GATE-04/GATE-06]**.

## Jalan pintas yang tampak praktis

Shortcut yang sering dipilih adalah membeli bar sedikit lebih besar lalu menyerahkan keputusan kepada operator mesin. Cara ini gagal ketika cacat atau bengkok berada di sisi yang tidak terlihat, atau ketika material tambahan habis sebelum permukaan bersih tercapai. Perubahan grade, toleransi, atau disposition cacat harus mengikuti persetujuan yang ditetapkan proyek; jangan mengandalkan keputusan operator seorang diri.

Alternatif yang lebih andal adalah membuat lembar penerimaan sederhana: identitas heat/lot, ukuran multi-titik, straightness, kondisi kulit, cacat, allowance minimum per permukaan, dan tanda tangan pemeriksa. Lampirkan gambar serta spesifikasi yang menjadi dasar. Bila bukti tidak cukup, tandai **[NEEDS CURRENT PROJECT EVIDENCE AND COMPETENT REVIEW]** dan jangan mengisi kekosongan dengan asumsi.

## Langkah penutup

Machining allowance bar stock harus ditetapkan dari ukuran akhir dan kondisi terburuk stok, lalu diverifikasi terhadap permukaan, straightness, cacat, toleransi, dan traceability. Ukuran nominal atau satu hasil uji tidak cukup untuk menyatakan stok siap.

Langkah berikutnya: minta gambar terbaru, spesifikasi produk, sertifikat heat/lot, dan format inspeksi; ukur stok pada titik yang disepakati; kemudian minta QC/engineering menutup **[NEEDS GATE-01, GATE-04, GATE-06]** sebelum work order diterbitkan. Untuk membandingkan kebutuhan material awal, lihat [panduan besi beton](/besi-beton); bila dokumen proyek belum lengkap, lanjutkan koordinasi melalui [halaman kontak](/kontak). Aturan operasinya sederhana: jika allowance minimum, identitas, atau kriteria cacat belum terbukti, bar tetap berstatus hold.

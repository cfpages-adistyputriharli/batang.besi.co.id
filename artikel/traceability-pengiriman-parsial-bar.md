---
article_id: BAR-12-05
title: "Traceability setelah Bar Dipotong dan Dikirim Parsial"
slug: "traceability-pengiriman-parsial-bar"
description: "Panduan menjaga jejak ID potongan, MTC, packing list, sisa, retur, dan substitusi saat bar dikirim parsial."
writing_contract_version: "native-id-v2"
status: draft
publication_date: "2026-06-11"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: BAR-12
primary_intent: "Preserve records"
reader_community: "Besi.co.id"
reader_address: "Sobat Besi.co.id"
final_route: "/artikel/traceability-pengiriman-parsial-bar.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/72532.html"
  - "https://www.iso.org/cms/live/live/en/sites/isoorg/contents/news/2026/03/new-iso-standards-bring-clarity.html"
  - "https://lysaght.com/support-technical/support/installation/product-care-and-storage-installation"
  - "https://jdih.kemnaker.go.id/peraturan/detail/1668/peraturan-menteri-nomor-8-tahun-2020"
---

# Traceability setelah Bar Dipotong dan Dikirim Parsial

<!-- BEGIN MANAGED IMAGE PLAN
Image ID: LOCAL-001
**Exact Markdown to insert:** `![Ilustrasi harga besi as](/wp-content/uploads/2024/07/harga-besi-as.jpg)`
![Ilustrasi harga besi as](/wp-content/uploads/2024/07/harga-besi-as.jpg)
Placement: setelah pembuka menjawab pertanyaan utama, sebelum H2 pertama
Caption/credit: Ilustrasi umum dari aset lokal Besi.co.id; bukan dokumentasi proyek tertentu.
END MANAGED IMAGE PLAN -->
Halo, Sobat Besi.co.id!

Ketika satu batang dipotong lalu dikirim dalam beberapa tahap, identitas material tidak boleh ikut terputus. Jawaban praktisnya: setiap potongan harus memiliki ID yang dapat ditelusuri kembali ke batang induk, pesanan, sertifikat uji material (MTC), dan packing list pada pengiriman tertentu. Catat juga sisa potongan, pengembalian, penggantian, dan siapa yang menyetujui perubahan. Untuk konteks dokumen proyek lain, Anda dapat mulai dari [beranda Besi.co.id](/).

Packing list tanpa hubungan ke MTC hanya membuktikan ada paket, bukan asal materialnya. Sebaliknya, MTC tanpa daftar potongan dan serah-terima membuat penerima sulit membuktikan potongan mana yang diterima. Bentuk rekaman yang tepat bergantung pada kontrak, sistem mutu, dan bukti proyek yang berlaku. **[NEEDS GATE-01: konfirmasi skema identifikasi dan persetujuan proyek]**

![Ilustrasi harga besi as](/wp-content/uploads/2024/07/harga-besi-as.jpg)

*Ilustrasi umum dari aset lokal Besi.co.id; bukan dokumentasi proyek tertentu.*

## Definisi dan batas objek

Traceability di sini berarti jejak administratif dan fisik dari batang induk sampai potongan yang dikirim parsial. “Piece ID” adalah kode unik untuk satu potongan atau satu bundel; “heat/lot” adalah identitas produksi yang tercantum pada dokumen pemasok; MTC adalah sertifikat yang menghubungkan heat/lot dengan hasil uji yang diserahkan pemasok. Ketiganya bukan jaminan keaslian dengan sendirinya. Keaslian memerlukan pemeriksaan dokumen asli, tanda material, dan persetujuan pihak yang berwenang.

Batas artikel ini adalah pengendalian catatan. Ia tidak menetapkan ukuran potong, toleransi, kapasitas angkat, metode pengelasan, atau penerimaan struktur. Panduan chain-of-custody ISO menjelaskan bahwa model segregasi fisik, mass-balance, dan klaim administratif memiliki aturan berbeda; sistem harus menetapkan karakteristik yang dilacak, batas sistem, pihak bertanggung jawab, serta aturan transfer dan anti-penghitungan ganda ([ISO 22095](https://www.iso.org/standard/72532.html), [pembaruan ISO 2026](https://www.iso.org/cms/live/live/en/sites/isoorg/contents/news/2026/03/new-iso-standards-bring-clarity.html)).

## Cara kerjanya

Mulai dari satu baris “master record” untuk batang induk. Isinya minimal nomor pesanan atau heat/lot sesuai dokumen pemasok, profil dan panjang yang dipesan, tanggal diterima, MTC yang dirujuk, serta status pemeriksaan. Jangan mengubah ID induk ketika batang dipotong; buat turunan seperti `INDUK-01-A`, `INDUK-01-B`, dan `INDUK-01-SISA`. Format bebas, tetapi harus unik, konsisten, dan dijelaskan dalam prosedur.

Sebelum memotong, buat cutting list yang menghubungkan nomor gambar atau permintaan kerja, panjang rencana, jumlah, dan operator atau pemeriksa. Setelah potong, ukur dan catat hasil aktual, tanggal, alat ukur bila diwajibkan prosedur, serta deviasi yang memerlukan persetujuan. Piece ID ditempel pada potongan atau tag bundel yang tetap terbaca selama pemindahan. Jika tag bisa lepas, gunakan dua titik penandaan atau rekaman foto sesuai prosedur proyek—bukan sebagai pengganti pemeriksaan.

Setiap pengiriman parsial memiliki nomor packing list sendiri. Daftar itu menyebut piece ID, kuantitas, panjang atau berat yang disepakati, kondisi kemasan, kendaraan atau tanggal muat bila diwajibkan, serta dokumen yang ikut: MTC, cutting list, catatan inspeksi, dan surat jalan. Pada penerimaan, pihak penerima membubuhkan status cocok, kurang, rusak, atau ditahan (quarantine). Satu koreksi harus meninggalkan jejak: siapa mengubah, kapan, alasan, dan referensi persetujuannya.

Simpan tabel rekonsiliasi: kuantitas batang induk = potongan terkirim + sisa di gudang + retur + potongan ditolak atau diganti. Rumus ini adalah pemeriksaan aritmetika, bukan bukti mutu. Selisih harus menjadi tiket penyimpangan, bukan dihapus dengan mengedit packing list lama.

## Faktor yang mengubah hasil

Pertama, perubahan fisik. Potongan yang dipendekkan lagi, dibor, dilas, atau digabung harus memperoleh ID revisi dan rujukan gambar atau instruksi yang menyetujui perubahan. Sisa (remnant) tetap berstatus material yang belum dialokasikan sampai diperiksa dan diberi lokasi penyimpanan. Jangan mengembalikan sisa ke stok umum tanpa label asal.

Kedua, kondisi pengiriman. Penandaan dapat tertutup lumpur, kondensasi, atau kerusakan kemasan. Panduan penyimpanan pabrikan menekankan perlunya dukungan stabil, pencegahan terguling atau menyebar, akses antar tumpukan, drainase dan ventilasi, serta perlindungan dari cuaca dan kontak yang merusak lapisan ([LYSAGHT product care](https://lysaght.com/support-technical/support/installation/product-care-and-storage-installation)). Ketentuan tersebut adalah panduan teknis, bukan otomatis aturan hukum Indonesia. Untuk pengangkatan, massa, geometri, titik berat, alat, dan catatan pemeriksaan harus mengikuti desain angkat dan persyaratan K3 yang berlaku; rujuk sumber nasional seperti [Permenaker 8/2020](https://jdih.kemnaker.go.id/peraturan/detail/1668/peraturan-menteri-nomor-8-tahun-2020) bersama penanggung jawab K3.

Ketiga, klaim keberlanjutan atau asal. Bila pelanggan meminta klaim berbasis rantai pasok, pisahkan catatan material yang benar-benar tersegregrasi dari klaim mass-balance atau administratif. Jangan mencampur model di satu packing list tanpa menyebut aturan transfer dan batas klaim. **[NEEDS GATE-02: skema klaim, batas assurance, dan bukti transaksi harus disetujui proyek]**

Keempat, retur dan substitusi. Retur menerima ID lama, alasan, kondisi saat tiba, dan status karantina. Substitusi tidak boleh hanya diberi label “pengganti”; catat ID material pengganti, alasan, persetujuan desain atau pembeli, MTC yang relevan, serta pembaruan packing list. Jika persetujuan belum ada, tandai “hold” dan jangan memasukkannya ke stok siap kirim.

## Contoh keputusan praktis

Bayangkan pesanan memerlukan dua pengiriman. Pada pengiriman pertama, penerima menandatangani tiga bundel dan menyatakan satu bundel basah dengan tag tidak terbaca. Keputusan aman bukan menebak heat/lot dari bentuknya. Catat sebagai `HOLD-01`, cocokkan berat dan jumlah hanya sebagai data bantu, lalu minta verifikasi dokumen dan penandaan ulang.

| Situasi | Catatan minimum | Keputusan sementara |
| --- | --- | --- |
| ID, packing list, dan MTC cocok | Tanggal terima, pemeriksa, kondisi | Terima dan pindahkan ke lokasi berlabel |
| ID terbaca, MTC belum tersedia | Nomor ID, dokumen kurang, status hold | Jangan klaim kesesuaian material |
| Tag hilang atau rusak | Foto kondisi, lokasi, nomor kendaraan, saksi | Karantina sampai identitas dipulihkan |
| Potongan retur | ID lama, alasan, kondisi, pemeriksaan ulang | Kembalikan ke stok hanya setelah rilis tertulis |
| Substitusi disetujui | ID pengganti, MTC, persetujuan, revisi daftar | Terbitkan packing list revisi dan tutup jejak lama |

Kawan Besi.co.id, contoh ini tidak menetapkan kriteria penerimaan. Ia menunjukkan urutan keputusan ketika bukti tidak lengkap: tahan, rekonsiliasi, minta persetujuan, lalu rilis. Simpan versi kerja ini bersama dokumen operasional di [halaman besi dan produk Besi.co.id](/besi-beton) agar tim memakai prosedur yang sama.

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah memakai nomor bundel yang sama untuk pengiriman berbeda. Tambahkan nomor pengiriman dan tanggal pada packing list, tetapi pertahankan piece ID agar riwayat tetap tersambung. Kesalahan kedua adalah menyalin MTC ke semua potongan tanpa memastikan setiap potongan memang berasal dari heat/lot tersebut. Buat kolom “MTC reference” per ID dan larang sel kosong pada saat rilis.

Kesalahan ketiga adalah menghapus baris ketika jumlah berubah. Gunakan status batal, retur, atau diganti sehingga rekaman awal tetap terlihat. Kesalahan keempat adalah menganggap tanda tangan penerima sebagai bukti mutu. Tanda tangan hanya bukti serah-terima pada kondisi yang dicatat; inspeksi dan keputusan teknis tetap terpisah.

Pemeriksaan mingguan dapat berupa empat pertanyaan: apakah semua ID fisik muncul di packing list; apakah setiap ID menunjuk satu MTC dan cutting list; apakah total potongan, sisa, retur, dan reject merekonsiliasi batang induk; dan apakah setiap perubahan memiliki persetujuan. Sobat Besi.co.id, simpan versi dokumen dengan kendali akses, cadangan, dan masa retensi sesuai kontrak. **[NEEDS GATE-04: periode retensi, penanggung jawab, dan format rekaman harus ditetapkan proyek]**

## Jalan pintas yang sering dipilih

Shortcut yang tampak hemat adalah mengirim potongan dengan label profil dan panjang saja, lalu “mencocokkan MTC nanti”. Ini gagal ketika beberapa heat/lot memiliki profil serupa, ketika terjadi retur, atau ketika pelanggan meminta jejak pengiriman tertentu. Pencocokan setelah fakta juga tidak memulihkan identitas yang sudah hilang.

Alternatifnya adalah menetapkan titik henti: tidak ada potongan keluar tanpa piece ID, packing list, dan rujukan MTC; tidak ada retur masuk tanpa status karantina; dan tidak ada substitusi tanpa persetujuan. Teman Besi.co.id, bila sistem Anda belum mampu menghasilkan tiga catatan itu, gunakan formulir terkendali sementara dan minta review mutu sebelum pengiriman berikutnya.

## Penutup

Traceability setelah bar dipotong dan dikirim parsial berarti menjaga hubungan utuh antara batang induk, piece ID, MTC, cutting list, packing list, sisa, retur, dan substitusi. Buat master record, rekonsiliasi setiap pergerakan, tahan material yang identitasnya meragukan, dan dokumentasikan persetujuan perubahan.

Langkah berikutnya: ambil satu pesanan aktif, uji empat pertanyaan pemeriksaan di atas, lalu minta penanggung jawab mutu dan K3 menandatangani prosedur identifikasi, penyimpanan, dan serah-terima. Untuk menyiapkan formulir dan rekaman terkait, hubungi [kontak Besi.co.id](/kontak). Catatan yang rapi membantu audit, tetapi tidak menjamin keaslian atau penerimaan struktur tanpa verifikasi dokumen asli dan persetujuan profesional.

**[NEEDS GATE-06: konfirmasi akhir tentang batas klaim, penerimaan, dan review teknis sebelum publikasi.]**

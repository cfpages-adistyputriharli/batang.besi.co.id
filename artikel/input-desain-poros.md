---
article_id: BAR-06-02
title: "Input Poros: Beban, Putaran, Keyway, dan Lingkungan"
slug: "input-desain-poros"
description: "Panduan menyiapkan data torsi, lentur, putaran, keyway, bearing, korosi, dan fatigue sebelum sizing poros"
status: draft
writing_contract_version: "native-id-v2"
publication_date: "2026-01-01"
publication_date_basis: editorial_backfill
date_modified: null
parent_topic: BAR-06
primary_intent: "Prepare shaft brief"
reader_community: "Besi.co.id"
reader_address: "Sobat Besi.co.id"
final_route: "/artikel/input-desain-poros.html"
technical_review: required
sources:
  - "https://www.iso.org/standard/78322.html"
  - "https://www.iso.org/standard/72529.html"
  - "https://www.iso.org/standard/89449.html"
  - "https://www.iso.org/standard/73841.html"
  - "https://www.fhwa.dot.gov/bridge/steel/pubs/nhi16016.pdf"
  - "https://www.fhwa.dot.gov/bridge/inspection/"
  - "https://www.fhwa.dot.gov/publications/ndec/ndecnews.cfm"
---

# Input Poros: Beban, Putaran, Keyway, dan Lingkungan

Halo, Sobat Besi.co.id! Sebelum memilih diameter atau meminta penawaran poros, tim mesin perlu membekukan input yang benar. Input yang dimaksud bukan hanya torsi nominal: gaya lentur, putaran, pola start-stop, keyway, tumpuan bearing, korosi, dan riwayat beban harus masuk dalam satu brief. Tanpa peta itu, angka dari katalog atau perhitungan awal mudah terlihat rapi tetapi menjawab kondisi yang keliru.

Jawaban singkatnya: siapkan lembar input yang memisahkan beban torsi dan lentur, menjelaskan siklus serta putaran, menunjukkan detail pengurang penampang seperti keyway, dan mencatat lingkungan serta kondisi bearing. Dokumen tersebut kemudian diperiksa engineer yang berwenang. Artikel ini membantu Anda menyiapkan data dan pertanyaan; ini bukan panduan sizing poros. [NEEDS GATE-01: data beban proyek dan kombinasi pembebanan belum tersedia]

![Ilustrasi harga besi as](/wp-content/uploads/2024/07/harga-besi-as.jpg)

*Ilustrasi umum dari aset lokal Besi.co.id; bukan dokumentasi proyek tertentu.*

## Definisi dan batas objek

“Input poros” adalah kumpulan kondisi yang diterima komponen sebelum analisis. Poros dapat meneruskan torsi, menerima gaya radial atau aksial dari pulley, gear, kopling, atau impeller, lalu menyalurkan reaksi ke bearing. Karena itu, satu nilai daya motor tidak cukup untuk menggambarkan keadaan di setiap penampang.

Ruang lingkup di sini berhenti pada penyiapan brief: identitas komponen, diagram gaya, putaran, siklus, detail geometri, tumpuan, material yang benar-benar dipesan, dan lingkungan operasi. Penentuan diameter, faktor keamanan, umur fatigue, pilihan perlakuan panas, serta persetujuan perubahan tetap menjadi pekerjaan engineer dan pemeriksa proyek. Jangan mengubah istilah “baja struktural” menjadi grade poros secara otomatis. ISO 630-1 menempatkan produk struktural dalam konteks bentuk, bagian standar, grade, kondisi pasokan, dimensi, dan persyaratan pesanan; abstraknya bukan pengganti spesifikasi produk yang berlaku ([ISO 630-1:2021](https://www.iso.org/standard/73841.html)).

Data material juga harus punya jejak. Hasil uji tarik hanya bermakna bila identitas heat atau produk, lokasi dan orientasi spesimen, persiapan, kondisi, metode, satuan, serta laporan laboratorium tercatat. ISO 6892-1 menjelaskan metode uji pada temperatur ruang, sedangkan ISO 377 dan amendemennya membahas pengambilan sampel dan benda uji; keduanya tidak otomatis membuktikan seluruh stok memenuhi grade atau mampu menahan beban poros ([ISO 6892-1:2019](https://www.iso.org/standard/78322.html), [ISO 377:2017](https://www.iso.org/standard/72529.html), [ISO 377:2017/Amd 1:2025](https://www.iso.org/standard/89449.html)). Untuk langkah dokumentasi berikutnya, Anda dapat mulai dari [beranda Besi.co.id](/) atau meninjau [produk besi as](/as-s45c).

## Cara kerjanya

Mulailah dari rantai beban. Minta engineer menggambar sumber daya, elemen transmisi, posisi bearing, dan lokasi penampang kritis. Untuk setiap keadaan operasi, tulis torsi dan gaya sebagai fungsi waktu atau setidaknya sebagai keadaan terpisah: mulai, normal, berhenti, macet, pembalikan arah, dan kejadian gangguan yang memang mungkin terjadi. Sertakan arah putaran dan tanda gaya; diagram tanpa arah sering membuat reaksi bearing tertukar.

Berikutnya cocokkan kecepatan. Catat rpm minimum, normal, maksimum yang diizinkan, serta berapa lama setiap keadaan berlangsung. Rasio reduksi, variasi kecepatan, dan start-stop mengubah frekuensi siklus yang dialami detail poros. Jika ada kontrol kecepatan, kirimkan rentang dan pola perintahnya, bukan hanya angka set point.

Setelah beban dan putaran, petakan geometri aktual. Tandai perubahan diameter, bahu, alur snap ring, ulir, lubang melintang, radius fillet, dan keyway. Keyway adalah alur tempat pasak meneruskan torsi; alur itu mengurangi penampang efektif dan menciptakan konsentrasi tegangan. Lebar, kedalaman, ujung alur, orientasi, serta radiusnya harus diambil dari gambar atau pengukuran yang disetujui, bukan ditebak dari nama komponen.

Terakhir, hubungkan material, bearing, dan lingkungan. Masukkan grade serta kondisi pasokan yang tercantum di sertifikat, jenis dan jarak bearing, kelonggaran atau preload yang disyaratkan, pelumasan, temperatur, kelembapan, media korosif, partikel, dan metode perlindungan permukaan. Bila poros pernah beroperasi, lampirkan jam kerja, perubahan beban, kejadian macet, inspeksi, dan perbaikan. Semua perubahan itu menjadi konteks untuk menilai fatigue dan retak, bukan sekadar catatan pemeliharaan.

## Faktor yang mengubah hasil

**Beban gabungan.** Torsi murni jarang bertahan di sepanjang poros. Gaya dari gear atau pulley menimbulkan lentur; gaya aksial dapat mengubah reaksi tumpuan. Nyatakan apakah angka yang diberikan adalah puncak, rata-rata, atau hasil pengukuran, dan pada titik mana angka itu berlaku. Jika kombinasi beban belum disepakati, tandai sebagai data terbuka, bukan mengisi dengan asumsi.

**Siklus dan transien.** Dua mesin dengan torsi puncak sama dapat memiliki risiko berbeda bila salah satunya sering start-stop atau membalik arah. Catat jumlah kejadian yang diketahui, urutan, durasi, dan kondisi ketika poros berhenti mendadak. Jangan menyimpulkan umur fatigue dari satu nilai kekuatan tarik; evaluasi fatigue memerlukan detail tegangan, riwayat beban, material, fabrikasi, dan kondisi kerusakan.

**Stress raiser dan kontak.** Keyway, bahu tajam, ulir, dan perubahan kekakuan adalah lokasi yang perlu ditinjau khusus. Posisi bearing menentukan momen lentur dan reaksi; perubahan dudukan, misalignment, atau preload dapat memindahkan lokasi kritis. Simpan gambar toleransi dan catatan alignment bersama brief. [NEEDS GATE-02: detail geometri, toleransi, dan alignment belum diverifikasi]

**Korosi dan temperatur.** Media basah, garam, bahan kimia, atau kondensasi dapat mengurangi penampang dan membuat cacat permukaan menjadi pemicu retak. Temperatur operasi memengaruhi pelumas, clearance, dan perilaku material. Jelaskan lokasi paparan, siklus basah-kering, metode pembersihan, dan rencana inspeksi; kata “indoor” saja tidak cukup.

**Bukti material dan proses.** Sertifikat material, rekaman heat treatment, hasil inspeksi permukaan, dan riwayat machining harus cocok dengan komponen yang dipasang. Standar uji memberi cara memperoleh data, bukan jaminan bahwa setiap produk atau proses telah diterima. [NEEDS GATE-03: identitas material dan rekaman proses belum dicocokkan dengan komponen]

## Contoh keputusan praktis

Gunakan tabel berikut saat menyusun brief. Isinya adalah pertanyaan keputusan, bukan nilai desain.

| Situasi yang diketahui | Data yang harus diminta | Keputusan yang ditahan |
|---|---|---|
| Motor memiliki nominal daya dan rpm | Torsi saat start, normal, macet, dan pembalikan; pola waktunya | Jangan menerjemahkan daya nominal langsung menjadi ukuran poros |
| Gear atau pulley berada di antara dua bearing | Gaya tangensial/radial, jarak, arah, dan reaksi tumpuan | Jangan memakai diagram torsi tanpa diagram lentur |
| Poros memiliki keyway atau bahu | Gambar detail, kedalaman, radius, orientasi, dan kualitas permukaan | Jangan menganggap penampang polos mewakili detail aktual |
| Lingkungan basah atau korosif | Media, temperatur, siklus paparan, coating, dan inspeksi | Jangan mengunci material atau umur layanan sebelum review |
| Komponen pernah beroperasi | Jam kerja, kejadian overload, retak, perbaikan, dan hasil NDE | Jangan menyebutnya “baru” berdasarkan tampilan saja |

Misalkan data yang tersedia baru torsi normal dan rpm. Brief masih boleh dikirim untuk meminta kelengkapan, tetapi statusnya harus “belum siap sizing” sampai torsi transien, gaya radial, geometri keyway, bearing, dan lingkungan terisi. Sebaliknya, jika semua data telah ada tetapi sertifikat material tidak menunjuk heat yang sama, tahan keputusan material dan minta penelusuran dokumen. Itulah titik di mana [NEEDS GATE-04: kombinasi beban dan status penerimaan komponen belum disetujui] perlu tetap terlihat.

Untuk poros yang menunjukkan goresan, korosi, atau indikasi retak, pisahkan keputusan operasi dari keputusan desain. Hentikan penggunaan bila prosedur keselamatan proyek mengharuskannya, amankan komponen, dan minta pemeriksaan kompeten. Sumber FHWA tentang fatigue dan inspeksi jembatan menekankan pentingnya identitas detail, riwayat beban, kondisi material/fabrikasi, korosi, temuan sebelumnya, akses, dan evaluasi yang kompeten; panduan tersebut bukan aturan bangunan Indonesia atau dasar menghitung sisa umur poros Anda ([manual fatigue/fracture FHWA](https://www.fhwa.dot.gov/bridge/steel/pubs/nhi16016.pdf), [pusat inspeksi FHWA](https://www.fhwa.dot.gov/bridge/inspection/), [program NDE retak fatigue FHWA](https://www.fhwa.dot.gov/publications/ndec/ndecnews.cfm)).

## Kesalahan umum dan cara memeriksanya

Kesalahan pertama adalah mengirim “daya motor, rpm, dan material SS” tanpa diagram gaya. Periksa apakah setiap sumber gaya punya lokasi, arah, kombinasi, dan keadaan operasi. Kesalahan kedua adalah menyebut “ada keyway” tanpa ukuran. Cocokkan model 3D, gambar manufaktur, dan pengukuran aktual; bila berbeda, gunakan status revisi yang jelas.

Kesalahan ketiga ialah memakai satu angka tensile strength untuk menyimpulkan kapasitas atau umur. Tanyakan sumber spesimen, metode, kondisi uji, heat, dan spesifikasi produk yang menjadi acuan penerimaan. Kesalahan keempat adalah mengabaikan bearing. Minta tipe, jarak, mounting, clearance atau preload, pelumasan, serta bukti alignment. Kesalahan kelima adalah menyebut lingkungan “aman” tanpa media dan siklus paparan. Minta foto lokasi hanya sebagai petunjuk visual, lalu konfirmasi dengan catatan operasi dan inspeksi.

Shortcut yang sering dipilih adalah menyalin ukuran poros lama karena mesin terlihat sama. Cara itu gagal bila beban, rpm, keyway, bearing, material, atau lingkungan telah berubah. Alternatif yang lebih aman: gunakan poros lama hanya sebagai data pembanding, dokumentasikan perbedaannya, lalu kirim brief lengkap untuk review engineer. [NEEDS GATE-06: keputusan kelayakan operasi, fatigue, dan perubahan desain memerlukan review kompeten]

## Kesimpulan dan langkah berikutnya

Input poros yang siap ditinjau harus memetakan torsi dan lentur per keadaan, rentang putaran dan transien, detail keyway serta stress raiser, tumpuan bearing, material yang dapat ditelusuri, dan lingkungan beserta riwayat kerusakan. Kawan Besi.co.id, jadikan daftar itu satu paket: diagram gaya, tabel siklus, gambar detail, data bearing, sertifikat dan rekaman proses, catatan lingkungan, serta temuan inspeksi. Teman Besi.co.id, simpan versi dokumen dan tanggal pengukurannya agar perubahan dapat dilacak.

Langkah berikutnya adalah minta engineer menandatangani kombinasi beban dan detail geometri, kemudian minta pemeriksa kompeten menutup marker `[NEEDS GATE-01]`, `[NEEDS GATE-02]`, `[NEEDS GATE-03]`, `[NEEDS GATE-04]`, dan `[NEEDS GATE-06]` dengan bukti proyek yang berlaku. Jika perlu mengirim data atau meminta penelusuran dokumen, gunakan [kanal kontak Besi.co.id](/kontak). Selama gate tersebut belum tertutup, jangan mengubah brief menjadi keputusan sizing, umur fatigue, atau izin operasi. Aturan kerjanya sederhana: poros baru boleh dihitung setelah inputnya dapat ditelusuri dan batas penggunaannya disetujui.

<!-- BEGIN MANAGED IMAGE PLAN
## Image plan

- **Image ID:** `LOCAL-001`
- **Source type:** `local`
- **Placement:** after opening, before the first detailed H2
- **Exact Markdown to insert:** `![Ilustrasi harga besi as](/wp-content/uploads/2024/07/harga-besi-as.jpg)`
- **Caption/credit:** Ilustrasi umum dari aset lokal Besi.co.id; bukan dokumentasi proyek tertentu.
- **Selection basis:** filename/source metadata identifies `harga besi as` as relevant content media; no pixels were inspected.
- **Hard boundary:** do not infer or describe unseen visual details, project ownership, location, people, brands, condition, performance, or outcome.
- **Substitution rule:** do not replace this image. If unavailable or provenance is incomplete, insert `[NEEDS IMAGE REVIEW: LOCAL-001]` and continue drafting the prose.
END MANAGED IMAGE PLAN -->

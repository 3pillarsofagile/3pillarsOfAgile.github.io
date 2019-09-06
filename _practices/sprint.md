---
layout: practice
title:  "Sprint"
subtitle: "Menghasilkan target rilis dalam jendela waktu yang singkat & konsisten, sehingga kecepatan kerja meningkat & estimasi lama pengerjaan makin akurat."
permalink: "sprint"
is_boosting_transparency: true
categories: [first-pillar, second-pillar, third-pillar]
targets: [product-owner, product-manager, development-team]
question: "Punya pengalaman pribadi dalam melakukan Sprint? Ada tips-dan-trik untuk menjalankan Sprint yang baik dan benar?"
---

_Sebagai pihak yang mempopulerkan konsep Sprint, [Scrum Guide](https://www.scrumguides.org/scrum-guide.html) mendapatkan keistimewaan tersendiri: menjadi acuan dasar definisi Sprint di laman wiki ini. Pendetailan praktik diperbolehkan, asalkan tidak melanggar definisi praktik Sprint di Scrum Guide._

#### Apa itu 'Sprint'?

Sprint adalah praktik agar kita bisa:

* mengestimasi & menyelesaikan pekerjaan-pekerjaan, lalu mendemokan & membahas hasil kerja bersama _stakeholder_, di setiap sprint;
  * yang mana pekerjaan-pekerjaan di sebuah sprint harus memiliki satu tema besar yang sama;
  * tema besar di sebuah sprint tidak boleh berubah sampai semua pekerjaan terkait selesai (baca: siap rilis);
  * panjang sebuah sprint sendiri harus konsisten &mdash; bebas pilih berapa lama asalkan di bawah satu bulan;
  * dan tidak ada jeda antar-sprint.

_Apa yang dimaksud dengan 'stakeholder'?_ Semua pihak di luar tim pengembang (pihak bisnis & developer) yang terkena dampak langsung dari produk yang dibuat. _Stakeholder_ termasuk dan tidak terbatas pada: pengguna langsung software, bos/divisi dari pengguna langsung software (misal itu software yang membantu perusahaan), pemimpin di organisasi pembuat software, dan pemilik organisasi pembuat software.

_Apa yang dimaksud dengan 'tema besar pekerjaan'?_ Di dalam sebuah sprint bisa dikerjakan lebih dari satu pekerjaan. Semua pekerjaannya harus memiliki benang merah yang sama, yaitu tema besar tersebut. Di pertengahan sprint, detail sebuah pekerjaan boleh berubah-ubah &mdash; bahkan pekerjaannya itu sendiri boleh keluar-masuk. Namun tema besarnya harus sama sampai semua pekerjaan-pekerjaan yang terkait dengan tema besar tersebut selesai &mdash; bisa di akhir atau di pertengahan sprint. Tujuannya adalah agar bisnis memiliki fokus & perbedaan perubahan permintaan bisnis tidak terlalu membuat developer stres. 

_Apa yang dimaksud dengan 'siap rilis'?_ Sudah dites sehingga tidak ada lagi keraguan untuk merilis hasil kerja tersebut ke pengguna. Jadi, istilah 'pengembangan' di sprint berarti sudah termasuk 'pengujian akhir' di dalamnya. Tujuannya agar minimal di setiap sprint, pihak bisnis mampu untuk merilis sesuatu guna mendapatkan data empirik baru terkait kebutuhan pengguna.

_Apa yang dimaksud dengan 'konsisten'?_ Konsisten dengan panjang sprint-nya. Kalau satu minggu, sprint selanjutnya juga satu minggu. Saat berjalan, panjang sprint tidak boleh berubah secara _ad-hoc_. Jangan diperpanjang karena pekerjaan belum selesai, atau justru diakhiri lebih cepat karena selesai lebih cepat.

Setelah sebuah sprint selesai, baru dipersilahkan mengubah panjang sprint untuk sprint selanjutnya. Namun, tujuan perubahan hanyalah untuk mencari panjang sprint yang pas buat tim & pekerjaan. Setelah dirasa pas, wajib kembali konsisten. Dengan panjang sprint yang konsisten, tim developer jadi terlatih mengukur kapasitas mereka setiap X minggu. Estimasi mereka akan lebih akurat.

_Apa yang dimaksud dengan 'tanpa jeda'?_ Di antara dua sprint, tidak ada waktu kosong. Tujuannya agar melatih akurasi estimasi & menjaga momentum.

#### Bagaiamana 'Sprint' Bisa Melatih Akurasi Estimasi Developer / Tim Developer?

Seperti yang sudah dijelaskan di atas, 'Sprint' bisa melatih akurasi asalkan:

1. Panjang waktunya konsisten.
2. Tidak ada jeda antar-sprint.
3. Fokus hanya pada satu tema besar di tiap sprint.

Tiga syarat di atas sebenarnya masih kurang. Yang kurang adalah 'Hak penuh developer untuk mengestimasi kapasitas tanpa intervensi'. Kenapa?

Idealnya di awal sprint, developer atau tim developer mengambil sendiri pekerjaan-pekerjaan mereka, sesuai prioritas bisnis yang sudah ditentukan. Jika di awal sprint mereka dituntut/dirayu untuk mengambil (baca: mengestimasi) lebih, maka, saat di akhir sprint ternyata mereka tidak bisa menyelesaikan semua pekerjaan mereka akan cenderung menyalahkan pihak yang menuntut/merayu di awal. Padahal bisa jadi kelalaian internal mereka, atau faktor-faktor eksteral turut mengambil peran. Intervensi ke estimasi membuat mereka jadi sulit mempelajari berapa sebenarnya kapasitas produksi mereka. Padahal bisnis akan sangat terbantu kalau estimasi mereka akurat.

_Lalu bagaimana jika pihak bisnis punya target besar dengan waktu yang terbatas?_ Justru di kondisi seperti inilah akurasi estimasi makin dibutuhkan. Di kondisi krusial seperti ini, pihak bisnis makin butuh estimasi yang jujur & akurat. Karena kegagalan bisa memalukan di mata klien/publik. Istilahnya, "kalau memang tidak bisa, bilang tidak bisa dari awal".

Jika mempraktikkan Sprint dan berada di kondisi seperti di atas (ada target besar dan strategis namun waktu terbatas), pihak bisnis bisa buka-bukaan ke developer, terkait kenapa ekspektasi beliau bisa krusial untuk kesukesan produk. Jika developer bisa memahami, mereka bisa jadi akan bersedia menambah jam kerja (lembur) &mdash; asalkan tidak _burnout_ / merekomendasikan developer _freelance_ ahli kenalan mereka untuk bergabung / memberikan alasan yang masuk akal untuk mengurangi ekspektasi fitur.

Jangan pernah coba-coba menego estimasi mereka, jika ingin kultur keterbukaan seperti di atas tercapai. Anggap Anda adalah pihak bisnis. Anda takut otonomi terhadap estimasi ini membuat developer sengaja mengambil pekerjaan sesedikit mungkin &mdash; sehingga jam berkerja mereka jauh lebih sedikit dari jam kerja yang kalian sepakati (9-to-5 misalnya) &mdash; lakukan dua hal berikut:

1. Terapkan praktik-praktik transparansi organisasi (baca [panduan Tiga Pilar Agile](/user-guide) khususnya [Retrospektif Tim](/team-retrospective), [Papan Kanban Proyek](kanban-board-for-a-project) &mdash; karena sebuah sprint bisa dianggap sebagai sebuah proyek, dan [Daily Standup](/daily-standup))
2. Sering muncul dan bergaul di dekat tempat tim developer berkerja. Sehingga terlihat bagaimana mereka memanfaatkan jam kerja di kantor. Hal ini bisa diwakilkan oleh orang yang Anda percayai.

Bagaiamana Sprint bisa melatih akurasi estimasi developer / tim developer?

1. Panjang waktu yang konsisten.
2. Tidak adanya jeda.
3. Fokus hanya pada satu tema besar di tiap sprint.
4. **Hak penuh developer untuk mengestimasi kapasitas tanpa intervensi.**

#### Apa yang Terjadi di Sebuah Sprint?

Di dalam sebuah sprint, ada 4 tahap yang terjadi secara berurutan: planning, development, review, retrsopective.

**Planning**  
Sprint dibuka dengan kegiatan planning. Berikut garis besar agendanya:

1. Pihak bisnis mencanangkan sebuah fokus utama produk dari bisnis (bisa dijadikan tema besar sprint ini).
2. Pihak bisnis & developer memastikan antrian pekerjaan-pekerjaan teratas sudah mencerminkan fokus tersebut.
3. Jika ada yang belum jelas dari pekerjaan-pekerjaan teratas, pihak bisnis & developer berdiskusi.
4. Developer atau tim developer mengambil pekerjaan sejumlah yang dia/mereka estimasi sanggup lakukan di satu sprint &mdash; tanpa intervensi. Pengambilan harus sesuai antrian pekerjaan yang telah disetujui pihak bisnis.
5. Selain dicanangkan oleh pihak bisnis, tema besar sprint bisa ditentukan benang merah dari pekerjaan-pekerjaan yang diambil.
6. Developer membahas strategi pengerjaan sampai waktu planning habis.

Artinya, di akhir planning sudah ada tema besar sprint, pekerjaan-pekerjaan sprint yang cukup detail buat developer, dan strategi pengerjaannya.

Kegiatan planning ini maksimum 8 jam untuk sprint yang panjangnya satu bulan. Untuk sprint yang lebih pendek, waktu planning bisa lebih pendek.

**Development**  
Pihak bisnis hanya bisa menulis ekspektasi hasil kerja dengan bahasa bisnis (baca: bahasa orang awam) &mdash; bukan bahasa teknis. Jadi, kegiatan diskusi pertama tim developer untuk membahas desain/arsitektur teknis, sudah terhitung kegiatan development sebenarnya.

Kalau itu ujung awal development, ujung akhirnya apa? Ujung akhirnya adalah saat waktu development-nya habis. Ingat, panjang sprint tidak boleh berubah. Idealnya, di penghujung waktu development (baca: tepat sebelum kegiatan review), semua pekerjaan yang diestimasikan di awal sudah selesai dites dan siap rilis. Jika belum selesai, waktu review tidak bisa diundur.

Bagaimana jika development pekerjaan-pekerjaan yang diestimasi di planning, selesai jauh lebih awal dari jadwal review? Apakah boleh liburan? Atau boleh langsung mengeksekusi ide-ide developer sendiri terhadap produk? Keduanya tidak boleh. Yang boleh adalah mengambil antrian pekerjaan berikutnya &mdash; meski tema besarnya mungkin berbeda. Akan bagus jika pekerjaan(-pekerjaan) berikutnya sudah dalam kondisi cukup detail untuk dikerjakan developer &mdash; yang juga berarti planing sprint berikutnya sudah lebih siap. Jika pekerjaan(-pekerjaan) teratas di antrian belum cukup detail, sementara di tengah sprint developer sebentar lagi akan menyelesaikannya, segera hubungi pihak bisnis untuk mendetailkan pekerjaan berikutnya.

Diskusi developer dan pihak bisnis, untuk membahas spesifikasi pekerjaan (baik untuk sprint ini maupun sprint-sprint berikutnya) bisa terjadi di tengah development. Dengan syarat waktunya tidak melebihi 10% dari panjang sprint.  

**Review**  
Spesial untuk kegiatan review, pihak bisnis juga mengundang perwakilan _stakeholder_. Tujuan review memang untuk menutup semua kegiatan terkait pekerjaan dengan demo produk dan diskusi. Hadirnya perwakilan _stakeholder_ jadi krusial. Berikut garis besar agenda Review:

* Seremoni: pernyataan resmi dari pihak bisnis akan pekerjaan-pekerjaan apa saja yang mereka terima sebagai 'selesai'.
* Pembukaan: rangkuman singkat baik dari tim developer maupun pihak bisnis, terkait berjalannya pekerjaan masing-masing selama sprint ini (apa yang bagus & apa yang kurang bagus);
* Demo: demonstrasi hasil kerja yang dilakukan sendiri oleh tim developer;
* Diskusi: membahas segala hal menarik yang mungkin memperbaiki arah produk di sprint(-sprint) berikutnya. Seperti hasil kerja yang baru saja didemokan, kondisi antrian pekerjaan saat ini, ide-ide baru, kondisi kompetitor, sisa anggaran/waktu, target rilis terdekat, dll.

Kegiatan review ini maksimum empat jam untuk sprint yang satu bulan.

**Retrospective**  
Review adalah penutup semua kegaitan terkait pekerjaan. Namun sprint belum berakhir. Review dilanjutkan oleh retrospektif. Di retrospektif, bukan pekerjaan yang dibahas, melainkan cara berkerja & segala perasaan-perasaan positif/negatif tiap-tiap orang pihak bisnis maupun tim developer.

Selepas retrospective, harusnya sudah ada aksi perbaikan untuk dieksekusi di sprint berikutnya &mdash; dan dibahas hasilnya di retrospektif sprint tersebut. Agar tidak lupa mengeksekusi aksi perbaikan, diwajibkan untuk mengikutkannya ke _to-do-list_ visual pekerjaan-pekerjaan sprint berikutnya.

Tips & trik implementasi retrospective di sprint bisa dibaca di praktik [Retrospektif Tim](/team-retrospective).

#### Apakah Tema Besar Semua Sprint bisa Diplot di Awal?

Bayangkan: di awal sebuah inisiatif &mdash; sebelum ada pengembangan sama sekali &mdash; sudah diplot tema besarnya...

* Sprint 1: Register
* Sprint 2: Koneksi ke Daftar Kontak 
* Sprint 3: Chat text 1-on-1
* Sprint 4: Chat text 1-on-1
* Sprint 5: Chat emoji 1-on-1
* dst..

Apakah prediksi di atas akan jadi kenyataan?

Jawabannya tidak mungkin.

Pertama, sisi lama pengembangan yang sulit diestimasi. Di programming, banyak variabel yang sulit diprediksi di awal. Realitanya, bisa saja fitur 'Register' baru selesai di Sprint 3. Tentu plot-plot tema besar di bawahnya juga ikut turun.

Kedua, kebutuhan bisnis terus berubah. Ingat, pengembangan yang tangkas pasti mempraktikkan '[MVP](/mvp)' & menjiwai [Build-Measure-Learn]('/2-flexible') (Pilar 2). Bisa jadi baru diketahui di tengah-tengah sprint 3, bahwa 'Chat gambar 1-on-1' lebih dibutuhkan pengguna daripada 'Chat emoji 1-on-1'.

Biasanya pihak bisnis punya bayangan yang cukup jelas akan tema-tema besar & pekerjaan-pekerjaan terkait untuk 3-4 sprint ke depan. Lebih jauh dari itu, makin kabur. Ini adalah hal kunci yang membedakan praktik-praktik agile dengan praktik-praktik era sebelumnya (waterfall).

#### Bagaimana Jika Di Tengah-Tengah Sprint Ada Kebutuhan Mendesak di Luar Tema Besar?

_Kebutuhan apa dulu? Bugfix dari hasil pekerjaan sprint sebelumnya?_ Jika tidak punya tim khusus untuk bugfix, mau bagaimana lagi? Tentu dibolehkan. Silahkan kerjakan meski tidak ada hubungan dengan tema besar sprint saat ini.

_Fitur baru?_ Ini yang tidak boleh. Karena tidak sesuai dengan tema besar. Kalau dibolehkan, developer bisa pusing. Karena sayangnya, pekerjaan programming tidak seperti pekerjaan membuat bangunan &mdash; yang bisa dengan mudah ditinggal di tengah-tengah, pindah ke pekerjaan lain, lalu kembali mengerjakan pekerjaan yang ditinggal. Ada banyak informasi yang harus dimasukkan ke otak programmer saat dia mengerjakan sebuah fitur. Jika ada fitur lain yang jauh berbeda dengan fitur yang dia kerjakan, dia harus mengosongkan otaknya dan mengisi dengan informasi lain. Di programming, perpindahan konteks itu tidak mudah, tidak sebentar, dan memakan banyak energi.

_Lalu bagaimana solusinya?_ Tunggu sprint berikutnya. Atau jika bisnis punya justifikasi yang bagus kenapa tidak bisa menunggu, batalkan sprint yang berjalan. Pembatalan dibolehkan, asalkan ditutup dengan baik-baik (jelaskan justifikasinya & terima semua pekerjaan developer). Developer atau tim developer pasti kecewa pekerjaannya diinterupsi, namun jika masuk akal buat mereka, pada akhirnya mereka akan menerima.

NB: Kasus pembatalan sprint ini juga bisa terjadi misal tiba-tiba pemerintah merilis regulasi yang melarang fitur yang dibuat di sprint ini.

#### Bagaimana Peran 'Sprint' ke Pilar 1?

Jelas, praktik Sprint mempercepat & mempersering rilis. Bahkan dalam satu Sprint bisa jadi lebih dari satu rilis. Karena Sprint tidak mewajibkan rilis harus di akhir / setelah sprint. Yang diwajibkan adalah merencanakan & mengusahakan adanya hasil kerja yang kondisinya siap rilis selambat-lambatnya di akhir sprint &mdash; perihal dirilis atau tidak, tidak dibahas di praktik Sprint.

#### Bagaimana Peran 'Sprint' ke Pilar 2?

Sebagaimana yang disebutkan di atas, praktik Sprint tidak mewajibkan rilis di akhir sprint. Kalau sebuah MVP ternyata membutuhkan 5 sprint, berarti rilis pertama baru terjadi setelah menunggu 5 sprint. Dalam konteks ini, Sprint tidak mempunyai peran langsung ke Pilar 2.

Namun, karena praktik Sprint mewajibkan adanya demo hasil kerja & pembahasan bersama _stakeholder_ di akhir sprint, praktik Sprint bisa jadi pemicu untuk munculnya ide-ide baru terkait produk. Ide-ide baru tersebut bisa merubah arah produk ke depannya. Artinya, Sprint berperan langsung menegakkan Pilar 2.

#### Bagaimana Peran 'Sprint' ke Pilar 3?

Jika estimasi developer atau tim developer diintervensi & tidak dihargai, maka itu bukanlah praktik Sprint &mdash; silahkan baca [Scrum Guide](https://www.scrumguides.org/scrum-guide.html#events-planning) jika tidak percaya.

_Apakah developer pasti tidak akan 'burnout' kalau dibebaskan mengestimasi?_ Belum tentu. Contoh kasus: sebuah tim developer mengambil pekerjaan terlampau banyak. Karena mereka [berkerja secara otonom](/small-autonomous-team), mereka dibiarkan saja saat memutuskan untuk tetap menyelesaikan semuanya &mdash; bahkan sampai harus lembur berhari-hari. Akhirnya, jatuh sakit (alias _burnout_). Hal ini mungkin terjadi saat mempraktikkan Sprint yang benar. Namun &mdash; juga karena praktik Sprint yang benar &mdash; di sprint berikutnya mereka sudah belajar untuk mengambil pekerjaan lebih sedikit. Jadi, tetap _happy ending_.

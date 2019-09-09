---
layout: practice
title:  "Antrian Pekerjaan yang Transparan (Backlog)"
subtitle: "Memvisualkan antrian pekerjaan ke semua orang, sehingga siapapun berempati & punya ekspektasi yang lebih masuk akal."
permalink: "transparent-work-backlog"
is_boosting_transparency: true
categories: [first-pillar, second-pillar, third-pillar]
targets: [everyone]
checklist: [scrum]
question: "Punya pengalaman pribadi saat menggunakan Backlog?"
---

_Di Scrum, praktik ini biasa disebut dengan Product Backlog. Penjelasan di halaman ini tidak hanya mencakup product backlog Scrum, namun juga backlog-backlog lain._

#### Apa itu Work Backlog?

Hampir semua orang tahu _to-do-list_. Jadi mari kita mulai dari sana.

{% include image.html
    img = "to-do-list.jpg"
    caption = "Contoh to-do-list."
    max-width = "300px"
    %}

Maka, work backlog adalah _to-do-list_ permintaan suatu pihak pengarah ke pihak eksekutor, **namun** harus diambil dari sesuai prioritas (dari atas ke bawah).

{% include image.html
    img = "to-do-list-vs-work-backlog.jpg"
    caption = "Karena diurutkan berdasarkan prioritas, pekerjaan-pekerjaan di backlog wajib 'dicoret' satu persatu dari atas ke bawah."
    max-width="600px"
    %}

Karena pekerjaan yang baru selesai dicoret dari atas ke bawah secara konsisten, Work Backlog bisa juga disebut sebagai 'antrian dari pekerjaan yang belum selesai'.

{% include image.html
    img = "work-backlog-di-papan-kanban.jpg"
    caption = "Work backlog di papan kanban repetitif."
    %}

#### Jika Namanya Antrian, Apa Berarti Pasti 'First-In-First-Out'?

Tidak. Pemrioritasan dibebaskan ke pihak yang berwenang pada work backlog.

Dalam konteks pengembangan produk inovasi, First-In-First-Out merupakan cara yang buruk, karena bisa jadi ada pekerjaan yang baru terpikir di pertengahan/akhir tapi lebih bernilai untuk pengguna daripada yang ada di atas-atas work backlog sekarang.

Selain memasukkan pekerjaan baru, mengeluarkan sebuah pekerjaan dari work backlog juga bisa saja terjadi.

#### Apakah Boleh Memasukkan Pekerjaan yang Belum Detail ke Work Backlog?

Boleh saja. Yang penting, pekerjaan-pekerjaan teratas di work backlog sudah cukup detail di mata tim yang akan mengerjakan &mdash; karena sebentar lagi akan dikerjakan.

#### Kenapa Work Backlog Harus Transparan?

Karena jika sebuah work backlog disembunyikan, dia hanya akan jadi _to-do-list_ internal.

Itu jelas tidak masalah &mdash; jika sudah memenuhi kebutuhan. Namun, jika kita bicara dalam konteks produk inovasi, sebuah work backlog wajib transparan. Ada dua skenario yang menjelaskan kenapa:

**1. Semua Berebut untuk Didahulukan**  
Umumnya, sebuah tim inovasi (pihak bisnis & developer) tidak berkerja sendiri. Mereka bisa saja punya atasan & investor. Ada pula tim inovasi yang membuat produk untuk perusahaan (baik internal maupun eksternal). Pengguna produknya biasa disebut klien.

Atasan, investor, atau klien, semuanya punya kepentingan terhadap produk yang sedang dikembangkan. Seringkali ekspektasi-ekspektasi mereka berbenturan &mdash; baik antar mereka, maupun dengan tim inovasinya itu sendiri. Semua pihak ingin permintaannya didahulukan. 

Di kondisi seperti ini, work backlog yang transparan bisa sangat membantu. Kalau ada yang ingin permintaannya didahulukan, yang bersangkutan harus bisa menjelaskan secara logis, kenapa nilai bisnisnya lebih tinggi dari pekerjaan-pekerjaan yang didahulukan. Semua pihak pada akhirnya akan mendengar juga penjelasan tersebut, karena perubahan apapun di work backlog bisa dibaca oleh semua.

**2. _Trust_ ke Estimasi Developer**  
Tekanan ke developer bukan hanya datang dari pihak bisnis yang sehari-hari berhubungan dengan mereka, tapi juga dari 'pihak bisnis di atas sana' alias atasan atau investor.

Pihak bisnis-pun sering mendapat tekanan-tekanan langsung juga dari para klien. 

Work backlog yang transparan meningkatkan rasa percaya atasan, investor, dan klien atas estimasi yang mereka dengar (baik langung dari developer maupun lewat pihak bisnis yang sehari-hari bersama developer). Bagaimana bisa?

Karena dengan melihat work backlog sebuah tim developer, mereka bisa mendapatkan data kapasitas produksi dari sebuah tim. Mereka jadi bisa dengan mudah menanyakan ke rekan-rekan mereka di luar, apakah kapasitas produksi tiap bulan dari sebuah tim, sesuai dengan total gaji bulanan mereka.

Dalam konteks hubungan vendor-klien, tidak sedikit vendor yang mencurangi kontrak dengan membuat tim developer mengerjakan produk klien lain &mdash; padahal waktunya sudah dibeli. Transparansi work backlog bisa meluruhkan kecurigaan terkait hal ini. Karena _output_ & _cost_ bisa diaudit secara langsung.

#### Bagaimana Cara Membuat Work Backlog bisa Transparan?

Yang termudah, adalah menaruhnya di internet. Ada banyak pilihan, namun yang murah dan cukup intuitif untuk work backlog adalah [Trello](https://trello.com).

#### Bagaimana Kontribusi 'Work Backlog' ke Pilar 1?

Kontribusinya ada, namun tidak langsung. Semuanya bisa ada karena transparansinya:

1. Dengan work backlog yang transparan, semua pihak (atasan, investor, dan klien termasuk) bisa melihat kecepatan produksi developer dalam berkerja. Hal ini memunculkan tekanan tersendiri ke developer / tim developer untuk berkerja secara efektif dan efisien.
2. Dengan work backog yang transparan &mdash; dan fakta bahwa developer / tim developer terbatas &mdash; semua pihak jadi merasa butuh untuk membuat permintaan fitur yang jelas, singkat ([MVP](/mvp)), dan berdasarkan data empirik.

#### Bagaimana Kontribusi 'Work Backlog' ke Pilar 2?

Dengan work backlog yang transparan, akan terpicu diskusi dari semua pihak (atasan, investor, dan klien termasuk) terkait arah produk terbaik ke depannya.

#### Bagaimana Kontribusi 'Work Backlog' ke Pilar 3?

Sebagaimana yang telah dijelaskan (di 'Kenapa Work Backlog Harus Transparan?'), _trust_ ke estimasi developer jadi meningkat &mdash; jika work backlog mereka transparan.
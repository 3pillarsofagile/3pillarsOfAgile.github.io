---
layout: practice
title:  "Checklist untuk Kualitas"
subtitle: "Memastikan standar minimum kualitas wajib dipenuhi agar pekerjaan bisa dibilang selesai, sehingga tidak ada hutang teknis yang harus dibayar di masa depan dan produk jadi tetap bisa mudah dikembangkan."
permalink: "checklist-on-quality"
is_boosting_transparency: true
categories: [first-pillar, third-pillar]
targets: [product-owner, prouct-manager, development-team, CTO]
checklist: [scrum]
question: "Punya pengalaman pribadi dalam menggunakan Chekclist?"
---

_Praktik ini dipopulerkan bersama konsep papan Kanban dari Toyota Lean Manufacture. Di Scrum, praktik ini biasa disebut dengan istilah Definition of Done._

#### Apa itu Checklist?

Semua orang sudah tahu _checklist_.

{% include image.html
    img = "checklist-illustration.png"
    caption = "Checklist"
%}

Ini yang mungkin belum semua tahu: penerapan checklist oleh tenaga medis bisa mengurangi tingkat kematian sampai 23%[^checklist-di-medis]. Checklist bisa mengurangi kelalaian manusia.

[^checklist-di-medis]: ["Systematic review and meta-analysis of the effect of the World Health Organization surgical safety checklist on postoperative complications"](https://onlinelibrary.wiley.com/doi/full/10.1002/bjs.9381), The British Journal of Surgery (Feb 2014).

#### Bagaimana Penerapan Checklist di Software?

Checklist bisa digunakan untuk memastikan kualitas produk memenuhi standar, baik di mata pengguna maupun di mata developer.

{% include image.html
    img="software-development-checklist-example.jpg"
    caption="Terlihat kalau checklist di pengembangan software bisa berguna untuk banyak pihak."
    max-width="700px"
%}

Standar kualitas di mata developer termasuk kualitas kode &mdash; sesuatu yang pengguna tidak rasakan. _Kalau begitu kenapa harus dikerjakan? Apa nilai bisnisnya?_ Nilai bisnisnya ada di kecepatan pengembangan di masa depan. Makin berkurang kualitas, kode akan makin susah dibaca di masa depan. Kode yang susah dibaca akan susah untuk dikembangkan.

Pengorbanan atas kualitas kode &mdash; demi kecepatan rilis &mdash; merupakan fenomena yang wajar. Oleh karena itu, penting bagi pimpinan untuk memahami ini & tidak menego standar kualitas kode yang diminta developer &mdash; bahkan kalau bisa, mengajarkan standar kualitas kode yang lebih tinggi.

Di level taktis, checklist akan menjaga para eksekutor untuk pasti mengeksekusinya.

{% include image.html
    img = "checklist-di-kanban-board-repetitif.jpg"
    caption = "Penerapan checklist di papan kanban repetitif. Terlihat ada checklist di setiap langkah, yang mana harus dipenuhi pekerjaan agar bisa masuk kolom 'Selesai'."
%}

{% include image.html
    img = "checklist-di-kanban-board-proyek.jpg"
    caption = "Penerapan checklist di papan kanban proyek di Scrum (biasa disebut 'Sprint Backlog'). Terlihat kalau pekerjaan-pekerjaan di checklist masuk ke task-task di kolom to-do. Terlihat juga kalau penulisan skrip tes otomatis dan pengujiannya dimasuk ke fase development &mdash; berbeda dengan papan kanban repetitif di atas."
    max-width = "600px"
%}

#### Siapa yang Berhak Menentukan 'Checklist'?

Yang pertama, tentu, organisasi. CTO bisa menentukan langkah-langkah wajib apa dari development.

Disarankan agar tidak berhenti dari standar kualitas yang ditentukan organisasi. Berikan developer atau tim developer kebebasan untuk menambah & mengurangi isi checklist mereka &mdash; selama tidak mengurangi yang diwajibkan organisasi.

Minta mereka menjelaskan, kenapa sebuah langkah yang mereka tambahkan ke checklist akan bermanfaat untuk produk ke depannya.

Hal ini akan meningkatkan rasa kepemilikan mereka terhadap produk & pekerjaan[^peopleware]. Mereka akan lebih produktif.

[^peopleware]: Bab 4 di Buku Peopleware (1987), "Quality&mdash;if Time Permit"

#### Bagaimana Peran 'Checklist' ke Pilar 1?

Praktik Checklist meminimalisir kemungkinan meengerjakan ulang pekerjaan yang sama. Hal tersebut jelas-jelas memperlambat waktu rilis. Penyebabnya bisa _error_ atau sekedar lupa melakukan hal penting & wajib terkait pekerjaan.

#### Bagaimana Peran 'Checklist' ke Pilar 3?

Yang sudah jelas:

1. Checklist meminimalisir _bug_.
2. Checklist meningkatkan standar minimum kualitas kode, sehingga kode tetap mudah dikembangkan di masa depan.

Selain itu, praktik Checklist juga memberikan penjelasakan ke pihak bisnis (baik yang tiap hari berinteraksi dengan developer maupun yang 'di atas langit sana') tentang kenapa mereka bisa berkerja lebih lama.

Karena kualitas kode tidak bisa dicek sendiri dan dipahami oleh mereka &mdash; jika tidak diedukasi oleh orang teknis. Mereka hanya tahu apa-apa yang bisa dirasakan langsung oleh pengguna.


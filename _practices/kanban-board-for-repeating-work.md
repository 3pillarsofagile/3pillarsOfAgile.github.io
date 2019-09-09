---
layout: practice
title:  "Papan Kanban Repetitif"
subtitle: "Membuat detail pekerjaan berulang (repetitif) jadi transparan ke semua, sehingga kecepatan kolaborasi dan rasa percaya bisa meningkat."
permalink: "kanban-board-for-repeating-work"
is_boosting_transparency: true
categories: [first-pillar, second-pillar, third-pillar]
targets: [project-executor, developer]
question: Apa pandangan kamu terhadap papan kanban repetitif? Ada pengalaman?
---

#### Apa itu Papan Kanban?

Papan kanban adalah alat bantu visualisasi status pekerjaan, dengan memanfaatkan kartu-kartu yang digeser antar kolom-kolom status pekerjaan. Fungsinya adalah untuk meningkatkan transparansi, baik ke internal maupun ke eksternal.

{% include image.html 
    img="https://user-images.githubusercontent.com/2253841/61527448-a558be80-aa46-11e9-9d65-9ca4e6713391.png"
    caption="Papan kanban paling sederhana, karena hanya memiliki satu langkah pengerjaan. Task-Task di atas digeser ke kanan sesuai status. Sumber: Sven Wiegand (klik gambar)."
    url="https://hackernoon.com/personal-kanban-part-1-why-todo-lists-don-t-work-3b5c6dc78708"
    max-width="500px"
    %}

Langsung terlihat kalau papan kanban bisa dimanfaatkan oleh individu maupun tim.

#### Apakah Papan Kanban Bisa Dimanfaatkan untuk Pekerjaan Repetitif yang Langkahnya Pasti & Berulang?

Bisa. Justru papan kanban lahir di tipe pekerjaan yang seperti ini, yaitu di [pabrik pembuatan mobil Toyota](https://www.wikiwand.com/en/Kanban). 

Jika kita bicara pengembangan software secara besar, kita mengetahui setiap fitur baru pasti akan melalui langkah berikut:

1. deciding (meriset apakah dari sisi bisnis sebuah fitur layak disegerakan),
2. detailing (mendetailkan fitur apa yang diinginkan bisnis),
3. developing (membuat fitur),
4. acceptance testing (pengujian akhir sebelum rilis),
5. deploying (rilis).

Karena langkahnya tetap dan sudah jelas, papan kanban repetitif bisa dibuat.

{% include image.html
    img="kanban-for-operational1.jpeg"
    %}

Kita tahu, setelah selesai dikerjakan di sebuah tahap, sebuah fitur belum tentu bisa langsung dikerjakan di tahap berikutnya. Untuk itu, kita membuat sub-kolom 'Done' dan 'Selected'.

{% include image.html
    img="kanban-for-operational2.jpeg"
    %}

Asumsinya, tim di papan kanban ini tidak butuh banyak waktu untuk merilis sebuah fitur. Maka dari itu tidak ada sub-kolom 'In Prog.' di tahapan 'Deploying'.

#### Apakah Papan Kanban Opersional bisa Dipakai Bersamaan dengan Papan Kanban Proyek?

Jawabannya bisa. Namun untuk mengambarkan dua hal yang berbeda.

Contoh: saat sebuah fitur dikerjakan (berarti di 'In Prog.'-nya 'Developing'), ada banyak pekerjaan-pekerjaan kecil yang dinamis&mdash;bisa jauh berbeda antar fitur. Dengan begitu, sebuah tim bisa memiliki dua papan kanban, satu yang repetitif (untuk melihat gambaran besar), dan satu lagi yang proyek (untuk melihat detail pekerjaan-pekerjaan kecil di pengambangan).

#### Bagaimana Papan Kanban Repetitif Menegakkan Pilar 1?

Papan Kanban Repetitif membantu seseorang untuk melihat kondisi keseluruhan dari sebuah proyek saat ini. Informasi tersebut bisa membuat seseorang bergerak lebih cepat.

Jika proyek dieksekusi oleh tim, Papan Kanban Repetitif meningkatkan kolaborasi.

#### Bagaimana Papan Kanban Repetitif Menegakkan Pilar 2?

Papan Kanban Repetitif membuat masalah jadi mudah terlihat. Jika ada satu _task_ yang lama di kolom 'In Progress' / 'Doing', atau banyak _task_ mengantri di sebuah kolom 'Done', seluruh orang jadi terpicu untuk menanyakan kendala ke pihak yang mengerjakan.

#### Bagaimana Papan Kanban Repetitif Menegakkan Pilar 3?

Papan Kanban Repetitif bisa membantu para eksekutor menolak pekerjaan tambahan. Karena sudah jelas secara visual bagi atasan, bahwa pekerjaan mereka masih banyak&mdash;sehingga tidak bisa ditambah lagi. Manfaat ini juga berlaku sebaliknya&mdash;menunjukkan kalau tim eksekutor sedang agak lowong.

#### Seperti Apa Cara Penggunaannya?

Sederhana. Buat papannya, isi, lalu terus perbarui. Perbarui minimal setiap hari&mdash;meski langsung setelah pengerjaan (baca: _realtime_) tentu lebih baik.

Jika memungkinkan, buat papan kanban fisik di dinding.

Jika ingin meningkatkan _trust_ dari seseorang, beri beliau akses ke papan kanban repetitif Anda & notifikasi jika ada pembaruan penting.

_Lihat juga praktik [Kanban Personal CEO](/ceos-personal-kanban) & [Papan Kanban Proyek](/kanban-board-for-a-project)_
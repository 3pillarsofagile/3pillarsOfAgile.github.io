---
layout: practice
title:  "Unit Testing"
subtitle: "Menjaga kevalidan komponen-komponen terkecil software dengan bantuan software, sehingga analis jadi lebih tajam dan bug berkurang."
permalink: "unit-testing"
categories: [first-pillar, third-pillar]
targets: [programmer]
question: Apa pandangan-mu terhadap Unit Testing? Punya kisah nyata? Ada cara mengenalkan & mengajarkan Unit Testing ke orang lain?
---

Unit testing adalah bagian keluarga besar praktik test otomatis (testing software yang dilakukan oleh software lain&mdash;bukan manual oleh manusia). Unit test sendiri hanya mengacu pada komponen-komponen terkecil dari kode software, yaitu class & function.

#### Contoh Unit Test

Fungsi pendaftaran user---registering_user()---yang diberi input berbagai format password. Mulai dari yang dibolehkan, tidak dianjurkan, sampai dilarang. Fungsi harus berhasil menolak yang dilarang.

#### Praktik Unit Testing

Unit Testing sendiri adalah praktik untuk menulis unit test dahulu sebelum membuat kelas fungsi & fungsi. Setiap ada bug / perubahan spesifikasi fitur, kode unit test diperbarui.

#### Manfaat Unit Testing

Dengan disiplin melakukan unit testing,

* pengembangan jadi lebih cepat,
* bug jadi berkurang.
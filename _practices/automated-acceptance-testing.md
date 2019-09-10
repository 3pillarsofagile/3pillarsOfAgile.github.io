---
layout: practice
title:  "Automated Acceptance Testing"
excerpt: "Menjaga kevalidan software dengan bantuan software lain, sehingga komunikasi makin akurat, bug makin minim, & rilis makin penuh rasa aman."
permalink: "automated-acceptance-testing"
is_boosting_transparency: false
categories: [first-pillar, third-pillar]
targets: [product-owner, qa-engineer, programmer]
question: Apa pandangan-mu terhadap AAT? Punya kisah nyata? Ada cara mengenalkan & mengajarkan AAT ke orang lain?
---

Automated Acceptance Testing (AAT) adalah bagian keluarga besar praktik test otomatis (testing software yang dilakukan oleh software lain&mdash;bukan manual oleh manusia). Jika Unit Testing menguji komponen-komponen terkecil dari kode software (class & function), AAT menguji fitur software itu sendiri.

Sama seperti Unit Test, kode skrip AAT diharapkan ditulis lebih dulu sebelum satu baris kode software ditulis (atau kode skrip unit test). Setiap ada bug / perubahan spesifikasi fitur, kode AAT diperbarui.

{% include youtube.html
    code="iHou7-TgCpY"
    caption="Demo singkat. Bukan demo yang baik, karena selectornya terlalu butuh pengetahuan HTML." %}
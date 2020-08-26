---
title: ROC
tags: research methods, lecture
description: materi ini adalah bagian dari 
---

# *Relative Operating Curve* (ROC)

<!-- Put the link to this slide here so people can follow -->
salindia: https://hackmd.io/@ameliazein/roc

---

### Pada saat kapan digunakan?

<div style="text-align: left">

* Misalnya seorang peneliti ingin membuat *screening test* untuk mendeteksi dini gejala depresi
* Yang ia lakukan kemudian adalah membandingkan hasil ukur alat tersebut dengan **hasil asesmen Psikolog** sebagai ==*gold standard*==
* Bagaimana peneliti tsb tahu bahwa alatnya benar-benar bisa membedakan antara pasien dengan gangguan, dengan pasien yang sehat?

</div>

---

![](https://i.imgur.com/KG0xYfR.jpg)

---

![](https://i.imgur.com/mstVTgx.png)

---

## Untuk tahu apakah alat kita akurat :dart: 

<div style="text-align: left">

* Kita dapat mengecek ==*sensitivity*== :arrow_forward: "saya tahu **klien saya mengalami depresi**, berapa peluangnya alat *screening* tersebut menunjukkan bahwa **klien tsb positif depresi**?"
* ..dan ==*specificity*== :arrow_forward: "saya tahu **klien saya tidak depresi**, berapa peluangnya alat *screening* menunjukkan **hasil negatif**?"

</div>

---

## Cara menghitungnya :1234: 

<div style="text-align: left">

* ==*Sensitivity*== :arrow_forward: TP/TP+FN 
* ==*Specificity*== :arrow_forward: TN/TN+FP

Ingat :exclamation: 

*Sensitivity* dan *specificity* adalah dua hal yang harus di *trade-off*. Menaikkan *sensitivity* alat ukur akan mengurangi *specificity*, dan begitu pula sebaliknya.

</div>

---

## Selain itu...

<div style="text-align: left">

* ==*Positive predictive value*== :arrow_forward: "alat *screening* saya menunjukkan **hasil positif**, berapa peluangnya bahwa klien saya **benar-benar depresi**?"
* ==*Negative predictive value*== :arrow_forward: "alat saya menunjukkan **hasil negatif**, berapa peluangnya bahwa klien saya **tidak depresi**?"

</div>

---

<!-- .slide: data-background="#fff" -->
![](https://i.imgur.com/uAv9Ciu.png)

---

<!-- .slide: data-background="#fff" -->
![](https://i.imgur.com/heWqF9x.png =500x500)

---

<!-- .slide: data-background="#fff" -->
![](https://i.imgur.com/AIeZe11.png)

---

## Menggunakan ROC di jamovi

<div style="text-align: left">

* Pasang *module* PPDA terlebih dahulu
* Siapkan datasetnya :exclamation: 
* Satu kolom (variabel) berisi skor total tes yang ingin diuji, satu kolom untuk keputusan diagnosis (berdasarkan *gold standard*)

[Unduh dataset contoh disini](https://osf.io/v54gt/)

</div>

---

## Dataset

<div style="text-align: left">

* Kita akan membandingkan *mental health inventory* dengan *self-reporting questionnaire* (SRQ-20)
* SRQ-20 adalah alat *screening* standar yang dikeluarkan oleh WHO dan digunakan di RISKESDAS (2007, 2013, 2018)
* Kita akan mencari ==*cut-off score*== dari MHI, berapa **batas skor** dimana klien dapat dikatakan mengalami gangguan mental-emosional?

</div>

---

## Langkahnya... 

<div style="text-align: left">

* Klik PPDA, dan pilih TestROC
* Masukkan variabel **MentalHealthIndex** (skor total MHI) pada kolom ==*dependent variable*== dan **SRQ_Diagnostik** pada ==*class variable*==
* Pada opsi ***visualisation***, centang ***ROC Curves***, ***standard error bars***, dan ***sensitivity-specificity tables***

</div>

---

## Interpretasi

<div style="text-align: left">

* Pilih *cut-off* yang menunjukkan ==Youden's index paling besar== :arrow_forward: menunjukkan *cut-off* dengan *sensitivity* dan *specificity* ==paling optimal==.
* Lihat angka *area under curve* (AUC) :arrow_forward: ==mendekati 1==, maka validitas alat ukur makin baik.
* Lihat kurva ROC :arrow_forward: apabila ==kurva menjauhi garis diagonal==, makin baik. Menunjukkan alat ukur dapat memisahkan antara 'yang sakit' dengan 'yang sehat'.

</div>

---

### Terima kasih! :tada: 

Pertanyaan dapat diajukan di:

- [Spreadsheet](https://docs.google.com/spreadsheets/d/1LqcvLnfamGoE3rxKFg9eVtttMbmkPfcF7OxMY1yVGYM/edit?usp=sharing); or
- [Drop-in session (setiap Jumat pukul 11-12)](https://meet.google.com/iis-oxiz-emc); or
- [Email](mailto:amelia.zein@psikologi.unair.ac.id)
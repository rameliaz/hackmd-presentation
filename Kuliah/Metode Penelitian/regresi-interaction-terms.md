---
title: regresi dengan interaction terms
tags: research methods, lecture
description: berikut ini adalah materi MPAD Kuantitatif pertemuan terakhir
---

# Regresi dengan *interaction terms*

<!-- Put the link to this slide here so people can follow -->
salindia: https://hackmd.io/@ameliazein/interaksi

---

## Digunakan pada saat... :chart_with_upwards_trend: 

<div style="text-align: left">

* Digunakan untuk menguji model ==moderasi== yang melibatkan variabel ==moderator==
* Melibatkan hubungan satu arah antara tiga variabel
* Dalam **kondisi yang seperti apa/pada siapa/kapan** hubungan antara X dengan Y menguat/melemah?
* Kondisi yang menjelaskan kekuatan dan arah hubungan antara X dengan Y adalah ==**variabel moderator**==

</div>

---

## Asumsinya :exclamation:

Variabel independen dan variabel moderator **tidak berkorelasi**, namun variabel moderator dengan variabel dependen **harus berkorelasi**.

---

## Dapat dilihat dengan... :eyes: 

<div style="text-align: left">

* Pendekatan eksplisit (inspeksi visual – dilihat dengan scatterplot)
    - *Random (simple) slope analysis* – yaitu dengan melihat *regression slope*, dimana ketika moderasi terjadi, maka garis regresi akan berbeda **tergantung nilai variabel moderator**

</div>

---

![](https://i.imgur.com/vxQFndb.jpg =550x500)

---

## Dapat dilihat dengan... :eyes: 

<div style="text-align: left">

* Pendekatan implisit (dilihat dari *interaction effects*)
 - Asumsinya, kalau ada *interaction effects* maka secara implisit interaksi memang terjadi terjadi memang terjadi
 - Perbandingan sub-kelompok :arrow_forward: biasanya opsi tersedia di **ANOVA**

</div>

---

## Yang dilakukan saat ini...

<div style="text-align: left">

* Kita menggunakan pendekatan eksplisit :arrow_forward: menginspeksi *slope* pada *scatterplot* (*simple slope analysis*)
* Tetapi **tidak melakukan analisis moderasi** untuk mengetahui ada/tidaknya efek moderasi (*interaction effects*) :arrow_forward: dapat dilakukan dengan membandingkan kontribusi masing-masing prediktor secara terpisah dan *interaction terms*
* Asumsinya :exclamation: kalau *interaction terms* signifikan, maka **(mungkin) ada *interaction effects***

</div>

---

## Demonstrasi

<div style="text-align: left">

* Unduh dataset [nilai-ujian.omv](https://osf.io/ubhqd/)
* Pada opsi **model builder**, klik **add new block**
  - Klik **Block 1**, sampai keluar *shading* di pinggir kotak 
  - Kemudian sambil menekan tombol `ctrl`, klik **intelegensi** kemudian **sosioekonomi**, lalu klik tanda panah yang kedua dan pilih **interaction**
* Pada opsi **estimated marginal means**, masukkan **intelegensi** dan **sosioekonomi** dalam **terms 1**

</div>

---

## Cara melaporkan

<div style="text-align: left">

* Model tepat menggambarkan data (*F*(1, 398)=39.251, *p*<.001) dan varians prediktor dapat menjelaskan 9% dari varians variabel dependen (*R*<sup>2</sup>=.090).
* Kita dapat **menolak hipotesis nol** bahwa tidak ada korelasi antara interaksi intelegensi-sosioekonomi (*B*=0.031 95%CI [0.021, 0.041], *SE*=0.005, *p*<.001) dengan prestasi akademik mahasiswa.

</div>

---

![](https://i.imgur.com/yCjOFqw.jpg)

---

### Terima kasih! :tada: 

Pertanyaan dapat diajukan di:

- [Spreadsheet](https://docs.google.com/spreadsheets/d/1LqcvLnfamGoE3rxKFg9eVtttMbmkPfcF7OxMY1yVGYM/edit?usp=sharing); or
- [Drop-in session (setiap Jumat pukul 11-12)](https://meet.google.com/iis-oxiz-emc); or
- [Email](mailto:amelia.zein@psikologi.unair.ac.id)
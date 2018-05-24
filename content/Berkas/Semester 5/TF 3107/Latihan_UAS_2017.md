---
date: 2018-05-03
title: Latihan Ujian Tengah Semester 2018 K-01 (Endra Joelianto)
layout: manual
markup: mmark

---
## Soal 1 (Nilai 20, menguji *program outcome* A, K, E)

Diberikan sinyal $x(t)=4+3\cos(\pi t) + 2\cos(2\pi t) + \cos(3\pi t)$ dengan t dalam milidetik

1. Tentukan laju sampling minimum yang tidak akan menimbulkan efek aliasing.
2. Tentukan sinyal $x_a(t)$ yang akan teralias oleh x(t) karena waktu sampling (cacah) setengah dari frekuensi Nyquist nya.

## Soal 2 (Nilai 30, menguji *program outcome* A, K, E)

Rancang filter yang memiliki spesifikasi:

- Pass band 0-8 kHz
- Stop band > 10 kHz
- atenuasi di sekitar -30 dB
- *sampling frequency* 20 kHz

1. Dengan menggunakan window yang sesuai (ambil orde filter ganjil terdekat), tentukan persamaan impuls respon filter.
2. Tentukan persamaan respon impuls filter kausal.
3. Buat diagram blok filter sesuai dengan nilai paramternya dengan hanya menampilkan 3 koefisien pertama dan 3 koefisien terakhir dan koefisien lain dengan tanda (...)
4. Tentukan berapa data yang diperlukan agar didapatkan minimum 25 data respon *steady state* untuk analisis pengolahan sinyal.

## Soal 3 (Nilai 15, menguji *program outcome* A, E)

Diberikan fungsi alih suatu FIR Filter berikut:
$$
  H(z^{-1}) = \frac{1}{5}(1-z^{-1})^3(1-0.5z^{-1})^2
$$

1. Tentukan apakah filter stabil? Berikan alasannya.
2. Buatlah diagram blok dalam bentuk direct form.
3. Tentukan respon terhadap masukan x(n) = {1 2 3 4 1 2 3 1}.

## Soal 4 (Nilai 15, menguji *program outcome* A, E)

Rancang suatu filter dijital High Pass FIR linear phase yang mendekati respon frekuensi ideal:

$$
 H_d(\omega) =
  \begin{cases}
    0   & \text{untuk } |\omega| < \frac{\pi}{5} \\
    1   & \text{untuk } \frac{\pi}{5} \geq |\omega| \geq \pi
  \end{cases}
$$

1. Tentukan koefisien dari filter dengan 10 tap menggunakan *rectangular window*.
2. Tuliskan persamaan filternya.
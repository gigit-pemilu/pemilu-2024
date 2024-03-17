# Gigit Pemilu

## Selayang Pandang

Bagaimanakah tetep dapat melihat grafik dan table SIREKAP KPU?

Gigit Pemilu jawabannya.

Bagaimanakah cara mengetahui suara caleg/paslon yang tidak wajar di TPS? Perlu kah cek manual satu per satu?

Tidak perlu, karena ada Gigit Pemilu sebagai solusi.

## Apa itu Gigit Pemilu?

Gigit Pemilu adalah sebuah inisiatif memanfaatkan software `git` untuk melihat dan menyimpan perubahan data di SIREKAP KPU.

TLDR. To long Didn't Read, Here we go:

Project Utama:

https://github.com/gigit-pemilu/pemilu-2024

Langsung ke Grafik Pileg DPR:

https://github.com/gigit-pemilu/pemilu-2024/tree/main/pileg-dpr/hitung-suara

Langsung ke Grafik Pilpres:

https://github.com/gigit-pemilu/pemilu-2024/tree/main/pilpres/hitung-suara

Melihat perubahan data partai PSI:

https://github.com/gigit-pemilu/pemilu-2024/commits/main/pileg-dpr/hitung-suara/sub/partai-15.txt

Melihat perubahan data partai PKB:

https://github.com/gigit-pemilu/pemilu-2024/commits/main/pileg-dpr/hitung-suara/sub/partai-1.txt

Mencari suara Paslon 02 lebih dari 200 (sampai 999) di TPS di Jakarta:

[Command yang digunakan][1].

[1]: https://gist.github.com/pedagangamanah/54cc28b5f9100cf1501d7ad319449982#file-sample-1-sh

Hasil: (204, 202, 205, 222)

- https://github.com/gigit-pemilu/pemilu-2024-31-dki-jakarta/tree/main/pilpres/hitung-suara/sub/31-dki-jakarta/sub/72-jakarta-utara/sub/01-penjaringan/sub/1004-pejagalan/sub/011-tps
- https://github.com/gigit-pemilu/pemilu-2024-31-dki-jakarta/tree/main/pilpres/hitung-suara/sub/31-dki-jakarta/sub/72-jakarta-utara/sub/05-pademangan/sub/1001-pademangan-timur/sub/046-tps
- https://github.com/gigit-pemilu/pemilu-2024-31-dki-jakarta/tree/main/pilpres/hitung-suara/sub/31-dki-jakarta/sub/73-jakarta-barat/sub/05-kebon-jeruk/sub/1005-duri-kepa/sub/123-tps
- https://github.com/gigit-pemilu/pemilu-2024-31-dki-jakarta/tree/main/pilpres/hitung-suara/sub/31-dki-jakarta/sub/73-jakarta-barat/sub/01-cengkareng/sub/1006-cengkareng-timur/sub/157-tps

Mencari suara Paslon 03 lebih dari 200 (sampai 999) di TPS di Jawa Tengah:

[Command yang digunakan][2].

[2]: https://gist.github.com/pedagangamanah/54cc28b5f9100cf1501d7ad319449982#file-sample-2-sh

Hasil: (291, 274, 271, 271)

- https://github.com/gigit-pemilu/pemilu-2024-33-jawa-tengah/tree/main/pilpres/hitung-suara/sub/33-jawa-tengah/sub/23-temanggung/sub/18-bejen/sub/2003-jlegong/sub/006-tps
- https://github.com/gigit-pemilu/pemilu-2024-33-jawa-tengah/tree/main/pilpres/hitung-suara/sub/33-jawa-tengah/sub/22-semarang/sub/01-getasan/sub/2010-polobogo/sub/014-tps
- https://github.com/gigit-pemilu/pemilu-2024-33-jawa-tengah/tree/main/pilpres/hitung-suara/sub/33-jawa-tengah/sub/09-boyolali/sub/01-selo/sub/2001-tlogolele/sub/004-tps
- https://github.com/gigit-pemilu/pemilu-2024-33-jawa-tengah/tree/main/pilpres/hitung-suara/sub/33-jawa-tengah/sub/06-purworejo/sub/12-kemiri/sub/2020-dilem/sub/003-tps

Untuk pencarian nasional, diperlukan cloning seluruh repository provinsi terlebih dahulu.

[Command yang digunakan][3].

[3]: https://gist.github.com/pedagangamanah/54cc28b5f9100cf1501d7ad319449982#file-sample-3-sh

## Kontribusi

Jika project ini dirasa bermanfaat, mari kita patungan server yang digunakan sebagai crawler.

Donasi melalui Ko-Fi: https://ko-fi.com/gigitpemilu

Terimakasih.

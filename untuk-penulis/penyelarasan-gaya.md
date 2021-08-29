# Gaya Penulisan

Dokumen ini ditulis untuk menyelaraskan gaya penulisan buku ini.

## Pembuka Bab
\[Thaza\]: Mungkin dalam pembukaan bab, kita boleh senaraikan formula-formula penting dan sediakan pautan ke subtopik berkaitan untuk setiap persamaan itu? Ia boleh jadi sebagai satu tempat rujukan pantas.

## Berkaitan pembuktian persamaan
\[Thaza\]: Dalam mekanik kuantum, aku strukturkannya begini:
  1. Senaraikan aksiom/postulat sebagai satu senarai bernombor.
  2. Petua-petua matematik yang digunakan dinyatakan dalam kotak tersendiri (supaya pembaca kenal ia tidak muncul dari kaedah yang sedang diusahakan tetapi dicedok dari luar).

## Berkaitan Peristilahan
Katalah ada istilah `istilah` pertama kali digunakan dalam teks, maka kita perkenalkan maksudnya dalam margin:
````{margin}
```{admonition} Istilah
:class: hint

Maksud istilah tersebut dijelaskan di sini.
```
````

Namun, kita tetap akan ada satu tempat lain yang mengumpulkan semua istilah.

## Berkaitan Petua dan Definisi
Semua petua dan definisi diletakkan dalam `admonition`. Aku (\[Thaza\]) rasa macam menggunakan `prf:definition` adalah overkill untuk kegunaan rujukan pelajar sekolah.
````{admonition} Nama Petua atau Definisi
Keterangan di atas...
```{math}
:label: nama_persamaan
:class:

x = \frac{-b \pm \sqrt{b^2-4ac}}{2a}
```
...Keterangan di bawah
````
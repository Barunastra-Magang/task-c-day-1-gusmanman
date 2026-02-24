[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/PuAHYMGy)
# c-lang-day1

| Name  | Division        | Sub-Division  |
| ----- | ---------- | ---------- |
| Gusmantara M N | ELC | Microcontroller |

Kerjakan Day 1. c di bagian latihan soal, kasih comment untuk menjelaskan bagaimana kode itu berjalan

Penjelasan :
1.  Soal 1 (Faktorial rekursif). 
Ini tuh intinya nyari “perkalian dari 1 sampai N”. Misal N=5, berarti 5×4×3×2×1. Nah di kodenya pakai rekursi, jadi fungsi faktorial(). tu “minta bantuan dirinya sendiri” terus tapi angkanya dikecilin.Biar ga jalan terus selamanya, harus ada stopnya. Makanya kalau n udah 1 atau 0, langsung balikin 1.

2. Soal 2 (Deret 1, 5, 14, 30, ...).
Ini awalnya kita cari pola dulu. Kalau diliat bedanya dari 1 ke 5 nambah 4, dari 5 ke 14 nambah 9, dari 14 ke 30 nambah 16. Nah 4, 9, 16 itu ternyata 2², 3², 4². Jadi tiap suku nambah “kuadrat”.Jadi tiap suku nambah “kuadrat”. Makanya dibuat fungsi deret(n). kalau n=1 hasilnya 1. Kalau n lebih besar, hasilnya deret(n-1) + n*n.

3. Soal 3 (Cari max & min array).
Misal punya banyak angka. Biar cepet, kamu anggap dulu angka pertama itu paling kecil dan paling besar (sementara). Terus kamu cek satu-satu angka berikutnya.Kalau ada yang lebih kecil, ya ganti "min". Kalau ada yang lebih besar, ganti "max". Selesai. Kenapa pakai pointer. Soalnya mau fungsi itu “balikin” dua jawaban sekaligus, min dan max. Jadi min atau maxnya ditaruh di variabel main, terus fungsi cuma ngubah isinya lewat alamatnya.
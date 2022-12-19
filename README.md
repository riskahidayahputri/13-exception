# Belajar Exception pada python

Dengan menggunakan block try except
Repository ini dibuat sebagai tugas Bahasa pemrogramman

1. Pertama kita buat sebuah folder bernama 13-exception dan didalamnya kita buat file bernama Praktikum.py , filedemo.txt dan filedemo2.txt, untuk penamaan folder dan file itu sesuai kesukaan kalian.

<img width="957" alt="Screenshot 2022-12-19 155349" src="https://user-images.githubusercontent.com/115815582/208386071-39e02b9c-bd0a-439e-89c0-a1e8694a70cb.png">

2. Sekarang mari kita buka file Praktikum.py lalu inputkan codingan sebagai berikut :

![carbon (6)](https://user-images.githubusercontent.com/115815582/208386191-403bbb52-b3a6-44e5-b23c-f6369d59ba52.png)

! Kita melakukan penanganan kesalahan NameError lalu run dengan cara ketik python Praktikum.py di terminal

Maka hasilnya sebagai berikut :
<img width="788" alt="Screenshot 2022-12-19 152426" src="https://user-images.githubusercontent.com/115815582/208386303-81adb28c-9f94-4e71-8b4d-5184990c6e71.png">

3. Masih difile yang sama yaitu Praktikum.py lalu inputkan codingan sebagai berikut :

![carbon (7)](https://user-images.githubusercontent.com/115815582/208386422-78b2ee4f-cff2-4412-a3a6-2568088b0cb2.png)

! Jangan lupa untuk mengcomment codingan sebelumnya atau kalian boleh hapus agar kita fokus di contoh kedua yaitu FileNotFoundError

lalu run dengan cara ketik python Praktikum.py di terminal

Maka hasilnya sebagai berikut :

<img width="797" alt="Screenshot 2022-12-19 153431" src="https://user-images.githubusercontent.com/115815582/208386550-7e5257c6-fed8-40af-94e1-50045f733cce.png">

4. Masih difile yang sama yaitu Praktikum.py lalu inputkan codingan sebagai berikut :

![carbon (8)](https://user-images.githubusercontent.com/115815582/208386647-108b01f2-49ec-430e-9dc3-e28ff634121b.png)

! Jangan lupa untuk mengcomment codingan sebelumnya atau kalian boleh hapus agar kita fokus di contoh kedua yaitu FileExistError

lalu run dengan cara ketik python Praktikum.py di terminal

Maka hasilnya sebagai berikut :

<img width="793" alt="Screenshot 2022-12-19 154229" src="https://user-images.githubusercontent.com/115815582/208386738-0529036f-001a-4f50-ae1d-04b389bbace8.png">

disini error bahwa file tersebut sudah ada, seperti yang kita lihat filedemo2 sudah kita buat diawal. jadi kita tidak boleh membuat file dengan nama yang sama dalam satu folder

5. Masih difile yang sama yaitu Praktikum.py lalu inputkan codingan sebagai berikut :

![carbon (9)](https://user-images.githubusercontent.com/115815582/208386940-0abad404-d070-4da6-b368-c4872b92c859.png)

! Jangan lupa untuk mengcomment codingan sebelumnya atau kalian boleh hapus agar kita fokus di contoh keempat yaitu TypeError

lalu run dengan cara ketik python Praktikum.py di terminal

Maka hasilnya sebagai berikut :

<img width="796" alt="Screenshot 2022-12-19 154854" src="https://user-images.githubusercontent.com/115815582/208387052-a73aef5e-aed7-4727-a350-80b1aa477ad1.png">

Baik disini errornya berupa type yaitu bahwa nim itu harus integer, karena fungsi input selalu mengembalikan type data string, jika kalian tidak ingin eror kalian bisa convert nim trsebut ke integer dngn cara berikut => nim = int(input("Masukan NIM : "))

Baik Teman teman kurang lebih seperti itu dalam belajar exception pada python.
di repository ini kita memang sengaja membuat kesalahan agar bisa mengetes exception dengan try except, Untuk kali ini kita hanya belajar beberapa saja dari exception

sekian dan terima kasih maaf jika ada kesalahan

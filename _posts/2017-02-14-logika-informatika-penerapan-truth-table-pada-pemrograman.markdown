---
comments: true
date: 2017-02-14 14:31:30
layout: post
slug: "logika-Informatika-penerapan-truth-table-pada-pemrograman"
title: "Logika Informatika - Penerapan Truth Table pada Pemrograman"
categories:
- ilmukomputer
---

**"The Truth Table"** atau Tabel kebenaran adalah tabel yang digunakan untuk melihat nilai kebenaran dari suatu pernyataan. Di sini tabel kebenaran dapat diartikan sebagai tabel yang berisi kombinasi-kombinasi variabel masukan (input) yang menghasilkan keluaran (output) yang logis.\\
<!--more-->
**Jenis-jenis tabel kebenaran**\\
Terdapat beberapa tabel kebenaran berdasarkan operator :
1.  Tabel Kebenaran AND
    Pada tabel kebenaran dengan operator AND, jika semua atau salah satu inputnya memiliki pernyataan salah/false/0, maka outputnya akan menjadi salah. Sedangkan jika semua input adalah pernyataan benar/true/1, maka hasilnya menjadi pernyataan yang benar.
    [![Tabel Kebenaran AND ](/images/uploads/2017/02-14/TruthTableAND.PNG)](/images/uploads/2017/02-14/TruthTableAND.PNG)\\
    Tabel kebenaran AND jika direpresentasikan kedalam bahasa pemrograman sebagai berikut :\\
    Pada contoh dibawah ini saya tampilkan dalam bahasa pemrograman java.
    ```java
    public class TruthTableAnd {
    public static void main(String[] args) {
         int bilPertama = 10;
         int bilKedua = 11;
         if (bilPertama >= 10 && bilKedua >= 12) {
             System.out.println("Benar");
         }else System.out.println("Salah");
        }
    }
    ```
    Output dari program diatas
    > Salah
    
    Berikut penjelasan dari kode program :
    > Pada contoh baris kode diatas tampilkan pengujian 2 pernyataan, **bilPertama** yang dibandingkan apakah lebih dari 10, pernyataan tersebut bernilai benar.
    Kemudian pada ruas kanan dibandingkan pernyataan kedua yaitu apakah **bilKedua** lebih besar sama dengan 12, pernyataan tersebut bernilai salah, maka hasil dari kedua pernyataan itu ialah **salah** 

2.  Tabel Kebenaran OR
    Pada tabel kebenaran dengan operator OR, jika salah input memiliki pernyataan benar, maka outputnya akan menjadi benar. Sedangkan jika semua input adalah pernyataan salah, maka hasilnya menjadi pernyataan yang salah.\\
    [![Tabel Kebenaran OR ](/images/uploads/2017/02-14/TruthTableOR.PNG)](/images/uploads/2017/02-14/TruthTableOR.PNG)
    ```java
    public class TruthTableOR {
    public static void main(String[] args) {
         int bilPertama = 10;
         int bilKedua = 11;
         if (bilPertama >= 10 || bilKedua >= 12) {
             System.out.println("Benar");
         }else System.out.println("Salah");
        }
    }
    ```
    Output dari program diatas
    > Benar
    
    Penjelasan kode program :
    > Pada contoh kode program diatas pernyataan pertama **bilPertama** bernilai benar karena lebih dari 10, kemudian pada pernyataan kedua **bilKedua** bernilai salah.
    Berdasarkan sifat dari operator OR pada tabel kebenaran. Jika salah satu pernyataan bernilai benar maka hasil dari kedua pernyataan tersebut bernilai benar.


3. Tabel Kebenaran NOT
   Pada tabel kebenaran dengan operator Negasi/Not, merepresentasikan pernyataan dengan keadaan terbalik, jika pernyataan tersebut benar, maka hasilnya akan menjadi salah.
   Begitupun akan berlaku sebaliknya sesuai dengan pernyataan yang diuji.\\
   [![Tabel Kebenaran Negasi/NOT ](/images/uploads/2017/02-14/TruthTableNot.PNG)](/images/uploads/2017/02-14/TruthTableNot.PNG)

   ```java
   public class TruthTableNot {
    public static void main(String[] args) {
         int bilPertama = 10;
         int bilKedua = 11;
         if (! (bilPertama >= 10) ) {
             System.out.println("Benar");
         }else System.out.println("Salah");
         
         if (! (bilKedua >= 12) ) {
             System.out.println("Benar");
         }else System.out.println("Salah");
        }
    }
    ```
    
    Pada kode program diatas menghasilkan 2 output :\\
    **Output pertama**\\
    Pada pernyataan pertama : **bilPertama** lebih besar sama dengan 10 bernilai **benar**, namun karena dinegasikan sehingga pernyataan tersebut bernilai **salah**.\\
    **Output Kedua**\\
    Pada pernyataan kedua : **bilKedua** lebih besar sama dengan 12 bernilai **salah**, namun karena dinegasikan sehingga pernyataan tersebut bernilai **benar**.

Sekian penjelasan saya terkait penerapan **Truth Table (Tabel Kebenaran )** pada bahasa pemrograman.


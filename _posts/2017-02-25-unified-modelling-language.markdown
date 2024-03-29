---
comments: true
date: 2017-02-25 09:08:30
layout: post
slug: "unified-modelling-language"
title: "Unified Modelling Language"
categories:
- softwaredevelopment
---

UML (Unified Modelling Language) adalah suatu metode dalam pemodelan secara visual yang digunakan sebagai sarana perancangan sistem berorientasi objek. Awal mulanya, UML diciptakan oleh Object Management Group dengan versi awal 1.0 pada bulan Januari 1997.

Apa itu UML? Untuk membuat suatu aplikasi, kamu memerlukan suatu pemodelan. Pemodelan sama halnya dengan perancangan, bedanya pemodelan sendiri merupakan bentuk implementasi sistem bagaimana meletakkan suatu rancang bangun ke dalam sebuah gambar (visual) yang berbentuk diagram.

<!--more-->

Seorang programmer dapat dengan mudah memahami, menganalisa dan, mempermudah pembuatan suatu program menggunakan UML (Unified Modelling Language). Sebuah program aplikasi biasanya berupa sistem yang digunakan dan diimplementasikan dalam jangka waktu yang cukup panjang. Program aplikasi bukan hanya digunakan pada saat itu saja, melainkan terus continue atau berlanjut. 

Karena program aplikasi digunakan pada waktu yang panjang, maka perlu adanya suatu analisis perencanaan, perancangan, dan pemodelan yang baik dan jelas, seperti flow untuk program aplikasi.

Pada artikel kali ini saya akan menjabarkan mengenai konsep suatu bahasa visual, di mana definisi dari UML beserta contohnya. Mari simak penjelasan berikut ini.

UML juga dapat didefinisikan sebagai suatu bahasa standar visualisasi, perancangan, dan pendokumentasian sistem, atau dikenal juga sebagai bahasa standar penulisan blueprint sebuah software.

Perlu kamu ketahui bahwa sistem yang baik itu berawal dari perancangan dan pemodelan yang matang. Salah satu yang bisa kamu praktekkan, yaitu dengan menggunakan UML. Adapun tujuan dan fungsi perlu adanya UML yaitu sebagai berikut:

1. Dapat memberikan bahasa pemodelan visual atau gambar kepada para pengguna dari berbagai macam pemrograman maupun proses umum rekayasa.
2. Menyatukan informasi-informasi terbaik yang ada dalam pemodelan.
3. Memberikan suatu gambaran model atau sebagai bahasa pemodelan visual yang ekspresif dalam pengembangan sistem.
4. Tidak hanya menggambarkan model sistem software saja, namun dapat memodelkan sistem berorientasi objek.
5. Mempermudah pengguna untuk membaca suatu sistem.
6. Berguna sebagai blueprint, jelas ini nantinya menjelaskan informasi yang lebih detail dalam perancangan berupa coding suatu program

Berikut contoh-contoh diagram :
1. **Use Case Diagram**.
   [![Use Case Diagram](/images/uploads/2017/02-25/use-case-diagram-atm.png)](/images/uploads/2017/02-25/use-case-diagram-atm.png)
   Use Case Diagram adalah satu jenis dari diagram UML (Unified Modelling Language) yang menggambarkan hubungan interaksi antara sistem dan aktor. Use Case dapat mendeskripsikan tipe interaksi antara si pengguna sistem dengan sistemnya. Use Case merupakan sesuatu yang mudah dipelajari. Langkah awal untuk melakukan pemodelan perlu adanya suatu diagram yang mampu menjabarkan aksi aktor dengan aksi dalam sistem itu sendiri, seperti yang terdapat pada Use Case.

2. **Activity Diagram**.
   [![Activity Diagram](/images/uploads/2017/02-25/activity-diagram-768x521.png)](/images/uploads/2017/02-25/use-case-diagram-atm.png)
   Activity diagram atau dalam bahasa Indonesia berarti diagram aktivitas, merupakan sebuah diagram yang dapat memodelkan berbagai proses yang tejadi pada sistem. Seperti layaknya runtutan proses berjalannya suatu sistem dan digambarkan secara vertikal. Activity diagram adalah salah satu contoh diagram dari UML dalam pengembangan dari Use Case.

3. **Sequence Diagram**.
   [![Sequence Diagram](/images/uploads/2017/02-25/sequence-diagram-768x504.png)](/images/uploads/2017/02-25/sequence-diagram-768x504.png)
   Sequence diagram merupakan diagram yang menjelaskan interaksi objek berdasarkan urutan waktu. Sequence dapat menggambarkan urutan atau tahapan yang harus dilakukan untuk dapat menghasilkan sesuatu, seperti yang tertera pada Use Case diagram.

4. **Class Diagram**.
   [![Class Diagram](/images/uploads/2017/02-25/class-diagram-768x352.png)](/images/uploads/2017/02-25/class-diagram-768x352.png)
   Class diagram atau diagram kelas merupakan suatu diagram yang digunakan untuk menampilkan kelas-kelas berupa pake-paket untuk memenuhi salah satu kebutuhan paket yang akan digunakan nantinya.
   Namun, pada Class diagram desain modelnya dibagi menjadi 2 bagian. Class diagram yang pertama merupakan penjabaran dari domain model yang merupakan abstraksi dari basis data. Class diagram yang kedua merupakan bagian dari modul program MVC pattern (Model View Controller), di mana terdapat class boundary sebagai class interface, class control sebagai tempat ditemukannya algoritma, dan class entity sebagai tabel dalam basis data dan query program.

5. **Statemachine Diagram**.
   [![Statemachine Diagram](/images/uploads/2017/02-25/statemachine-diagram-768x545.png)](/images/uploads/2017/02-25/statemachine-diagram-768x545.png)
   Statemachine yaitu salah satu jenis diagram pada UML yang berfungsi untuk menggambarkan transisi serta perubahan pada suatu objek pada sistem.

6. **Component Diagram**.
   [![Component Diagram](/images/uploads/2017/02-25/component-diagram-768x352.png)](/images/uploads/2017/02-25/component-diagram-768x352.png)
   Component diagram yang berfungsi untuk menggambarkan software pada suatu sistem. Component diagram merupakan penerapan pada piranti lunak atau software dari satu class maupun lebih, dan biasanya berupa file data, source code,.exe, table, dokumen, atau yang lainnya.
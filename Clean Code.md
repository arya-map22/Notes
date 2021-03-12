> **Judul : Clean Code : A Handbook of Agile Software Craftsmanship**
> 
> **Penulis : Robert C. Martin**
> 
> **Penerbit : Prentice Hall**
> 
> **Jumlah Halaman : +- 462 halaman**
> 
> **Genre : Computer**
> 
> ***Start : 11, Maret 2021***
> 
> ***Finish : -***

---

# Daftar isi :

- [Daftar isi :](#daftar-isi-)
- [Chapter 1 : Clean Code](#chapter-1--clean-code)
  - [There Will Be Code](#there-will-be-code)
  - [Bad Code](#bad-code)
  - [The Total Cost of Owning a Mess](#the-total-cost-of-owning-a-mess)
    - [The Grand Redesign in the Sky](#the-grand-redesign-in-the-sky)
    - [Attitude](#attitude)
    - [The Primal Conundrum](#the-primal-conundrum)
    - [The Art of Clean Code?](#the-art-of-clean-code)
    - [What Is Clean Code?](#what-is-clean-code)
      - [Bjarne Stroustrup, inventor of C++ and author of The C++ Programming Language](#bjarne-stroustrup-inventor-of-c-and-author-of-the-c-programming-language)
      - [Grady Booch, author of Object Oriented Analysis and Design with Applications](#grady-booch-author-of-object-oriented-analysis-and-design-with-applications)
      - [“Big” Dave Thomas, founder of OTI, godfather of the Eclipse strategy](#big-dave-thomas-founder-of-oti-godfather-of-the-eclipse-strategy)
      - [Michael Feathers, author of Working Effectively with Legacy Code](#michael-feathers-author-of-working-effectively-with-legacy-code)
      - [Ron Jeffries, author of Extreme Programming Installed and Extreme Programming Adventures in C](#ron-jeffries-author-of-extreme-programming-installed-and-extreme-programming-adventures-in-c)
      - [Ward Cunningham, inventor of Wiki, inventor of Fit, coinventor of eXtreme Programming. Motive force behind Design Patterns. Smalltalk and OO thought leader. The godfather of all those who care about code.](#ward-cunningham-inventor-of-wiki-inventor-of-fit-coinventor-of-extreme-programming-motive-force-behind-design-patterns-smalltalk-and-oo-thought-leader-the-godfather-of-all-those-who-care-about-code)
  - [Schools of Thought](#schools-of-thought)
  - [We Are Authors](#we-are-authors)
  - [The Boy Scout Rule](#the-boy-scout-rule)
- [Chapter 2 : Meaningful Names](#chapter-2--meaningful-names)

---

# Chapter 1 : Clean Code

## There Will Be Code

- Walaupun teknologi terus berkembang menjadi semakin canggih, kita tidak akan pernah terlepas dari **code**.

- **Code** menjadi sangat penting karena digunakan untuk memberi intstruksi pada komputer untuk melakukan pekerjaan yang diinginkan dan untuk merepresentasikan pikiran / ide yang akan diimplementasikan ke dalam komputer.

- Tanpa **code** komputer hanyalah sebuah *mesin bodoh* yang tidak tahu apa-apa. Tugas kita sebagai **programmer** untuk membuat komputer menjadi *mesin pintar* yang melakukan hal yang kita inginkan / butuhkan.

- Sebuah **code** haruslah tepat, akurat, formal, dan detail agar bisa dimengerti oleh komputer dan dieksekusi dengan tepat dan menghasilkan hasil yang dikehendaki.

## Bad Code

- **Code** yang buruk adalah **code** yang sulit dipahami, terstruktur dengan buruk, dan sulit untuk dimodifikasi / diupdate (ketika suatu bagian diubah akan merusak bagian lainnya).

- Kebanyakan **code** yang buruk adalah **code** yang ditulis dalam keadaan *terburu-buru* atau biasanya ketika dikejar deadline.

- Kebanyakan **programmer** menulis **code** dengan tergesa-gesa karena menurut mereka *mengerjakan sesuatu walaupun buruk lebih baik daripada tidak sama sekali.*

- Karena sulit dimodifikasi, **code** yang buruk bisa menyebabkan suatu aplikasi menjadi *produk yang gagal*. *Suatu perusahaan bisa hancur gara-gara **code** yang buruk.*

## The Total Cost of Owning a Mess

- **Code** yang buruk memperlambat produktivitas dengan drastis. 

- Ketika suatu tim **programmer** menulis **code** yang buruk di awal proyek, mereka akan mengalami penurunan produktivitas yang drastis di tengah-tengah pengerjaan.

### The Grand Redesign in the Sky

- Karena produktivitas menurun, para **programmer** ini akan mengusulkan untuk mendesain ulang proyek tersebut. Kemudian dibentuklah tim baru untuk membuat proyek baru untuk menggantikan sistem yang lama.

- Kemudian kedua tim (baru dan lama) tersebut akan berlomba untuk mengerjakan proyek masing-masing. Proyek baru harus bisa mengerjakan yang sama dengan sistem lama, dan manajer tidak akan mengganti sistem yang lama dengan yang baru sampai sistem tersebut selesai.

- Waktu pengerjaan proyek sistem baru tersebut memakan waktu yang sangat lama, dan ketika selesai biasanya anggota tim yang asli sudah lama tergantikan.

- Pelajaran yang bisa diambil adalah *menghabiskan waktu untuk menulis **code** yang baik akan memberikan dampak jangka panjang yang lebih efektif.*

### Attitude

- Kegagalan suatu proyek akibat **code** buruk bukan terletak pada manajer yang memberikan jadwal sangat padat atau pada kustomer yang memberikan spesifikasi yang rumit. Tetapi kesalahannya adalah pada **programmer** yang tidak profesional.

- Ketika kita (**programmer**) ditekan oleh manajer untuk menepati jadwal meskipun harus mengorbankan penulisan **code** yang baik, tugas kita adalah untuk mempertahankan **code** yang baik. Kita harus berani mengingatkan manajer kita bahwa **code** yang buruk justru akan merusak keseluruhan proyek.

### The Primal Conundrum

- **Code** yang buruk akan memperlambat kita. Kebanyakan kita akan menulis **code** yang buruk untuk menepati deadline, tetapi **code** yang buruk justru akan membuat kita melewatkan deadline.

- **Programmer** profesional paham bahwa kita tidak akan menepati deadline dengan **code** yang buruk.

- Satu-satunya cara untuk menepati deadline adalah dengan berusaha untuk menulis **code** yang baik setiap saat.

### The Art of Clean Code?

- Mampu untuk mengenali **code** yang baik bukan berarti kita mampu untuk menulis **code** yang baik.

- Untuk mampu menulis **code** yang baik diperlukan sebuah perasaan yang mendalam tentang **code**. Perasaan ini akan membantu kita menentukan baik buruknya sebuah **code**, dan menunjukkan kepada kita suatu cara untuk merubah **code** yang buruk menjadi baik.

- Ketika seseorang tanpa perasaan tentang **code** melihat **code** yang berantakan dan buruk ia tidak tahu harus berbuat apa. Kebalikannya seseorang yang punya perasaan tentang **code** akan melihat berbagai cara dan pilihan.

### What Is Clean Code?

#### Bjarne Stroustrup, inventor of C++ and author of The C++ Programming Language

> *I like my code to be elegant and efficient. The logic should be straightforward to make it hard for bugs to hide, the dependencies minimal to ease maintenance, error handling complete according to an articulated strategy, and performance close to optimal so as not to tempt people to make the code messy with unprincipled optimizations. Clean code does one thing well.*

- **Code** yang baik adalah **code** yang :
  - Menyenangkan untuk dibaca
  - Efisien
  - **Error handling** yang lengkap
  - Peforma optimal
  - Melakukan satu pekerjaan dengan baik

- **Code** yang buruk ketika dimodifikasi oleh seseorang biasanya akan menjadi lebih buruk.

#### Grady Booch, author of Object Oriented Analysis and Design with Applications

> *Clean code is simple and direct. Clean code reads like well-written prose. Clean code never obscures the designer’s intent but rather is full of crisp abstractions and straightforward lines of control.*

- **Code** yang baik adalah **code** yang :
  - Sederhana dan jelas
  - Ditulis dengan indah sehingga membacanya seperti membaca novel
  - Konkrit tanpa detail yang tidak berguna
  - Tidak membuat tujuan penulisannya ambigu

#### “Big” Dave Thomas, founder of OTI, godfather of the Eclipse strategy

> *Clean code can be read, and enhanced by a developer other than its original author. It has unit and acceptance tests. It has meaningful names. It provides one way rather than many ways for doing one thing. It has minimal dependencies, which are explicitly defined, and provides a clear and minimal API. Code should be literate since depending on the language, not all necessary information can be expressed clearly in code alone.*

- **Code** yang baik adalah **code** yang :
  - Dapat dimodifikasi dengan mudah oleh orang lain
  - Memuat nama-nama yang berarti (variabel)
  - Menyediakan satu cara untuk menyelesaikan sesuatu
  - Telah diuji
  - Menyediakan **Application Programming Interface (API)** yang jelas dan minimal

- Semakin kecil **code** semakin baik.

#### Michael Feathers, author of Working Effectively with Legacy Code

> *I could list all of the qualities that I notice in clean code, but there is one overarching quality that leads to all of them. Clean code always looks like it was written by someone who cares. There is nothing obvious that you can do to make it better. All of those things were thought about by the code’s author, and if you try to imagine improvements, you’re led back to where you are, sitting in appreciation of the code someone left for you—code left by someone who cares deeply about the craft.*

- **Code** yang baik adalah **code** yang :
  - Ditulis oleh seseorang yang *peduli*
  - Tidak ada hal yang bisa dilakukan untuk mengubahnya menjadi lebih baik
  - Setiap cara dan kemungkinan untuk membuatnya lebih baik sudah dipikirkan matang-matang oleh penulis

#### Ron Jeffries, author of Extreme Programming Installed and Extreme Programming Adventures in C#

> *In recent years I begin, and nearly end, with Beck’s rules of simple code. In priority order, simple code:*
> - *Runs all the tests;*
> - *Contains no duplication;*
> - *Expresses all the design ideas that are in the system;*
> - *Minimizes the number of entities such as classes, methods, functions, and the like.*
> 
> *Of these, I focus mostly on duplication. When the same thing is done over and over, it’s a sign that there is an idea in our mind that is not well represented in the code. I try to figure out what it is. Then I try to express that idea more clearly.*
> 
>  *Expressiveness to me includes meaningful names, and I am likely to change the names of things several times before I settle in. With modern coding tools such as Eclipse, renaming is quite inexpensive, so it doesn’t trouble me to change. Expressiveness goes beyond names, however. I also look at whether an object or method is doing more than one thing. If it’s an object, it probably needs to be broken into two or more objects. If it’s a method, I will always use the Extract Method refactoring on it, resulting in one method that says more clearly what it does, and some submethods saying how it is done.*
>
> *Duplication and expressiveness take me a very long way into what I consider clean code, and improving dirty code with just these two things in mind can make a huge difference. There is, however, one other thing that I’m aware of doing, which is a bit harder to explain.*
>
> *After years of doing this work, it seems to me that all programs are made up of very similar elements. One example is “find things in a collection.” Whether we have a database of employee records, or a hash map of keys and values, or an array of items of some kind, we often find ourselves wanting a particular item from that collection. When I find that happening, I will often wrap the particular implementation in a more abstract method or class. That gives me a couple of interesting advantages.*
> 
> *I can implement the functionality now with something simple, say a hash map, but since now all the references to that search are covered by my little abstraction, I can change the implementation any time I want. I can go forward quickly while preserving my ability to change later.*
> 
> *In addition, the collection abstraction often calls my attention to what’s “really”going on, and keeps me from running down the path of implementing arbitrary collection behavior when all I really need is a few fairly simple ways of finding what I want.*
>
> *Reduced duplication, high expressiveness, and early building of simple abstractions.That’s what makes clean code for me.*

- **Code** yang baik adalah **code** yang :
  - Tidak ada duplikasi
  - Melakukan satu pekerjaan
  - Pengekspresian yang jelas
  - Mengandung sedikit abstraksi

#### Ward Cunningham, inventor of Wiki, inventor of Fit, coinventor of eXtreme Programming. Motive force behind Design Patterns. Smalltalk and OO thought leader. The godfather of all those who care about code.

> *You know you are working on clean code when each routine you read turns out to be pretty much what you expected. You can call it beautiful code when the code also makes it look like the language was made for the problem.*

- **Code** yang baik adalah **code** yang :
  - Ketika dibaca tidak akan mengejutkan (sesuai ekspetasi)
  - Sangat sederhana sehingga tidak memerlukan banyak upaya untuk memahaminya
  - Terlihat seakan-akan bahasanya dibuat untuk masalah tersebut

- Adalah tugas seorang **programmer** untuk membuat **code** yang sederhana.

## Schools of Thought

- Kita tidak bisa hanya belajar dari satu sumber. Kita harus memperluas wawasan dengan belajar dari berbagai sumber sekaligus.

- Tidak ada sumber yang benar secara "mutlak", pasti ada kekurangan dan kelebihannya.

## We Are Authors

- Seorang **programmer** bisa dianalogikan dengan seorang penulis. Seorang penulis pasti akan mempunyai pembaca yang membaca karyanya, begitu juga dengan **programmer** pasti akan ada orang yang akan membaca **code**nya.

- Penulis bertanggung jawab untuk bisa berkomunikasi dengan baik dengan pembacanya lewat tulisannya, begitu juga dengan **programmer.**

- Kita lebih banyak menghabiskan waktu untuk membaca daripada menulis **code.**

- Ketika kita menulis **code** baru, mau tidak mau kita harus membaca dan memahami **code** yang lama.

- Kita tidak akan mampu menulis **code** yang baru ketika kita tidak dapat memahami **code** yang lama.

- *Membuat **code** mudah dibaca memudahkan kita untuk menulis **code** baru di masa depan.*

## The Boy Scout Rule

> *Leave the campground cleaner than you found it.*

- Sama dengan **code**, kita harus sebisa mungkin membuat **code** menjadi lebih baik daripada sebelumnya.

---

# Chapter 2 : Meaningful Names


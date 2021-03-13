> **Judul	: Discrete Mathematics, and Its Applications**
>
> **Penulis : Kenneth H. Rosen**
> 
> **Penerbit : McGraw-Hill Education**
> 
> **Jumlah Halaman : +- 1118 halaman**
> 
> **Genre : Mathematics**
> 
> ***Start : 12, Maret 2021***
> 
> ***Finish : -***

---

# Daftar isi :
- [Daftar isi :](#daftar-isi-)
- [Chapter 1 : The Foundations : Logic and Proofs](#chapter-1--the-foundations--logic-and-proofs)
  - [1.1 : Propositional Logic](#11--propositional-logic)
    - [1.1.1 : Introduction](#111--introduction)
    - [1.1.2 : Propositions](#112--propositions)
      - [Negation](#negation)
      - [Conjunction (AND)](#conjunction-and)
      - [Disjunction (OR)](#disjunction-or)
      - [Exclusive Or (XOR)](#exclusive-or-xor)
    - [1.1.3 : Conditional Statements](#113--conditional-statements)
      - [Implications](#implications)
      - [Converse, Contrapositive, and Inverse](#converse-contrapositive-and-inverse)
      - [Biconditionals](#biconditionals)
    - [1.1.4 : Truth Tables of Compound Propositions](#114--truth-tables-of-compound-propositions)
    - [1.1.5 : Precedence of Logical Operators](#115--precedence-of-logical-operators)
    - [1.1.6 : Logic and Bit Operations](#116--logic-and-bit-operations)

---

# Chapter 1 : The Foundations : Logic and Proofs

## 1.1 : Propositional Logic

### 1.1.1 : Introduction

- Tujuan dari aturan logika dalam matematika adalah untuk memberikan arti yang jelas pada pernyataan matematika.

- Logika digunakan untuk menentukan sah atau tidaknya argumen dalam matematika.

### 1.1.2 : Propositions

> **Proposisi** adalah sebuah kalimat pernyataan yang memiliki arti benar atau salah, *tetapi tidak keduanya.*

- Contoh proposisi :
  - Saya adalah anak laki-laki
  - Dia lulus tahun ini
  - Tahun ini adalah tahun 2021 M

- Contoh *bukan* proposisi :
  - Siapa dia? (*pertanyaan*)
  - Tolong bacakan tulisan itu (*perintah*)
  - x + 1 = 5 (*kita tidak tahu berapa nilai x*)

- Setiap proposisi dapat dinotasikan dengan sebuah *variabel proposisi* (umumnya : $p, q, r, s, t, ...$).

- **Nilai kebenaran** dari proposisi :
  - Benar (T) jika proposisinya benar
  - Salah (F) jika proposisinya salah

- Proposisi yang tidak bisa diekspresikan dengan proposisi yang lebih sederhana dinamakan **proposisi atomik.**

- Sebuah pernyataan matematika umumnya terdiri atas beberapa proposisi yang digabungkan menjadi 1 membentuk sebuah proposisi baru yang disebut **proposisi majemuk.**

- Proposisi majemuk dibentuk dengan menggabungkan beberapa proposisi yang sudah ada menggunakan **operator logika.**

#### Negation
> **Negasi** dari sebuah proposisi $p$ (dinotasikan dengan **$\neg p$**) adalah sebuah proposisi yang berarti "bukan $p$". 
>
> Memiliki nilai kebenaran yang berlawanan dengan nilai kebenaran dari $p$.

- Contoh :
  Misalkan $p$ = "saya adalah anak laki-laki".
  Maka $\neg p$ = "saya adalah anak perempuan" atau "saya bukan anak laki-laki".

- Tabel kebenaran dari negasi :
  |$p$   | $\neg p$ |
  |------|----------|
  |T     |F         |
  |F     |T         |
  
#### Conjunction (AND)
> Misalkan $p$ dan $q$ adalah sebuah proposisi maka **konjungsi** dari $p$ dan $q$ (dinotasikan dengan **$p \land q$**) adalah sebuah proposisi yang berarti "$p$ dan $q$".
>
> Bernilai benar jika $p$ dan $q$ keduanya benar, dan salah untuk nilai $p$ dan $q$ yang lain.

- Contoh :
  Misalkan $p$ = "hari ini adalah hari rabu", $q$ = "hari ini hujan deras".
  Maka $p \land q$ = "hari ini adalah hari rabu dan hari ini hujan deras" hanya benar ketika hari ini memang hari rabu dan hari ini sedang hujan deras.

- Tabel kebenaran dari konjungsi :
  |$p$|$q$|$p \land q$|
  |---|---|-----------|
  |T  |T  |T          |
  |T  |F  |F          |
  |F  |T  |F          |
  |F  |F  |F          |

#### Disjunction (OR)
> Misalkan $p$ dan $q$ adalah sebuah proposisi maka **disjungsi** dari $p$ dan $q$ (dinotasikan dengan **$p \lor q$**) adalah sebuah proposisi yang berarti "$p$ atau $q$".
>
> Bernilai salah jika $p$ dan $q$ keduanya salah, dan benar untuk nilai $p$ dan $q$ yang lain.

- Contoh :
  Misalkan $p$ = "saya akan membeli hp", $q$ = "saya akan membeli laptop".
  Maka $p \lor q$ = "saya akan membeli hp atau laptop" akan bernilai benar jika saya membeli hp, laptop, atau keduanya, dan akan bernilai salah jika saya tidak membeli keduanya.

- Disjungsi bersifat **inklusif** karena bernilai benar ketika *salah satu atau kedua proposisi bernilai benar.*

- Tabel kebenaran dari disjungsi
  |$p$|$q$|$p \lor q$|
  |---|---|-----------|
  |T  |T  |T          |
  |T  |F  |T          |
  |F  |T  |T          |
  |F  |F  |F          |

#### Exclusive Or (XOR)
> Misalkan $p$ dan $q$ adalah sebuah proposisi maka **eksklusif or** dari $p$ dan $q$ (dinotasikan dengan **$p \oplus q$**) adalah sebuah proposisi yang berarti "$p$ atau $q$" yang bernilai benar jika ***hanya salah satu*** dari $p$ dan $q$ bernilai benar, dan salah untuk nilai $p$ dan $q$ yang lain.

- Contoh :
  Misalkan $p$ = "pemenang akan mendapatkan sebuah piala", $q$ = "pemenang akan mendapatkan sebuah sertifikat".
  Maka $p \oplus q$ = "pemenang dapat memilih untuk mendapatkan piala atau sertifikat" atau "pemenang akan mendapatkan piala atau sertifikat, tetapi tidak keduanya" bernilai benar ketika pemenang hanya mendapatkan sebuah piala saja atau sertifikat saja, dan bernilai salah apabila pemenang mendapatkan keduanya atau tidak mendapatkan keduanya.

- Tabel kebenaran dari eksklusif or :
  |$p$|$q$|$p \oplus q$|
  |---|---|------------|
  |T  |T  |F           |
  |T  |F  |T           |
  |F  |T  |T           |
  |F  |F  |F           |

### 1.1.3 : Conditional Statements

#### Implications
> Misalkan $p$ dan $q$ adalah sebuah proposisi maka **implikasi** dari $p$ dan $q$ (dinotasikan dengan **$p \implies q$**) adalah sebuah proposisi yang berarti "jika $p$, maka $q$".
>
> Bernilai salah jika $p$ bernilai benar dan $q$ bernilai salah, dan benar untuk nilai $p$ dan $q$ yang lain.
>
> $p$ disebut premis / hipotesis, dan $q$ disebut konklusi / kesimpulan.

- Ada bervariasi cara penulisan $p \implies q$ dalam bahasa sehari-hari.

- Contoh :
  Misalkan $p$ = "saya lulus SMA", $p$ = "saya akan mendaftar ke ITS". Maka $p \implies q$ =
  - "Jika saya lulus SMA, maka saya akan mendaftar ke ITS" (jika $p$ maka $q$)
  - "Saya akan mendaftar ke ITS hanya jika saya lulus SMA" ($q$ hanya jika $p$)
  - "Saya akan mendaftar ke ITS ketika saya lulus SMA" ($q$ ketika $p$)
  - "Saya akan mendaftar ke ITS kecuali saya tidak lulus SMA" ($q$ kecuali $\neg p$)
  - Dsb

- Tabel kebenaran dari implikasi :
  |$p$|$q$|$p \implies q$|
  |---|---|--------------|
  |T  |T  |T             |
  |T  |F  |F             |
  |F  |T  |T             |
  |F  |F  |T             |

  \*) Nilai kebenaran pada implikasi hanya akan salah ketika $p$ benar dan $q$ salah. Implikasi akan bernilai benar ketika $p$ salah tidak peduli nilai $q$ benar atau salah.

- Penggunaan implikasi dalam matematika sedikit berbeda dengan penggunaan dalam bahasa sehari-hari. Implikasi dalam matematika *tidak memedulikan hubungan sebab-akibat dari premis dan konklusinya.*

#### Converse, Contrapositive, and Inverse
> **Konvers** dari implikasi $p \implies q$ adalah **$q \implies p$**.
>
> **Kontraposisi** dari implikasi $p \implies q$ adalah **$\neg q \implies \neg p$**.
>
> **Invers** dari implikasi $p \implies q$ adalah **$\neg p \implies \neg q$**.

- Dua proposisi majemuk yang memiliki nilai kebenaran sama tidak peduli nilai kebenaran dari variabel proposisinya disebut **ekuivalen.**

- Kontraposisi dari implikasi ekuivalen dengan implikasi aslinya. Invers juga ekuivalen dengan konvers.
\*) *Invers dan konvers tidak ekuivalen dengan implikasi aslinya*

- Contoh :
  Misalkan $p$ = "saya pergi ke luar negeri", $q$ = "saya memiliki paspor". Maka :
  - **Implikasi aslinya ($p \implies q$)** = "jika saya pergi ke luar negeri, maka saya memiliki paspor".
  - **Konvers ($q \implies p$)** = "jika saya memiliki paspor, maka saya pergi ke luar negeri"
  - **Kontraposisi ($\neg q \implies \neg p$)** = "jika saya tidak memiliki paspor, maka saya tidak pergi ke luar negeri"
  - **Invers ($\neg p \implies \neg q$)** = "jika saya tidak pergi ke luar negeri, maka saya tidak memiliki paspor"

- Tabel kebenaran dari konvers dan implikasi aslinya :

  |$p$|$q$|$p \implies q$|$q \implies p$|
  |---|---|--------------|--------------|
  |T  |T  |T             |T             |
  |T  |F  |F             |T             |
  |F  |T  |T             |F             |
  |F  |F  |T             |T             |
  \*) *Bisa dilihat dari tabel di atas bahwa nilai kebenaran dari konvers dan implikasi aslinya berbeda berarti keduanya tidak ekuivalen*

- Tabel kebenaran dari kontraposisi dan implikasi aslinya :
  |$p$|$q$|$\neg p$|$\neg q$|$p \implies q$|$\neg q \implies \neg p$|
  |---|---|--------|--------|--------------|------------------------|
  |T  |T  |F       |F       |T             |T                       |
  |T  |F  |F       |T       |F             |F                       |
  |F  |T  |T       |F       |T             |T                       |
  |F  |F  |T       |T       |T             |T                       |
  \*) *Bisa dilihat dari tabel di atas bahwa nilai kebenaran dari kontraposisi dan implikasi aslinya selalu sama berarti keduanya ekuivalen*

- Tabel kebenaran dari invers dan implikasi aslinya :
  |$p$|$q$|$\neg p$|$\neg q$|$p \implies q$|$\neg p \implies \neg q$|
  |---|---|--------|--------|--------------|------------------------|
  |T  |T  |F       |F       |T             |T                       |
  |T  |F  |F       |T       |F             |T                       |
  |F  |T  |T       |F       |T             |F                       |
  |F  |F  |T       |T       |T             |T                       |
  \*) *Bisa dilihat dari tabel di atas bahwa nilai kebenaran dari invers dan implikasi aslinya berbeda berarti keduanya tidak ekuivalen*

#### Biconditionals
> Misalkan $p$ dan $q$ adalah sebuah proposisi maka **biimplikasi** dari $p$ dan $q$ (dinotasikan dengan **$p \leftrightarrow q$**) adalah sebuah proposisi yang berarti "$p$ jika dan hanya jika$q$".
>
> Bernilai benar jika $p$ dan $q$ memiliki kebenaran yang sama, dan salah jika $p$ dan $q$ memiliki nilai kebenaran yang berlawanan.

- Contoh :
  Misalkan $p$ = "saya lolos beasiswa ke luar negeri", $q$ = "saya berprestasi di sekolah".
  Maka $p \leftrightarrow q$ = "saya lolos beasiswa ke luar negeri jika dan hanya jika saya berprestasi di sekolah".

- Biimplikasi memiliki nilai kebenaran yang sama dengan $(p \implies q) \land (q \implies p)$

- Biimplikasi biasanya digunakan secara tersirat dalam bahasa sehari-hari.
Contohnya ketika seseorang berkata "jika kamu lolos dari SMA/SMK, maka kamu bisa mendaftar ke perguruan tinggi", yang dimaksud disini sama dengan "kamu bisa mendaftar perguruan tinggi jika dan hanya jika kamu lulus dari SMA/SMK" karena kita tidak dapat mendaftar perguruan tinggi jika tidak memiliki ijazah SMA/SMK/sederajat.

- Tabel kebenaran dari biimplikasi :
  |$p$|$q$|$p \leftrightarrow q$|
  |---|---|---------------------|
  |T  |T  |T                    |
  |T  |F  |F                    |
  |F  |T  |F                    |
  |F  |F  |T                    |

### 1.1.4 : Truth Tables of Compound Propositions

- Tabel kebenaran dari sebuah proposisi majemuk dapat dibentuk dengan tabel dengan masing-masing kolom mewakili nilai dari proposisi penyusunnya, kolom terakhir mewakili nilai dari proposisi majemuk yang dicari.

- Contoh :
  Tabel kebenaran dari proposisi $(p \oplus \neg q) \lor (p \leftrightarrow q)$

  |$p$|$q$|$\neg q$|$p \oplus \neg q$|$p \leftrightarrow q$|$(p \oplus \neg q) \lor (p \leftrightarrow q)$|
  |---|---|--------|-----------------|---------------------|----------------------------------------------|
  |T  |T  |F       |T                |T                    |T                                             |
  |T  |F  |T       |F                |F                    |F                                             |
  |F  |T  |F       |F                |F                    |F                                             |
  |F  |F  |T       |T                |T                    |T                                             |
  \*) *Bisa dilihat dari tabel diatas bahwa $p \oplus \neg q$, $p \leftrightarrow q$, dan $(p \oplus \neg q) \lor (p \leftrightarrow q)$ semuanya ekuivalen*

### 1.1.5 : Precedence of Logical Operators

- Sama seperti operasi aritmatika, operasi dalam logika juga memiliki prioritas operator.

- Operasi di dalam tanda kurung '(' dan ')' dikerjakan terlebih dahulu.

- Tabel prioritas operator logika :

|Urutan prioritas|Operasi          |
|----------------|-----------------|
|1               |$\neg$           |
|2               |$\land$          |
|3               |$\lor$           |
|4               |$\implies$       |
|5               |$\leftrightarrow$|

### 1.1.6 : Logic and Bit Operations

- Komputer merepresentasikan suatu informasi dengan serangkaian **binary digit (bit)**.

- Bit termasuk ke dalam **variabel boolean**, yaitu variabel yang nilainya antara benar dan salah. Satu bit terdiri dari satu angka (0 atau 1) dengan 0 merepresentasikan salah, dan 1 merepresentasikan benar.

- Operasi dalam bit juga sama dengan operasi dalam logika.

> **String** adalah serangkaian bit dengan panjang tertentu.

- Komputer memanipulasi informasi dalam string dengan menerapkan operasi **bitwise AND, bitwise OR, bitwise XOR** yang sama dengan operasi dalam logika.

- Contoh operasi bitwise :
  Misalkan string $s_1$ = 0001 1101 0100 1111, dan $s_2$ = 1101 1110 1001 0000
  - $s_1$ **bitwise AND** $s_2$ = 0001 1100 0000 0000
  - $s_1$ **bitwise OR** $s_2$ = 1101 1111 1101 1111
  - $s_1$ **bitwise XOR** $s_2$ = 1100 0011 1101 1111
  \*) *Bisa dilihat di sini bahwa operasi bitwise sama dengan menerapkan operasi logika pada setiap bit dalam string*
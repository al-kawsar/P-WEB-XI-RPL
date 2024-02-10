# Tag Dasar

## Heading

1. `<h1>`
   merupakan heading utama dan biasanya digunakan untuk judul paling penting atau utama pada sebuah halaman. Ini memberikan informasi inti tentang topik atau konten utama.
2. `<h2>`
   digunakan untuk judul tingkat kedua dan ditempatkan di bawah `<h1>`. Umumnya, `<h2>` menggambarkan subbagian atau topik yang terkait dengan judul utama, membantu dalam membagi konten menjadi bagian-bagian yang lebih terorganisir.
3. `<h3>`
   menunjukkan judul tingkat ketiga dan digunakan untuk subbagian dari bagian yang diberi judul oleh `<h2>`. Ini membantu dalam menyajikan informasi lebih rinci dan terorganisir.
4. `<h4>`
   terletak di tingkat hierarki yang lebih rendah dan digunakan untuk memperinci subbagian dari judul `<h3>`. Penggunaan yang tepat dari `<h4>` membantu dalam memberikan kerangka dan struktur lebih lanjut.
5. `<h5>`
   digunakan untuk judul tingkat kelima dan sering kali menyajikan informasi yang lebih spesifik atau terperinci dari bagian yang diberi judul oleh `<h4>`. Ini dapat membantu dalam menyusun dan mengorganisir konten dengan lebih detail.
6. `<h6>`
   Terakhir, adalah elemen heading dengan tingkat kepentingan paling rendah. Digunakan untuk judul tingkat keenam, seringkali menunjukkan sub-subbagian atau penjelasan tambahan yang sangat spesifik. Penggunaan `<h6>` memberikan detil dan konteks tambahan pada tingkat hierarki yang paling rendah.

**Kode Program** :

```html
<h1>Judul Utama Halaman</h1>
<h2>Sub-Judul Pertama</h2>
<h3>Sub-Judul Kedua</h3>
<h4>Sub-Judul Ketiga</h4>
<h5>Sub-Judul Keempat</h5>
<h6>Sub-Judul Kelima</h6>
```

**Hasil Output** :
![](assets/Web/Pertemuan%203/h1-h6.png)

## Paragraf

1. `<p>`
   Elemen `<p>` digunakan untuk menandai dan mengelompokkan teks sebagai satu paragraf. Ini membantu dalam memberikan struktur dan keterbacaan pada konten halaman web.
   contoh kode :

```html
<p>Ini adalah sebuah paragraf.</p>
```

     Hasil Output :

![350](p-tag.png) 2. `<b>`
Elemen `<b>` digunakan untuk memberikan efek tebal pada teks di dalamnya. Meskipun sering digunakan, sebaiknya pertimbangkan penggunaan yang lebih semantik seperti `<strong>` untuk menekankan makna yang lebih kuat.
contoh kode :

```html
<b>Teks ini tebal</b>
```

     Hasil Output :

![400](b-tag.png) 3. `<u>`
Elemen `<u>` memberikan efek garis bawah pada teks di dalamnya. Meskipun berfungsi untuk memberikan garis bawah, penggunaan yang lebih semantik bisa dipertimbangkan, terutama karena garis bawah sering diasosiasikan dengan link.
contoh kode :

```html
<u>Terdapat garis bawah</u>
```

     Hasil Output :

![400](u-tag.png) 4. `<i>`
Elemen `<i>` digunakan untuk memberikan efek miring pada teks di dalamnya. Seperti halnya `<b>`, pertimbangkan penggunaan yang lebih semantik seperti `<em>` untuk menekankan teks dengan makna yang lebih kuat.
contoh kode :

```html
<i>Teks ini miring</i>
```

     Hasil Output :

![400](i-tag.png) 5. `<br>`
Elemen `<br>` digunakan untuk menyisipkan pemisah baris atau line break. Ini memindahkan teks berikutnya ke baris baru.Tidak memiliki tag penutup karena merupakan elemen tanpa konten.
contoh kode :

```html
<h1>Ini RPl 1</h1>
<br /><br /><br /><br /><br /><br /><br /><br />
<h2>Hallo Rpl 1</h2>
```

     Hasil Output :

![400](br-tag.png)

### Atribut Align

```html
<h3>Belajar Menggunakan Elemen Tag HTML P</h3>

<p align="left">
  Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eligendi praesentium
  aut corrupti doloribus atque ducimus perferendis ut! Ipsa saepe accusamus
  itaque quaerat a sed molestiae, sunt veritatis dolore ad nesciunt asperiores
  debitis minima non! Rem in animi sint distinctio minus dolore odit aspernatur
  itaque eum magnam molestiae dolorem blanditiis, iure labore aliquam alias
  ipsam esse, ducimus debitis earum? Veritatis tempore consequatur enim illum
  excepturi vero tenetur provident id praesentium nulla aspernatur laboriosam,
  ratione ad est distinctio. Officia, optio veritatis quam inventore aperiam
  quibusdam velit, maiores culpa, nihil id voluptatem atque fugit qui hic
  consequatur assumenda doloribus reiciendis dolorum modi aspernatur.
</p>

<p align="right">
  Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eligendi praesentium
  aut corrupti doloribus atque ducimus perferendis ut! Ipsa saepe accusamus
  itaque quaerat a sed molestiae, sunt veritatis dolore ad nesciunt asperiores
  debitis minima non! Rem in animi sint distinctio minus dolore odit aspernatur
  itaque eum magnam molestiae dolorem blanditiis, iure labore aliquam alias
  ipsam esse, ducimus debitis earum? Veritatis tempore consequatur enim illum
  excepturi vero tenetur provident id praesentium nulla aspernatur laboriosam,
  ratione ad est distinctio. Officia, optio veritatis quam inventore aperiam
  quibusdam velit, maiores culpa, nihil id voluptatem atque fugit qui hic
  consequatur assumenda doloribus reiciendis dolorum modi aspernatur.
</p>
<p align="center">
  Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eligendi praesentium
  aut corrupti doloribus atque ducimus perferendis ut! Ipsa saepe accusamus
  itaque quaerat a sed molestiae, sunt veritatis dolore ad nesciunt asperiores
  debitis minima non! Rem in animi sint distinctio minus dolore odit aspernatur
  itaque eum magnam molestiae dolorem blanditiis, iure labore aliquam alias
  ipsam esse, ducimus debitis earum? Veritatis tempore consequatur enim illum
  excepturi vero tenetur provident id praesentium nulla aspernatur laboriosam,
  ratione ad est distinctio. Officia, optio veritatis quam inventore aperiam
  quibusdam velit, maiores culpa, nihil id voluptatem atque fugit qui hic
  consequatur assumenda doloribus reiciendis dolorum modi aspernatur.
</p>

<p align="justify">
  Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eligendi praesentium
  aut corrupti doloribus atque ducimus perferendis ut! Ipsa saepe accusamus
  itaque quaerat a sed molestiae, sunt veritatis dolore ad nesciunt asperiores
  debitis minima non! Rem in animi sint distinctio minus dolore odit aspernatur
  itaque eum magnam molestiae dolorem blanditiis, iure labore aliquam alias
  ipsam esse, ducimus debitis earum? Veritatis tempore consequatur enim illum
  excepturi vero tenetur provident id praesentium nulla aspernatur laboriosam,
  ratione ad est distinctio. Officia, optio veritatis quam inventore aperiam
  quibusdam velit, maiores culpa, nihil id voluptatem atque fugit qui hic
  consequatur assumenda doloribus reiciendis dolorum modi aspernatur.
</p>
```

Penjelasan Program:

```html
<h3>Belajar Menggunakan Elemen Tag HTML P</h3>
```

- **Tag (`<h3>`):** Ini adalah tag HTML yang digunakan untuk membuat heading level 3.

```html
<p align="left">Lorem ipsum dolor, sit amet consectetur adipisicing ...</p>
```

- `<p>` adalah elemen paragraf dengan teks isi yang panjang.
- Atribut `align="left"` digunakan untuk mengatur teks di dalam paragraf agar rata kiri.

```html
<p align="right">Lorem ipsum dolor, sit amet consectetur adipisicing. ...</p>
```

- Ini adalah elemen paragraf kedua dengan teks isi yang mirip.
- Atribut `align="right"` digunakan untuk mengatur teks di dalam paragraf agar rata kanan.

```html
<p align="center">Lorem ipsum dolor, sit amet consectetur adipisicing. ...</p>
```

- Ini adalah elemen paragraf ketiga dengan teks isi yang mirip.
- Atribut `align="center"` digunakan untuk mengatur teks di dalam paragraf agar rata tengah.

```html
<p align="justify">Lorem ipsum dolor, sit amet consectetur adipisicing ...</p>
```

- Ini adalah elemen paragraf keempat dengan teks isi yang mirip.
- Atribut `align="justify"` digunakan untuk mengatur teks di dalam paragraf agar rata kanan dan kiri (justify).

Hasil _Output_ :
![100%](p-align.png)

## Komentar

Dalam HTML, komentar dimulai dengan `<!--` dan diakhiri dengan `-->`. Isi dari komentar dapat berupa teks, instruksi, atau catatan apapun yang diinginkan.
Contoh Kode :

```html
   
<!-- Ini komentar, tidak akan tampil di browser -->
   
<p>Ini bukan komentar, dan akan tampil di browser</p>
```

Hasil _Output_ :
![[p-komentar.png]]

---
title: "Dokumentasi Format Hugo [Versi Lengkap]"
date: 2024-03-09T13:38:14+07:00
created_date: "09 Maret 2024"
updated_date: "09 Maret 2024"
has_updated: false

meta_robot_is_indexed: true
meta_published_time: "2024-03-09T13:38:14+07:00"
meta_modified_time: "2024-03-09T13:38:14+07:00"
meta_description: "ini adalah teknik pemformatan di Hugo"
meta_keywords: 
- Format Hugo
- Hugo SSG
- Format MD

ads_disclosure: false
ads_sidebar: false
ads_sidebar_name: "Grammarly"
ads_header: false
ads_header_name: "Grammarly"

featured_image: "/img/360x200.jpg"
alt_featured_image: "feature_image"

author: "Defitra"
read_time: "5 min read"
type: "post"

categories: 
- Dokumentasi
tags: 
- Dokumentasi
- Hugo
- Format MD

series:
- Dokumentasi

description: "Ini adalah teknik pemformatan di Hugo. Setiap apa yang kita tulis menggunakan teknik ini. Artikel ini dibuat dengan harapan dapat dilihat jika kita lupa dengan pemformatan yang berlaku di Hugo"

show_table_of_content: true
archive: false
draft: true
---

## Format Umum

**ini paragraf biasa**. Kita sudah tidak asing dengan AI atau _Artificial Intelligence_. Namun apakah kita pernah mendengar konsep "Apa itu Augmented Intelligence?". Augmented Intelligence adalah konsep dimana manusia dan AI bekerjasama untuk menghasilkan keputusan yang efektif. Mungkin kita sering bertanya-tanya "apakah AI akan menggantikan manusia?". Maka konsep Augmented AI ini lebih menekankan pada AI sebagai alat untuk membantuk manusia dibanding menggantikan manusia.

**Tambahkan 2 spasi untuk mulai menulis di baris baru**
Kita sudah tidak asing dengan AI atau _Artificial Intelligence_. Namun apakah kita pernah mendengar konsep "Apa itu Augmented Intelligence?".  
Augmented Intelligence adalah konsep dimana manusia dan AI bekerjasama untuk menghasilkan keputusan yang efektif. Mungkin kita sering bertanya-tanya "apakah AI akan menggantikan manusia?". Maka konsep Augmented AI ini lebih menekankan pada AI sebagai alat untuk membantuk manusia dibanding menggantikan manusia.

_ini huruf miring (italic)_

*ini juga miring (italic*

**ini bold**

## Ini Format Link

[ini adalah link](https://www.google.com)

Here's [a link to something else][another place].
Here's [yet another link][another-link].
And now back to [the first link][another place].

[another place]: www.github.com
[another-link]: www.google.com

## Teks Referensi

Ini adalah [teks tautan][1].

[1]: https://www.google.com


## Format Gambar

![Teks deskripsi gambar](/img/360x200.jpg)


## Format Gambar Dengan Teknik Referensi

![Thumbnails][Thumbnail]

[Thumbnail]:/img/360x200.jpg



## Ini adalah Tabel

| Nama | Usia |
|------|------|
| John | 30   |
| Jane | 25   |

## Daftar Berurutan Ordered List

1. Item pertama
2. Item kedua
   - Subitem A
   - Subitem B
3. Item ketiga


## Daftar Tak Berurutan (Unordered List)

- Buah apel
- Buah pisang
- Buah jeruk

## Daftar Tak Berurutan (Unordered List) dengan format *
* Milk
* Eggs
* Salmon
* Butter

## Daftar Dengan Penjelasan
1. Crack three eggs over a bowl.

   Now, you're going to want to crack the eggs in such a way that you don't make a mess.

   If you _do_ make a mess, use a towel to clean it up!

2. Pour a gallon of milk into the bowl.

   Basically, take the same guidance as above: don't be messy, but if you are, clean it up!

3. Rub the salmon vigorously with butter.

   By "vigorous," we mean a strictly vertical motion. Julia Child once quipped:
   > Up and down and all around, that's how butter on salmon goes.
4. Drop the salmon into the egg-milk bowl.

   Here are some techniques on salmon-dropping:

   * Make sure no trout or children are present
   * Use both hands
   * Always have a towel nearby in case of messes
  

## Teks sebagai kode
Ini adalah contoh kode: `print("Hello, world!")`

```
def is_prime(number):
  if number <= 1:
    return False
  for divisor in range(2, int(number\*\*0.5) + 1):
    if number % divisor == 0:
    return False
  return True

# Contoh penggunaan

user_input = int(input("Masukkan sebuah bilangan: "))
if is_prime(user_input):
  print(f"{user_input} adalah bilangan prima.")
else:
  print(f"{user_input} bukan bilangan prima.")
```

## Block Quote

> Ini adalah contoh blok kutipan.
> Lebih banyak teks di dalam blok kutipan.

## Multi paragraf Blockqupte

>Once upon a time and a very good time it was there was a moocow coming down along the road and this moocow that was coming down along the road met a nicens little boy named baby tuckoo...
>
>His father told him that story: his father looked at him through a glass: he had a hairy face.
>
>He was baby tuckoo. The moocow came down the road where Betty Byrne lived: she sold lemon platt.

## Garis Horizontal

---
 
## Ini Prompt Box
{{<prompt_box>}}
<p>
Kita sudah tidak asing dengan AI atau _Artificial Intelligence_. Namun apakah kita pernah mendengar konsep "Apa itu Augmented Intelligence?". Augmented Intelligence adalah konsep dimana manusia dan AI bekerjasama untuk menghasilkan keputusan yang efektif. 
</p>
<p>
Mungkin kita sering bertanya-tanya "apakah AI akan menggantikan manusia?". Maka konsep Augmented AI ini lebih menekankan pada AI sebagai alat untuk membantuk manusia dibanding menggantikan manusia.
</p>


{{</prompt_box>}}
 

## Ini Code Syntax 
{{<code_syntax python >}}

<pre data-enlighter-language="python"> 
def is_prime(number):
  if number <= 1:
    return False
  for divisor in range(2, int(number\*\*0.5) + 1):
    if number % divisor == 0:
    return False
  return True

# Contoh penggunaan

user_input = int(input("Masukkan sebuah bilangan: "))
if is_prime(user_input):
  print(f"{user_input} adalah bilangan prima.")
else:
  print(f"{user_input} bukan bilangan prima.")
</pre>

{{</code_syntax>}}


## Emoji

> :warning: **Warning:** Do not push the big red button.

> :memo: **Note:** Sunrises are beautiful.

> :bulb: **Tip:** Remember to appreciate the little things in life.

## Tag Article (Tag yang berdiri sendiri)
{{<tag_article>}}

<h2>Tautan Afiliasi</h2>

<p>Tingkatkan kemampuan grammar Bahasa Inggris kamu menggunakan aplikasi <a href="https://grammarly.com">Grammarly</a>.</p>

{{</tag_article>}}

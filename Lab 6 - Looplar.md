# Lab 6 — Loops

### Masala 1

###### Description

>Bitta butun son `N` ni o’qing. Shu son qoldiqsiz bo’linadigan barcha sonlarni orasida bo’sh katak bilan, bitta qatorda chop etilsin.

> ✅ `while loop` ishlatilsin!


###### Input

Butun son `N`.

###### Output

Kiritilgan sonning barcha bo’luvchilari. `N` ning o’zi ham kiradi.

###### Namuna 1
| Input | Output |
| - | - |
| `7` | `1 7`



###### Namuna 2
| Input | Output |
| - | - |
| `18` | `1 2 3 6 9 18`


###### Namuna 3
| Input | Output |
| - | - |
| `23` | `1 23`

---

### Masala 2


### Sonni top o’yini

###### Description

>Bitta butun son `N` ni o’qing. Bu to’g’ri javobni bildiradi. Faraz qiling, siz javobni bilmaysiz. Shundan so’ng, tahminlarni kiritishni boshlaysiz va ularni butun sonni anglatuvchi `K` o’zgaruvchisiga saqlaysiz.

>- Agar siz kiritgan son `N` dan katta bo’lsa `K>` deb chop etilsin.
>- Aksincha, kichik bo’lsa bo’lsa `K<` deb chop etilsin.
>- Yuqoridagi ikki amalni to’g’ri javob topilguncha takrorlansin.
>- Agar to’g’ri javob topilsa, javob topilguncha nechta tahmin kiritilganini chop etilsin va o’yin tugatilsin.

###### Input

- Birinchi qatorda bitta butun son `N` .
- Ikkinchi qatordan boshlab `N` ga teng bo’lgan son kiritlmaguncha son o’qiyveriladi.

###### Output

Barcha urinishlar va ularning yuqorida aytilgan natijalarning har biri bittadan alohida qatorlarda, umuman **space** ishlatilmasdan chop etilsin.

###### Namuna 1
| Input | Output |
| - | - |
| `5`<br>`10`<br>`3`<br>`7`<br>`4`<br>`5` | `10>`<br>`3<`<br>`7>`<br>`4<`<br>`5`|

---

### Masala 3

###### Description

>`0` kiritlmaguncha bir nechta butun sonlar o’qing. `0` kiritilgunga qadar o’qilgan barcha sonlar yig’indisini hisoblab, chop etilsin.

> ✅ `do while loop` ishlatilsin!


###### Input

- Bir nechta butun sonlar o’qilsin.
- `0` kiritilganda o’qish to’xtatilsin.

###### Output

`0` dan oldin kiritilgan barcha sonlar yigi’indisi.

###### Namuna 1
| Input | Output |
| - | - |
| ` 2 3 4 0` | `9` |


###### Namuna 2
| Input | Output |
| - | - |
| ` 3 2 1 0` | `6` |

---

### Masala 4

###### Description

>2 dan 10 gacha bo’lgan barcha sonlarning faktorialini quyidagi ko’rinishda chop etuvchi dastur tuzilsin.

> ✅ `for loop` ishlatilsin!
> 

###### Input

Input mavjud emas. Shunchaki namunadagiday chop eting.

###### Output

2 dan 10 gacha sonlarning har birining alohida qatorlarda, namunadagidek ko’rinishda chop etilgan faktoriallar jadvali.

###### Namuna Output

```sh
2!=1*2=2
3!=1*2*3=6
4!=1*2*3*4=24
5!=1*2*3*4*5=120
6!=1*2*3*4*5*6=720
7!=1*2*3*4*5*6*7=5040
8!=1*2*3*4*5*6*7*8=40320
9!=1*2*3*4*5*6*7*8*9=362880
10!=1*2*3*4*5*6*7*8*9*10=3628800
```

---

### Masala 5

###### Description

>Ikkita butun sonlar `N` va `M` larni o’qilsin. Ularning EKUBini, ya’ni, Eng Katta Umumiy Bo’luvchisini chop etilsin.

> ✅ `for` yoki `while loop` ishlatilsin!
 

> ⚠️`Time limit` hisobga olinsin.
 

###### Input

Ikkita butun sonlar `N` va `M` bitta qatorda o’qilsin.

###### Output

Bir vaqtning o’zida shu sonlarning har ikkisi ham qoldiqsiz bo’linadigan sonlarning eng kattasini chop etilsin.

###### Namuna 1
| Input | Output |
| - | - |
| ` 4 3` | `1` |


###### Namuna 2
| Input | Output |
| - | - |
| ` 16 24` | `8` |


###### Namuna 3
| Input | Output |
| - | - |
| ` 27 36` | `9` |

---

### Masala 6

###### Description

>Bitta butun musbat `N` sonini o’qing va balandigi `N`ga bog’liq bo’lgan piramidani yulduzchalar orqali chop eting.

> ✅ Nested for loop ishlatilsin!
> 

> ✅ spacelardan to’g’ri foydalanilsin.
> 

> ✅ Piramida markaziy qatorigacha bo’lgan balandligi Nga teng bo’lishi kerak.
> 

###### Input

Bitta musbat butun son `N`: $2 \leq N \leq 1000$

###### Output

Namunadagidek piramida chop etilsin.

###### Namuna 1
| Input |  |
|- | - |
| `5` | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; `*`<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`***`<br>&nbsp;&nbsp;&nbsp;&nbsp;`*****`<br>&nbsp;&nbsp;`*******`<br>`*********`<br>&nbsp;&nbsp;`*******`<br>&nbsp;&nbsp; &nbsp;`*****`<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`***`<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;`*` |

---


### Masala 7

###### Description

>Bitta `10x10` , 0 dan birgacha raqamlardan yasalgan, namunadagidek kvadrat yasab, chop etilsin.

>- 9 lardan boshqa har bir sonning o’ng tomoni va pastidagi son shu sonning o’zidan bittaga ortiq — pastga va o’ngga qarab o’sib boradi. 9 dan keyin esa 0 ga teng bo’lib qoladi va yana 0 dan boshlab o’sishni davom ettirad.
>- Diagonallardan biri hamisha bitta sondan iborat bo’ladi

> ✅ `for loop` va `while loop`lar birga ishlatilsin.
> 

###### Input

Input mavjud emas. Shunchaki namunadagiday chop eting.

###### Output

Namunadagidek, raqamlardan yasalgan kvadrat chop etilsin.

- Har bir son orasida 1 ta **space** bo’lsin.
- Har bir qator bitta yangi qatorda chop etilsin. Ortiqcha, bo’sh qator tashlanmasin.

###### Namuna Output

```
1 2 3 4 5 6 7 8 9 0
2 3 4 5 6 7 8 9 0 1
3 4 5 6 7 8 9 0 1 2
4 5 6 7 8 9 0 1 2 3
5 6 7 8 9 0 1 2 3 4
6 7 8 9 0 1 2 3 4 5
7 8 9 0 1 2 3 4 5 6
8 9 0 1 2 3 4 5 6 7
9 0 1 2 3 4 5 6 7 8
0 1 2 3 4 5 6 7 8 9
```

---

### Masala 8

###### Description

>Bitta `N` butun soni o’qilsin. Agar 1 dan boshlab shu songacha barcha sonlarni yozib chiqilsa, klaviaturada 3️⃣ soni necha marta bosilishini aniqlaydigan dastur tuzilsin.

> Masalan, 100 kiritildi. Shunda, aytaylik, 33 soniga kelganda sanoq ikkitaga oshadi. Chunki 33 sonini yozish uchun 2 marta 3️⃣ bosiladi.
> 

> ✅ `for loop` va `while loop`lar birga ishlatilsin.
> 

###### Input

Bitta musbat butun son `N`: $3 \leq N \leq 1000000000$

###### Output

1 dan boshlab shu songa yetib kelguncha yozilishi kerak bo'lgan 3️⃣ lar soni.

###### Namuna 1
| Input | Output |
|- | - |
| `10` | `1` |



###### Namuna 2
| Input | Output |
|- | - |
| `33` | `8` |


###### Namuna 3
| Input | Output |
|- | - |
| `333` | `102` |

---

### Masala 9

###### Description

>Bitta butun son `N` ni o’qing va balandligi shu songa teng bo’lgan uchburchak chop eting. Uchburchakni `0~9` oraliqdagi raqamlar ketma-ketligini qayta-qayta chop etishdan hosil qiling.

> Namunaga qarang.
 

###### Input

Bitta butun son `N`: $2 \leq N \leq 1000$

###### Output

Uchburchakni namunadagidek chop eting.

- Har bir raqam orasida bitta **space** bo’lishi kerak.

###### Namuna 1
| Input |  |
|- | - |
| `7` | &nbsp;&nbsp;&nbsp; &nbsp; &nbsp;&nbsp;&nbsp;`1`<br>&nbsp; &nbsp;&nbsp;&nbsp; &nbsp;`2 3`<br>&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;`4 5 6`<br>&nbsp;&nbsp;&nbsp;&nbsp;`7 8 9 0`<br>&nbsp;&nbsp; `1 2 3 4 5`<br>&nbsp;`6 7 8 9 0 1 `<br>`2 3 4 5 6 7 8` |



###### Namuna 2
| Input | Output |
|- | - |
| `3` | &nbsp; &nbsp;`1`<br> &nbsp;`2 3`<br>`4 5 6` |

---

### Masala 10

###### Description

>Sonning singularity(yakkalik) qiymati quyidagi qoida bo’yicha topiladi.

>- agar son bir xonadan katta bo’lsa, uning yangi qiymati eski qiymatining raqamlari yig’indisiga teng.
>- sonning qiymati bir xonali bo’lguncha tepadagi operatsiyani takrorlash

>`N`soni berilganda uning singularity qiymatini topadigan dastur tuzing.


###### Masalan
```mermaid
graph LR;
     A[6345] -..-> B[6 + 3 + 4 + 5] --> C[18] -..-> D[1 + 8] --> E[9]
```
> 

###### Input

`int` turidagi bitta butun musbat `N` soni.

###### Output

Sonning singularity qiymati.

###### Namuna 1
| Input | Output |
| - | - |
| `6345` | `9` |


###### Namuna 2
| Input | Output |
| - | - |
| `1234567890` | `9` |


###### Namuna 3
| Input | Output |
| - | - |
| `123` | `6` |

---

### Masala 11


### **Dice Game**

###### Description

>3 ta kichkina kub bor. Har bir kubning 6 ta tomoni bor. Kublarning har bir tomoni 1 dan 6 gacha raqamlangan. Kublar otilganda ularning tepa tomonidagi qiymat 10 ga teng bo’lishi mumkin bo’lgan barcha holatlarni aniqlab, chop etadigan dastur tuzilsin

> ✅ `Nested(cascade) loop`lar ishlatilsin.
 

###### Input

Input mavjud emas. Shunchaki namunadagiday chop eting.

###### Output

Otilganda tepa tomonidagi qiymatlar yig'indisi 10 ga teng bo’lishi mumkin bo'lgan barcha kombinatsiyalarni alohida qatorlarda, qiymatlar orasida bitta **space** bilan chop etilsin.

###### Namuna Output

```
1 3 6
1 4 5
1 5 4
1 6 3
2 2 6
2 3 5
2 4 4
2 5 3
2 6 2
3 1 6
3 2 5
3 3 4
3 4 3
3 5 2
3 6 1
4 1 5
4 2 4
4 3 3
4 4 2
4 5 1
5 1 4
5 2 3
5 3 2
5 4 1
6 1 3
6 2 2
6 3 1
```
---

### Masala 12

###### Description

>Bitta butun musbat son `N` ni o’qing. 1 dan boshlab shu songacha bo’lgan barcha sonlarning yig’indisini chop etadigan dastur tuzing.

> ✅ `Infinite for loop` ishlatilsin.
> 

> ✅ `break statement` ishlatilsin.
> 

###### Input

Bitta butun musbat son `N`

###### Output

Shu sondan kichik bo’lgan barcha musbat sonlar yig’indisi. Shu sonning o’zi ham yig’indiga kiradi.

###### Namuna 1
| Input | Output |
| - | - |
| `10` | `55` |



###### Namuna 2
| Input | Output |
| - | - |
| `33` | `561` |


###### Namuna 3
| Input | Output |
| - | - |
| `40` | `820` |


---

### Masala 13

###### Description

>0 yoki manfiy son kiritilmaguncha `N` butun sonlari o’qilsin. O’qilgan sonlarning yig’indisi, o’rtacha qiymati va sonini hisoblab, chop etadigan dastur tuzilsin.

> ✅ `Infinite while loop` ishlatilsin.
> 

> ✅ `break statement` ishlatilsin.
> 

###### Input

0 yoki manfiy qiymat kiritilmaguncha o’qilaveradigan butun son `N`: $0 \leq N \leq 100$

###### Output

- Yig’indi;
- Nuqtadan keyin 2 xonagacha aniqlikda chop etiladigan o’rtacha qiymat;
- Kiritilgan raqamlarning umumiy soni;

Yuqoridagi uchalasini bitta qatorda, orasida bitta **space** bilan chop etilsin.

###### Namuna 1
| Input | Output |
| - | - |
| `2 8 3 7 4 6 0` | `30 5.00 6` |


###### Namuna 2
| Input | Output |
| - | - |
| `1 2 3 4 5 6 7 8 9 -1` | `45 5.00 9` |


###### Namuna 3
| Input | Output |
| - | - |
| `10 20 30 40 50 60 70 -3` | `280 40.00 7` |

---

### Masala 14

###### Description

>`N` ta son o’qing va ularni kublari yig’indisini chop eting.

###### Input

- Birinchi qatorda `N` soni kiritiladi:  $2 \leq N \leq 10$
- Ikkinchi qatorda `N` ta butun `sonlar`: $-50 \leq sonlar \leq 50$

###### Output

Kiritilgan `N` ta sonlarning kublari yig’indisini chop eting.

###### Namuna 1
| Input | Output |
| - | - |
| `3` <br> `2 2 2` | `24` |


###### Namuna 2
| Input | Output |
| - | - |
| `4` <br> ` -5 -5 50 1` | `124751` |

---

### Masala 15

###### Description

>Berilgan son biror boshqa sonning faktoriali ekanligini yoki unday emasligini aniqlaydigan dastur tuzing.

###### Input

Bitta butun son `N`ni o'qing: $1 \leq N \leq 1000000000$

###### Output

Agar `N` biror boshqa sonning faktoriali bo’lsa `true` deb, aks holda `false` deb chop eting.

###### Namuna 1
| Input | Output |
| - | - |
| `479001600` | `true` |


###### Namuna 2
| Input | Output |
| - | - |
| `5` | `false` |


###### Namuna 3
| Input | Output |
| - | - |
| `120` | `true` |

---

### Masala 16

###### Description

>Berilgan sondan keyingi tub sonni topadigan dastur tuzing.

###### Input

Bitta butun musbat `N` soni: $1 \leq N \leq 10000000$

###### Output

- Agar `N` soni tub bo’lsa o’zini chop eting.
- Agar `N` tub bo’lmasa, undan keyingi tub sonni chop eting.

###### Namuna 1
| Input | Output |
| - | - |
| `4` | `5` |


###### Namuna 2
| Input | Output |
| - | - |
| `21017` | `21017` |


###### Namuna 3
| Input | Output |
| - | - |
| `1299680` | `1299689` |

---

### Masala 17

###### Description

>2D haritada harakatlanuvchi robotni harakatlarini kuzating va so’nggi manzili kordinatasini chop eting.

>- Robotni boshlanish pozitsiyasi(`0,0`) va u shimol(⬆️)ga yuzlanib turibdi.
>- Robot har gal turli qadamlar harakatlanadi.
>- Robot har bir harakatlanishdan keyin soat strelkasi bo’ylab 90° buriladi.

> shimol  ⬆️
> 

> janub   ⬇️
> 

> sharq   ➡️
> 

> g’arb    ⬅️
> 

###### Input

- Birinchi qatorda robotning harakatlanishlari soni bo’lgan `N`ni o’qing: $2 \leq N \leq 1000$
- Ikkinchi qatorda robot har harakatlanishda mos ravishda necha qadam yo’l bosishini anglatuvchi, qadamlar sonini ifodalovchi `N` ta `Q` sonlarni o’qing:  $−50 \leq Q \leq 50$

 Agar kiritilgan qadam manfiy bo’lsa, robot burilmasdan, orqamachasiga yurishini anglatadi.
 

 Har bir qadam koordinata o’qida bir birlikka tengdir
 

###### Output

Robotni yakuniy manzili kordinatasining `x` va `y` qiymatlarini orasida bo’sh katak bilan chop eting.

###### Namuna 1
| Input | Output |
| - | - | 
| `3` <br> `2 -3 5` | `-3 -3` |


###### Namuna 2
| Input | Output |
| - | - | 
| `3` <br> `1 -5 2` | `-5 -3` |

---

### Masala 18

###### Description

>**Collatz** ketma-ketligi butun son ustida quyidagi qoidalarni qayta-qayta bajarishdan hosil qilinadi.

>- Agar son juft bo’lsa, sonni 2 ga bo’linadi.
>- Agar son toq bo’lsa, sonni 3 ga ko’paytirib 1 ni qo’shiladi.

>**Collatz** algoritmida barcha butun musbat sonlar uchun son doimo 1ga yetib boradi.

>Ikkita butun sonlar kiritilganda, qaysi biri 1ga ertaroq yetib borishini aniqlovchi dastur tuzing.

###### Input

2 ta butun sonlar `N` va `M`: $1 \leq N, M \leq 1000000000$

###### Output

Ikkala sondan 1 ga tezroq yetib boradiganini va Collatz algoritmi necha marta qaytarilganidan keyin 1 ga yetib borganini ikkisining orasida bitta bo’sh katak bilan chop eting.

###### Namuna 1
| Input | Output |
| - | - | 
| `423620969 670051213` | `423620969 153` |

###### Namuna 2
| Input | Output |
| - | - | 
| `174000990 81824353` | `174000990 118` |

---

### Masala 19

###### Description

>`N`- [Fibonacci](https://uz.wikipedia.org/wiki/Fibonachchi_sonlari) sonini chop etadigan dastur tuzing.

>- Dastlabki 2 ta fibonacci sonlar `0` va `1` deb olinsin.

###### Input

Bitta musbat `N` soni (`1 ≤ N ≤ 50`).

###### Output

`N`- Fibonacci sonni chop eting.

###### Namuna 1
| Input | Output |
| - | - |
| `43` | `267914296` |


###### Namuna 2
| Input | Output |
| - | - |
| `12` | `89` |

---

### Masala 20

###### Description

>`0~99` oraliqdagi son berilgan bo’lsa, ular ustida quyidagi operatsiyani amalga oshirsa bo’ladi:

>- Agar son bir xonali bo’lsa, ikki xonali qilish uchun uning chap tarafiga `0` yoziladi.
>- Keyin, hosil qilingan 2 xonali sonning o’ng tarafidagi xonasi va berilgan son raqamlari yig’indisining o’ng tarafidagi xonasi ketma-ket yozilib, yangi son hosil qilinadi.

```mermaid
graph TD;
     A[26] --> B[2 + 6 = 8]
     subgraph 26ni oxirigi xonasi va 26ni raqamlar yig'indisini oxirgi xonasi
          B --> C[68]
     end
     subgraph 68ni oxirigi xonasi va 68ni raqamlar yig'indisini oxirigi xonasi
          C --> D[6 + 8 = 14]
          D --> E[84]
     end
     subgraph 84ni oxirigi xonasi va 84ni raqamlar yig'indisini oxirigi xonasi
          E --> F[8 + 4 = 12]
          F --> G[42]
     end
     subgraph 42ni oxirigi xonasi va 42ni raqamlar yig'indisini oxirigi xonasi
          G --> H[4 + 2 = 6]
          H --> I[26]
     end
```
 

> Endi ushbu operatsiya yangi yaratilgan son ustida amalga oshiriladi. Qayta-qayta shu operatsiya amalga oshirilsa, bir nechta qaytarishdan keyin, albatta, yangi hosil qilingan son dastlab kiritilgan songa teng bo’lib qoladi.

>`N` soni kiritilganda nechta operatsiyadan keyin dastlabki qiymatiga qaytib kelishini aniqlaydigan dastur tuzing.

###### Input

Bitta butun musbat son `N` (`0≤N≤99`).

###### Output

Qaytarilish sikli soni.

###### Namuna 1
| Input | Output |
| - | - |
| `26` | `4` |


###### Namuna 2
| Input | Output |
| - | - |
| `1` | `60` |

###### Namuna 3
| Input | Output |
| - | - |
| `5` | `3` |


###### Namuna 4
| Input | Output |
| - | - |
| `0` | `1` |

---

### Masala 21

###### Description

>Palindrom son deb teskarisiga o’qiganda ham qiymati o’zgarmaydigan songa aytiladi (1221).Palindrom son va uning raqamlarini teskari yozilishidan hosil bo’lgan sonni qo’shib yangi palindrom hosil qilish mumkin.Agar son Palindrom bo’lmasa, yangi palindrom hosil qilish uchun yuqoridagi amalni bir necha marta takrorlashga to’g’ri keladi.

> Masalan: 78 soni berilgan bo’lsa, to’rtta qadamda palindrom hosil qilsa bo’ladi: 78 + 87 = 165. 165 + 561 = 726. 726 + 627 = 1353. 1353 + 3531 = 4884.
> 

>`10~1000`oraliqda son berilganda, undan nechta qadamda palindrom hosil bo’lishini aniqlovchi dastur tuzing.

###### Input

Bitta butun musbat son `N`: $10 \leq N \leq 1000$

###### Output

Palindrom hosil qilish uchun ketadigan qadamlar soni va hosil qilingan palindromni orasida bo’sh katak bilan chop eting.

###### Namuna 1
| Input | Output |
| - | - |
| `240` | `1 282` |


###### Namuna 2
| Input | Output |
| - | - |
| `596` | `3 5335` |


---

### Masala 22

### Armstrong Sonlari

###### Description

Agar son `n` xonali bo’lsa va sonning har bir xonasidagi 1 xonali raqamning `n`-darajalari yig’indisi shu sonning o'ziga teng bo’lsa, bu sonlar `Armstrong sonlari` deyiladi.

`N` sonidan kichik barcha `Armstrong` sonlarni chop etadigan dastur tuzing.

###### Input

Bitta butun musbat son `N`: $1 \leq N \leq 100000$

###### Output

`N`gacha bo’lgan barcha `Armstrong` sonlar.

###### Namuna 1
| Input | Output |
| - | - |
| `1` | `0 1 2 3 4 5 6 7 8 9` |


###### Namuna 2
| Input | Output |
| - | - |
| `21955` | `0 1 2 3 4 5 6 7 8 9 153 370 371 407 1634 8208 9474` |

---

### Masala 23

###### Description

>Berilgan son necha xonali ekanini aniqlaydigan dastur tuzing.

###### Input

`int` turidagi bitta butun musbat son `N`.

###### Output

Berilgan son necha xonali ekanini chop eting.

###### Namuna 1
| Input | Output |
| - | - |
| `12345678` | `8` |

---

### Masala 24

###### Description

>Balandligi `N`ga teng bo’lgan uchburchakni yulduzchalar (`*`) orqali chop eting.

###### Input

Bitta butun musbat son `N`: $1 \leq N \leq 1000$

###### Output

Namunadagidek uchburchak chop eting.

###### Namuna 1
| Input | Output |
| - | - |
| `3` | `*`<br>`**`<br>`***` |


###### Namuna 2
| Input | Output |
| - | - |
| `1` | `*` |

---
## Lab 8 — Arrays

### Masala 1.

###### Description

> - 5 ta son o'qib, ularni  ***`array`*** ga saqlansin.
> - Ularning o'rtachasini hisoblab, shu o'rta arifmetik qiymatdan katta sonlarning o'zinigina chop etilsin.

 

###### Input

5 ta butun son.

###### Output

Kiritilgan sonlarning o'rtachadan kattalarini chop eting.

###### Namuna 1
| Input | Output |
| - | - |
| `1 1 1 10 10` | `10`<br> `10` |

---

### Masala 2.

###### Description

> - 5 ta son o'qib, ularni ***`array`*** ga saqlansin.
> - ***`Array`*** ning birinchi va ikkinchi elementlarini taqqoslansin.
> - Agar birinchi element ikkinchisidan katta bo'lsa, ularning qiymatlarini almashtirilsin(swap).
> - Yuqoridagi amalni ***`array`*** ning birinchi elementidan oxiridan bitta oldingi elementigacha takrorlansin.

###### Input

5 ta butun son.

###### Output

Hosil bo'lgan ***`array`*** ning har bir elementini alohida qatorlarda chop etilsin.

###### Namuna 1
| Input | Output |
| - | - |
| `5 4 3 2 1` | `4`<br> `3`<br> `2`<br> `1`<br> `5` |

---

### Masala 3.

###### Description

> - 10 ta butun `N` sonlarni o'qib, ularni ***`array`*** ga saqlansin (`1 ≤ N ≤ 3`).
> - Arrayda har bir sonning nechtadan mavjudligini aniqlansin.
> - Har bir sonni va shu sonning sanog'icha yulduzchalarni chop etadigan dastur tuzilsin.

###### Input

10 ta butun son `N` (`1 ≤ N ≤ 3`).

###### Output

Har bir sonni va shu sonning sanog'icha yulduzchalarni orasini `:` va ***`space`*** bilan ajratilgan holda chop etilsin.

###### Namuna 1
| Input | Output |
| - | - |
| `1 1 1 2 2 2 3 3 3 3` | `1: ***`<br>`2: ***`<br>`3: ****` |


---

### Masala 4.

###### Description

- 5 ta butun sonlarni o'qib, ularni ***`array`*** ga saqlansin.
- Kiritilgan elementlarning eng kattasini va ikkinchi eng kattasini chop etilsin.

###### Input

5 ta butun son.

###### Output

Arrayning eng katta qiymatga ega 2 ta elementlarini alohida qatorlarda chop etilsin.

###### Namuna 1
| Input | Output |
| - | - |
| `5 4 3 2 1` | `5`<br>`4` |



###### Namuna 2
| Input | Output |
| - | - |
| `5 5 3 2 1` | `5`<br>`5` |

---

### Masala 5.

###### Description

> - 7 ta **`char`** belgi o'qib, ularni ***`array`*** ga saqlansin.
> - Hosil bo'lgan ***`array`*** da `cat` **`char`** lar ketma-ketligi necha marta uchrashini aniqlab chop etilsin

###### Input

7 ta **`char`** belgi.

###### Output

***`Array`*** da **`cat`** so'zining takrorlanish soni.

###### Namuna 1
| Input | Output |
| - | - |
| `catbcat` | `2` |

---

### Masala 6.

###### Description

> - 5 ta **`char`** belgi o'qib, ularni ***`array`*** ga saqlansin.
> - 5 ta qatorda ***`array`*** ni namunadagidek aylantirib, chop eting:
    - 1 - qatorda kiritilgan ***`array`*** ning o'zi chop etiladi.
    - 2 - qatordan boshlab har safar bitta oldingi qatordagi chop etilgan yozuvning oxirgi elementi eng birinchi chop etiladi, qolgan elementlarni oldingi qatordagi bilan bir xil chop etiladi.

###### Input

5 ta **`char`** belgi.

###### Output

  ***`Array`*** ni 5 ta qatorda, namunadagidek aylantirib chop eting.
  ***`Array`*** elementlarining joyi o'zgarmasligi, faqat chop etish jarayonida to'g'ri chaqirib olinishi kerak.

###### Namuna 1
| Input | Output |
| - | - |
| `*abcd` | `*abcd`<br>`d*abc`<br>`cd*ab`<br>`bcd*a`<br>`abcd*` |

---

### Masala 7.

###### Description

> - 9 ta butun son o'qib, ularni 3x3 `array`ga saqlansin.
> - Asosiy diagonaldagi (`\`) elementlarning yig'indisini hisoblab, chop etilsin.

###### Input

9 ta butun son.

###### Output

  Asosiy diagonaldagi sonlar yi'g'indisi.

###### Namuna 1
| Input | Output |
| - | - |
|`1 2 3`<br>`4 5 6`<br>`7 8 9` | `15` |

---

### Masala 8.

###### Description

 3 ta butun `sonlar` o'qilsin (`0 ≤ sonlar ≤ 5`).
 Shu sonlarni ifodalovchi ingliz tilidagi so'zlar 3 ta alohida qatorlarda, namunadagidek chop etilsin.

> HINT: 2 o'lchamli `array`dan foydalanilsin.

[image](Lab%208%20%E2%80%94%20Arrays%208ce752ab651248cdb4f04b8f7fc97ff6/Untitled.png)

###### Input

3 ta butun `sonlar` (`0 ≤ sonlar ≤ 5`).

###### Output

Shu sonlarning ingliz tilidagi nomini alohida qatorlarda chop etilsin.

###### Namuna 1
| Input | Output |
| - | - |
| `1 3 5` | `ONE--`<br>`THREE`<br>`FIVE-` |

---

### Masala 9.

###### Description

> - 2 o'lchamli ***`array`*** e'lon qilinsin.
> - 3 ta talabaning *`Fizika`* va *`C dasturlash`* fanlaridan olgan ballarini o'qib, e'lon qilingan ***`array`*** ga joylansin.
> - Har bir talabaning 2 ta fandan olgan umumiy ballini hisoblaydigan dastur tuzilsin.

###### Input

Uchala talabaning 2 ta fandan olgan ballarini bitta qatorda o'qing. Oldin bir talabaning 2 ta fan bo'yicha ballini, keyin boshqasinikini o'qilsin.

###### Output

Har bir talabaning umumiy balli alohida qatorlarda chop etilsin.

###### Namuna 1
| Input | Output |
| - | - |
| `10 20 30 40 50 60` | `30`<br>`70`<br>`110` |

---

### Masala 10.

###### Description

### Achchiq Haqiqat

90% birinchi kurs talabalari o'zlarini o'rtachadan yuqori baho oladi deb hisoblashadi. Achchiq haqiqatni aytish vaqti keldi

###### Input

 - Birinchi qatorda `testcase`lar soni `C` (1 ≤ C ≤ 1000).
 - Keyingi `C` ta qatorlarda studentlar soni `N` va ularning `N` ta baholari bitta qatorda ketma-ket kiritiladi. (1 ≤ N ≤ 1000).
 - Baholar 1 dan 100 gacha bo'lgan butun sonlar (1 ≤ baholar ≤100).

###### Output

Har bir `testcase` uchun o'rtachadan yuqori natija ko'rsatgan o'quvchilar foizini nuqtadan keyin 3 ta raqam aniqlikda chop etilsin.

###### Namuna 1
| Input | Output |
| - | - |
| `5`<br>`5 50 50 70 80 100`<br>`7 100 95 90 80 70 60 50`<br>`3 70 90 80`<br>`3 70 90 81`<br>`9 100 99 98 97 96 95 94 93 91` | `40.000%`<br>`57.143%`<br>`33.333%`<br>`66.667%`<br>`55.556%` |

---

### Masala 11.

### Soyabon

###### Description

>   Wahid amaki *Gluwa* kompaniyasida ishlaydi. U har kuni biznes uchrashuvlarga qatnashish uchun *Gluwa*ning **`N`** ta ko'p qavatli binolari o'rtasida u binodan bu binoga borib keladi. Avval u $B_0$ binoga boradi va **`M`** marta binodan binoga sayohat qiladi. $B_1$, $B_2$, $B_3$... BM - bu binolar orasidagi sayohatlar ketma-ketligini anglatadi.

> Ba'zi vaqtlar yog'ingarchilik bo'lgani sabab binodan binoga borayotganda soyabon kerak bo'ladi. $B_{i−1}$ binodan $B_i$ binoga borishda soyabon ehtiyojini $R_i$ deb olaylik. Shunda, $R_i=1$ soyabon kerakligini va $R_i=0$ soyabon kerak emasligini anglatadi.‌

>Keyingi binoga borishda soyabon shart bo'lmasa, shunchaki soyabonsiz harakatlanadi. Agar soyabon kerak bo'lsa va hozirgi bino javonida soyabonlar bo'lsa, shu soyabonlardan birini olib yo'lga chiqadi. Agar unga narigi binoga borishga soyabon kerak bo'lsayu, u turgan binoda soyabon yo'q bo'lsa, bino magazinidan soyabon sotib oladi. Soyabon bilan binoga kelsa va keyingi binoga borishda soyabon kerak bo'lmasa, qo'lidagi soyabonni shu bino javonida qoldiradi. Sizga binolar o'rtasidagi harakatlanish va soyabon zarurati haqida ma'lumot berilgan bo'lsa, binolarda birorta ham soyabon yo'q deb hisoblagan holda Wahid bugun nechta soyabon sotib olishini aniqlaydigan dastur yarating.

###### Input

Birinchi qatorda **`3`** ta butun sonlar ($N, M$, $B_0$) berilgan.

> - $N$ — binolar soni (2 ≤ $N$ ≤ 10).
> - $M$ — harakatlanishlar soni (1 ≤ $M$ ≤ 200).
> - $B_0$ — harakatlanish boshlanadigan bino (1 ≤ $B_0$ ≤ $N$).
    
>  Keyingi $M$ qatorning har bir i - qatorida Wahid ketayotgan $B_i$ bino va soyabon ehtiyojini anglatuvchi $R_i$ kiritiladi. (1 ≤ $B_i$ ≤ $N$; 0 ≤ $R_i$ ≤ 1; $B_{i − 1}$ $!= B_i$)
    

###### Output

Sotib olingan soyabonlar sonini chop eting.

###### Namuna 1
| Input | Output |
| - | - |
| `2 5 1`<br>`2 0`<br>`1 1`<br>`2 0`<br>`1 1`<br>`2 1` | `2` |

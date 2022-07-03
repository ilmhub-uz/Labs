## Lab 9 — Pointers

### Masala 1.

###### Description

> - `int` turidagi bitta butun son `x` va `int` turidagi bitta `px` ***`pointer`*** e'lon qilinsin. `px` ga `x`ning adresi o'zlashtirilsin.

> - `scanf()` yordamida `x`ga qiymat o'qilsin.
> - `scanf()` va `px` ***`pointer`*** yordamida `x` ning qiymatini yangilansin.
> - `x`ning o'zgartirilgan qiymatini `px` ***`pointer`*** dan foydalanib chop etilsin.

###### Input

2 ta butun son (`x`ga avval bitta butun son o'qib, keyin uning qiymatini `px` pointer yordamida yangilansin).

###### Output

`x`ning yangilangan qiymatini `px` ***`pointer`*** yordamida chop etilsin.

#### Namuna 1
| Input | Output |
| - | - |
| `5` <br> `10` | `10` |

---

### Masala 2.

###### Description

> - Ikkita butun `N` va `M` butun musbat sonlar o'qilsin. `N`dan `M`gacha bo'lgan sonlar yig'indisini hisoblab, chop etadigan dastur tuzilsin.

> - `N` ham, `M` ham yig'indiga qo'shilishi kerak.
> - Hamisha `N < M` tengsizlikni qanoatlantiradigan sonlar kiritilsin.
> - E'lon qilingan har bir o'zgaruvchi uchun ***`pointer`*** o'zgaruvchilar e'lon qilinsin va mos ravishda ularning manzili ushbu ***`pointer`*** larga saqlansin.
> - Yig'indini hisoblash uchun ***`pointer`*** o'zgaruvchilardan foydalanilsin.
    >- Hisoblashda ***`array`*** dan boshqa barcha elementlar ***`pointer`*** bo'lishi kerak.
    >- Oddiy o'zgaruvchi va ***`pointer`*** o'zgaruvchi e'lon qilinsin.
    >- Oddiy o'zgaruvchining manzilini ***`pointer`*** o'zgaruvchiga saqlansin.
    >- Oddiy o'zgaruvchiga murojaat qilish uchun ***`pointer`*** o'zgaruvchidan foydalanilsin.

###### Input

2 ta butun son `N` va `M`.

###### Output

`N` dan `M`gacha yig'indini chop etilsin. `N` ham, `M` ham yig'indiga qo'shilsin.

#### Namuna 1
| Input | Output |
| - | - | 
| `1` `100` | `5050` |


#### Namuna 2
| Input | Output |
| - | - | 
| `3` `7` | `25` |

---

### Masala 3.

###### Description

> - Hajmi 100 ga teng bo'lgan ***`array`***  e'lon qilinsin. So'ngra ***`array`*** ga `N` ta butun son o'qilsin. Keyin, foydalanuvchidan bitta indeks o'qilsin. 

> - ***`Array`*** ning kiritilgan indeksdagi elementini chop etadigan dastur tuzilsin.

> - ***`Array`*** dan boshqa barcha o'zgaruvchilarga faqatgina ***`pointer`*** o'zgaruvchilar orqali murojaat qilinsin.
> - To'rtburchak qavslardan foydalanish mumkin emas (`arr[1]`  ⇒  ❌).

###### Input

- Birinchi qatorda musbat `N` butun soni (1 ≤ N ≤ 100);
- Ikkinchi qatorda ***`array`*** ga N ta qiymat o'qilsin.
- Uchunchi qatorda `a` index o'qilsin. (0 ≤ a ≤ N).

###### Output

Arrayning `a` indeksdagi elementini chop etilsin.

#### Namuna Input 1
| Input | Output |
| - | - |   
| `5` <br> `2 4 7 9 3` <br>`3` | `9` |

---

### Masala 4.

###### Description

> - Hajmi 100 ga teng bo'lgan ***`array`***  e'lon qilinsin. So'ngra ***`array`*** ga `N` ta butun son o'qilsin.

> - ***`Pointer`*** lar orqali ***`array`*** ning eng katta va eng kichik qiymatini chop etadigan dastur tuzilsin.

> - ***`Array`*** dan boshqa barcha o'zgaruvchilarga ***`pointer`*** o'zgaruvchilar orqali murojaat qilinsin.
> - To'rtburchak qavslardan foydalanish mumkin emas (`arr[1]`  ⇒  ❌).

###### Input

- Birinchi qatorda musbat `N` butun soni (`1 ≤ N ≤ 100`);
- Ikkinchi qatorda ***`array`*** ga N ta qiymat o'qilsin.

###### Output

***`Array`*** ning eng katta va eng kichik elementlarini chop etilsin.

#### Namuna 1
| Input | Output |
| - | - | 
| `5` <br> `10 4 7 27 1` | `1` <br> `27` |


---


### Masala 5.

###### Description

> - `#` kiritilmaguncha maksimum 20 ta belgi o'qilsin. `#` dan oldin kiritilgan elementlarni ***`pointer`*** lar orqali teskari tartibda chop etilsin.

> - ***`Array`*** dan boshqa barcha o'zgaruvchilarga ***`pointer`*** o'zgaruvchilar orqali murojaat qilinsin.
> - To'rtburchak qavslardan foydalanish mumkin emas (`arr[1]`  ⇒  ❌).

###### Input

Maksimum 20 ta ***`space`*** larsiz bir qator belgilar.

###### Output

`#` kiritilgunga qadar o'qilgan belgilarni teskari tartibda chop etilsin.

#### Namuna 1
| Input | Output |
| - | - | 
| `duck#` | `kcud` |


#### Namuna 2
| Input | Output |
| - | - | 
| `duck#pond` | `kcud` |

---

### Masala 6.

###### Description

> - 10 ta alifbo harflarini o'qilsin. ***`Pointer`*** yordamida eng ko'p uchragan harfni va uning necha marta uchraganini chop etilsin. Agar eng ko'p uchragan 2 yoki undan ko'proq harflar mavjud bo'lsa, eng birinchi qaysi biri maksimumga erishgan bo'lsa, o'shani chop eting.

> - ***`Array`*** dan boshqa barcha o'zgaruvchilarga ***`pointer`*** o'zgaruvchilar orqali murojaat qilinsin.
> - To'rtburchak qavslardan foydalanish mumkin emas (`arr[1]`  ⇒  ❌).
> - **`Loop`** ichida o'zgaruvchilarning faqatgina manzilidan foydalanib ishlansin.

###### Input

10 ta ***`space`*** larsiz bir qator belgilar.

###### Output

Eng ko'p uchragan harfni va necha marta takrorlanganligini orasida ***`space`***  bilan chop etilsin.

#### Namuna 1
| Input | Output |
| - | - |
| `domination` | `i 2` |

---

### Masala 7.

###### Description

> - Hajmi 3 ga teng bo'lgan ***`array`***  e'lon qilinsin. Foydalanuvchidan 3 ta butun son o'qib, kiritilgan qiymatlar bilan arrayni to'ldirilsin.  ***`Array`*** ning o'rtancha qiymatga ega bo'lgan elementini chop etilsin.

> - `int x[3]` ***`array`*** dan foydalanilsin.
> - `x[0], x[1], x[2]` deb ishlatilmasin. `p` pointer o'zgaruvchisini ishlatilsin.
> - ❌ Qo'shimcha o'zgaruvchilardan foydalanilmasin.
    >- ***`Array`*** dan boshqa barcha o'zgaruvchilarga ***`pointer`*** o'zgaruvchilar orqali murojaat qilinsin.
    >- To'rtburchak qavslardan foydalanish mumkin emas (`arr[1]`  ⇒  ❌).
    >- **`Loop`** ichida o'zgaruvchilarning faqatgina manzilidan foydalanib ishlansin.

###### Input

3 ta butun son.

###### Output

Kiritilgan sonlarning o'rtanchasini chop etilsin.

#### Namuna 1
| Input | Output |
| - | - |
| `1 9 7` | `7` |


#### Namuna 2
| Input | Output |
| - | - |
| `-7 0 10` | `0` |

---

### Masala 8.

###### Description

> Foydalanuvchidan 5 ta butun son o'qilsin va hajmi 5 ga teng bo'lgan `arr[]` ***`array`*** ga saqlansin.  Bu 5 ta o'quvchining imtihon natijalarini anglatadi. Eng katta ball olgan o'quvchi birinchi o'rin, eng kam ball olgan o'quvchi oxirgi o'rin deb topiladi. Agar 2 talaba bir xil ball olgan bo'lsa ularning o'rni ham bir xil bo'ladi.

> Har bir talabaning ballini va uning o'rnini yonma-yon chop etadigan dastur tuzilsin. 

> Masalan, 1, 6, 4, 9, 1 sonlari kiritilsa, o'quvchilarning o'rni mos ravishda 9, 6, 4, 1, 1 bo'ladi va 1 balldan olgan ikki o'quvchilarning ikkalasi ham  4-o'rin bo'ladi.
> 
> - `arr[i]` yoki `rank[i]` kabi ifodalardan foydalanilmasin. Uning o'rniga, ***`array`*** larga murojaat qilish uchun 2 ta ***`pointer`*** > — `p` va `q` lardan foydalanilsin.
> - ***`Array`*** dan boshqa barcha o'zgaruvchilarga ***`pointer`*** o'zgaruvchilar orqali murojaat qilinsin.
> - To'rtburchak qavslardan foydalanish mumkin emas (`arr[1]`  ⇒  ❌).
> - **`Loop`** ichida o'zgaruvchilarning faqatgina manzilidan foydalanib ishlansin.

###### Input

5 ta butun son.

###### Output

Kiritilgan sonlarning o'rni. Ikki bir xil son kiritilgan taqdirda ikkisi ham bitta o'rinda turishi kerak.

#### Namuna 1
| Input | Output |
| - | - |
| `1 2 3 4 5` | `1=r5 2=r4 3=r3 4=r2 5=r1` |


#### Namuna 2
| Input | Output |
| - | - |
| `1 6 4 9 1` | `1=r4 6=r2 4=r3 9=r1 1=r4` |

---

### Masala 9.

###### Description

> - Hajmi 50 bo'lgan bitta `int` ***`array`***  e'lon qilinsin. Unga `N` ta son o'qib, ularni ***`array`*** ga joylansin. 0 dan avval kiritilgan barcha raqamlar nechta ekanini chop etilsin.

> - `N ≤ 50`;
> - `0` soni faqat bir marta kiritilishi mumkin.
> - `0` dan oldin kiritilgan barcha sonlar bir necha marta, takroriy kiritilishi mumkin.
> - E'lon qilingan barcha o'zgaruvchilar uchun pointer o'zgaruvchilar e'lon qilinsin va ularga murojaat qilishda faqat mana shu ***`pointer`*** o'zgaruvchilardan foydalanilsin.
> - Kiritilgan raqamlar sonini sanash uchun ***`pointer`*** ishlatilsin.
    >- ***`Array`*** dan boshqa barcha o'zgaruvchilarga ***`pointer`*** o'zgaruvchilar orqali murojaat qilinsin.
    >- To'rtburchak qavslardan foydalanish mumkin emas (`arr[1]`  ⇒  ❌).
    >- **`Loop`** ichida o'zgaruvchilarning faqatgina manzilidan foydalanib ishlansin.

###### Input

1. Birinchi qatorda `N` butun soni (1 ≤ N ≤ 50).
2. Ikkinchi qatorda `N` ta butun sonlar. 

###### Output

`0` dan avval kiritilgan raqamlarning sonini chop etilsin.

#### Namuna 1
| Input | Output |
| - | - |
| `10` <br>`4 5 8 9 8 1 0 1 0 1 9 3` | `6` |


#### Namuna 2
| Input | Output |
| - | - |
| `5` <br>`0 1 3 -2 -4` | `0` |

---

### Masala 10.

###### Description

> - Hajmi 50 bo'lgan bitta `int` ***`array`***  e'lon qilinsin. Unga `N` ta son o'qib, ularni ***`array`*** ga joylansin. So'ngra, ***`array`*** ning indeksini anglatuvchi 2 ta butun son ***`a`*** va ***`b`*** larni o'qilsin. Arrayning ikkala indeksidagi sonlarni bir-biri bilan almashtirilsin. Yangilangan arrayni chop etilsin.

> - $a < b$ yoki  $b < a$;
> - `swap()` funksiyasi:
    >- Argumentlari: ikkita `int` ***`pointer`*** o'zgaruvchilar.
    >- Return type: `void`.
    >- Ikkala ***`pointer`***lar qarab turgan manzillardagi qiymatlarni almashtiradi.
>- `main()` funksiyasi:
    - Sonlarni o'qiydi va natijani chop etadi.

###### Input

1. Birinchi qatorda `N` butun soni (1 ≤ N ≤ 50).
2. Ikkinchi qatorda `N` ta butun sonlar. 
3. Uchinchi qatorda `a` va `b` butun sonlar.

###### Output

`a` va `b` indeksdagi qiymatlari almashtirilgan yangilangan ***`array`*** ni chop etilsin.

#### Namuna 1
| Input | Output |
| - | - |
| `6` <br>`3 2 0 1 4 6` <br>`2 4` | `3 2 4 1 0 6` |

---

### Masala 11.

###### Description

 - Ikkita butun sonlar o'qib ularning yig'indisini chop etadigan dastur tuzilsin.

- `sum()` funksiyasi:
    - Argumentlari: bitta `int` ***`pointer`*** va ikkita butun son.
    - Return type: `void`.
    - ***`Pointer`*** qarab turgan ozgaruvchiga ikkala butun sonning yig'indisini joylaydi.
- `main()` funksiyasi:
    - Ikkita son o'qiydi va ularning yig'indisini chop etadi.

###### Input

Ikkita butun son `a` va `b`.

###### Output

`a` va `b`larning yig'indisi.

#### Namuna 1
| Input | Output |
| - | - |
| `20 30` | `50` |


#### Namuna 2
| Input | Output |
| - | - |
| `17 7` | `24` |

---

### Masala 12.

###### Description

`N` ta butun son o'qilsin va kiritilgan sonlardagi **juft raqam**larning sonini chop etilsin.

- `findeven()` funksiyasi:
    - Argumentlari: bitta `int` ***`array`***  va uning hajmi `int size`.
    - Return type: `int`.
    - ***`Array`*** dagi juft raqamlar sonini qaytaradi.
- `main()` funksiyasi:
    - `N` ta son o'qiydi va natijani chop etadi.

###### Input

1. Birinchi qatorda bitta butun son $`N`$ (1 ≤ N ≤ 100).
2. Ikkinchi qatorda $`N`$ ta butun sonlar.

###### Output

Nechta juft son kiritilganini chop etilsin.

#### Namuna 1
| Input | Output |
| - | - |
| `5` <br>`10 3 8 13 20` | `3` |

---

### Masala 13.

###### Description

6 ta belgi o'qilsin va uni ***`array`*** ga joylansin. Ushbu ***`array`***  elementlarini boshqa arrayga ko'chiring. Ikkala arrayda ham belgilar saqlanib qolish kerak,

- `strcopy()` funksiyasi:
    - Argumentlari: Ikkita `int` ***`array`*** lar `a[]` va `b[]`.
    - Return type: `void`.
    - `b[]` ***`array`*** dagi elemntlarni `a[]` ***`array`*** ga ko'chiradi.
- `main()` funksiyasi:
    - `N` ta son o'qiydi va natijani chop etadi.

###### Input

6 ta belgi.

###### Output

Shu oltita belgini ikkichi ***`array`***  orqali chop etilsin.

#### Namuna 1
| Input | Output |
| - | - |
| `beyond` | `beyond` |

---

### Masala 14.

###### Description

N ta butun son o'qilsin. Kiritilgan sonlarning yig'indisini chop etadigan dastur tuzilsin.

- `arrsum()` funksiyasi:
    - Argumentlari: Bitta `int` ***`array`***  `a[]` va uning hajmi.
    - Return type: `int`.
    - `Array` elementlarining yig'indisini qaytaradi.
- `main()` funksiyasi:
    - `N` ta son o'qiydi va natijani chop etadi.

###### Input

Birinchi qatorda butun son `N` (1 ≤ N ≤ 100).

Ikkinchi qatorda `N` ta butun sonlar.

###### Output

Kiritilgan sonlarning yig'indisini chop etilsin.

#### Namuna 1
| Input | Output |
| - | - |
| `5` <br>`3 10 15 20 27` | `75` |

---

### Masala 15.

###### Description

10 ta butun son o'qilsin va kiritilgan sonlarni kamayib borish tartibida saqlab, chop etilsin.

- `ABC()` funksiyasi:
    - Argumentlari: Bitta `int` ***`array`***  `a[]` va bitta butun son `int k`.
    - Return type: `void`.
    - ***`Array`*** ning`k` indeksdagi elementidan boshlab ***`array`*** ning oxirgi elementigacha bo'lgan elementlarni solishtirib shu oraliqdagi eng katta sonni aniqlaydi va `k` indeksga joylaydi.
- `main()` funksiyasi:
    - Array elementlarini o'qiydi.
    - `ABC()` funksiyasini 9 marta chaqiradi.
    - Tartiblangan arrayni chop etadi.

###### Input

10 ta butun son `N`.

###### Output

Kiritilgan sonlarni kattasidan  kichigiga qarab array orqali chop etilsin.

#### Namuna 1
| Input | Output |
| - | - |
| `1 3 5 7 9 2 4 6 8 10` | `10 9 8 7 6 5 4 3 2 1` |


#### Namuna 2
| Input | Output |
| - | - |
| `13 56 27 89 43 76 32 68 91 8` | `91 89 76 68 56 43 32 27 13 8` |

---

### Masala 16.

###### Description

`N` ta butun son o'qilsin. Kiritilgan sonlarni yoki o'sib borish, yoki kamayib borish tartibida chop etilsin. 

- `userAlign()` funksiyasi:
    - Argumentlari: ***`Array`*** ga qarab turgan bitta `int` ***`pointer`,***  ***`array`*** ning hajmi, tartiblash qaysi tartibda (o'sib borish yoki kamayib borish) bo'lishi kerakligini anglatuvchi bitta butun son (0: o'sib borish, 1: kamayib borish).
    - Return type: `void`.
    - Butun sonlarni o'sib borish yoki kamayib borish tartibida joylashtiradi.
- `main()` funksiyasi:
    - Sonlarni o'qiydi va natijani chop etadi.
    - Sonlarni takroran kiritish mumkin emas.

###### Input

1. Birinchi qatorda butun son `N` va yana bitta butun son `a`. Agar a = 1 bo'lsa kamayib borish tartibida, a = 0 bo'lsa o'sib borish tartibida joylashtiriladi.
2. Ikkinchi qatorda `N` ta butun sonlar o'qiladi.

###### Output

`a` ning qiymatiga qarab, sonlarni o'sib borish yoki kamayib borish tartibida joylashtirilsin.

#### Namuna 1
| Input | Output |
| - | - | 
| `5 0` <br>`5 7 9 4 3` | `3 4 5 7 9` |


#### Namuna 2
| Input | Output |
| - | - | 
| `3 1` <br>`3 8 9` | `9 8 3` |

---

### Masala 17.

###### Description

2 marta `N` ta butun son o'qilsin va 2 ta `arr1[]` va `arr2[]` ***`array`*** larga saqlansin. Ikkinchi arrayni birinchi arrayga teskari tartibda qo'shib, chop etadigan dastur tuzilsin. Uchinchi array ham e'lon qilinsin.  

- `addArray()` funksiyasi:
    - Argumentlari: 3 ta ***`array`***  uchun 3 ta ***`pointer`,*** 3 ta arrayning hajmi uchun bitta butun son `int size`.
    - Return type: `void`.
    - 1-***`array`*** ning 1-elementini 2-***`array`*** ning oxirgi elementiga, 1-***`array`*** ning 2-elementini 2-***`array`*** ning oxirgidan bitta oldingi elementiga (va hokazo) qo'shib, natijani 3-arrayga saqlaydi.
- `main()` funksiyasi:
    - Sonlarni o'qiydi va natijani chop etadi.

###### Input

1. Birinchi qatorda bitta butun son `N` (N ≤ 20).
2. Ikkinchi qatorda 1-arrayga `N` ta element o'qilsin.
3. Uchinchi qatorda 2-arrayga `N` ta element o'qilsin.

###### Output

Uchinchi arrayni chop etilsin.

#### Namuna 1
| Input | Output |
| - | - | 
| `3` <br>`1 2 3` <br>`5 10 15` | `16 12 8` |


#### Namuna 2
| Input | Output |
| - | - | 
| `4` <br>`3 8 9 5` <br>`0 1 -5 6` | `9 3 10 5` |


---

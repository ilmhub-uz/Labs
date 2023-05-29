##  Lab 4 -  Ifodalar

###  Masala 1 -  !!!!
  
#####  Description
    
> **`0`** dan **`99999`** gacha bitta son o'qing, va sonni har bir raqamini na'munadagidek chop eting.


##### Input
  
Bitta butun son `N`   $(1 <= N <= 99999)$
  
###### Output
  
Kiritilgan sonning har bir xonasi orasida **`!`** belgisi bilan chop eting.

###### Namuna 1
  
| Input | Output |
| - | - |
| `12345` | `1!2!3!4!5` |
  
###### Namuna 2
  
| Input | Output |
| - | - |
| `2016` | `0!2!0!1!6` |

###### Namuna 3
  
| Input | Output |
| - | - |
| `100` | `0!0!1!0!0` |
  
---
  
### Masala 2 - Sekundlar⏳
  
  
###### Description
  
  > - Bitta musbat **int** son o'qing. Bu son sekundlar (seconds)ni anglatadi. Shu sekundlarni **`hours:minutes:seconds`** formatida chop eting.
  
###### Input
  
  Sekundlarni anglatuvchi **`N`** butun musbat son.
  
###### Output
  
  Shu sekund ichidagi mavjud **`soat`**,**`minut`** va **`sekundlar`** ni chop eting.
  Agarda *soat*, *minut* yoki *sekundlarni* birontasi bir xonali bo'lsa, uni oldiga `0` chop etiladi.

  
###### Namuna 1
  
| Input | Output |
| - | - |
| `9741`  | `02:42:21` |
  
###### Namuna 3
  
| Input | Output |
| - | - |
| `63` | `00:01:03` |
  

  
---
###  Masala 3 - Sonning markazi
  
######  Description
    
> - **`10000`**~**`99999`** oraliqda musbat `int` son o'qing, va *`yuzlar`* xonasidagi raqamni chop eting.
  
###### Input
  
  Bitta son **`N`** $(10000 ≤ N ≤ 99999)$
  
###### Output
  
  Berilgan **5** xonali sonning **3**-xonasini chop eting.

  
###### Namuna 1
  
| Input | Output |
| - | - |
| `71000` | `0` |
  
###### Namuna 2
  
| Input | Output |
| - | - |
| `12345` | `3` |
  
###### Namuna 3
  
| Input | Output |
| - | - |
| `99999` | `9` |
  
---
###  Masala 4 - Yandex taxi
  
######  Description
    
>Yandex taxi Toshkent shaxrida anchayin ommalashib ketdi. Lekin oddiy bir muammoni hali ham hal qilinmagani mijozlar va haydovchilar o'rtasida tez-tez tushinmovchilik va noroziliklar tug'dirmoqda.Toshkent shaxri bo'ylab taxi narxlari shunday belgilanadiki, agar mijozlar 1000ga karrali summa berishsa haydovchilarda qoldiq summani, ya'ni 1000 sumdan kam qaytim berishda muammo yuzaga keladi. Ko'p hollarda haydovchilar qaytim haqida o'ylab ham o'tirmay jimgina ketib qolishadi. Bu o'z navbatida mijozlar o'rasida noroziliklar tug'diradi.

>Taxi narxini *`1000`* sum dan kam laxtak qismini yaxlitlaydigan dastur tuzing. Bu dastur mijozlar va haydovchilar orasidagi tushinmovchilikka barham beradi va oradagi ishonchni qayta tiklaydi.
  
###### Input
  
Yo'l haqini ifodalovchi butun musbat son **`N`** $(3000 ≤ N ≤ 1000000)$
  
###### Output
  
Berilgan sonni *`minglar`* xonasigacha yaxlitlab ko'rsating.

  
###### Namuna 1
  
| Input | Output |
| - | - |
| `35800` | `36000` |
  
###### Namuna 2
  
| Input | Output |
| - | - |
| `29300` | `29000` |
  
###### Namuna 3
  
| Input | Output |
| - | - |
| `99999` | `100000` |
  
---


###  Masala 5 - Doiraning yuzi
  
######  Description
    
>Doiraning uzunligi sifatida bitta kasr-son **`L`** ni o'qing. Shu doirani yuzini toping va natijani nuqtadan keyin `0` ta aniqlikda chop eting.

> * `π` ning qiymati: $3.14$
> * Raduisi **r** bo'lgan doiraning uzunligi: $L = 2πr$
> * Doiraning yuzi formulasi: $S = πr^2$
  
###### Input
  
Doiraning uzunligini anglatuvchi kasr-son **`L`**.
  
###### Output
  
  Berilgan uzunlik orqali doiraning yuzini toping va natijani nuqtadan keyin **`0`** ta aniqlikda yaxlitlab chop eting.

  
###### Namuna 1
  
| Input | Output |
| - | - |
| `24.5` | `48` |
  
###### Namuna 2
  
| Input | Output |
| - | - |
| `50` | `199` |
  
###### Namuna 3
  
| Input | Output |
| - | - |
| `1` | `0` |
  
---

###  Masala 6
  
######  Description
    
> - **`N`** sonini o'qing. Agar `N` soni *20* va *30* orasida **(20 va 30 ham kiradi)** bo'lsa , **`1`** ni chop eting. Aks holda **`0`** ni chop eting.
  
###### Input
  
Bitta butun son **`N`**.
  
###### Output
  
**`N`** soni *20* va *30* oraliqda bo'lsa, **`1`** ni aks holda **`0`** ni chop eting.

  
###### Namuna 1
  
| Input | Output |
| - | - |
| `20` | `1` |
  
###### Namuna 2
  
| Input | Output |
| - | - |
| `19` | `0` |
  
###### Namuna 3
  
| Input | Output |
| - | - |
| `-10` | `0` |
  
---

###  Masala 7 - Alifbo
  
######  Description
    
> - Bitta *belgi* o'qing va shu belgini alifbo harfi ekanini aniqlang.
  
###### Input
  
  **`ACSII`** jadvalida mavjud bitta belgi.
  
###### Output
  
  Agar kiritilgan belgi *alifbo harfi* bo'lsa `1` ni, aks holda `0` ni chop eting.

  
###### Namuna 1
  
| Input | Output |
| - | - |
| `k` | `1` |
  
###### Namuna 2
  
| Input | Output |
| - | - |
| `t` | `1` |
  
###### Namuna 3
  
| Input | Output |
| - | - |
| `#` | `0` |

###### Namuna 4
  
| Input | Output |
| - | - |
| `1` | `0` |
  
---

###  Masala 8 - Toq <-> Juft
  
######  Description
    
>Bitta butun `son` kiriting va shu sonni **`juft`** yoki **`toq`** ekanini aniqlang.
  
###### Input
  
Bitta butun son **`N`**.
  
###### Output
  
> - agar kiritilgan son **juft** bo'lsa, **`even`** deb chop eting.
> - agar son **toq** bo'lsa, **`odd`** deb hop eting.

  
###### Namuna 1
  
| Input | Output |
| - | - |
| `1` | `odd` |
  
###### Namuna 2
  
| Input | Output |
| - | - |
| `2` | `even` |
  
###### Namuna 3
  
| Input | Output |
| - | - |
| `7` | `odd` |
  
###### Namuna 4
  
| Input | Output |
| - | - |
| `1024` | `even` |
  
---

###  Masala 9 - Katta son
  
######  Description
    
> 2 ta son kiriting va `kattasini` chop eting.
  
###### Input
  
Ikkita butun sonlar **`N`** va **`M`**.  
  
###### Output
  
Kiritilgan sonlarni *kattasini* chop eting.

  
###### Namuna 1
  
| Input | Output |
| - | - |
| `1`  `2` | `2` |
  
###### Namuna 2
  
| Input | Output |
| - | - |
| `1`  `1` | `1` |
  
###### Namuna 3
  
| Input | Output |
| - | - |
| `1`  `-1` | `1` |
  
---

###  Masala 10 - Bo'linma | Qoldiq
  
######  Description
    
> - Ikkita butun son kiriting. Kattasini kichigiga bo'lib, **`natija`** va **`qoldiqni`** chop eting.
  
###### Input
  
Ikkita butun sonlar **`N`** va **`M`**.
  
###### Output
  
Katta sonni kichigiga bo'lib, `natija` va `qoldiq`ni ketma-ket alohida qatorlarda chop eting.
  
###### Namuna 1
  
| Input | Output |
| - | - |
| `4`  `26` | `6` </br> `2`|
  
###### Namuna 2
  
| Input | Output |
| - | - |
| `9`  `3` | `3` </br> `0` |
  

---

###  Masala 11 - Vaqlar oralig'i
  
######  Description
    
>Bir sutkadagi ikki vaqt ko'rsatkichlarini foydalanuvchidan o'qib, ikki vaqt ko`rsatkichlari oralig'ida necha sekund borligini aniqlaydigan dastur tuzing.

> * **Ikkinchi ko'rsatilgan vaqt birinchi ko'rsatilgan vaqtdan oldin kelmaganligi aniq.**
  
###### Input
  
> - Birinchi qatorda birinchi vaqt ko'rsatkichlari — `soat`, `minut` va `soniya` ni anglatuvchi **`h`** , **`m`** , **`s`** o'zgaruvchilari kiritiladi.
> - Ikkinchi qatorda ikkinchi vaqt ko'rsatkichlari — `soat`, `minut` va `soniya`ni anglatuvchi **`h2`** , **`m2`** , **`s2`** o'zgaruvchilari kiritiladi.
  
###### Output
  
Kiritilgan ikki vaqt orali'gidagi muddatning necha soniya ekanligini aniqlaydigan dastur tuzing.
  
###### Namuna 1
  
| Input | Output |
| - | - |
| `1` `14` `18` </br> `6` `32` `2` | `19064`|
  
###### Namuna 2
  
| Input | Output |
| - | - |
|  `21` `27` `14` </br> `21` `30` `33` | `199` |
  
---

###  Masala 12 - Qoldiqlar yig'indisi
  
######  Description
    
> - 4 ta **`A, B, C, D`** butun sonlari berilgan. *Birinchi* sonni to'*rtinchisiga*, *uchinchi* sonni *ikkinchisiga* bo'lgandagi **qoldiqlar yig'indisini** toping.


###### Input
  
Bir qatorda 4 ta butun son **`A, B, C, D`**. $(1 < A, B, C, D < 10000)$
  
###### Output
  
Qoldiqlar yig'indisini chop eting.
  
###### Namuna 1
  
| Input | Output |
| - | - |
| `9` `2` `7` `4`| `2`|
  
###### Namuna 2
  
| Input | Output |
| - | - |
|  `17` `4` `15` `5` | `5` |
  
---
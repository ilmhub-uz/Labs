##  Lab 5 —  Shart Operatorlari
  
  
###  Masala 1
  
  
#####  Description
    
>Bitta butun son `N` ni o'qing va quyidagicha chop eting
  
> - Agar `N < 0` bo'lsa  ⇒  **ichkarida o'yna** deb chop eting.
> - Agar `0 ≤ N < 40` bo'lsa  ⇒  **tashqarida o'yna** deb chop eting.
> - Agar `N ≥ 40` bo'lsa  ⇒  **ichkarida o'yna** deb chop eting.
  
####  Input
  
  
Bitta butun son `N` .
  
####  Output
  
  
Kiritilgan sonning qiymatiga qarab **ichkarida o'yna** yoki **tashqarida o'yna** matnlaridan biri.
  
######  Namuna 1
  
| Input | Output |
| - | - |
| `-1` | `ichakarida o'yna` |
  
######  Namuna 2
  
| Input | Output |
| - | - |
| `0` | `tashqarida o'yna` |
  
######  Namuna 3
  
| Input | Output |
| - | - |
| `40` | `ichkarida o'yna` |
  
---
  
### Masala 2
  
  
#####  Description
  
  
>Ikkita butun sonlar `N` va `M`larni o'qing. Agar ulardan biri boshqasining kvadratiga teng bo'lsa namunadagidek chop eting. Aks holda, **none** deb chop eting.
  
####  Input
  
  
Ikkita butun `N` va `M` sonlar.
  
####  Output
  
  
Namunadagidek tenglama yoki **none** so'zi.
  
######  Namuna 1
  
| Input | Output |
| - | - |
| `4 2`  | `2*2=4` |
  
######  Namuna 3
  
| Input | Output |
| - | - |
| `3 9` | `3*3=9` |
  
######  Namuna 3
  
| Input | Output |
| - | - |
| `3 4` | `none` |
  
---
  
### Masala 3
  
  
#####  Description
  
  
>Ikkita butun son o'qing va kattasini chop eting.
  
####  Input
  
  
2 ta butun sonlar.
  
####  Output
  
  
Kiritilgan sonlarning kattarog'i.
  
######  Namuna 1
  
| Input | Output |
| - | - |
| `2 3` | `3` |
  
######  Namuna 2
  
| Input | Output |
| - | - |
| `-5 -9` | `-5` |
  
######  Namuna 3
  
| Input | Output |
| - | - |
| `1 1` | `1` |
  
---
  
### Masala 4
  
  
#####  Description
  
  
>Uchta butun sonlar o'qing. Kiritilgan sonlarning eng kattasini va eng kichigini chop eting.
  
> - *Maksimum* va *minimum* qiymatlarning orasida ***space*** bo'lishi, *minimum* qiymatdan keyin esa bo'lmasligi kerak.
  
####  Input
  
  
3 ta butun sonlar.
  
####  Output
  
  
Kiritilgan sonlarning eng kattasi va eng kichigini orasida ***space*** bilan chop eting.
  
######  Namuna 1
  
| Input | Output |
| - | - |
| `2 3 4` | `4 2` |
  
######  Namuna 2
  
| Input | Output |
| - | - |
| `3 2 1` | `3 1` |
  
---
  
### Masala 5
  
  
#####  Description
  
  
>Bitta musbat son o'qing va songa qarab alifbo harflarini quyidagicha chop eting:
  
> - `2`, `3`, va `5` larning har biriga bo'linsa  ⇒  **A**
> - Faqat `2` va `3` larga bo'linsa  ⇒  **B**
> - Faqat `2` va `5` larga bo'linsa  ⇒  **C**
> - Faqat `3` va `5` larga bo'linsa  ⇒  **D**
> - `2`, `3`, va `5` larning faqat bittasiga bo'linsa  ⇒  **E**
> - `2`, `3`, va `5` larning hech biriga bo'linmasa  ⇒  **N**
  
####  Input
  
  
Bitta butun musbat son `N` .
  
####  Output
  
  
Bo'linish-bo'linmasligiga ko'ra chop etlishi so'ralgan tegishli alifbo harfi (yuqoridagi jadval bo'yicha).
  
######  Namuna 1
  
| Input | Output |
| - | - |
| `30` | `A` |
  
  
######  Namuna 2
  
| Input | Output |
| - | - |
| `6` | `B` |
  
######  Namuna 3
  
| Input | Output |
| - | - |
| `7` | `N` |
  
---
  
### Masala 6
  
  
#####  Description
  
  
>Yilni anglatuvchi bitta butun musbat son `N`ni o'qing va kabisa yili yoki oddiy yil ekanligini aniqlaydigan dastur tuzing.
  
> - Kiritilgan yil kabisa yili bo'ladi, **agar**:
>   - 4 ga bo'linsa va 100 ga bo'linmasa;
>   - 4 va 400 ga bo'linsa (garchi 100 ga bo'linsa ham).
> - Kiritilgan yil kabisa yili bo'lmaydi, **agar**:
>   - 4 ga bo'linmasa;
>   - 4 va 100 ga bo'linsa, lekin, 400 ga bo'linmasa.
  
####  Input
  
  
Yilni anglatuvchi bitta butun musbat son `N` (`1 ≤ N ≤ 4000`).
  
####  Output
  
  
Agar kiritilgan yil kabisa yili bo'lsa **leap year** deb, aks holda **normal year** deb chop eting.
  
![Lab%205%20%E2%80%94%20Shart%20Operatorlari%20ea0b410d36fc4fc7869dbfc0c505738f/Untitled.png](Lab%205%20%E2%80%94%20Shart%20Operatorlari%20ea0b410d36fc4fc7869dbfc0c505738f/Untitled.png )
  
######  Namuna 1
  
| Input | Output |
| - | - |
| `4` | `leap year` |
  
######  Namuna 2
  
| Input | Output |
| - | - |
| `1900` | `normal year` |
  
######  Namuna 3
  
| Input | Output |
| - | - |
| `2016` | `leap year` |
  
  
### Masala 7
  
  
#####  **Sonni Tahmin qil o'yini**
  
##### Desctription  
  
> - 1-qatorda bitta butun son `N` .
> - 2-qatordan boshlab tahmin qilish boshlanadi(faraz qiling siz to'g'ri javobni bilmaysiz).

> - To'g'ri javobni topishga ko'pi bilan 2 ta imkoniyat beriladi.
> - 2-qatorda tahminni bildiruvchi `M` soni kiritiladi. Agar `M` soni `N` ga teng bo'lsa **Correct** deb chop etilsin.
> - Agar `M` soni `N`dan kichik bo'lsa **UP** deb chop etilsin.
> - Agar `M` soni `N`dan katta bo'lsa **DOWN** deb chop etilsin.
> - Agar birinchi urinishdan so'ng to'g'ri javob topilmasa `M` ni yana o'qilsin va yuqorida ta'kidlangan shartlarga ko'ra **Correct**, **UP**, yoki **DOWN** lardan birini chop etilsin va o'yin tugatilsin.
  
####  Input
  
  
- O'yin javobi sifatida bitta butun son `N`.
- Birinchi tahmin sifatida `M` butun soni.
- Agar `M` soni `N`ga teng bo'lmasa `M` soni yana qayta o'qiladi. 
  
####  Output
  
  
- Birinchi tahmin to'g'ri bo'lsa **Correct** deb chop eting va o'yinni tugating.
- Birinchi taxmin javobdan kichik bo'lsa **UP** deb, aks holda **DOWN** deb chop eting.
- Agar bitta urinishda javob topilmasa birinchi va ikkinchi qadamlarni yana bir marta takrorlang va o'yinni tugating.
  
######  Namuna 1
  
| Input | Output |
| - | - |
| `5 4 5` | `UP`<br>`Correct` |
  
######  Namuna 2
  
| Input | Output |
| - | - |
| `5 4 7` | `UP`<br>`DOWN` |
  
######  Namuna 3
  
| Input | Output |
| - | - |
| `5 5` | `Correct` |
  
---
  
### Masala 8
  
  
#####  Description
  
  
>`char` turdagi bitta belgi `c`ni o'qing. 
  
> - Agar katta harf bo'lsa kichik harfga, kichik harf bo'lsa katta harfga aylantirib chop eting.
> - Agar alifbo harfi bo'lmasa **none** deb chop eting.
  
###### Input
  
  
Bitta belgi `c`.
  
###### Output
  
  
- Belgi katta harf bo'lsa, kichigini chop eting.
- Belgi kichik harf bo'lsa, kattasini chop eting.
- Belgi harf bo'lmasa, **none** deb chop eting.
  
######  Namuna 1
  
| Input | Output |
| - | - |
| `A` | `a` |
  
######  Namuna 2
  
| Input | Output |
| - | - |
| `t` | `T` |
  
######  Namuna 3
  
| Input | Output |
| - | - |
| `#` | `none` |
  
---
  
### Masala 9
  
  
#####  Description
  
  
> - To'g'ri javobni anglatuvchi 3 ta butun sonlarni o'qing. Har bir son 0~9 oraliqda bo'lsin.
> - Tahminni anglatuvchi 3 ta butun 0~9 oraliqdagi sonlarni o'qing.
> - Nechta **strike**, nechta **ball** borligini namunadagidek chop eting.
>   - `strike` - son bir xil ustunda taxmin qilib topilsa;
>   - `ball` - son boshqa ustunda taxmin qilib topilsa.
  
###### Input
  
  
- 1 - qatorda o'yin javobi uchun uchta sonlar`(0 ≤ SON ≤ 9)`.
- 2- qatorda taxminlar uchun uchta sonlar`(0 ≤ SON ≤ 9)`.
  
###### Output
  
  
`strike` va `ball`lar sonini *x***S** *y***B** ko'rinishida chop eting. (`x` o'rnida **strike**lar soni, `y` o'rnida **ball**lar soni).
  
######  Namuna 1
  
| Input | Output |
| - | - |
| `5 2 3`<br>`5 3 4` | **`1S1B`** |
  
######  Namuna 2
  
| Input | Output |
| - | - |
| `5 2 3`<br>`5 2 3` | **`3S0B`** |
  
  
######  Namuna 3
  
| Input | Output |
| - | - |
| `5 2 3`<br>`2 3 5` | **`0S3B`** |
  
######  Namuna 4
  
| Input | Output |
| - | - |
| `1 1 1`<br>`1 0 0` | **`1S0B`** |
  
######  Namuna 5
  
| Input | Output |
| - | - |
| `0 0 1`<br>`1 1 1` | **`1S2B`** |
  
---
  
### Masala 10
  
  
#####  Description
  
  
>Bitta operator va ikkita butun musbat sondan iborat ifodani bitta qatorda o'qing va shu ifodaning natijasini chop eting.
  
> - butun son, operator, butun son ketma-ketligida, orasida ***space*** bilan ajratilgan holda kiritiladi.
> - Faqat `+` yoki `-` operatorlari ishlatilsin, boshqa hech qanday operatorlarni ishlatish mumkin emas!
  
####  Input
  
  
`son1 +/- son2` ko'rinishidagi ifoda.
  
####  Output
  
  
Kiritilgan ifodaning javobini chop eting.
  
######  Namuna 3
  
| Input | Output |
| - | - |
| `7 + 12` | `19` |
  
######  Namuna 3
  
| Input | Output |
| - | - |
| `7 - 2` | `5` |
  
---
  
### Masala 11

#####  Vending machine

##### Description
  
>Ikkita butun musbat sonlar `N` va `M`larni o'qing. `N` tanlangan ichimlik raqamini bildiradi:
  
>1. Americano = 500;
>2. Caffe Latte = 400;
>3. Lemon Tea = 300;
  
>M tanlangan ichimlik uchun kiritilgan summani anglatadi. (`M` 100 ga karrali bo'ladi, deb faraz qilinsin). **Vending machine** faqat 500 va 100 so'mlik kupyuralarni qaytara oladi, xolos. Tanlangan ichimlik nomi, va shu  ichimlik uchun berilgan qaytim pullarning sonini chop etadigan dastur tuzing.
  
####  Input
  
  
- Birinchi qatorda ichimlik raqamini anglatuvchi bitta `N` soni (1≤ N ≤ 3).
- Ikkinchi qatorda shu tanlangan ichimlik uchun kiritilgan pul summasi.
  
####  Output
  
  
- Birinchi qatorda tanlangan ichimlik nomi.
- Ikkinchi qatorda, avval 500 so'mlikdan nechta pul qaytarilishi, keyin 100 so'mlik puldan nechta qaytarishini ifodalovchi ikkita `son`ni orasida ***space*** bilan chop eting.
  
######  Namuna 1
  
| Input | Output |
| - | - |
| `3 1000` | `Lemon Tea`<br>`1 2` |
  
######  Namuna 2
  
| Input | Output |
| - | - |
| `1 1000` | `Americano`<br>`1 0` |
  
######  Namuna 3
  
| Input | Output |
| - | - |
| `2 1000` | `Caffe Latte`<br>`1 1` |
  
---
  
### Masala 12
  
  
#####  Description
  
  
>Bitta butun son kiriting va shu sonning juft yoki toq ekanini aniqlang.
  
####  Input
  
  
Bitta butun son `N`.
  
####  Output
  
  
- agar kiritilgan son juft bo'lsa `even` deb chop eting
- agar kiritilgan son toq bo'lsa `odd` deb chop eting
  
######  Namuna 1
  
| Input | Output |
| - | - |
| `1` | `odd` |
  
######  Namuna 2
  
| Input | Output |
| - | - |
| `10` | `even` |
  
---
  
### Masala 13
  
  
#####  Description
  
  
>**2** ta son o'qing. Agar ikkala sonning yig'indisi **100** dan katta bo'lsa, `true` deb chop eting. Aks holda `false` deb chop eting.
  
######  Namuna 1
  
| Input | Output |
| - | - |
| `1 100` | `true` |
  
######  Namuna 2
  
| Input | Output |
| - | - |
| `99 1` | `false` |
  
######  Namuna 3
  
| Input | Output |
| - | - |
| `25 78` | `true` |
  
---
  
### Masala 14
  
  
#####  Description
  
  
>**3** ta son o'qing. Agar shu sonlar Pifagor sonlari bo'lsa, `true` deb chop eting. Aks holda `false` deb chop eting.
  
> - Pifagor sonlari deb 2 ta sonning kvadratlari yig'indisi 3-son kvadratiga teng bo'lgan sonlarga aytiladi.
> - **a**, **b** va **c** Pifagor sonlari bo'lish uchun ular quyidagi shartlardan birini qoniqtirishi kerak:
>   - <img src="https://latex.codecogs.com/gif.latex?a^2+b^2=c^2"/>
>   - <img src="https://latex.codecogs.com/gif.latex?a^2+c^2=b^2"/>
>   - <img src="https://latex.codecogs.com/gif.latex?b^2+c^2=a^2"/>
  
######  Namuna 1
  
| Input | Output |
| - | - |
| `3 4 5` | `true` |
  
######  Namuna 2
  
| Input | Output |
| - | - |
| `5 4 3` | `true` |
  
######  Namuna 3
  
| Input | Output |
| - | - |
| `4 5 6` | `false` |
  
---
  
### Masala 15
  
  
#####  Description
  
  
>Bitta belgi (`char`) o'qing. Agar u belgi arifmetik operator bo'lsa `true` deb chop eting. Aks holda `false` deb chop eting.
  
> - Arifmetik operatorlar quyidagilardan iborat: **`+`** , **`-`** , **`*`** , **`/`** , **`%`**
  
  
>✅ **`switch()`** *kontroli orqali ishlansin!*
  
######  Namuna 1
  
| Input | Output |
| - | - |
| `+` | `true` |
  
######  Namuna 2
  
| Input | Output |
| - | - |
| `-` | `true` |
  
######  Namuna 3
  
| Input | Output |
| - | - |
| `%` | `true` |
  
######  Namuna 4
  
| Input | Output |
| - | - |
| `#` | `false` |
  
---
  
### Masala 16
  
  
#####  Description
   
>Bitta son o'qing. Agar u son `0` va `9` oraliqda bo'lsa, o'sha sonni o'zbekcha chop eting. Aks holda `boshqa` deb chop eting.
  
> - so'zlar  kichik harflarda chop etilsin.
  
>✅ **switch()** *kontroli orqali ishlansin!*
  
######  Namuna 1
  
| Input | Output |
| - | - |
| `1` | `bir` |
  
######  Namuna 2
  
| Input | Output |
| - | - |
| `8` | `sakkiz` |
  
######  Namuna 3
  
| Input | Output |
| - | - |
| `10` | `boshqa` |
  
--- 
  
### Masala 17
  
  
#####  Description
  
  
>Wahid amaki har kuni budilnik ovoziga uyg'onadilar. Budilnik ovozini eshitgach *yana-biroz, yana-biroz* 😴 deb doim budilnik ovozidan keyin ham bir qancha vaqtdan keyin o'rinlaridan turadilar. Shuning uchun Wahid amaki doim vaqtida o'rindan turish uchun yangi yechim topdilar. Endi budilnikni turishlari kerak bo'lgan vaqtdan 45 minut avvalroqqa to'g'rilab qo'yadigan bo'ldilar.
  
> - Wahid amakining turishi kerak bo'lgan vaqti ko'rsatilsa, ular budilnikni nechaga to'g'rilashlari kerakligini aniqlaydigan dastur tuzing.
> - Kun `00:00` dan boshlanadi va `23:59` da yakunlanadi.
  
####  Input
  
  
Wahid amakining turishi kerak bo'lgan vaqtini anglatuvchi ikki butun sonlar **S** va **M** (`0 ≤ S ≤ 23`, `0 ≤ M ≤ 59`).
  
####  Output
  
  
Budilnik to'g'rilanishi kerak bo'lgan vaqtning soat va minutini bir qatorda, orasida **space**larsiz, ortiqcha nollarsiz chop eting.
  
######  Namuna 1
  
| Input | Output |
| - | - |
| `10 10` | `9 25` |
  
######  Namuna 2
  
| Input | Output |
| - | - |
| `0 30` | `23 45` |
  
---
  
### Masala 18
  
  
#####  Description
  
  
>Imtihon natijasini anglatuvchi bitta butun musbat son `N`ni o'qing.
> Agar **N** soni 
> - **90** dan katta yoki teng bo'lsa ⇒ **`A`** 
> - **80** dan katta yoki teng bo'lsa ⇒ **`B`** 
> - **70** dan katta yoki teng bo'lsa ⇒ **`C`** 
> - **60** dan katta yoki teng bo'lsa ⇒ **`D`** 
> - **60** dan kichik bo'lsa **`F`** deb chop eting.
  
####  Input
  
  
Bitta butun musbat son **`N`** (`1 ≤ N ≤ 100`).
  
####  Output
  
Jadvaldagi kiritilgan songa mos harf chop eting.
  
######  Namuna 1
  
| Input | Output |
| - | - |
| `100` | `A` |
  
######  Namuna 2
  
| Input | Output |
| - | - |
| `79` | `C` |
  
  
######  Namuna 3
  
| Input | Output |
| - | - |
| `57` | `F` |
  
---
  
### Masala 19
  
  
#####  Yandex Taxi 🚕
  
##### Description
  
>Yandex taxi Toshkent shahrida ancha-muncha ommalashib ketdi. Lekin, oddiy bir muammoni hali ham hal qilinmagani mijozlar va haydovchilar o'rtasida tez-tez tushunmovchilik va noroziliklarga sabab bo'lmoqda. Toshkent shahri bo'ylab taksi narxlari shunday belgilanadiki, agar mijozlar 1000ga karrali summa berishsa haydovchilarda qoldiq summani, ya'ni, 1000 so'mdan kam qaytimni berishda muammo yuzaga keladi. Ko'p hollarda haydovchilar qaytim haqida o'ylab ham o'tirmay jimgina ketib qolishadi. Bu o'z navbatida mijozlar o'rtasida noroziliklar tug'diradi.
  
>✅ Taksi narxini **1000** so'mdan kam laxtak qismini yaxlitlaydigan dastur tuzing. Bu dastur mijozlar va haydovchilar orasidagi tushunmovchilikka barham beradi va oradagi ishonchni qayta tiklaydi.
  
####  Input
  
  
Taksi yo'l haqini ifodalovchi bitta butun musbat son **`N`** (`3000 ≤ N ≤ 1000000`).
  
####  Output
  
  
Berilgan sonni **minglar** xonasigacha yaxlitlab chop eting.
  
######  Namuna 1
  
| Input | Output |
| - | - |
| `35800` | `36000` |
  
######  Namuna 2
  
| Input | Output |
| - | - |
| `29300` | `29000` |
  
  
######  Namuna 3
  
| Input | Output |
| - | - |
| `99999` | `100000` |
  
---
  
### Masala 20
  
  
#####  Description
  
  
>Bitta belgi o'qib, shu belgini alifbo harfi, yoki boshqa belgi ekanligini aniqlaydigan dastur tuzing.
  
####  Input
  
  
`ASCII` jadvalida mavjud bitta belgi.
  
####  Output
  
  
Agar kiritilgan belgi alifbo harfi bo'lsa `1` ni, aks holda `0` ni chop eting.
  
######  Namuna 1
  
| Input | Output |
| - | - |
| `K` | `1` |
  
######  Namuna 2
  
| Input | Output |
| - | - |
| `t` | `1` |
  
######  Namuna 3
  
| Input | Output |
| - | - |
| `#` | `0` |
  
######  Namuna 4
  
| Input | Output |
| - | - |
| `0` | `0` |
  
---
  
### Masala 21
  
  
#####  Description
  
  
>Masala sonini anglatuvchi `n` butun sonini o'qing. (`1 ≤ n ≤ 20`)
  
>- yuqoridagi songa mos keluvchi masalani ishga tushiring
  
####  Input
  
  
- birinchi qatorda masala soni;
- ikkinchi qatordan boshlab o'sha songa mos keladiga masalaga kerak bo'ladigan inputlar kiritilsin.
- agar kiritilgan sonli masala mavjud bo'lmasa, **ERROR** deb chop eting.
  
####  Output
  
  
- tanlangan raqamdagi masalani shartida nimalarni chop etish kerak bo'lsa, o'shalarni chop eting va dasturni yakunlang.
- ✅`switch()` operatoridan foydalanilsin;
- oldin yozilgan funksiyalarni o'z o'rnida chaqirib olish kerak: `main_1();`, `main_1();`, ... .
  
######  Namuna 1
  
| Input | Output |
| - | - |
| `1`<br>`2 3 4` | `4 2` |
  
######  Namuna 2
  
| Input | Output |
| - | - |
| `2`<br>`5 2 3`<br>`5 3 4` | `1S1B` |
  
<br>
######  Yordam
  
```cpp
#include <iostream>
  
using namespace std;
  
int main_1()
{
    ...
}
...
int main_20()
{
    ...
}
  
int main()
{
    int masalan_soni;
    cin >> masala_soni:
  
    switch(masala_soni)
    {
        case 1: main_1(); break;
        ...
        case 20: main_20(); break;
        default: cout << "ERROR" << endl;
    }
  
    return 0;
}
```
  
---
  
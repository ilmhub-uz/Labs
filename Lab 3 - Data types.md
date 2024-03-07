##  Lab 3 -  Ma'lumotlar turlari

###  Masala 1
  
######  Description
    
> Ikkita butun sonni foydalanuvchidan olib ularni yig'indisini chop etadigan dastur tuzing.


###### Input
  
Ikkita butun sonlar `x` va `y`  ${-2}^{32} \leq x, y \leq 2^{32} - 1$
  
###### Output
  
Ikkala kiritilgan sonlarning yig'indisi.

###### Namuna 1
  
| Input | Output |
| - | - |
| `1` `2` | `3` |
  
###### Namuna 2
  
| Input | Output |
| - | - |
| `4294967294` `4294967294` | `4294967294` |

###### Namuna 3
  
| Input | Output |
| - | - |
| `-1` `1` | `0` |
---

###  Masala 2
  
######  Description
    
> Foydalanuvchidan bitta kasr son o'qib uni butun qiymatini chop etadigan dastur tuzing.

###### Input
  
Bitta kasr son `kasr`.
  
###### Output
  
Kiritilgan kasr sonning butun qismini chop eting.

###### Namuna 1
  
| Input | Output |
| - | - |
| `3.14` | `3` |
  
###### Namuna 2
  
| Input | Output |
| - | - |
| `0.15` | `0` |

###### Namuna 3
  
| Input | Output |
| - | - |
| `-4.5` | `-4` |
---

###  Masala 3
  
######  Description
    
> Foydalanuvchidan bitta butun son o'qib shu sonni hex (16 lik) sanoq tizimida chop eting.

###### Input
  
Kiritilgan bitta butun son `x` ${-2}^{64} \leq x \leq 2^{64} - 1$
  
###### Output
  
Kiritilgan butun sonni `hex` formatda chop eting.

###### Namuna 1
  
| Input | Output |
| - | - |
| `26` | `1a` |
  
###### Namuna 2
  
| Input | Output |
| - | - |
| `6699` | `1a2b` |
---

###  Masala 4
  
######  Description
    
> Foydalanuvchidan bitta butun son o'qib shu sonni hex (16 lik) sanoq tizimida chop eting.

###### Input
  
Kiritilgan bitta butun son `x` ${-2}^{64} \leq x \leq 2^{64} - 1$
  
###### Output
  
Kiritilgan butun sonni `hex` formatda chop eting.
- `0x` prefix bo'lishi shart
- Prefix bilan birgalikda kamida 18ta katak ajratilishi kerak
- bo'sh kataklar 0 bilan to'ldirilishi kerak
- hamma `hex` harflari katta harfda bo'lishi kerak

###### Namuna 1
  
| Input | Output |
| - | - |
| `26` | `0X000000000000001A` |
  
###### Namuna 2
  
| Input | Output |
| - | - |
| `6699` | `0X0000000000001A2B` |

###### Namuna 3
  
| Input | Output |
| - | - |
| `9223372036854775807 ` | `0X7FFFFFFFFFFFFFFF` |
---

###  Masala 5
  
######  Description
    
> Foydalanuvchidan bitta belgi o'qib shu belgini hex (16 lik) sanoq tizimida chop eting.

###### Input
  
Kiritilgan bitta belgi.
  
###### Output
  
Kiritilgan belgini `hex` formatda chop eting.
- `0x` prefix bo'lishi shart
- Prefix bilan birgalikda kamida 4ta katak ajratilishi kerak
- bo'sh kataklar 0 bilan to'ldirilishi kerak
- hamma `hex` harflari katta harfda bo'lishi kerak

###### Namuna 1
  
| Input | Output |
| - | - |
| `a` | `0X61` |
  
###### Namuna 2
  
| Input | Output |
| - | - |
| `m` | `0X6D` |
---
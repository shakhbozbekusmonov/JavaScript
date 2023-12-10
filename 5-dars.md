- Math operators + - * / % () .
- Tenglik = == ===.
- Qisqartmalar.
- Increment.
- Decrement
---
    Matematik operatorlar:
        +: Qo'shish.
        -: Ayirish.
        *: Ko'paytirish.
        /: Bo'lish.
        %: Qoldiqni olish.
        () : Quvvatlash uchun qo'shimcha qavs.

    Tenglik operatorlari:
        =: O'zlashtirish operatori.
        ==: Tengmi? Ma'lum bir qiymat boshqa qiymatga tengmi?
        ===: To'g'ri tengmi? Qiymatlar bir-biriga to'g'ri mos keladimi va tur?

    Qisqartmalar:
        ++: O'zgaruvchini birga ko'tarish (increment).
        --: O'zgaruvchini birga kamaytirish (decrement).

++ operatori o'zgaruvchini birga ko'taradi, ya'ni quyidagi misoldek:
```javascript
let x = 5;
x++; // x hozir 6 ga teng bo'ladi
```

-- operatori esa o'zgaruvchini birga kamaytiradi:

```javascript
let y = 8;
y--; // y hozir 7 ga teng bo'ladi
```

### Question:
- Math keyvordi nima?
- sonni butun qismini ajratib olish uchun mathning qaysi metodian foydalanamiz?
- mathning 8ta metodini sanab bering.
- pre va post incrementlarning asosiy ishlashdagi farqlari nimada.
- berilgan sonlar ichida eng katta va eng kichigini topish uchun qanday metod foydalanamz?
- = / == / ===  bir biridan farqi.
- Sonni ihtiyoriy darajaga ko'tarish uchun nima qilamiz?

1. **Math keyvordi nima?**
   - `Math` JavaScriptda standart kutubxonadur, unda matematik amallar (ko'paytirish, bo'lish, ildiz olish, trigonometrik amallar va boshqalar) uchun metodlar jamlangan.

2. **Sonni butun qismini ajratib olish uchun mathning qaysi metodian foydalanamiz?**
   - `Math.floor()` metodi sonni ildizlariga qarab pastki butun son ga yaqinlashtiradi. Misol uchun, `Math.floor(3.8)` natijada 3 ga yaqin butun son qaytaradi.

3. **Mathning 8 ta metodini sanab bering:**
   - `Math.abs()`, `Math.ceil()`, `Math.floor()`, `Math.max()`, `Math.min()`, `Math.pow()`, `Math.round()`, `Math.random()`.

4. **Pre va post incrementlarning asosiy farqlari nimada?**
   - Pre-increment (`++i`) o'zgaruvchini o'zgartirishdan so'ng, yangi qiymatni olishadi, post-increment esa (`i++`) qiymatni olishdan so'ng, o'zgaruvchini o'zgartiradi.

5. **Eng katta va eng kichik sonni topish uchun qanday metod foydalanamz?**
   - `Math.max()` eng katta sonni topish uchun, `Math.min()` esa eng kichik sonni topishda ishlatiladi.

6. **= / == / === bir biridan farqi.**
   - `=` o'zlashtirish operatori, `==` tengmi operatori va `===` to'g'ri tengmi operatorlari. `==` turi bilan qiymatlar bir-biriga mos keladiganligini tekshiradi, `===` esa turi va qiymatlar o'zaro to'g'ri mos keladiganligini tekshiradi.

7. **Sonni ihtiyoriy darajaga ko'tarish uchun nima qilamiz?**
   - Sonni ihtiyoriy darajaga ko'tarish uchun `Math.pow()` metodi ishlatiladi. Masalan, `Math.pow(2, 3)` 2 ning 3-darajasini hisoblaydi va natija sifatida 8 qaytaradi (2^3 = 8).



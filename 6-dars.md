- Comparision
- AND / OR / NOT
- Tenglik = == ===.
- Logical comparision.
- ASCII table haqida.
- amaliy mashqulotlar.
---
1. **Tenglik operatorlari:**
   - `=`: O'zlashtirish operatori (misol: `x = 5`).
   - `==`: Tengmi? Ma'lum bir qiymat boshqa qiymatga tengmi?
   - `===`: To'g'ri tengmi? Qiymatlar bir-biriga to'g'ri mos keladimi va tur?

2. **Mantiqiy operatsiyalar:**
   - `AND (&&)`: Agar ikkala shart ham rost bo'lsa, barcha shartlar rost bo'lishi lozim.
   - `OR (||)`: Agar kamida bir shart rost bo'lsa, boshqa shartlarga qarab to'xtamaydi.
   - `NOT (!)`: Shartni teskari qiladi (rostdan yoki yolg'onchadan boshqa qiladi).

3. **Tenglik (`=`, `==`, `===`) farqlari:**
   - `=` o'zlashtirish operatori.
   - `==` turi bilan qiymatlar bir-biriga mos keladiganligini tekshiradi.
   - `===` turi va qiymatlar o'zaro to'g'ri mos keladiganligini tekshiradi.

4. **Mantiqiy solishtirish:**
   - Bu solishtirishlar, qiymatlarni solishtirishda va shartlarda ishlatiladi. Masalan: `x > 5`, `y == 10`, `a !== b` kabi.

5. **ASCII jadvali haqida:**
   - ASCII jadvali, belgilarning raqamli kodlarini (0 dan 127 gacha) ko'rsatadi. Bu kodlar, belgilarni kompyuterda ifodalash uchun ishlatiladi. Masalan, harf A ning ASCII kodi 65 ga teng.

6. **Amaliy mashq:**

   - **Misol 1:**
     ```
     let x = 5;
     let y = 10;
     let z = x < 10 && y > 5;
     ```
     Bu misolda, `z` qiymati `true` bo'ladi, chunki `x` 10 dan kichik va `y` 5 dan katta.

   - **Misol 2:**
     ```
     let a = 20;
     let b = 25;
     let c = !(a === b);
     ```
     `c` qiymati `true` bo'ladi, chunki `a` va `b` teng emas va `!` operatori teskari qiladi.
---
### Questions:
- AND ga amaliy misollar keltiring. 
- OR ga amaliy misollar keltiring.
- NOT ga amaliy misollar keltiring. 
- ASCII table haqida malumot bering?
- = / == / ===  bir biridan farqi.
- "A" va "a" taqqoslashdan qanday javob chiqadi. natijani tushuntirib bering
---
### Answers:
1. **AND ga amaliy misollar:**
   - `let x = 5; let y = 10; if (x > 0 && y < 15) { /* kod */ }` - Agar x qiymati 0 dan katta va y qiymati 15 dan kichik bo'lsa, shart rost bo'ladi.

2. **OR ga amaliy misollar:**
   - `let a = 20; let b = 5; if (a === 20 || b === 10) { /* kod */ }` - Agar a qiymati 20 ga teng yoki b qiymati 10 ga teng bo'lsa, shart rost bo'ladi.

3. **NOT ga amaliy misollar:**
   - `let z = true; let result = !z;` - `!z` operatsiyasi teskari qiladi va `result` o'zgaruvchisi `false` bo'ladi.

4. **ASCII jadvali haqida:**
   - ASCII (American Standard Code for Information Interchange) belgilar uchun bir kodlashma tizimi. Bu jadval 127 ta belgi uchun belgilar va ularning kompyuterda kodini ifodalaydi. Masalan, A harfining kodi 65, a harfiningki esa 97.

5. **= / == / === bir biridan farqi:**
   - `=` o'zlashtirish operatori.
   - `==` qiymatlarni solishtiradi, lekin tur farqli bo'lsa turini moslashtirib tekshiradi.
   - `===` qiymatlar va turlar bir-biriga to'g'ri mos kelishini tekshiradi.

6. **"A" va "a" taqqoslashdan qanday javob chiqadi:**
   - Bu harflar katta va kichik, shunday qilib, `A === a` ifodasi `false` qiymat chiqaradi, chunki ularning ASCII kodi farq qiladi. Katta harfning kodi kichik harfning kodidan farqli. Demak, ular bir-biriga teng emas.
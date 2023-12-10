- O'tilgan darslar yuzasidan savol javob.
- if else tushunchasi..
- birdan oshiq holatni taqqoslash.
- else if.
- else if bilan if ning ishlatilishidagi farqi.
- if ishlatishda orderning ahamiyati
---
1. **if else tushunchasi:**
   - `if` va `else` operatorlari shartlarga asoslangan toifadur. `if`, shart rost bo'lsa, u yozuvni bajaradi. Agar rost bo'lmasa, `else` operatoriga o'tadi, shu bilan bajarilishi mumkin bo'lgan ikkinchi bir blok aniqlanadi.

2. **Birdan oshiq holatni taqqoslash:**
   - `if` va `else` bloklari yordamida, ikki holat (rost va yolg'on)ni taqqoslash mumkin. Misol uchun:
     ```javascript
     let x = 10;
     if (x > 5) {
         console.log("Rost"); // Agar x 5 dan katta bo'lsa, "Rost" chiqaradi
     } else {
         console.log("Yolg'on"); // Aks holda, "Yolg'on" chiqaradi
     }
     ```

3. **else if:**
   - `else if` operatori, ikkita shartdan birini tekshiradi. Agar avvalgi shart rost bo'lmasa, keyingi shartni tekshiradi. Misol uchun:
     ```javascript
     let y = 12;
     if (y > 15) {
         console.log("Katta");
     } else if (y < 10) {
         console.log("Kichik");
     } else {
         console.log("Boshqa");
     }
     ```
     Agar `y` 15 dan katta bo'lsa, "Boshqa" chiqadi.

4. **else if bilan if ning ishlatilishidagi farqi:**
   - `else if` ko'p shartli holatlarni tekshirishda ishlatiladi, aks holda, undan keyingi shartlar `if` dan foydalaniladi.

5. **if ishlatishda orderning ahamiyati:**
   - Shartlar `if`ning quyidagi shartlari uchun bajarilishi. Bunday holatda, birinchi rost bo'lgan shartni topganda, qolgan shartlarni tekshirishga kerak qoladi. Shuning uchun, shartlar chiziqli bo'lsa, ularni o'ngacha qat'iylik tartibi boyicha yozish juda muhimdir.

### Questions:
- if else ishlatish holatlari?
- else if bilan if ni ishlatishda Nima farq bor ?
- if tugaganligini qayerdan bilamiz
- if ni {} belgilarisiz yozish holati?
- nullish operatori haqida malumot bering?
- Nullish operatori nima?
- ?? vs || - farqi?

### Answers:
1. **if else ishlatish holatlari:**
   - `if else` to'g'ri va yolg'on (rost va yolg'on) holatlarni tekshirishda ishlatiladi. Agar biror shart bajarilmasa, keyingi shartni tekshirish uchun ishlatiladi.

2. **else if bilan if ni ishlatishda nima farq bor:**
   - `else if` operatori, ikkita yoki undan ko'p shartni tekshirish uchun ishlatiladi. `if` bilan faqatgina bir shartni tekshirish mumkin.

3. **if tugaganligini qayerdan bilamiz:**
   - Shart bajarilgandan so'ng, shuning qanday bajarilganligini bilish uchun `if` ning ichidagi blok yoki shart bajarilgan joydan keyin kelgan qismida kod yozish mumkin.

4. **if ni {} belgilarisiz yozish holati:**
   - Agar `if` bloki yoki `else` bloki faqat bitta qatorda yozilgan bo'lsa, `{}` belgilari ishlatmaslik mumkin, ammo kod o'zgartirish jarayonida qoladi.

5. **Nullish operatori haqida malumot:**
   - Nullish operatori (`??`) JavaScriptning o'zgaruvchi yoki qatori `null` yoki `undefined` bo'lgan qiymatlarni tekshirishda ishlatiladi.

6. **Nullish operatori nima:**
   - Nullish operatori, o'zgaruvchining `null` yoki `undefined` bo'lgan holatlarni tekshirishda ishlatiladi. `||` operatori esa `falsy` qiymatlar (0, "", false)ni ham tekshirishi mumkin.

7. **?? vs || — farqi:**
   - `??` operatori faqat `null` yoki `undefined` bo'lgan qiymatlarni tekshiradi.
   - `||` operatori esa `falsy` qiymatlarni ham (0, "", false) tekshirishi mumkin.
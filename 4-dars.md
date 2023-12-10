- O'tilgan darslar yuzasidan savol javob.
- Number Type Conversion.
- String Type Conversion.
- Boolean Type Conversion.
- Null vs Undefined
---
- Number Type Conversion: Bu, ma'lumotlarni raqam ko'rinishiga o'girish jarayoni. Misol uchun, bir matnni raqamga aylantirish. Masalan, "25" ni 25 ga o'girish.

- String Type Conversion: Bu esa, ma'lumotlarni matn ko'rinishiga o'girishdir. Raqamni matnga aylantirish misol bo'lishi mumkin. 25 ni "25" ga o'girish.

- Boolean Type Conversion: Bu turdagi o'girish, qiymatlarni true yoki false ga aylantirishdir. Misol uchun, 0 qiymatini false ga aylantirish yoki bosh matnni true ga o'girish.

- Null vs Undefined: null va undefined JavaScript tilida o'zaro farq qiladigan narsalar. null, o'zgaruvchiga o'zgartirish bo'lsa bo'lmasa qiymat berish uchun qo'llaniladi. undefined esa o'zgaruvchi o'rniga hech narsa berilmagan holatdir.
---
### Questions:
- Nega typelarni boshqa turga convert qilishimiz kerak?
- String ichidagi butun va kasr sonlarni number turiga o'tkazish uchun qanday methoddan foydalanamiz?
- Number cosntructori haqida malumot bering.
- falseni ifodalaydigan qiymatlarni sanab bering.
- ParseInt bn parseFloatni bir biridan farqi nimada?
### Answer
- Nega typelarni boshqa turga o'tkazish uchun JavaScriptda parseInt() va parseFloat() funksiyalardan foydalanish mumkin. parseInt() butun sonlarni o'zgartiradi (masalan, stringdan butun son qilib olish), parseFloat() esa kasr sonlarni o'zgartiradi.

- String ichidagi butun va kasr sonlarni number turiga o'tkazish uchun parseInt() va parseFloat() funksiyalardan foydalanishingiz mumkin. parseInt() butun sonlarni ajratib olish uchun, parseFloat() esa kasr sonlarni ajratib olish uchun ishlatiladi.

- Number constructor'i JavaScriptda ma'lum bir qiymatni raqam (number) turiga o'tkazadi. Misol uchun: Number("42") string "42" ni raqamga o'zgartiradi va natija sifatida 42 raqamini qaytaradi.

- JavaScriptda false qiymati 0 bo'ladi. Boolean qiymatlarni sonlash uchun, true qiymati 1 ga o'xshab, false esa 0 ga o'xshab turadi.

- parseInt() va parseFloat()ning bir necha farqli usullari mavjud. parseInt() butun sonlarni ajratib olishda ishlatiladi, ya'ni raqamlar to'g'ri kelganda qat'iy sonni olish uchun. Biroq, parseFloat() kasr sonlarni ajratib olishda ishlatiladi, ya'ni sonlarning oldi olish uchun qo'shimcha belgilar (masalan, nuqta) ham o'qiladi va qaytariladi.
- JavaScript ishlash strukturasi
- Threadlar haqida umumiy tushuncha.
- Variables va Declorations haqida batafsil.
- let, var const larning bir biridan farqi.

JavaScript-da "threadlar" mavzusi bir qancha dasturlash tillaridagi "threadlar"ga o'xshash emas. JavaScript brauzerda qurilgan oddiy til bo'lib, u "single-threaded" - yani, bir bor ishlaydigan modelga ega. Bu esa, JavaScript dasturlari bitta "thread" (ish paralell ravishda olib boriladigan kod bo'lmagan o'zgaruvchi) orqali ishlaydi.

"Variables" JavaScript-da ma'lumotlarni saqlash uchun ishlatiladigan elementlardir.
Bu ma'lumotlar sonlar, matnlar, obyektlar, funksiyalar va boshqa qiymatlar bo'lishi mumkin.
JavaScript-da o'zgaruvchilarni aniqlash uchun var, let, va const operatorlari ishlatiladi.

var o'zgaruvchilarni e'lon qilish uchun ishlatiladi, ammo u "function-scoped" - ya'ni, o'zgaruvchi funktsiya ichida e'lon qilinsa, faqatgina o'sha funktsiya ichida ishlaydi.

let esa ES6 (ECMAScript 2015) da qo'shilgan yangi o'zgaruvchi e'lon qilish uslubi. U esa "block-scoped" - ya'ni, o'zgaruvchi blok ichida e'lon qilinsa, shu blok ichida faqatgina ishlaydi.

const esa o'zgarmas (immutable) o'zgaruvchilarni e'lon qilish uchun ishlatiladi. U esa qiymat bir marta tayinlangan bo'lsa, unda o'zgartirib bo'lmaydi, ammo obyekt yoki massiv kabi o'zgaruvchilarga tegishli ma'lumotlarni o'zgartirish imkoniyatiga ega.

let va const var-ga nisbatan kodni qisqartiradi va o'zgaruvchilarni to'g'ri manzilda e'lon qilish va ularning qo'llanishini chuqurlashtiradi.

Shunday qilib, JavaScript-da o'zgaruvchi e'lon qilishda let, var va const qo'llaniladi va ularning har birining o'z foydalanish sohasi va huquqlari mavjud.



## Question:

1. JavaScript ishlash strukturasi haqida malumot bering?
2. Single threaad nima?
3. JavaScript code'ni necha hil usulda ishlatib(compile) ko'rsak bo'ladi?
4. Reserved keyword nima?
5. var let const larning bir biridan farqi nimada?
6. Global variable nima?

## Answer:

1. JavaScript ishlash strukturasi yozilgan dasturlarni tuzish va bajarishning asosiy qoidalari va tartiblari to'g'risidagi tuzilmadir. Bunda, muhim elementlar funktsiyalar, o'zgaruvchilar, obyektlar, operatorlar, va boshqa elementlar kiritiladi. JavaScript tilida kod yozishda, umumiy ravishda quyidagi struktura kuzatiladi:

- Funktsiyalar: Kodning modullarini va boshqa funksiyalarni e'lon qilish. JavaScript-da funksiya deklaratsiyasi (function so'zi bilan) yoki funksiya ifodasi (arrow function) orqali yoziladi.

- O'zgaruvchilar va ma'lumotlar turi: Sonlar, matnlar, obyektlar, massivlar va boshqa ma'lumotlar turlari JavaScript tilida foydalaniladigan o'zgaruvchi va ma'lumotlar tipini ifodalaydi.

- Shartlar va qaytaruv qiymatlari: if, else if, else operatorlari, switch operatori va boshqa shart operatorlari yordamida shartlar va qaytaruv qiymatlari ifodalaydi.

- Sikl operatorlari: for, while, do while va for...in sikllari orqali sikllar yaratish va bajarish.

- Ob'ektlar va metodlar: JavaScript ob'ektlari yaratish va ularning metodlarini ishlatish. Ob'ektlar {} yordamida yaratiladi.

- Async kod va promise'lar: Asinxron kodlar, callback funksiyalari, promise'lar va async/await mekanizmalari orqali kodni asinxron ravishda bajarish imkoniyatlarini beradi.

2. "Single thread" yoki "bitta tasma" dasturlash tilida yozilgan dasturlarda, kodning barcha qismlari o'zaro o'zgaruvchilarni (variables) va ma'lumotlarni ulash uchun bitta boshqa ishlatiladi. Bu esa, kodning barcha qismlari bitta asosiy o'zgaruvchi orqali birlashtiriladi va bitta boshqaruvchidan yuritiladi.

3. JavaScript kodini ishlatishning ko'p usullari mavjud, ular:

- Brauzerda ishlatish: HTML faylida <script> tegi orqali skriptni joylash va brauzerda HTML sahifasini yuklash orqali ishga tushirish.

- Node.js orqali ishlatish: JavaScript fayllarni kompyuterda o'z ishletish.

4. "Reserved keyword" JavaScript tilida o'zgaruvchi nomlanishi uchun ishlatilishi taqiqlangan so'zlar. Bu so'zlar JavaScriptning o'zgaruvchi, funksiya, va boshqa struktura elementlari nomlanishida foydalanish mumkin emas.

5. var, let, va const o'zgaruvchilarni e'lon qilish uchun ishlatiladigan operatorlar. Ularning farqi esa ularning qo'llanish sohalari va o'zgaruvchi turini o'z ichiga oladi. var funktsiya-scope ga ega bo'lib, let va const esa blok-scope ga ega. const esa o'zgarmas (immutable) o'zgaruvchilarni e'lon qilish uchun ishlatiladi.

6. "Global variable" esa dastur ichidagi eng katta skop (ob'ektlar, funksiyalar va boshqa o'zgaruvchilar o'rtasidagi o'zgaruvchi) sifatida nomlanadi. Bu o'zgaruvchi barcha dastur ichidagi har qanday joydan qo'llanish mumkin bo'lgan o'zgaruvchidir.
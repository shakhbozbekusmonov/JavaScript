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

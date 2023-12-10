- Data Types nima?
- Primitive vs Non Primitive
- Number.
- Bigint.
- String.
- Boolean
- Null
- Undefined
- Symbols
- Objects
- Arrays
- Functions

---

- Primitive (Oddiy): Bu oddiy ma'lumot turlari, ular to'g'ri, kapsulatsiya qilmagan.
- Number: Sonlar (misol: 5, 3.14, -10).
- BigInt: Katta butun sonlar (misol: 9007199254740992n).
- String: Matnlar (misol: "Salom", 'Hello').
- Boolean: Mantiqiy qiymatlar (true yoki false).
- Null: Qiymati "bo'sh" (null).
- Undefined: O'zgaruvchiga qiymat berilmagan holat (undefined).
- Symbol: Unikal simvollar (misol: const mySymbol = Symbol('description')).

---

- Non-Primitive (Oddiydan tashqari): Bu turlar ma'lumotlarni ko'p qatlamli yoki ko'plikda o'z ichiga oladi.
- Object: Umumiy ma'lumot o'zgaruvchisi ({} yoki new Object()).
- Array: Ma'lumotlar to'plami ([] yoki new Array()).
- Function: Funksiya (function() {}).

## Question:

- Data Types nima?
- Primitive vs Non Primitive farqi nimada?
- Number misollar bilan tushuntirib bering.
- Bigint misollar bilan tushuntirib bering.
- String misollar bilan tushuntirib bering.
- Boolean misollar bilan tushuntirib bering.
- Null misollar bilan tushuntirib bering.
- Undefined misollar bilan tushuntirib bering.
- Symbols misollar bilan tushuntirib bering.
- Objects misollar bilan tushuntirib bering.
- Arrays misollar bilan tushuntirib bering.
- Functions misollar bilan tushuntirib bering.

### Data Types (Ma'lumot turkumi):
Ma'lumotlar turlari, ma'lumotlarni kategoriyalarga ajratadigan turkumlardir.

Primitive vs Non-Primitive (Oddiy va Oddiydan Tashqari):
Oddiy (Primitive): To'g'ri, kapsulatsiya qilmagan ma'lumotlardir.
Oddiydan tashqari (Non-Primitive): Ma'lumotlarni ko'p qatlamli yoki ko'plikda o'z ichiga oladigan ma'lumotlar turlari.
```
Number misollar:
let integerNumber = 10; // Butun son
let floatNumber = 3.14; // O'nlik son
let negativeNumber = -20; // Manfiy son

Bigint misollar:
const bigIntNumber = 9007199254740992n; // Katta butun son
const anotherBigInt = BigInt("123456789012345678901234567890"); // Stringdan BigIntga o'tkazish

String misollar:
let greeting = "Assalomu alaykum"; // Matn
let myName = 'John'; // Matn
let multilineString = `Bu bir nechta qatorli
matn bo'lishi mumkin`; // Ko'p qatorli matn


Boolean misollar:
let isLogged = true; // Mantiqiy qiymat
let hasPermission = false; // Mantiqiy qiymat

Null misollar:
let emptyValue = null; // Bo'sh qiymat

Undefined misollar:
let undefinedValue; // Qiymat berilmagan o'zgaruvchi
console.log(undefinedValue); // Output: undefined

Symbols misollar:
const uniqueSymbol = Symbol('description'); // Unikal simvol
const anotherSymbol = Symbol('description'); // Boshqa unikal simvol

Objects misollar:
let person = { // Ob'ekt
name: 'John',
age: 30,
isStudent: false
};

Arrays misollar:
let numbers = [1, 2, 3, 4, 5]; // Ma'lumotlar to'plami
let fruits = ['Apple', 'Banana', 'Orange']; // Ma'lumotlar to'plami

Functions misollar:
function greet(name){
  return Salom, ${name}!;
}

let result = greet('Ali'); // Funksiya chaqirish
console.log(result); // Output: Salom, Ali!
```
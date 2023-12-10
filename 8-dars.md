- ternary operator nima?
- if else bn ternaryning ishlatilishidagi farqi.
- ikkitadan oshiq holatlarni taqqoslash.

1. **Ternary operator nima?**
   - Ternary operator (`? :`) if-else operatorining qisqa shakli hisoblanadi. U, shartni tekshirib, shart rost bo'lsa bir qiymatni, aks holda boshqa qiymatni qaytaradi.

2. **If else bilan ternaryning ishlatilishidagi farq:**
   - Ternary operator (`? :`) qisqa va qulay shaklda shartlarni tekshirishda ishlatiladi va if-else bilan bir xil vazifani bajaradi, ammo qisqa yozuvda.

3. **Ikkitadan oshiq holatlarni taqqoslash:**
   - If-else bloklari:
     ```javascript
     let x = 10;
     if (x > 5) {
         console.log("Katta");
     } else {
         console.log("Kichik");
     }
     ```
   - Ternary operator:
     ```javascript
     let y = 15;
     let result = y > 10 ? "Katta" : "Kichik";
     console.log(result);
     ```

### Questions:
- ternary operator nima?
- if bn ternary operatorni taqqoslab bering ?
- ikki holatdan ortiq malumotni tekshirishda nega ? ishlatish yaxshi emas?

### Answers:
1. **Ternary operator nima?**
   - Ternary operator `? :` ifodasidan iborat operator hisoblanadi. U, shartni tekshirib, shart rost bo'lsa bir qiymatni, aks holda boshqa qiymatni qaytaradi.

2. **If bn ternary operatorni taqqoslab bering:**
   - `if` bilan:
     ```javascript
     let x = 10;
     let message;
     if (x > 5) {
         message = "Katta";
     } else {
         message = "Kichik";
     }
     ```
   - Ternary operator bilan:
     ```javascript
     let y = 15;
     let result = y > 10 ? "Katta" : "Kichik";
     ```
   Ternary operator qisqa shaklda shartni yozishga imkoniyat beradi, shuning uchun kodni qisqa va barqaror qiladi.

3. **Ikki holatdan ortiq malumotni tekshirishda nega `? :` ishlatish yaxshi emas?**
   - O'zgaruvchini yoki bir qiymatni ikki holatdan ortiq tekshirish uchun ternary operator juda qulay bo'lishi mumkin. Bunday holatlarda, kodning o'zida qulaylik va qisqacha yozish uchun foydalanish mumkin. Ammo, qisqa yozuvlarni o'qish va tushunish qiyinchilikka olib kelishi mumkin, shuning uchun, kodni juda qisqa qilish odatda yaxshi ko'rinmaydi.

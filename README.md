# String-in-JS
---

### 🔤 Что такое строка?
Строка — это просто **последовательность символов**, взятых в кавычки:
```js
let message = "Hello, world!";
```
Можно использовать:
- двойные кавычки `"Hello"`
- одинарные кавычки `'Hello'`
- или обратные кавычки `` `Hello` `` (о них чуть позже — это **template literals**, наши любимчики).

---

### ✨ Основные способы работы со строками:

#### 1. **Конкатенация** (склеивание строк)
```js
let firstName = "John";
let lastName = "Doe";
let fullName = firstName + " " + lastName; // John Doe
```

#### 2. **Template literals (шаблонные строки)** — магия с обратными кавычками:
```js
let name = "Alice";
let age = 18;
let message = `My name is ${name} and I’m ${age} years old.`;
```
> Больше не надо играть в "плюсики"! Это чистое удовольствие ✨

---

### 📐 Полезные свойства и методы строк:
| Метод / Свойство         | Что делает                                                 |
|--------------------------|-------------------------------------------------------------|
| `length`                 | Длина строки (`"hello".length → 5`)                         |
| `toUpperCase()`          | Все буквы — заглавные (`"hello".toUpperCase()` → `"HELLO"`)|
| `toLowerCase()`          | Все буквы — маленькие                                      |
| `charAt(index)`          | Символ по индексу                                          |
| `indexOf("word")`        | Где впервые встречается подстрока                         |
| `includes("word")`       | Есть ли такое слово? (true/false)                         |
| `slice(start, end)`      | Вырезает часть строки                                      |
| `trim()`                 | Убирает пробелы по краям                                   |
| `replace(old, new)`      | Заменяет одно на другое                                    |
| `split(separator)`       | Делит строку в массив                                       |

Пример:
```js
let text = " Hello, JavaScript! ";
console.log(text.trim().toUpperCase()); // "HELLO, JAVASCRIPT!"
```

---

### 🧠 Маленький лайфхак:
```js
"apple" === "Apple" // false (регистр важен!)
```
Так что, если сравниваешь строки — иногда лучше сразу привести к одному регистру.

---

Хочешь, я сделаю тебе маленький **чек-лист или шпаргалку по строкам**? Или может, хочешь потренироваться с задачками — например, сделать функцию, которая переворачивает строку или считает гласные? 😉

Скажи только слово — и я готов выдать порцию весёлого и полезного контента. 💥

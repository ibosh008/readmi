# JavaScript Strings ва Numbers

## 📚 Шарҳи лексия
Дар ин дарс мо дар бораи **String** ва **Number** дар JavaScript омӯхтем.
String = матн
Number = рақам

---

## 1. Method дар JavaScript
**Method** функсияест, ки ба object вобаста аст.

Мисол:
```javascript
let text = "Hello";
console.log(text.toUpperCase());
```

Натиҷа:
```javascript
HELLO
```

`toUpperCase()` ҳамаи ҳарфҳоро калон мекунад.

---

## 2. length
Барои ёфтани дарозии string аз `.length` истифода мекунем.

```javascript
let text = "Mozilla";
console.log(text.length);
```

Натиҷа:
```javascript
7
```

Яъне калимаи "Mozilla" 7 ҳарф дорад.

> `.length` property аст, method нест.

---

## 3. Гирифтани ҳарф аз string

### Бо index
```javascript
let text = "Hello";
console.log(text[0]);
```

Натиҷа:
```javascript
H
```

Index аз 0 сар мешавад.

H = 0
e = 1
l = 2
l = 3
o = 4

### charAt()
```javascript
console.log(text.charAt(1));
```

Натиҷа:
```javascript
e
```

### at()
```javascript
console.log(text.at(-1));
```

Натиҷа:
```javascript
o
```

`-1` ҳарфи охиринро мегирад.

---

## 4. Ҷустуҷӯ дар string

### includes()
Месанҷад ки калима ҳаст ё не.

```javascript
let text = "hello world";
console.log(text.includes("world"));
```

Натиҷа:
```javascript
true
```

### indexOf()
Ҷойи калимаро меёбад.

```javascript
console.log(text.indexOf("world"));
```

Натиҷа:
```javascript
6
```

`world` аз index 6 сар мешавад.

---

## 5. Буридани string

### slice()
```javascript
let text = "Hello World";
console.log(text.slice(0,5));
```

Натиҷа:
```javascript
Hello
```

Аз 0 то 5 мегирад.

### substring()
```javascript
console.log(text.substring(0,5));
```

Натиҷа:
```javascript
Hello
```

Монанди slice кор мекунад.

---

## 6. Тоза кардани string

### trim()
Фосилаҳоро нест мекунад.

```javascript
let text = "   hello   ";
console.log(text.trim());
```

Натиҷа:
```javascript
hello
```

### toLowerCase()
Ҳама хурд:

```javascript
console.log("HELLO".toLowerCase());
```

Натиҷа:
```javascript
hello
```

### toUpperCase()
Ҳама калон:

```javascript
console.log("hello".toUpperCase());
```

Натиҷа:
```javascript
HELLO
```

---

## 7. Иваз кардани текст

### replace()
```javascript
let text = "Hello World";
console.log(text.replace("World","Universe"));
```

Натиҷа:
```javascript
Hello Universe
```

### replaceAll()
Ҳамаашро иваз мекунад.

```javascript
let text = "cat cat cat";
console.log(text.replaceAll("cat","dog"));
```

Натиҷа:
```javascript
dog dog dog
```

---

## 8. split()
String-ро ба array табдил медиҳад.

```javascript
let text = "Hello JavaScript";
console.log(text.split(" "));
```

Натиҷа:
```javascript
["Hello","JavaScript"]
```

---

## Чизҳои муҳим
- String тағйир намешавад (immutable)
- Аксари method-ҳо string-и нав бармегардонанд
- `.length` бе `()` навишта мешавад

---

## Мавзуъҳо
- Methods
- Properties
- length
- charAt()
- at()
- includes()
- indexOf()
- slice()
- substring()
- trim()
- replace()
- split()

---

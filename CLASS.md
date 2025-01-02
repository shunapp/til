# クラス(Class)

## 設計図のこと

## コンストラクタ

```js
class Human {
  constructor(name, age) {
    this.name = name;
    this.age = age;
  }

  greeting() {
    console.log("Hello World!");
    console.log(`I'm ${this.name}`);
    console.log(`I'm ${this.age} years old`);
  }
}

const human = new Human("John", 20);
```

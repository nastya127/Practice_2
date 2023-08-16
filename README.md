# Practice with getting the information from objects, processing it, store, etc.

## Завдання 1 

Дано: функція яка приймає масив чисел або стрічок. 

Результат: вивести у консоль масив унікальних значень початкового масиву 

Приклад: 

[2, 3, 1, 3, 3, 7] => [2,3,1,7]
```
function unicFn(initialArray) {
 // Write code here 
}
```
## Завдання 2 

Дано: функція яка приймає масив чисел 

Результат: вивести у консоль "YES" якщо усі числа у масив парні та "NO" в іншому випадку 

Приклад: 

[1, 2, 3, 9] => “NO” 
[2, 4, 6] => “YES”
```
function isEvenArray(initialArray) {
 // Write code here
}
```
## Завдання 3 

Дано: функція яка приймає масив елементів будь-яких типів 

Результат: вивести у консоль масив який містить лише стрічки початкового масиву 

Приклад: 

[2, “string”, 3, , , ”test”] => [“string”, “test”]
```
function filterArray(initialArray) {
 // Write code here
}
```
## Завдання 4 

Дано: Функція приймає Об’єкт типу {[name]: {age: number, city: string}} 

Результат: Вивести у консоль масив із іменами людей які із міста "London" та старше 18 років 

Приклад: 

{Max: {age: 23, city: “London”}, Mike: {age: 20: city: “NY”}} => [“Max”]
```
function findUser(initialObject) {
 // Write code here
}
```
## Завдання 5 

Дано: Функція приймає три параметри: масив обєктів [{}, {}], назву поля обєкту (string), значення (string) 

Результат: Вивести у консоль новий масив з якого видалені усі обєкти в яких keyName буде дорівнювати value 

Приклад: 

removeObj([{age: 1}, {age: 2}, {age: 2}, {year: 2}], "age", 2) => [ { age: 1 }, { year: 2 } ]

```
function removeObj(arrayOfObj, keyName, value) {
// Write code here
}
 
const arr = [{ age: 1 }, { age: 2 }, { age: 2 }, { year: 2 }];

removeObj(arr, "age", 2);

removeObj(arr, "year", 2);
```

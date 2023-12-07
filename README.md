# goit-js-hw-06

Завдання №1 Перед звільненням розробник зламав вихідний код управління акаунтами
користувачів нашого сервісу доставки їжі. Виконай рефакторинг методів об'єкта
customer, розставивши відсутні this під час звернення до властивостей об'єкта.

const customer = { username: "Mango", balance: 24000, discount: 0.1, orders:
["Burger", "Pizza", "Salad"], // Change code below this line getBalance() {
return balance; }, getDiscount() { return discount; }, setDiscount(value) {
discount = value; }, getOrders() { return orders; }, addOrder(cost, order) {
balance -= cost - cost \* discount; orders.push(order); }, // Change code above
this line };

customer.setDiscount(0.15); console.log(customer.getDiscount()); // 0.15
customer.addOrder(5000, "Steak"); console.log(customer.getBalance()); // 19750
console.log(customer.getOrders()); // ["Burger", "Pizza", "Salad", "Steak"]

Завдання №2 Створи клас Storage, який створюватиме об'єкти для управління
складом товарів. Клас очікує лише один аргумент — початковий масив товарів, який
записується до створеного об'єкта в приватну властивість items.

Оголоси наступні методи класу:

getItems() — повертає масив поточних товарів у приватній властивості items.
addItem(newItem) — приймає новий товар newItem і додає його до масиву товарів у
приватну властивість items об'єкта. removeItem(itemToRemove) — приймає рядок з
назвою товару itemToRemove і видаляє його з масиву товарів у приватній
властивості items об'єкта. Оголошений клас Storage У класі Storage оголошений
метод getItems У класі Storage оголошений метод addItem У класі Storage
оголошений метод removeItem Властивість items у класі Storage оголошена
приватною Метод getItems повертає значення приватної властивості items
екземпляра класу, який його викликає Метод addItem змінює значення приватної
властивості items екземпляра класу, який його викликає Метод removeItem змінює
значення приватної властивості items екземпляра класу, який його викликає

Завдання №3 Створи клас Storage, який створюватиме об'єкти для управління
складом товарів. Клас очікує лише один аргумент — початковий масив товарів, який
записується до створеного об'єкта в приватну властивість items.

Оголоси наступні методи класу:

getItems() — повертає масив поточних товарів у приватній властивості items.
addItem(newItem) — приймає новий товар newItem і додає його до масиву товарів у
приватну властивість items об'єкта. removeItem(itemToRemove) — приймає рядок з
назвою товару itemToRemove і видаляє його з масиву товарів у приватній
властивості items об'єкта. Оголошений клас Storage У класі Storage оголошений
метод getItems У класі Storage оголошений метод addItem У класі Storage
оголошений метод removeItem Властивість items у класі Storage оголошена
приватною Метод getItems повертає значення приватної властивості items
екземпляра класу, який його викликає Метод addItem змінює значення приватної
властивості items екземпляра класу, який його викликає Метод removeItem змінює
значення приватної властивості items екземпляра класу, який його викликає

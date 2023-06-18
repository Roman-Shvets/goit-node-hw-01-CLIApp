Команди:

npm start — старт сервера в режимі production

npm run start:dev — старт сервера в режимі розробки (development)

Посилання на скріншоти виконання команд:
https://drive.google.com/drive/folders/1Obh2qUCoBdnk8lq3StX8HIKu1gPU5pXW?usp=sharing

# Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)

node index.js --action="list"

# Отримуємо контакт по id і виводимо у консоль об'єкт контакту або null, якщо контакту з таким id не існує.

node index.js --action="get" --id 05olLMgyVQdWRwgKfg5J6

# Додаємо контакт та виводимо в консоль об'єкт новоствореного контакту

node index.js --action="add" --name Mango --email mango@gmail.com --phone 322-22-22

# Видаляємо контакт та виводимо в консоль об'єкт видаленого контакту або null, якщо контакту з таким id не існує.

node index.js --action="remove" --id qdggE76Jtbfd9eWJHrssH

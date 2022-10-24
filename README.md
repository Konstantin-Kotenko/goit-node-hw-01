# Получаем и выводим весь список контактов в виде таблицы (console.table)
node index.js --action list
https://monosnap.com/file/DyIG3oAsZ44IO1nZb2ysJM5dEsJ211

# Получаем контакт по id
node index.js --action get --id 5
https://monosnap.com/file/dab96ZRuwXUNxygcM72NkqNxLeF6KB

# Добавялем контакт
node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22
https://monosnap.com/file/7gR4ls9A7IOOkSQJhobvTIAzl3pZFy

# Удаляем контакт
node index.js --action remove --id=3
https://monosnap.com/file/5jSN0Xd48okqe9gNkDAuOyfJGiTg9u

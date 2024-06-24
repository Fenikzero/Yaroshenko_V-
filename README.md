# Yaroshenko_V-
# Проект: Гра "Хрестики-Нулики"

## Опис
Цей проект реалізує класичну гру "Хрестики-Нулики" на мові програмування C++. Гра підтримує базові функціональні можливості, такі як:
- Збереження та завантаження гри
- Визначення переможця
- Обробка нічиєї

## Мета проекту
Метою проекту є створення консольної гри, яка дозволяє:
- Двом гравцям змагатися один з одним у грі "Хрестики-Нулики"
- Зберігати та завантажувати стан гри

## Функціональні можливості
- Гра для двох гравців
- Збереження поточного стану гри у файл
- Завантаження збереженої гри з файлу
- Перевірка перемоги або нічиєї

## Технології
- **C++**
- **Стандартна бібліотека вводу-виводу (iostream)**
- **Файлова система (fstream)**

## План реалізації
1. **Розробка класу `TicTacToe` для представлення гри**
2. **Реалізація функцій для відображення ігрового поля**
3. **Реалізація логіки для перевірки перемоги або нічиєї**
4. **Реалізація функцій для збереження та завантаження гри**
5. **Реалізація основного циклу гри**

## Використання

### Компіляція
Для компіляції коду використовуйте компілятор C++. Наприклад, можна використати `g++`:
```bash
g++ -o tic_tac_toe tic_tac_toe.cpp
###Гра
Після запуску програма запитає, чи бажаєте ви завантажити попередню гру. Якщо так, введіть y, якщо ні — введіть n. Після цього дотримуйтесь інструкцій на екрані для здійснення ходів.


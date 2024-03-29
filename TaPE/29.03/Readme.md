# Задание

## Написать программу, реализующую игру "угадай число"

Правила игры следующие. Играют двое. Один задумывает число, второй — угадывает.
На каждом шаге угадывающий делает предположение, а задумавший число — говорит, сколько цифр числа угаданы и сколько из угаданных цифр занимают правильные позиции в числе.
Например, если задумано число 725 и выдвинуто предположение, что задумано число 523, то угаданы две цифры (5 и 2) и одна из них (2) занимает верную позицию.
Ниже приведен рекомендуемый вид экрана во время работы программы.
Данные, введенные пользователем, выделены полужирным шрифтом. Компьютер задумал трехзначное число.
Вы должны его отгадать. После очередного числа вам будет сообщено, сколько цифр угадано и сколько из них находятся на своих местах.

После ввода числа нажимайте `Enter`.

Для завершения игры нажмите `Esc`.

```bash
Ваш вариант -> 123 Угадано: О. На своих местах: О
Ваш вариант -> 456 Угадано: 1 На своих местах: О
Ваш вариант -> 654 Угадано: 2 На своих местах: 2
Ваш вариант -> 657 Угадано: 2 На своих местах: 2
Ваш вариант -> 658 Угадано: 3 На своих местах: 3
 ***ВЫ УГАДАЛИ !***
```

Нажмите `Enter` для завершения.
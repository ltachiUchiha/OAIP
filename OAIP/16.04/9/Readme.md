# Задача №9

Анатолию в последний месяц удача улыбалась очень плохо. У него 3 раза взломали пароль. Вот он и задумался над тем, что неправильно подходит к вопросу составления паролей. Чтобы не напрягаться больше и опять не попасть впросак, молодой человек решил написать функцию на `Python`, которая будет проверять его пароль на надежность.

Требования к паролю у Анатолия следующие (он внимательно изучил рекомендации знатоков):

- Длина – 8 символов (если меньше – то проще взломать, а если длиннее – то сложно запомнить)
- В пароле должны быть заглавные буквы, строчные символы, числа и специальные знаки (из перечня «*-#»; другие спецсимволы недопустимы, так как Анатолий их не может запомнить).

Помогите парню составить функцию `check_pass(pswd)`, которая проверит пароль на соответствие требованиям. 

В случае верного пароля выведется на печать «Пароль идеален», а в остальных случаях будут перечислены все ошибки, которые Анатолий допустил (для представления перечня ошибок заведите переменную err в виде словаря).
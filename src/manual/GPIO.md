# 1. Порты ввода-вывода (.)

## Теория

## Задания

### Базовые задания

### Задания повышенного уровня сложности


## Типовые проблемы

1. Микроконтроллер в общем случае программируется через ножки PA13 и PA14. Соответственно, если ваш код задевает настройку этих ножек, плата может перестать прошиваться. В этом нет ничего страшного. это можно исправить с использованием программы [ST-link utility](https://www.st.com/en/development-tools/stsw-link004.html), подключившись к плате **"under reset"** и полностью очистив память. Чтобы избежать этой ошибки в дальнейшем рекомендуется проверить, чтобы в настройке порта А не было операций "=", а вместо них были операции "|=" и "&= ~".

## Контрольные вопросы

1. Какая разрядность у процессоров STM32?
2. Сколько бит входит в 1 байт?
3. Какое количество бит входит в слов в процессорах STM32?
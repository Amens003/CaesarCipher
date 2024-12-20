# Шифр Цезаря

## Описание

Этот проект реализует шифр Цезаря — метод шифрования текста, который сдвигает буквы на определенное количество позиций в алфавите. 
Пользователи могут вводить текст на английском или русском языках, указывать величину сдвига и получать зашифрованный или расшифрованный текст.

## Пример

- Входной текст: FZRYYF YVXR GRRA FCVEVG
- Сдвиг: 13
- Язык: en
- Расшифровка: SMELLS LIKE TEEN SPIRIT

## Объяснение кода main.js 

1) Принимается три параметра: text (текст для шифрования/дешифрования), shift (величина сдвига), и language (язык текста).
2) Проходим по каждому символу введенного текста и приводим символы к нижнему регистру для обработки.
3) Находим индекс символа в алфавите.
   Если символ не найден в алфавите (пробел или пунктуация), он добавляется к результату без изменений.
   Если символ найден, вычисляется новый индекс с учетом сдвига.
4) Выводится результат.

Для расшифровки используется тот же текст и язык, но с отрицательным сдвигом.



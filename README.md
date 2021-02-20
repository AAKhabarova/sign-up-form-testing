# sign-up-form-testing
Test cases for complex SignUp form.

Тестирование сложной формы регистрации пользователся

## Описание задачи
Написать тест-кейсы на английском языке для тестирования сайта http://qa.noveogroup.com, протестировать сайт согласно тест-кейсам, описать найденные ошибки.

## Принятые допущения и ограничения.
Нормы для формы "пароль" взяты в соотвествии с требованиями безопасности:
- не менее 8 символов;
- не более 128 символов;
- как минимум одна заглавная и одна строчная буква;
- только латинские или кириллические буквы;
- как минимум одна цифра;
- только арабские цифры;
- без пробелов;
- другие допустимые символы:~ ! ? @ # $ % ^ & * _ - + ( ) [ ] { } > < / \ | " ' . , : ;

## Ссылка на форму
http://qa.noveogroup.com

## Ссылка на Google Sheet с тест кейсами и багрепортами
https://docs.google.com/spreadsheets/d/1_3NsspZafQh6yClysesedCSC8NkThZdiFnaLSPkKcos/edit#gid=0

## Summary
Найдено багов: 18
### Дополнительные рекомендации:
- Set restrictions on the number of characters for the fields: "Name", "Email" and "Description"
- Change the http protocol to https, since this is a registration form and there is personal data
- Set rules for the password (https://support.kaspersky.com/KPC/1.0/ru-RU/183862.htm)
- Usually in the "password" field there is an additional button to remove the mask. It is worth considering adding such functionality
- For the convenience of the user, you can change the format for entering the date of birth in the field "birthday"
- Set limits for textarea
- Add placeholder for fields
- Adapt the registration form for mobile devices

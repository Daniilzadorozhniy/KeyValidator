# Отчёт о тестировании KeyValidator
## *Краткое описание*
<06.10.2020> - <07.10.2020> было проведено: 
1. Тестирование документации;
2. Нефункциональное тестирование;
- тестирование установки;
- тестирование совместимости;
3. Функциональное тестирование;
- Позитивное тестирование;
- Негативное тестиррвание;

## *На тестирование затрачено*:  4 часа.

## *В результате тестирования выявлены следующие дефекты*:

* [Валидные ключи не прошли валидацию в KeyValidator #1](https://github.com/Daniilzadorozhniy/KeyValidator/issues/1#issue-715875866)
* [Невалидный ключ 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 прошел валидацию в KeyValidator #2](https://github.com/Daniilzadorozhniy/KeyValidator/issues/2#issue-715882528)

Описание процесса тестирования

## *В процессе тестирования использовались следующие артефакты*:

[Спецификация ПО KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

[Инструкция по установке OpenJDK11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)

Баг репорты

[Tast Case](https://github.com/Daniilzadorozhniy/Test-case.git)

## *В качестве тестовых данных использовались данные*- [Руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md):

1. Валидные ключи
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
* 80b427f8-92cd-3aae-ba04-3927fbe17c6
* b295bc63-9f03-3b4b-af80-969b39f8c262
* 387eedc6-12e9-3b32-9881-63b6b5e85317
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180
2. Невалидные ключи
* 18252235-78e0-44a5-8720-556f0c7da17a
* e66075b6-ddad-445e-baf6-161b3289522b
* b6d53250-f07e-4352-a293-6102ddf7f1ca
* c2bc778a-1cb9-46c6-b435-0489649d2a42
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

## *Тестирование производилось в следующем окружении*:

* ОС Windows 7 (Домашняя версия), 64 разрядная
* java -version
openjdk version "11.0.8" 2020-07-14
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)
* Браузер Google Chrome (ерсия 81.0.4044.138 (Официальная сборка), (64 бит))
* Git Bash
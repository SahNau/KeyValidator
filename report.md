# **Отчёт о тестировании KeyValidator**
## Краткое описание
03.03.2021 - 03.03.2021  было проведено функциональное тестирование приложения KeyValidator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Не активируется лицензия приложения при вводе правильного ключа #1](https://github.com/SahNau/KeyValidator/issues/1)
* [Не активируется лицензия приложения при вводе правильного ключа #2](https://github.com/SahNau/KeyValidator/issues/2)
* [Активируется лицензия приложения при вводе ключа, который не должен работать #3](https://github.com/SahNau/KeyValidator/issues/3)

## Описание процесса тестирования
 В процессе тестирования использовались следующие артефакты:

*  [Инструкция по установке OpenJDK11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
* [Руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)
* [Домашнее задание к занятию «1.1. Введение в Java: JDK, JRE, JVM, IntelliJ IDEA»](https://github.com/netology-code/javaqa-homeworks/tree/master/intro)


В качестве тестовых данных использовались данные [ключи](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md):
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 Ответ "OK", ключ работает
* 80b427f8-92cd-3aae-ba04-3927fbe17c6 Ответ "OK", ключ работает
* b295bc63-9f03-3b4b-af80-969b39f8c262 Ответ "OK", ключ работает
* 387eedc6-12e9-3b32-9881-63b6b5e85317 Ответ "OK", ключ работает
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180 Ответ "OK", ключ работает
* 18252235-78e0-44a5-8720-556f0c7da17a Ответ "FAIL", ключ не работает
* e66075b6-ddad-445e-baf6-161b3289522b Ответ "FAIL", ключ не работает
* b6d53250-f07e-4352-a293-6102ddf7f1ca Ответ "FAIL", ключ не работает
* c2bc778a-1cb9-46c6-b435-0489649d2a42 Ответ "FAIL", ключ не работает
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 Ответ "FAIL", ключ не работает

Тестирование производилось в следующем окружении:

* Windows 10 x64
* Java 11
* IntelliJ IDEA 2020.3.2
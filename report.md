# Название приложения 
Credit Card Number Validator

# Краткое описание
01.04.2021 - 01.04.2021 было проведено Smoke test приложения Credit Card Number Validator.

На тестирование затрачено: 3 (три) часа

# В результате тестирования выявлены следующие дефекты:
* [Неудачный результат при вводе валидных значений карт #1](https://github.com/Maksim-Pat/1DZ-IDEA/issues/1)

# Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:
* [Домашнее задание к занятию «1.1. Введение в Java: JDK, JRE, JVM, IntelliJ IDEA»](https://github.com/netology-code/javaqa-homeworks/tree/master/intro)


В качестве тестовых данных использовались данные:
* [getcreditcardnumbers.com](https://www.getcreditcardnumbers.com/generated-credit-card-numbers)

Карты VISA:
* 4532945868739751 
Ожидаемый результат: Result is OK
* 4916374281134258 
Ожидаемый результат: Result is OK
* 4539447184051741 
Ожидаемый результат: Result is OK

Карты Mastercard 
* 5578872860657223 
Ожидаемый результат: Result is OK
* 5451124603457863 
Ожидаемый результат: Result is OK
* 5438352259274641 
Ожидаемый результат: Result is OK

Карты Discover
* 6011238691929665 
Ожидаемый результат: Result is OK
* 6011870581208964 
Ожидаемый результат: Result is OK
* 6011907931832653 
Ожидаемый результат: Result is OK

Карты American Express
* 348933494361879 
Ожидаемый результат: Result is OK
* 374829719102477 
Ожидаемый результат: Result is OK
* 341647711337184 
Ожидаемый результат: Result is OK

Тестирование производилось в следующем окружении:
* windows 7
* IntelliJ IDEA Community Edition 2020.3.3
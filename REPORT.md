# Отчёт о тестировании приложения KeyValidator

### Краткое описание

17.12.2020 было проведено функциональное тестирование приложения KeyValidator.

Всего  затрачено времени : 2 часа

### В результате тестирования выявлены следующие дефекты:

[Дефект №1 [В приложении Key Validator в списке валидных ключей обнаружен не валидный](https://github.com/NastiaZe/key-validator/issues/3) 
 [Дефект №2 [В приложении Key Validator в списке не валидных ключей обнаружен валидный](https://github.com/NastiaZe/key-validator/issues/2)  


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

1.  [Документ "Инструкция по установке OpenJDK 11"](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
2.  [Документ "Руководство использования"](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

В качестве тестовых данных использовались данные: документ  ["Руководство использования"](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

## Ожидаемые данные:

валидные ключи для проверки - ответ приложения result for "key" OK 
не валидные ключи для проверки  - ответ приложения result for "key" FAIL

## Тестирование производилось в следующем окружении:

Micrsoft Windows 10 pro, версия: 1909 сборка 18363.418  
openjdk version "11.0.9.1" 2020.11.04
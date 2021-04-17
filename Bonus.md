# Отчёт о тестировании кода (Дополнительный бонус)

## Краткое описание

<17.04.2021> - <17.04.2021>. Было проведено функциональное тестирование кода (Дополнительный бонус)

На тестирование затрачено: <1 час>

В результате тестирования выявлены следующие дефекты:
* [Бонус] Ошибка в расчетах #1](https://github.com/AlexandraOwl/Java-3/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Домашнее задание к занятию «1.2. Программирование на Java: переменные, операторы, работа с отладчиком»](https://github.com/netology-code/javaqa-homeworks/tree/master/programming)
Программа IntelliJ IDEA

В качестве тестовых данных использовался следующий код.

```public class Main {
    public static void main(String[] args) {
        double regularBonus = 0.3;
        double specialBonus = 0.6;
        double totalBonus = regularBonus + specialBonus;
        System.out.println(totalBonus);
    }}
```
Ожидаемый результат - сумма двух бонусов рассчитывается верно.

Программное окружение:
* Windows 10 Pro
* Версия Java 11.0.10


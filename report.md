# Отчёт о тестировании Precision

## Краткое описание

12.05.2021 - 12.05.2021 было проведено функциональное тестирование приложения, которое осуществляет cложение значений

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* issues #1

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Баг-репорты
* Отчет о тестировании


В качестве тестовых данных использовались данные:

`public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }`


Тестирование производилось в следующем окружении:
* Windows 10 Version 20H2
* 11 Java
* IntelliJ IDEA 2021.1 (Community Edition)

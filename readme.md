# Отчёт о тестировании приложения "Precision"

## Краткое описание

30 апреля 2020 проведено тестирование кода приложения Precision.
В результате тестирования выявлен баг: программа делает неверное вычисление.


## Описание тестов

1. Создать проект в IntelliJ IDEA.
2. Копировать код приложения:

```java
public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}
```
3. Запустить код на исполнение через конопку Run.
4. Наблюдать результат.

## Результаты

1. После запуска приложения появился результат = 0.8999999999999999. Ожидаемый результат = 0,9.
2. [Ссылка на баг-репорт](https://github.com/katalsheva/java2.2/issues/1)


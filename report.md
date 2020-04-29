# Отчёт о тестировании приложения "Precision"

## Краткое описание

При выполнениии программы бонус высчитывается не по математическим правилам. 0.3 + 0.6 = 0.8999999999999999

## Описание тестов

Выполнялось позитивное тестирование без изменений данных.

## Результаты

1. 100% не успешных тестов
2. Ссылки на баг-репорты

## Общие рекомендации

Из документации: «This data type should never be used for precise values, such as currency. For that, you will need to use the java.math.BigDecimal class instead.Numbers and Strings covers BigDecimal and other useful classes provided by the Java platform.»
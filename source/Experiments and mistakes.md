# Основные ошибки при проведении экспериментов

Леонид Кулигин, Google.

## Мнение спикера
* PM должен обладать базовым знанием статистики.
* Стоит вкладываться в разработку собственных статистических моделей.
* Только 10% фич влияют на бизнес-результат.

## Ликбез
[Нулевая гипотеза](https://ru.wikipedia.org/wiki/%D0%9D%D1%83%D0%BB%D0%B5%D0%B2%D0%B0%D1%8F_%D0%B3%D0%B8%D0%BF%D0%BE%D1%82%D0%B5%D0%B7%D0%B0) - изменения нет.

[Альтернативная гипотеза](http://statistica.ru/glossary/general/alternativnaya-gipoteza-alternativa/) - изменение есть.

[False positive:](https://ru.wikipedia.org/wiki/%D0%9E%D1%88%D0%B8%D0%B1%D0%BA%D0%B8_%D0%BF%D0%B5%D1%80%D0%B2%D0%BE%D0%B3%D0%BE_%D0%B8_%D0%B2%D1%82%D0%BE%D1%80%D0%BE%D0%B3%D0%BE_%D1%80%D0%BE%D0%B4%D0%B0_(%D1%81%D1%82%D0%B0%D1%82%D0%B8%D1%81%D1%82%D0%B8%D0%BA%D0%B0))
* выявлен некий эффект, которого на самом деле не было.
* эффект был, но мы не заметили. 

[A/B testing](https://ru.wikipedia.org/wiki/A/B-%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5) - онлайн-проверка гипотез на конверсии (изменении поведения) в группе A и B в зависимости от наличия фичи:
* изменение = 0;
* изменение > 0.
 Отсутствие изменения - повод отвергнуть гипотезу.

## Инструменты
Должны быть правила проверки гипотез => методика проведения экспериментов:
* сколько мерим (например, 2 недели по какой-то причине),
* когда НЕ мерим (например, установку Plesk не мерить по воскресеньям, и в рождественский период),
и т.д.
## Ошибки
* Прогнозировать итоги до начала проверки гипотезы.
* Продолжать трекинг после завершения тестирования гипотезы.
* Мерить до тех пор, пока не увидим изменение / желаемый результат.

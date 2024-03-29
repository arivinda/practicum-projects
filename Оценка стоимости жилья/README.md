# Прогнозирование стоимости жилья в жилом массиве.

## Описание
Сервис по продаже квартир закал разработку модели по прогнозированию стоимости квартиры.

## Цели
1. Обучить модель линейной регрессии на данных о жилье в Калифорнии за 1990 год.
2. Сделать предсказания медианной стоимости домов в жилых массивах на тестовой выборке.
3. Оценить качество модели, используя метрики RMSE (среднеквадратичная ошибка), MAE (средняя абсолютная ошибка) и R2 (коэффициент детерминации).

## Вывод
В задаче предсказания медианной стоимости домов в жилых массивах были разработаны две модели регрессии: первая обучена на всех доступных данных, включая категориальные признаки, преобразованные через one-hot encoding, вторая — только на числовых данных. Используя линейную регрессию и заполняя пропуски медианными значениями, модель на полном наборе данных показала лучшие результаты, вероятно, благодаря учёту важных категориальных признаков, таких как удалённость от океана, влияющих на стоимость жилья. Рекомендуется использовать первую модель и рассмотреть оптимизацию гиперпараметров или использование других моделей для улучшения результатов.

## Сферы деятельности
- Площадки объявлений
- Интернет-сервисы
- Оффлайн

## Направление деятельности
- Big-Data
- Машинное обучение
- Регрессия

## Задачи проекта
- Определить медианную стоимость квартиры

## Ключевые слова для поиска
- Большие данные
- Spark

## Навыки и инструменты
- `Python`
- `Pandas`
- `Spark`
```

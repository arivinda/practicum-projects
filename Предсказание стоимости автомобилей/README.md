# Построение модели определения стоимости автомобиля

## Описание
Сервис по продаже автомобилей с пробегом разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. На основе исторических данных необходимо построить модель для определения стоимости автомобиля.

## Цели
1) Провести EDA анализ
2) Избавиться от выбросов и артефактов, а также бесполезных столбцов
3) С помощью перебора гиперпараметров построить несколько моделей и выбрать лучшую по метрике

## Вывод
Нашей основной задачей было создание модели для предсказания цены автомобиля на основе данных с сайтов объявлений. После проведения EDA-анализа и удаления выбросов, дубликатов, артефактов и ненужных столбцов, датасет был сокращён с 354369 до 192485 строк. Для решения задачи были разработаны несколько моделей, включая градиентный бустинг (CatBoost и LightGBM), линейную регрессию, решающее дерево и случайный лес, с использованием RMSE в качестве метрики. Лучшие результаты показал градиентный бустинг от CatBoost, однако с точки зрения соотношения скорости и качества предпочтение было отдано LightGBM за его способность обучаться и делать предсказания всего за 8 секунд по сравнению с 37 секундами у CatBoost. Рекомендуется использовать градиентный бустинг от LightGBM.

## Сферы деятельности
- Интернет-сервисы
- Интернет-магазины
- Бизнес

## Направление деятельности
- Машинное обучение

## Задачи проекта
- Разработка системы рекомендации стоимости автомобиля на основе его описания

## Ключевые слова для поиска
- Градиентный бустинг
- Регрессия

## Навыки и инструменты
- `Python`
- `Pandas`
- `lightgbm`


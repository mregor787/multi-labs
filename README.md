# Лабораторные работы по курсу:

## Методы, средства и технологии мультимедиа
Выполнил: Белоусов Е.Л., группа М8О-408Б-21

## Выбранные датасеты

Классификация: https://www.kaggle.com/datasets/muratkokludataset/date-fruit-datasets

Регрессия: https://www.kaggle.com/datasets/niteshyadav3103/concrete-compressive-strength

## Итоги работы

В таблице указаны значения метрик Accuracy и F1-Score для классификации; RMSE и R² для регрессии.

<table>
    <tr>
        <th rowspan="1">Алгоритм</th>
        <th>Задача</th>
        <th>Бейзлайн</th>
        <th>Улучшенный бейзлайн</th>
        <th>Самостоятельная имплементация алгоритма</th>
    </tr>
    <tr>
        <td rowspan="2">KNN</td>
        <td>классификация</td>
        <td>Acc=0.7111; F1=0.6919</td>
        <td>Acc=0.9222; F1=0.9222</td>
        <td>Acc=0.9222; F1=0.9213</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>RMSE=8.2983; R²=0.7328</td>
        <td>RMSE=7.1234; R²=0.8031</td>
        <td>RMSE=7.1210; R²=0.8032</td>
    </tr>
    <tr>
        <td rowspan="2">Линейные модели</td>
        <td>классификация</td>
        <td>Acc=0.9222; F1=0.9208</td>
        <td>Acc=0.9278; F1=0.9263</td>
        <td>Acc=0.1444; F1=0.0452</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>RMSE=9.7967; R²=0.6275</td>
        <td>RMSE=9.7951; R²=0.6277</td>
        <td>RMSE=9.7967; R²=0.6275</td>
    </tr>
    <tr>
        <td rowspan="2">Решающее дерево</td>
        <td>классификация</td>
        <td>Acc=0.8056; F1=0.7969</td>
        <td>Acc=0.8556; F1=0.8590</td>
        <td>Acc=0.7889; F1=0.7776</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>RMSE=9.5792; R²=0.6439</td>
        <td>RMSE=6.6985; R²=0.8259</td>
        <td>RMSE=9.2196; R²=0.6701</td>
    </tr>
    <tr>
        <td rowspan="2">Случайный лес</td>
        <td>классификация</td>
        <td>Acc=0.9222; F1=0.9214</td>
        <td>Acc=0.9278; F1=0.9281</td>
        <td>Acc=0.8667; F1=0.8678</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>RMSE=5.5397; R²=0.8809</td>
        <td>RMSE=5.4444; R²=0.8850</td>
        <td>RMSE=7.4933; R²=0.7821</td>
    </tr>
    <tr>
        <td rowspan="2">Градиентный бустинг</td>
        <td>классификация</td>
        <td>Acc=0.8778; F1=0.8807</td>
        <td>Acc=0.8833; F1=0.8868</td>
        <td>Acc=0.0056; F1=0.0026</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>RMSE=5.5422; R²=0.8808</td>
        <td>RMSE=4.3941; R²=0.9251</td>
        <td>RMSE=10.2411; R²=0.5930</td>
    </tr>
</table>

## Вывод

Итак, лучшей моделью для классификации является *Случайный лес с улучшенным бейзлайном*.
Лучшей моделью для регрессии является *Градиентный бустинг с улучшенным бейзлайном*.
# Project-workshop
Задача регресии.

В данном проекте решалась задача предсказания продолжительности поездки на такси в Нью-Йорке.

Порядок работы:
1. Первым этапом проводился базовый анализ и расширение данных.
Были добавлены новые признаки (описание признаков в тетрадке).
2. Далее производился разведывательный анализ данных:
* Исследовался сформированный набор данных;
* Были найдены закономерности, позволяющие сформулировать предварительные гипотезы;
* Добавлена визуализация в проект;
3. Следующим шагом производился отбор и преобразование признаков.
* Были закодированы категориальные признаки (OHE);
* Отобраны признаки, которые вносят наибольший вклад в обучение модели (SelectKBest);
* Проведена нормализация предикторов (MinMaxScaler);
4. Далее задача регрессии решалась следующими моделями (после двоеточия - значение RMSLE на валидационной выборке):
* Линейная регрессия: 0.54
* Полиномиальная регрессия 2ой степени: 0.49
* Дерево решений: 0.43
* Случайный лес: 0.41
* Градиентный бустинг над деревьями решений: 0.39
### Наилучший результат показал градиентный бустинг над деревьями решений: 0.39 (RMSLE)

В результате проекта была решена задача регрессии:

Выполнена предобработка данных, отбор значимых параметров, обучено несколько моделей и оценено качество простроенных моделей.

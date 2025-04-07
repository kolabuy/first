# Проект "Мой Чемпион: Прогнозирование успешности элементов фигурного катания"

Описание

Этот проект представляет собой решение для прогнозирования вероятности успешного выполнения элементов (прыжков) в фигурном катании на основе истории выступлений спортсменов. Цель - помочь тренерам и спортивным школам в планировании программы и выявлении потенциальных проблемных элементов.


Ключевые особенности:

Анализ исторических данных: Использование данных о предыдущих выступлениях спортсменов, включая успешность выполнения различных элементов.

Прогнозирование ошибок: Модель сфокусирована на предсказании элементов (прыжков), в которых вероятны ошибки.

MultiOutputClassifier на основе LGBMClassifier: Использование ансамблевой модели для многоклассовой классификации.

Weighted-averaged F1-score: Оценка качества модели с использованием Weighted-averaged F1-score (0.7388 на тестовой выборке).

# Исследование технологического процесса очистки золота 
## Использованные данные:
в csv файлых представлены полный набор данных, обучающая выборка и тестовая выборка
## Задача
Требуется подготовить прототип модели машинного обучения для очистки золота. Модель должна предсказать коэффициент восстановления золота из руда заданных параметров. 
## Библиотеки
pandas, matplotlib, seaborn, numpy, skalearn
## Выводы
Для обучении модели была проведена стандартизация данных, и предложена модель случайного леса с поиском оптимальных параметров путем gridsearch. Итоговое SMAPE = 0.18 на тестовых данных. 




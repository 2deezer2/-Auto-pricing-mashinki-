# -Auto-pricing-mashinki-
# Цель проекта 
Для анализа рынка автомобилей мы собрали данные с сайта auto.ru. Наша цель состояла в построении модели, которая могла бы предсказывать цену автомобиля в зависимости от его характеристик. Для этого мы провели анализ различных параметров, таких как марка, модель, год выпуска, тип кузова, объем двигателя, пробег, тип топлива, тип привода и многие другие. Мы изучили взаимосвязи и корреляции между этими параметрами и ценой автомобиля. На основе этих данных мы выбрали наиболее важные характеристики, которые влияют на цену автомобиля, и использовали их в нашей модели для предсказания будущих цен. В результате наша модель может быть использована в автомобильной индустрии для прогнозирования цен на автомобили.
# Сбор данных 
Тетрадка с парсингом: [Parser.ipynb](https://github.com/2deezer2/-Auto-pricing-mashinki-/blob/main/Parser.ipynb)

Таблица с данными: [Data.csv](https://github.com/2deezer2/-Auto-pricing-mashinki-/blob/main/Data.csv)

Таблица со старыми данными: [Data.csv](https://github.com/2deezer2/-Auto-pricing-mashinki-/blob/main/folder1/Data.csv)
# Визуализация 
Тетрадка с визуализациями: [Visualizations.ipynb](https://github.com/2deezer2/-Auto-pricing-mashinki-/blob/main/Visualizations.ipynb)
# Гипотезы 
Проверка гипотез: [Hypothesis_testing.ipynb](https://github.com/2deezer2/-Auto-pricing-mashinki-/blob/main/Hypothesis_testing.ipynb)

Гипотезы, которые мы проверили:

- Чем новее модель автомобиля, тем выше цена на него.

- Цена на автомобиль тем меньше, чем больше его пробег.

- Автомобили, которые имеют наменьшее количество владельцев, стоят дороже.

- Цена на автомобиль зависит от того, где он сейчас находится (регион продажи).

- Автомобили, которые имеют большую мощность, имеют более высокую цену на рынке.

- Математическое ожидание цены при условии, что владельцев больше трех, равно математическому ожиданию цены при условии, что владельцев больше двух.
# Методы
Мы будем пользоваться следующими методами машинного обучения: регрессионный анализ (сatboost), корреляционный анализ.

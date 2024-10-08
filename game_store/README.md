# Изучение закономерностей, определяющих успешность игр

## Описание и цель проекта

Нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.

## Задачи

1. Исследовать данные, чтобы:
- выбрать потенциально прибыльные платформы
- оценить влияние оценок на продажи
- выявить жанры с высокими и низкими продажами
2. Составить портреты пользователей по регионам (Северная Америка, Европа, Япония).
3. Проверить гипотезы:
- средние пользовательские рейтинги платформ Xbox One и PC одинаковые
- средние пользовательские рейтинги жанров Action и Sports разные

## Данные

В наличии были исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы. Двнные из открытых источников до 2016 года.

## Используемые библиотеки
- pandas
- numpy
- matplotlib
- seaborn
- scipy

## Вывод

Выявлены параметры, определяющие успешность игры в разных регионах. Составлены портреты пользователя для каждого региона.
Проверены гипотезы:
- средние пользовательские рейтинги платформ Xbox One и PC одинаковые
  Результат: разница между средними пользовательскими оценками Xbox One и PC не является статистически значимой.
- средние пользовательские рейтинги жанров Action и Sports разные
  Результат: средние пользовательские рейтинги Xbox One и PC различаются статистически значимо.

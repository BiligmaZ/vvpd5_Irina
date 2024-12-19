# Экспоненциальный ряд и чередующийся ряд

Этот проект предоставляет функции для вычисления суммы экспоненциального ряда $$ e^x $$ и чередующегося ряда. Пользователь может выбрать, какую функцию использовать, и ввести необходимые параметры.

## Функции

### 1. Чередующийся ряд

Функция `alternating_series(x, n_terms)` вычисляет сумму чередующегося ряда для заданного значения $$ x $$ и количества членов ряда.

**Формула:**
$$ S = \sum_{n=0}^{n\_terms} \frac{(-1)^n \cdot x^{2n}}{(2n)!} $$

### 2. Экспоненциальный ряд

Функция `exp_series(x, n_terms)` вычисляет сумму ряда для экспоненты $$ e^x $$ с заданным количеством членов.

**Формула:**
$$ S = \sum_{n=0}^{n\_terms} \frac{x^n}{n!} $$

## Установка

1. Склонируйте репозиторий:
   ```bash
   git clone https://github.com/ваш-репозиторий.git
   cd ваш-репозиторий

## Использование

1. Запустите скрипт:
    ```bash
    python script_name.py
    ```

2. Выберите одну из опций меню:
 
    Введите 1 для вычисления суммы чередующегося ряда.
    Введите 2 для вычисления суммы ряда для экспоненты.
    Введите 0 для выхода из программы.

3. Введите необходимые параметры:

    Для чередующегося ряда: значение x (в диапазоне -1 < x <= 1) и количество членов ряда.
    Для экспоненциального ряда: значение x и количество членов ряда.

## Пример

1. Введите номер функции (1/2/0): 2
    Введите значение x: 1
    Введите количество членов ряда (по умолчанию 100): 10
    Сумма ряда для e^1 составляет: 2.7182818284

##  Чек-бокс

Перед запуском проекта убедитесь, что вы выполнили следующие шаги:

1. Установили Python 3.x
2. Склонировали репозиторий
3. Перешли в директорию проекта



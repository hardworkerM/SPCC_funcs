# Реализация функций корреляции и представление в виде SPSS

Программный код разрабатывался для друзей, не знакомых с программированием, во времена проблем с доступом в SPSS.\
Функции написаны на python, при использовании библиотек scipy и pandas. Позволяет посчитать корреляции 
Спирмана, Пирсона, Кендалла как между двумя признаками так и множественные.

Визуализация данных в табличном виде, имитирующем работу SPSS.

<img src='https://github.com/hardworkerM/SPSS_funcs/blob/main/one_one_corr.png' width="500"/>

Также и множественная корреляция

<img src='https://github.com/hardworkerM/SPSS_funcs/blob/main/mulri_corr.png' width="500"/>

## Установка

1. Скачайте репозиторий к себе на ПК

```
git clone https://github.com/hardworkerM/SPSS_funcs.git
```
2. Установите необходимые библиотеки

```
pip install -r requirements.txt
```

Функции принимают данные в таблице типа pd.DataFrame\
Поэтому для использования сделайте следующие действия:

Введите путь до файла с данными:\
<code>file_name = 'your_file.csv"</code> \
Создайте объект класса pd.DataFrame:\
<code>df = pd.read_csv(file_name)</code>


_Коррелирующие факторы - имена столбцов_


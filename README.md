# Реализация функций корреляции и представление в виде SPSS

Программный разрабатывался для друзей не знакомых с программированием когда были проблемы с доступом в SPSS.\
Позволяет написан на python, при использовании библиотек scipy, python и позволяет посчитать корреляции 
Спирамана, Пирсона, Кендалла как между двумя признаками так и множественные.\

Визуализация данных в табличном виде, имитирующем работу SPSS.

<img src='https://github.com/hardworkerM/SPSS_funcs/blob/main/one_one_corr.png'>

Также и множественная корреляция

<img src='https://github.com/hardworkerM/SPSS_funcs/blob/main/mulri_corr.png'>

## Установка

1. Скачайте репозиторий к себе на ПК

```
git clone https://github.com/hardworkerM/SPSS_funcs.git
```
2. Установите необходимые библиотеки

```
pip install -r requirements.txt
```

Так как функции работают с pd.DataFrame, то перенесите файл с информацией в папку с кодом и в отдельной строке \
<code>file_name = 'your_file.csv"</code> \
<code>df = pd.read_csv(file_name)</code>


_Коррелирующие факторы - имена столбцов_


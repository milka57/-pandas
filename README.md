# Всем привет! Это мой мини проект по библиотеке Pandas 



Для начала установим библиотеку.

**Устновка библиотеки pandas:**

Установим через командную строку anaconda.
```
pip install pandas
```

Задачи будем решать по таблице **playstore_2.csv**

![krasivo](https://i.postimg.cc/zvBH6ryt/2024-03-28-082029.png)

**Импортируем таблицу в наш файл:**
```
import pandas as pd
play_store = pd.read_csv("playstore_2.csv")
```
Всё! Теперь можем начинать решать задачи.


# Задача №1
"**Подробное решение вы сможете посмотреть в самих задачах** "

Для начала я присвоил к переменной  **"a"** все колонки из таблицы **playstore_2**
потом через команду **len** я подсчитал сколько колонок в таблице тем самым решив **1** условия задачи

Я присвоил к переменной **"b"** всю таблицу и через команду **len** я подсчитал сколько строчек в таблице тем самы решив всю задачу.

(  **Ответ вы сможете посмотреть в моих решениях:)**  )

# Задача №2
"**Подробное решение вы сможете посмотреть в самих задачах** "

Через команду **.isna** я проверил есть ли в колонке **["App"]** пропущенные значение и с помощью команду **.any** я проверил точно ли нету,
тем самым решив условие задачи.

(  **Ответ вы сможете посмотреть в моих решениях:)**  )

# Задача №3
"**Подробное решение вы сможете посмотреть в самих задачах** "

Через команду **.isna** я проверил есть ли пропущенные значение в колонке **["Rating"]** и с помощью команды **.sum** я сумировал все пропущеные значение (**если они есть**), тем самым решив условия задачи.

(  **Ответ вы сможете посмотреть в моих решениях:)**  )

# Задача №4
"**Подробное решение вы сможете посмотреть в самих задачах** "

Для начала я присвоил к переменным через **.loc** срезы которые указывали на строчки в таблицах и к переменной **colums** я присвоил колонки которые указаны в условии задачи.

Следующим шагам я импортировал pandas и через команду **.concat** объединил мои переменные и колонки.

Тем самым решив условие задачи

(  **Ответ вы сможете посмотреть в моих решениях:)**  )

# Задача №5
"**Подробное решение вы сможете посмотреть в самих задачах** "

Через команду **.drop_duplicates(subset="App")** я убрал в колонке **["App"]** все дубликаты и присвоил это все в переменную **"unique_playstore"**.

Тем самым решив условие задачи.

(  **Ответ вы сможете посмотреть в моих решениях:)**  )

# Задача №6
"**Подробное решение вы сможете посмотреть в самих задачах** "

Для начало я вывел все колонки через команду **.columns**. 

Потом через команду **.lower** я поставил все название колонок в нижний регистер и через команду **.replace(" ", "_")** я заменил все пробелы на нижнее подчеркиванияю.

Тем самым решив условие задачи.

(  **Ответ вы сможете посмотреть в моих решениях:)**  )

# Задача №7
"**Подробное решение вы сможете посмотреть в самих задачах** "


Через команду **.value_counts()**  я подсчитал сколько в колонке **["Type"]**

 Free приложений  и Paid  приложений.

 Тем самым решив условие задачи.

 (  **Ответ вы сможете посмотреть в моих решениях:)**  )

 # Задача №8
 Первым шагом я к колонке **["Category"]** присвоил "EDUCATION" 
 
 и через оператор **& (и)** присвоил к колонке **["Reviews"]** > 1000, по условию задачи. 
 
 Потом эти две колонки сгрупировал с помощью **.groupby**, и через команду **.size**
 я решил узнать длину массива, и через еще одну команду **.reset_index(drop=True)**
 я убрал все то, что было удалено.

Тем самым решив условие задачи.

(  **Ответ вы сможете посмотреть в моих решениях:)**  )

# Задача №9
"**Подробное решение вы сможете посмотреть в самих задачах** "

В столбце **["Installs"]** через команду **.replace** я заменил **+** на **(ничего)**

Тем самым решив условие задачи.

(  **Ответ вы сможете посмотреть в моих решениях:)**  )

## Ну вот мы и решили все задачи! **Подробнее про [pandas](https://pythonist.ru/polnoe-rukovodstvo-po-pandas-dlya-nachinayushhih/)** 


























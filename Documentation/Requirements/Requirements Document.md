# Требования к проекту
---

# Содержание
1. [Введение](#intro)  
1.1 [Назначение](#appointment)  
1.2 [Бизнес-требования](#business_requirements)  
1.2.1 [Исходные данные](#initial_data)  
1.2.2 [Возможности бизнеса](#business_opportunities)  
1.2.3 [Границы проекта](#project_boundary)  
1.3 [Аналоги](#analogues)  
1.3.1 [bulavka.by](#bulavka_by)  
1.3.2 [OZ.by](#OZ_by)  
1.3.3 [bestbooks.by](#bestbooks_by)  
2. [Требования пользователя](#user_requirements)  
2.1 [Программные интерфейсы](#software_interfaces)  
2.2 [Интерфейс пользователя](#user_interface)  
2.3 [Характеристики пользователей](#user_specifications)  
2.3.1 [Классы пользователей](#user_classes)  
2.3.2 [Аудитория](#application_audience)  
2.3.2.1 [Целевая аудитория](#target_audience)  
2.3.2.1 [Побочная аудитория](#collateral_audience)  
2.4 [Предположения и зависимости](#assumptions_and_dependencies)  
3. [Системные требования](#system_requirements)  
3.1 [Функциональные требования](#functional_requirements)  
3.1.1 [Основные функции](#main_functions)  
3.1.1.1 [Авторизация пользователя](#user_login_to_the_application)  
3.1.1.2 [Настройка профиля активного пользователя](#setting_up_the_profile_of_the_active_user)  
3.1.1.3 [Добавление комментариев](#add_comments)
3.1.1.4 [Добавление объявления](#add_advertisement)  
3.1.1.5 [Выход пользователя из учётной записи](#active_user_change)   
3.1.2 [Ограничения и исключения](#restrictions_and_exclusions)  
3.2 [Нефункциональные требования](#non-functional_requirements)  
3.2.1 [Атрибуты качества](#quality_attributes)  
3.2.1.1 [Требования к удобству использования](#requirements_for_ease_of_use)  
3.2.1.2 [Требования к безопасности](#security_requirements) 
3.2.1.3 [Требования к производительности](#performance_requirements)
3.2.2 [Внешние интерфейсы](#external_interfaces)  
3.2.3 [Ограничения](#restrictions)  

<a name="intro"/>

# 1 Введение

<a name="appointment"/>

## 1.1 Назначение
AllBooks - это веб-сайт для продажи книг, где любой пользователь сможет выставить собственное объявление о продаже. 

<a name="business_requirements"/>

## 1.2 Бизнес-требования

<a name="initial_data"/>

### 1.2.1 Исходные данные
В настоящее время в мире всё большую популярность обретают электронные гаджеты, в которые можно загрузить огромное количество различной литературы, но всё же по-прежнему много людей, которые предпочитают читать обычные "бумажные" книги. Вместе с тем есть люди, у которых дома полно книг, которые им попросту мешают. И данный сайт предназначен для решения этих проблем: на нем люди, которые хотят продать или возможно отдать уже ненужные им книги могут оставить объявления, а люди, которые хотят найти книгу, смогут просмотреть множество объявлений и выбрать наиболее понравившееся предложение.

<a name="business_opportunities"/>

### 1.2.2 Возможности бизнеса
Данный сайт будет пользоваться популярностью, так как в мире достаточно много людей, которые предпочитают читать обычные бумажные книги, но не всегда есть возможность их преобрести в магазинах. А также много людей, которые хотели бы избавиться от уже ненужных книг, но не могут их просто выбросить.

<a name="project_boundary"/>

### 1.2.3 Границы проекта
На веб-сайте пользователи смогут оставлять комментарии к книгам, делать объявления о продаже, а также просматривать базу данных книг по названию,автору и жанру. 

<a name="analogues"/>

## 1.3 Аналоги

<a name="bulavka_by"/>

### 1.3.1 bulavka.by

**Русский интерфейс:** есть    
**Ссылка на сайт:** https://bulavka.by/  

bulavka.by - это сайт на котором возможно оставлять объявления о продаже любой вещи. На сайте есть поиск по категориям или названию. Есть возможность оставлять объявления только зарегистрированным пользователям. На странице объявления только вся самая необходимая информация о товаре. Так же есть возможность написать пользователю прямо на сайте.

<a name="oz_by"/>

## 1.3.2 OZ.by
**Русский интерфейс:** есть  
**Ссылка на сайт:** https://oz.by/

OZ.by - это сайт для продажи не только книг, но также и концтоваров, различной косметики и даже сладостей. Что касается книг, то на данном сайте уже лучше реализован поиск, там можно найти как по названию, так и по жанрам. Все товары, это товары самих магазинов. На странице товара есть небольшое описание, а также возможность оставлять комментарии. Есть возможность заказа прямо с сайта.

<a name="bestbooks_by"/>

## 1.3.3 bestbooks.by
**Русский интерфейс:** есть  
**Ссылка на сайт:** https://bestbooks.by/

bestbooks - это сайт посвященный только книгам. Поиск книг на сайте сдеал, как по названию, так и по жанру. Это также интеренет магазин, соответсвенно нет возможности оставлять объявления другим пользователям. На данном сайте есть возможность сравнить книги, а также оставить отзыв. При покупке товар заносится в корзине, а дальше уже оформляется, т.е. есть возможность приобрести сразу несколько книг. На странице каждой книге есть подробная информация о ней: автор, название, год написания и небольшое описание.

<a name="comparison_of_applications"/>

# 2 Сравнение приложений

| Функция | bulavka.by |  OZ.by | bestbooks.by | 
|:---|:---:|:---:|:---:|
| Поддержка русского языка | + | + | + |
| Оставлять объявления о продаже | + | - | - |
| Подробное описание книг | - | + | + | 
| Подробный поиск | - | + | + |
| Возможность оставлять комментарии под книгой | - | + | + | 

<a name="user_requirements"/>

# 2 Требования пользователя

<a name="software_interfaces"/>

## 2.1 Программные интерфейсы
Веб-сайт будет реализован на фреймворке для языка python - django. А также использовать базу данных sqlite.

<a name="user_interface"/>

## 2.2 Интерфейс пользователя
Главная страница сайта.  
![Главное окно приложения](https://github.com/Sicphy/AllBooks-Websyte/blob/master/Images/Mockups/Main_page.png)  

Страница авторизации.  
При нажатии на кнопку "Войти" - переход к окну авторизации.
При нажатии на кнопку "Ок" - переход к главной странице, если введены верно логин и пароль.
При нажатии на кнопку "Назад" - возврат к главной странице сайта.       
![Страница авторизации](https://github.com/Sicphy/AllBooks-Websyte/blob/master/Images/Mockups/Autorisation_page.png)  

Страница регистрации нового пользователя.  
При нажатии на кнопку "Зарегистрироваться" - переход к окну регистрации нового пользователя.
При нажатии на кнопку "Ок" - переход к главной странице, если введены все поля.  
При нажатии на кнопку "Назад" - переход к главной странице сайта.  
![Страница регистрации нового пользователя](https://github.com/Sicphy/AllBooks-Websyte/blob/master/Images/Mockups/Registration_page.png)
  
Окно настройки профиля пользователя.  
![Окно настройки профиля пользователя](https://github.com/Sicphy/AllBooks-Websyte/blob/master/Images/Mockups/Profile_page.png)

<a name="user_specifications"/>

## 2.3 Характеристики пользователей

<a name="user_classes"/>

### 2.3.1 Классы пользователей

| Класс пользователей | Описание |
|:---|:---|
| Зарегистрированные пользователи | Пользователи, которые зашли на сайт под своим именем (псевдонимом), желающие оставить комментарий или добавить объявление. |
| Незарегистрированные пользователи | Пользователи, которые не авторизировались, могут просматривать объявления или пользоваться поиском книг в базе данных. |
| Администратор | Имеет права супер-пользователя: может добавлять новые книги, жанры, авторов, удалять или изменять объявления, удаялть и оставлять комментарии и т.д. |

<a name="application_audience"/>

### 2.3.2 Аудитория приложения

<a name="target_audience"/>

#### 2.3.2.1 Целевая аудитория
Люди средней возрастной категории, обладающие минимальной технической грамотностью.

<a name="collateral_audience"/>

#### 2.3.2.2 Побочная аудитория
Люди младшей и старшей возрастных категорий, обладающие минимальной технической грамотностью.

<a name="assumptions_and_dependencies"/>

## 2.4 Предположения и зависимости
1. Сайт работает некорректно при слабом интернет соединении (меньше 100 Кбит/c).

<a name="system_requirements"/>

# 3 Системные требования

<a name="functional_requirements"/>

## 3.1 Функциональные требования

<a name="main_functions"/>

### 3.1.1 Основные функции

<a name="user_login_to_the_application"/>

#### 3.1.1.1 Вход пользователя на сайт
**Описание.** Не авторизированному пользователю предоставляется не весь функционал сайта (нельзя оставлять комментарии или создавать свои объявления)

| Функция | Требования | 
|:---|:---|
| Регистрация нового пользователя | Сайт должен запросить у пользователя ввести имя, пароль, адрес электронной почты, свой город, дату рождения и пол для создания учётной записи. Пользователь должен либо ввести это, либо отменить действие |
| Вход зарегистрированного пользователя | Пользователь должен вести логин и пароль для входа |

<a name="setting_up_the_profile_of_the_active_user"/>

#### 3.1.1.2 Настройка профиля активного пользователя
**Описание.** Зарегистрированный пользователь имеет возможность редактировать свои данные.
 
| Функция | Требования | 
|:---|:---|
| Изменение каких-либо данных о пользователе | Сайт должен запросить ввести новые данные. Имя пользоваетля должно быть уникальным и если выбранное имя уже существует, сайт предоставит возможность повторного ввода |
| Изменение пароля | Зарегистрированный пользователь имеет возможножность изменить пароль, при этом приложение запрашивает ввести старый пароль для подтверждения личности |
| Удаление учётной записи пользователя | Зарегистрированный пользователь имеет возможность удалить созданную учётную запись, для чего приложение запрашивает пароль |

<a name="add_comments"/>

#### 3.1.1.3 Добавление комментариев
**Описание.** После авторизации пользователя возможно оставлять комментарии под книгой.

| Функция | Требования | 
|:---|:---|
| Создание комментария| Сайт должен предоставить пользователю поле для оставления комментария под книгой |
| Удаление комментария | Сайт должен предоставить возможность удалить комментарий пользователю, который его создал |

<a name="add_advertisement"/>

#### 3.1.1.4 Добавление объявления
**Описание.** После авторизации пользователя возможно оставлять объявления о продаже.

| Функция | Требования | 
|:---|:---|
| Создание объявления | Сайт должен предоставить пользователю форму для заполнения, в которой находятся обязательные поля для заполнения, такие как описание состояния и стоимость книги, а также необязательный телефонный номер |
| Редактирование записи | Сайт должен предоставить доступ к уже созданной записи, для её дополнения/изменения |
| Удаление записи | Сайт должен предоставить возможность удалить объявление пользователю, который его создал |


<a name="active_user_change"/>

#### 3.1.1.5 Выход зарегистрированного пользователя из учётной записи
**Описание.** Зарегистрированный пользователь имеет возможность выйти из учётной записи.

**Требование.** Сайт должно предоставить зарегистрированному пользователю возможность выйти из учётной записи с возвратом к окну входа.

<a name="restrictions_and_exclusions"/>

### 3.1.2 Ограничения и исключения
1. Обязательно иметь доступ к интернету;
2. Возможность пользоваться веб-сайтом только при наличии веб-браузера. 

<a name="non-functional_requirements"/>

## 3.2 Нефункциональные требования

<a name="quality_attributes"/>

### 3.2.1 Атрибуты качества

<a name="requirements_for_ease_of_use"/>

#### 3.2.1.1 Требования к удобству использования
1. Все важные операции на веб-сайте сопровождаются дополнительными информационными сообщениями;
2. Все функциональные элементы пользовательского интерфейса имеют названия, описывающие действие, которое произойдет при выборе элемента;
3. Основная информация о функционале веб-сайта отображена в справке;

<a name="security_requirements"/>

#### 3.2.1.2 Требования к безопасности
Возможность добавлять на сайт объявление возможно только зарегестрированным пользователям.

<a name="#performance_requirements"/>

### 3.2.1.3 Требования к производительности
При скорости интернета не меньше 12,5 Мбит/c, скорость загрузки страниц будет до 3 секунд.

<a name="external_interfaces"/>

### 3.2.2 Внешние интерфейсы
Окна приложения удобны для использования пользователями с плохим зрением:
  * размер шрифта не менее 14пт;
  * функциональные элементы контрастны фону окна.

<a name="restrictions"/>

### 3.2.3 Ограничения
1. Приложение реализовано на фреймворке django;
2. Все записи хранятся в базе данных SQLite.
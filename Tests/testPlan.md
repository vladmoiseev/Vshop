
# План тестирования

---

## Содержание
1. [Введение](#introduction)  
2. [Объект тестирования](#items)  
3. [Атрибуты качества](#quality)  
4. [Риски](#risk)  
5. [Аспекты тестирования](#features)  
6. [Подходы к тестированию](#approach)  
7. [Представление результатов](#pass)  
8. [Выводы](#conclusion)

<a name="introduction"/>

## Введение

Данный документ описывает план тестирования приложения "Vshop". Документ предназначен для людей, выполняющих тестирование данного проекта. Цель тестирования — проверка соответствия реального поведения программы проекта и ее ожидаемого поведения, которое описано в требованиях.

<a name="items"/>

## Объект тестирования

В качестве объектов тестирования можно выделить следующие функциональные требования:

- Вход в аккаунт;
- Регистрация нового аккаунта;
- Просмотр корзины;
- Добавление нескольких товаров в корзину;
- Просмотр различных категорий товаров;
- Отображение списка транзакций за текущий день.

<a name="quality"/>

## Атрибуты качества

1. **Функциональность**:
    - Функциональная полнота: приложение должно выполнять все заявленные функции;
    - Функциональная корректность: приложение должно выполнять все заявленные функции корректно.
   
2. **Удобство использования**:
    - Все функциональные элементы пользовательского интерфейса имеют названия, описывающие действие, которое произойдет при выборе элемента.

<a name="risk"/>

## Риски

К рискам можно отнести:
- Потерю соединения с сервером, что может привести к некорректному проведению транзакции.

<a name="features"/>

## Аспекты тестирования

В ходе тестирования планируется проверить реализацию основных функций приложения. Аспекты, подвергаемые тестированию: 
- Запуск приложения;  
- Регистрация нового пользователя;  
- Вход в существующий аккаунт;  
- Выбор товара в каждой из категорий;  
- Просмотр корзины;  
- Редактирование корзины;    
- Добавление нового товара;  
- Выбор этого товара;  
- Последующая обработка этого товара.  

### Запуск приложения
Необходимо протестировать:
- Запуск приложения;
- Отображение окна приложения.

### Регистрация нового пользователя
Необходимо протестировать:
- Добавление данных о пользователе в базу данных;
- Корректное отображение нового пользователя.

### Вход в существующий аккаунт
Необходимо протестировать:
- Корректный переход на главное меню с данными пользователя.

### Отображение всех товаров 
Необходимо протестировать:
- Корректное отображение всех ранее просмотренных товаров на главном экране.

### Просмотр корзины
Необходимо протестировать:
- Отображение всех товаров в корзине.

### Редактирование корзины
Необходимо протестировать:
- Обновление корзины с товарами.

### Настройки приложения
Необходимо протестировать:
- Открытие настроек и доступность всех параметров.

### Добавление нового товара
Необходимо протестировать:
- Добавление нового товара и его корректное отображение.

<a name="approach"/>

## Подходы к тестированию

При тестировании будет использован ручной подход.

<a name="pass"/>

## Представление результатов

Результаты представлены в документе "Результаты тестирования".

<a name="conclusion"/>

## Выводы

Данный тестовый план позволяет протестировать основной функционал приложения "Vshop". Успешное прохождение всех тестов не гарантирует полной работоспособности на всех версиях платформ и архитектурах, однако позволяет полагать, что данное программное обеспечение работает корректно.

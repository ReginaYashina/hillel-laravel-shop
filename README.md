### Запуск

```bash
composer install
php artisan migrate
php artisan db:seed
php artisan serve
```

### Требования

* Каталог
* Категории товаров
    * Вывод категорий в виде дерева
* Корзина
* Создание заказа
    * Сохранять user_id в деталях заказа
    * Хранить способы оплаты/доставки в БД
* Фильтры
* Личный кабинет
    * Регистрация
    * Авторизация
    * История заказов
    * etc
* Страница товара:
    * Фотографии
    * Цена
    * Описание
    * Ссылка
    * Коментарии
* Админ панель
    * Авторизация
    * Управление товарами
    * Управление категориями
    * Управление заказами заказов

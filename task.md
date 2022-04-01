# Задание 2 Вариант №3

Ваша предметная область - статьи и теги  
У статьи может быть несколько тэгов.  
Один тег может быть прикреплен к нескольким статьям.  
### Поля статьи:
- Идентификатор
- Название
- Символьный код
- Содержание
- Дата и время создания
- Автор 
### Поля тэга:
- Идентификатор
- Название
- Символьный код  
  В задании необходимо:
- Написать миграции для добавления указанных сущностей в БД
- Создать модели, прописать в них связи между сущностями
- Наполнить каждую из таблиц 100 записями через Database Seeders
- Проверить что данные появились в БД
  # Задание 3
  В задании необходимо реализовать две страницы и консольную команду  
  3.1 Список статей uXXXXXX-lab2.local/posts  
  В списке вывести все поля статей. Реализовать постраничную навигацию и фильтры по полям
- “Символьный код”,
- “Название”,
- а также фильтр, позволяющий отфильтровать статьи по тегу

## 3.2 Страница статьи uXXXXXX-lab2.local/posts/{code}

На странице вывести все поля статьи. Над полями статьи вывести блок с названиями всех тэгов статьи. Теги должны быть
отсортированы в алфавитном порядке

## 3.3 Консольная команда php artisan tag:count {id}

Консольная команда должна возвращать количество статей привязанных к тегу с идентификатором {id}
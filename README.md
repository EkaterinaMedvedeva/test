# Екатерина Медведева - "Online-сервис планирования и подготовки с преподавателями к ОГЭ по информатике для учеников 9-х классов"

1. **Медведева Екатерина**

**Группа: 10-МИ-4**

**Электронная почта:Medsvetlan@yandex.ru**

**VK:https://vk.com/id170127979**

2.**Название проекта:**
"Online-сервис планирования и подготовки с преподавателями к ОГЭ по информатике для учеников 9-х классов"

3.**Проблемное поле:**
В настоящее время в школах с неуглубленным изучением информатики ученикам достаточно сложно подготовиться к сдаче ОГЭ по данному предмету. Сайты, обеспечивающие подготовку школьников к экзамену, должны выполнять следующие требования:
* 1)Возможность прохождения тестов на время;
* 2)Наличие системы регистрации и авторизации пользователей с разграничением прав доступа;
* 3)Ключи к тестам. 
Однако, во всех имеющихся программных продуктах отсутствует, по моим данным: 
### 1)Возможность проверки части C;
### 2)Наличие методических материалов;
### 3)Возможность визуально отражать прогресс в прохождении тестов и отдельных заданий;
### 4)Возможность визуально отражать общий рейтинг пользователей и поддерживать состязательность среди учеников.
Заявляемый программный продукт позволит решить эти проблемы и обеспечит пользователям широкий функционал и интуитивно понятный интерфейс.

4.**Потенциальная аудитория:**
Программный продукт может заинтересовать учеников 9 классов, которые сдают ОГЭ по информатике.

5.**Аппаратные требования:**

*Требования к аппаратному обеспечению:*

     -Сервер под управлением OS  ubuntu;
     
     -4 ГБ операционной памяти и 15 ГБ HDD;
     
*Требования к программному обеспечению:*

    - База данных MC MySQL;
    
    - Web-сервер Apache.
    
    
 6.**Функциональные требования:**
 Программный продукт должен предоставлять следующие возможности:
 
Должен поддерживать следующие роли пользователей:

     -Администратор(может изменять внешний вид страниц, осуществлят контрольи управление и управление сайтом);
     
     -Редактор(может редактироваь отдельные задания тестов добавлять/удалять задания или сами тесты;
     
     -Эксперт(может осуществлять проверку и выставление оценок за часть C);
     
     -Пользователь(Может просматривать материалы, решать тесты);
     
Должен поддерживать систему регистрации(для пользователей) и авторизации(для всех) с разграничением прав доступа;

Визуализация результатов прохождения тестов;

Поддержка прохождения тестов на время;

Поддержка экспорта тестов и результатов их прохождения в формате PFD;

Возможность участия для пользователей в пробных онлайн-тестированиях  в назначенную дату и время;

Поддержка рейтингов пользователей и статистика прохождения тестов и отдельных заданий для конкретных пользователей.


7.**Аналогичные продукты:**
Анализ 3 программных продуктов, которые максимально приближены к заданному функционалу, показал, что:

  -Сайт "Решу ОГЭ" и http://gia-online.ru/tests/10 : нет возможности проверки части C; нет теории; нет возможности визуально отражать прогресс в прохождении тестов и отдельных заданий;нет общего рейтинга участников.
  
  -Сайт https://neznaika.info/:нет возможности проверки части C; нет теории.
  
  
 8.**Инструменты разработки:**
 -HTML/CSS/JS/Django/jQuery-web-разработка
 
--Pycharm/notepad ++-инструменты разработки


 9.**Этапы разработки:**
 
-Разработка сценариев использования программного продукта для всех ролей;

-Разработка архитектуры;

-Программирование Web-интерфейса пользователя;

-Подготовка методических материалов;

-Подготовка базы тестов;

-Разработка модулей и библиотек:

    Создание библиотеки для работы с тестами и заданиями;
    
    Разработка модуля для сбора и обработки статистики тестов,заданий и рейтингов пользователей;
    
    Разработка визуализации данных;
    
-Разработка web-сайта и интеграция с разработанными модулями;

-Тестирование, отладка на локальной машине;

-Размещение проекта в сети интернет;

-Подготовка проекта к защите.


10.**Возможные риски:**

-Риск увеличения длительности этапа разработки основных модулей программы продукта, связанный с необходимостью освоения нового фреймворка Django;

-Риск увеличения длительности этапа тестирования и отладки проекта.





### **Техническое задание на разработку системы управления задачами**  

**Заказчик:** Преподаватель колледжа, курирующий командные студенческие проекты.  
**Исполнители:** Группа студентов.  
**Срок разработки:** 3 дня.  

---  
## **1. Введение**  
Цель проекта — создать простую систему управления задачами, позволяющую небольшим командам организовывать работу, отслеживать статус задач и фиксировать прогресс.  

Основные пользователи системы:  
- **Преподаватель (Администратор)** — управляет проектами, контролирует выполнение задач.  
- **Студент (Пользователь)** — создает и выполняет задачи в проекте.  

---  
## **2. Функциональные требования**  

### **2.1 Регистрация и аутентификация**  
✔ Пользователь должен иметь возможность зарегистрироваться в системе (логин, пароль, имя).  
✔ Вход в систему с использованием логина и пароля.  
✔ Хранение паролей в зашифрованном виде.  

### **2.2 Управление проектами**  
✔ Администратор может создавать проекты и приглашать пользователей.  
✔ Каждый проект содержит набор задач.  
✔ Просмотр списка всех проектов пользователя.  

### **2.3 Управление задачами**  
✔ Создание, редактирование и удаление задач.  
✔ Возможность назначать задачи на конкретного пользователя.  
✔ Установка сроков выполнения задач.  
✔ Изменение статуса задачи (в очереди, в работе, выполнено и др.).  
✔ Комментарии к задачам.  

### **2.4 Отображение информации**  
✔ Просмотр всех задач проекта с возможностью фильтрации (по статусу, исполнителю, сроку).  
✔ Визуальное представление задач в виде списка или канбан-доски.  
✔ (дополнительно) История изменений задачи.  

### **2.5 Уведомления**  
✔ Уведомления о новых задачах и изменениях в существующих.  
✔ Уведомления о приближении дедлайна.  

---  
## **3. Нефункциональные требования**  

### **3.1 Интерфейс**  
✔ Удобный и минималистичный UI (ориентир на простоту и функциональность).  
✔ Адаптивность.  

### **3.2 Технологический стек**  
✔ **Backend:** любой.  
✔ **Frontend:** любой, но желательно desktop
✔ **База данных:** MySQL / MS SQL (Entity Framework) / другое

### **3.3 Безопасность**  
✔ Хранение паролей с хешированием.  
✔ Авторизация и разграничение прав пользователей.  

---  
## **4. Ограничения**  
- Разработка должна быть завершена за 3 дня.  
- Приложение рассчитано на небольшие команды (до 10 пользователей на проект).  
- Отсутствие сложных ролей и интеграции с внешними сервисами (Jira, Trello и т. д.).  

---  
## **5. Приоритеты разработки**  

🔹 **День 1:**  
- Настройка базы данных и моделей.  
- Реализация аутентификации.  
- CRUD-операции для задач.  

    #### Демонстрация
- Диаграмма прецендентов
- Проволочные диаграммы / прототипы интерфейса
- Распределение задач разработки по участникам

🔹 **День 2:**  
- Фильтрация и сортировка задач.  
- Канбан-доска или таблица задач.  
- Уведомления и дедлайны.  

    #### Демонстрация
- Структура API и БД
- Пользовательский интерфейс

🔹 **День 3:**  
- Тестирование.  
- Финальные доработки UI.  
- Презентация проекта.  

    #### Демонстрация
- Результаты тестирования ПО
- Руководство пользователя, руководство по развертыванию
- Защита продукта

---  
### **6. Ожидаемый результат**  
По итогам проекта должна получиться рабочая система, позволяющая управлять задачами в рамках небольших учебных проектов.  
